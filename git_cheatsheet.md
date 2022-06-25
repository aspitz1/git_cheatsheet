# Git Cheatsheet

**Link to [git docs](https://git-scm.com/doc)**

| Terminal Command | Action |
| ---------------- | ------ |
| `git status` | returns repo status or lack there of if it's not a repo |
| `git log` | commit history |
| `git log --oneline` | simplified history |
| `git log --author=<name>` | history of just that contributor |
| `git init` | initialize repo |
| `git add` | add files to working directory |
| `git commit -m` | commit with a commit message |
| `git commit -a -m` | add and message |
| `git commit --amend` | amend previous commit message |
| `git branch` | list of current branches |
| `git branch <branch-name>` | create new branch |
| `git branch -m` | merge branch, or rename a branch using current branch name and new branch name |
| `git switch <branch-name>` | switch branches |
| `git switch -c <branch-name>` | create new branch and switch to it |
| `git diff` | shows difference between upstaged changes that haven't been committed |
| `git diff --HEAD` | difference between current changes and HEAD |
| `git diff --staged` | difference between last commit and staged changes |
| `git stash` | stash changes |
| `git stash pop` | reapply the stashed changes |
| `git stash apply` | applies stash but still keeps copy in stash |
| `git restore <file-name>` | restores to last commit |
| `git reset <commit-hash>` | reset back to the commit hash |
| `git rebase -i HEAD~<X>` | enter interactive detached HEAD, follow instructions |
