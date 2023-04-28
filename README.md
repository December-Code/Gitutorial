# Git Tips

## **Git config**
### Setting
global
```cmd
git config --global user.name "your name"
git config --global user.email "your@email"
```

local
```cmd
git config --local user.name "your name"
git config --local user.email "your@email"
```

### List config
global
```cmd
git config --gobal --list
```

local
```cmd
git ocnfig --local --list
```

## **Git Status**
```cmd
git status
```

## **Git init**
### Current dir
```cmd
git init
```
### Set dir
```cmd
git init <directory>
```
## **Git clone**
### normal
```cmd
git clone <url>
```
### accelerate
single branch
```cmd
git clone <url> --depth 1
```
git clone <url> --depth 1 == git clone <url> --depth 1 --single-branch

All branch
```cmd
git clone <url> --depth 1 --no-single-branch
```

## **Git Add (Stage)**

single
```cmd
git add <file_name>
```

All
```cmd
git add .
```
git remove added-file
```cmd
git reset HEAD <file_name>
```

## **Git Commit**

commit has been added
```cmd
git commit -m "information"
``` 

open edit file and commit
```cmd
git commit -a
```

edit last commit information
```cmd
git commit --amend
```

## **Git Push**
```cmd
git push
```

new branch for github
```
git push --set-upstream <url> <branch_name>
```

replace last commit (not recommend)
```
git push -f
```

Avoid replace other commit
```
git push --force-with-lease
```

## **Git Log**
```cmd
git log
```
log GUI Graph
```
git log --graph --pretty=format:"%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset" --abbrev-commit --date=relative
```

## **Git HEAD**
go current head
```
git reset --hard HEAD
```

go specific head
```
git reset --hard <HEAD_ID>
```

git reset has three tags\
`--hard` 捨棄過去 commit，不保留現在視窗\
`--soft` 捨去過去commit，保留現在視窗\
`--mixed`

`--soft` 適用在合併無用commit
