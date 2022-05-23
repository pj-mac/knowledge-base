# Multiple Git Profiles

A simple way of handling multiple Git profiles involves leveraging the `includeIf` directive in the user's global `.gitconfig` file. An additional `.gitconfig` file is then created for each profile.

A typical use case would be using one configuration for personal use and another for work use. With this method, there is no need to manually switch profiles.

## Directory Structure

```bash
~/.gitconfig
~/personal/.gitconfig
~/work/.gitconfig
```

## ~/.gitconfig

```bash
[includeIf "gitdir:~/personal/"]
	path = ~/personal/.gitconfig
[includeIf "gitdir:~/work/"]
	path = ~/work/.gitconfig
[filter "lfs"]
	required = true
	clean = git-lfs clean -- %f
	smudge = git-lfs smudge -- %f
	process = git-lfs filter-process
```

## ~/personal/.gitconfig

```bash
[user]
	email = <personal email>
	name = <name>
[init]
	defaultBranch = main
```

## ~/work/.gitconfig

```bash
[user]
	email = <work email>
	name = <name>
[init]
	defaultBranch = main
```

## Helpful Commands

To identify the email address being used for a particular repository (stored in the `.gitconfig` file), first `cd` to the Git repository directory, then:

```bash
git config --show-origin --get user.email
```

Edit the `.gitconfig` files as needed using a text editor or command line text editor.
