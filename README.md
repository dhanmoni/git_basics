# Git commands

- git init
- git add .
- git commit -m "message"
  ### combine add and commit
- git commit -am "msg"

### add alias to command

- git config --global alias.ac "commit -m"

### change last commit msg

- git commit --amend -m "updated msg"

### add files to previous commit without changing cmt msg

- git add .
- git commit --amend --no-edit

### stash - save code without commiting

- git stash save coolStuff
- git stash list
- git stash apply 0

- git remote add origin
- git push -u origin main

- git branch
- git checkout -b branchname
- git branch -M main

### go to previous branch

- git checkout -

### docorate branches

- git log --graph --oneline --decorate

### remove files from staging

- git rm --cached filename
