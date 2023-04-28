# Git Tips

## **Git config**
## Setting
<u>global</u>
```
git config --global user.name "your name"
git config --global user.email "your@email"
```
<u>local</u>
```
git config --local user.name "your name"
git config --local user.email "your@email"
```

## List config
<u>global</u>
```
git config --gobal --list
```
<u>local</u>
```
git ocnfig --local --list
```

## **Git Status**
```
git status
```

## **Git init**
## Current dir
```
git init
```
## Set dir
```
git init <directory>
```
## **Git clone**
## normal
```
git clone <url>
```
## accelerate
<u>single branch</u>
```
git clone <url> --depth 1
```
git clone <url> --depth 1 == git clone <url> --depth 1 --single-branch

<u>All branch</u>
```
git clone <url> --depth 1 --no-single-branch
```

## **Git Add (Stage)**

<u>single</u>
```
git add <file_name>
```
<u>All</u>
```
git add .
```
<u>git remove added-file</u>
```
git reset HEAD <file_name>
```

## **Git Commit**

<u>commit has been added</u>
```
git commit -m "information"
``` 
<u>open edit file and commit</u>
```
git commit -a
```
<u>edit last commit information</u>
```
git commit --amend
```

## **Git Push**
````
git push
````

## **Git Log**
```
git log
```