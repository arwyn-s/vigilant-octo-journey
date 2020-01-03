# Git tutorials

## Welcome

Initialize repository 
```
$ git init
```
Stage the changes to tracked and untracked files 
```
$ git add .
```
Commit the staged changes
```
$ git commit -m "First commit"
```
Check status of the current working directory.
```
$ git status
```
To view all commit history.
```
$ git log --oneline
```
To go back and view a commit.
```
$ git checkout <commit-id>
```
Add remote github repository 
```
$ git remote add origin https://github.com/arwyn-s/vigilant-octo-journey.git
```
push all commit to remote repository
```
$ git push -u origin master
To create a new branch from HEAD
```
$ git branch <branch-id>
```
switch to branch
```
$ git checkout <branch-id>
```