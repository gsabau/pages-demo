# How to Git

Successful Git commands used to set up **gsabau/pages-demo**, from clone through committing and pushing this file.

## Clone

```powershell
git clone git@github.com:gsabau/pages-demo.git
cd .\pages-demo\
```

## Develop branch

```powershell
git switch -c develop
git remote set-url origin git@github.com:gsabau/pages-demo.git
git push -u origin develop
```

## README feature

```powershell
git switch -c feature/readme
git add .
git commit -m "updated readme"
git push -u origin feature/readme
git checkout develop
```

## Hello World page

```powershell
git switch -c feature/hellopage
git add .
git commit -m "added hello pagE"
git push -u origin feature/hellopage
git checkout develop
```

## GitHub Pages CI

```powershell
git switch -c feature/pagesconfig
git add .
git commit -m "ci for pages"
git push -u origin feature/pagesconfig
git checkout develop
```

## This branch

```powershell
git switch -c feature/howtogit
git add .
git commit -m "added howtogit md file"
git push -u origin feature/howtogit
```
