# Git Tips

## **Git config**
## Setting
global
```git
git config --global user.name "your name"
git config --global user.email "your@email"
```

local
```git
git config --local user.name "your name"
git config --local user.email "your@email"
```

## List config
global
```git
git config --gobal --list
```

local
```git
git ocnfig --local --list
```

## **Git Status**
```git
git status
```

## **Git init**
## Current dir
```git
git init
```
## Set dir
```git
git init <directory>
```
## **Git clone**
## normal
```git
git clone <url>
```
## accelerate
single branch
```git
git clone <url> --depth 1
```
git clone <url> --depth 1 == git clone <url> --depth 1 --single-branch

All branch
```git
git clone <url> --depth 1 --no-single-branch
```

## **Git Add (Stage)**

single
```git
git add <file_name>
```

All
```git
git add .
```
git remove added-file
```git
git reset HEAD <file_name>
```

## **Git Commit**

commit has been added
```git
git commit -m "information"
``` 

open edit file and commit
```git
git commit -a
```

edit last commit information
```git
git commit --amend
```

## **Git Push**
```git
git push
```

## **Git Log**
```git
git log
```