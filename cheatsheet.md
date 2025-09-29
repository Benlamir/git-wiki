# Git Cheatsheet

## Basics
git status               # show working directory status
git add .                # stage all changes
git commit -m "msg"      # commit staged changes
git push -u origin main  # push to remote

## Branching
git branch               # list branches
git checkout -b feature  # create new branch and switch
git merge feature        # merge branch into current

## Push new branch
git push -u origin feature-x
# Why: push a new branch to remote and set upstream
# Notes: `-u` means you can later just run `git push`
