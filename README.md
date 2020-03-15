# gitSessionClass24


This repo is for git training purposes

## Get started
```
git clone https://github.com/ammarvehbi/gitSessionClass24.git
```

## Committing
```
git status
git add .
git commit -m "initial commit"
git push
```

## Amend
! Only on your own branch, use with care!
```
git commit --amend
git push --force
```
## Get changes from remote
```
git pull --rebase
```
## Get changes from master without switching branches
```
git fetch origin master:master
```
## Rebase with master
```
git rebase master
```
# Undo commits
## undo last commit
```
git reset --mixed HEAD~1
```
## undo last 2 commits
```
git reset --mixed HEAD~2
```
## cherry picking
```
git cherry-pick <commit>
```
