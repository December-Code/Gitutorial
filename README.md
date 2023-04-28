# Git Tips

## **Git config**
## Setting
<sub>global</sub>
```
git config --global user.name "your name"
git config --global user.email "your@email"
```
<sub>local</sub>
```
git config --local user.name "your name"
git config --local user.email "your@email"
```

## List config
<sub>global</sub>
```
git config --gobal --list
```
<sub>local</sub>
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
<sub>single branch</sub>
```
git clone <url> --depth 1
```
git clone <url> --depth 1 == git clone <url> --depth 1 --single-branch

<sub>All branch</sub>
```
git clone <url> --depth 1 --no-single-branch
```

## **Git Add (Stage)**

<sub>single</sub>
```
git add <file_name>
```
<sub>All</sub>
```
git add .
```
<sub>git remove added-file</sub>
```
git reset HEAD <file_name>
```

## **Git Commit**

<sub>commit has been added</sub>
```
git commit -m "information"
``` 
<sub>open edit file and commit</sub>
```
git commit -a
```
<sub>edit last commit information</sub>
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