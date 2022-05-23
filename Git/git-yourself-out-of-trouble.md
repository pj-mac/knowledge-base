# Git Yourself Out of Trouble

Commands for recovering from common Git mistakes.

## I committed to the wrong branch, but at least I didn't push.

1. Get the hash of the commit *before* the one you accidentally committed.
2. Switch to the branch you accidentally committed to, then:

```bash
git reset --mixed <commit hash>
```

> Resets the index but not the working tree (i.e., the changed files are preserved but not marked for commit). https://git-scm.com/docs/git-reset 

The commit should have been removed from the branch you accidentally committed to, and it now appears as an *uncommitted* change.

Switch to the branch you want to commit to. Enter a commit message, stage and commit.

## I committed to the wrong branch *and* pushed.

1. Get the hash of the commit *before* the one you accidentally committed.
2. Switch to the branch you accidentally committed to, then:

```bash
git reset --mixed <commit hash>
```

> Resets the index but not the working tree (i.e., the changed files are preserved but not marked for commit). https://git-scm.com/docs/git-reset 

The commit should have been removed from the branch you accidentally committed to, and it now appears as an *uncommitted* change.

Now that you've undone the change to the local branch, you must force push to the remote branch. (The following assumes that your remote repository uses the "origin" alias and that you have "force push" permissions.)

```bash
git push origin <branch name> --force
```

Now the commit should have disappeared from the remote branch, like it never happened.

Switch to the branch you want to commit to. Enter a commit message, stage and commit. Push your changes when ready.

## How to recreate a Git repository with current files and clear all history.

Delete the project's `.git` folder from the local file system. This removes the Git repository.

Recreate the repository, add all files, and then commit.

```bash
git init
git add .
git commit -m "Initial commit"

```

Add a remote connection and then force push to overwrite all changes.

```bash
git remote add origin <repo url>
git push -u --force origin main
```

