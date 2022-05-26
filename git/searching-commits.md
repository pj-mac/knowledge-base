# Searching for Commits

To start, `cd` to the Git repository. The following examples search the Git log for commit messages containing the word `foobar` and  by email address of the author.

```
git log --grep="foobar"

git log --oneline --grep "foobar"

git log --oneline --abbrev-commit --all --graph --decorate --color --grep "foobar"

git log --author=jdoe@email.com

git log --author=jdoe@email.com --oneline --grep "foobar"

git log -n 1 <commit ID>

Type "q" to exit.
```

## References

- https://www.atlassian.com/git/tutorials/git-log
- https://www.toolsqa.com/git/git-log/
