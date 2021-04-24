# Git Commands

## existing repository

repo -> repository

### Clone

**Clone** -> bring a repo down from the internet (remote repository like Github) to your local machine

`git clone (repository link)`

### Add

**add** -> track your files and changes with Git

`git add .`
or
`git add (file name.extension)`

### Commit

**Commit** -> save your changes into Git

`git commit -m "(commit message)" -m "(description message)"`

### Push

**Push** -> push your changes to your remote repo on Github (or another website)

`git push origin master`

### Pull

**Pull** -> pull changes down from the remote repo to your local machine

`git pull origin master` if upstream is not set

`git pull` if upstream is set

## local repository

### Init

**Init** -> For Initializing git in that folder or repository(only if file is locally created).

`git init`

### remote

`git remote add origin (repository link)`

#### remote check -v

`git remote -v`

### Push Upstream

`git push -u origin master`

## Other Commands

### Status

**Status** -> The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.

`git status`

### Branch

**Branch** -> A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically, To know on which branch you are working on.

`git branch`

### Checkout

**Checkout -b** -> to create a branch

`git checkout -b (name of branch)`

**Checkout** -> to change branch,The git checkout command lets you navigate between the branches created by git branch .

`git checkout (branch name)`

### merge

**Merge** ->  The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch, Simply merging two branches or merging the branch into master branch.

`git merge (branch name)`

### diff

**Diff** -> Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them.

`git diff (branch name)`

### delete

**-d** -> Deleting a branch

`git branch -d (branch name)`

### add and commit

**-am** -> Adding and Commiting changes to repository

`git commit -am "commit message" -am "description message"`

### Reset

**Reset** ->to unstage

`git reset` or `git reset (file name)` or `git reset HEAD` -> **Head is pointer to last commit** or `git reset HEAD~1` ->last last commit

### log

**Log** -> To see the all commits

`git reset (commit hash)`

### hard

**Hard** -> to completely delete

`git reset --hard (commit hash)`
