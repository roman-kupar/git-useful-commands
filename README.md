# git-useful-commands
Useful git commands for EIST tutorial

```git status``` - tells you which branch are you on (modified, commited, staged...)

```git add <file>``` - adds content from the working directory into the staging area (or index) for the next commit. Note: in real world, don't use ```git add .``` blidnly!

```git commit -m <commit-message>``` - a snapshot of your git repository at one point in time

```git push origin <branch-name>``` - pushes a local branch(es) to a remote repository (origin)

```git log --oneline --graph``` - shows git history in a clean graph representation

```git branch``` - lists all availabe branches

```git checkout <branch-name>``` - switch branch to another

```git pull``` - updates your workspace and local git repository from changes in a remote repository

```git merge <branch-name>``` - merge your branch (referred as `ours`), and <branch-name> (referred as `theirs`) 
