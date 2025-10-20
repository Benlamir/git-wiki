# Git Cheatsheet

## Basics
git init                 # Initializes a new local Git repository in the current folder
git status               # show working directory status
git add .                # stage all changes
git commit -m "msg"      # commit staged changes
git git remote add origin git@github.com:Benlamir/Example.git        #Links your local repository to the remote GitHub repository at that address
git branch -M main              # Renames the current branch to main (creating it if needed) and sets it as the primary branch.
git push -u origin main  # push to remote
git clone git@github.com:username/example-repo     # clone a repo into the local machine
gh repo list username --limit 100     # list the repos of a github account (requires the GitHub CLI; install it via sudo apt install gh if not already installed).
 
## Branching
git branch               # list branches
git checkout -b feature  # create new branch and switch
git merge feature        # merge branch into current

## Push new branch
git push -u origin feature-x
# Why: push a new branch to remote and set upstream
# Notes: `-u` means you can later just run `git push`
