## Git and Git Branching Cheat Sheet

Categories of git commands and practice with branching:


### Basic Commands

Practice with merging and merge conflicts.

* `git init` - initialize curent directory with repository
* `git add .` - add all new or changed files in current directory on git index, staging them for commit
* `git commit -m "some message"` - commit staged changes to local repository


### Info Commands

* `git status` - show status of current working directory
*`git log` - list commit history
* `git log --oneline` - list commit history (compact)
* `git config -l` -list local git configuration settings

### Branch Commands

*`git branch` -list local branches, highlight current branch
*`git branch branchName` - create branch 'branchName'
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch`, creating it if it doesn't exist

## Remote commands

* `git remote add origin someURL` - connect local repo to remote repo url as `oigin`
* `git push origin branchName` - push local commits to remote repo into branch `branchName`
*`git pull origin branchName` -pull remote branch `branchName` into local current branch

### Other Commands

* `git help` - list git subcommands and options
* `git config --help` -show options for `git config`
