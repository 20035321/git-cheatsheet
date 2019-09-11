# Git Cheat Sheet 
## File: ReadMe.md 

This is my `git` cheat sheet.It's my **first** cheat sheet!

Please feel free to give feedback with corrections and additions.

## git commands

```bash
git init REPO-NAME
```
- creates a repository called REPO-NAME

```bash
git status
```
- shows the status of the git repository

```bash
git show
```
- shows the commit history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
- adds the file FILENAME and ANOTHERFILENAME to the stash

```bash
git commit -m "MESSAGE"
```
- commits the stashed files to the repo, and adds 
the MESSAGE that describes what was done

```bash
git log
```
- show a history of the commits made to this point in time

```bash
git log --all --decorate --oneline --graph
```
- displays a 'graph' of the commits, one commit per line

```bash
git config --global alias.adog "log --all --decorate --oneline --graph"
```
- creates a git alias for the log all decorate oneline command 
- uses this by entering `git adog` (much shorter) 



## Other Git Things

**.gitignore** is a file that tells git files/folders that are
not to be part of the repository (that is - ignored when 
adding/commiting)

Comprehensive .gitignore found at:
(https://github.com/github/gitignore/blob/master/Python.gitignore )[https://github.com/github/gitignore/blob/master/Python.gitignore ]
