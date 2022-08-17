## Git and Git Branching Cheat Sheet


### Basic Commands
* `git init` - initialize curent directory with repository

* `git add .` - add all new or changed files in current directory on git index, staging them for commit

* `git commit -m "some message"` - commit staged changes to local repository

### Info Commands

* `git status` - show status of current working directory
*`git log` - list commit history
* `git log --oneline` - list commit history (compact)

### Branch Commands

*`git branch` -list local branches, highlight current branch
*`git branch branchName` - create branch 'branchName'
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch`, creating it if it doesn't exis

### Other Commands

* `git help` - list git subcommands and options
* `git config --help` -show options for `git config`
