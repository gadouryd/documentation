# Branches

git branch

```
git checkout -b <branch_name>
``

This is shorthand for:
  $ git branch <branch_name>
  $ git checkout <branch_name>

## sync local branch with remote branch
git fetch --prune
git pull -p (https://git-scm.com/docs/git-pull) 

## what is in each release or pending releases
git fetch origin && git log origin/master --oneline

## download branch
git checkout -b newlocalbranchname origin/branch-name
git checkout -t origin/branch-name

## sync to remote
git commit -m "commit message"
git push orgin master

## add upstream
git remote add upstream git@github.com:original/repo.git

## sync repos
git fetch upstream
