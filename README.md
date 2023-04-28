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