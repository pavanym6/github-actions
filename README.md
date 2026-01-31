
# Git Commands Cheat Sheet

## 🔧 Configure Git (One-Time Setup)
```bash
git config --global user.name "pavanym6"
git config --global user.email "pavanym6@gmail.com"
```
## Initialize and Stage Files
```bash
git init
git status
git add <files>
git add *
git add .
```
## Commit and History
```bash
git commit -m "initial commit"
git log
```
## Navigating Commits and Resetting
```bash
git checkout <id>
git checkout master
git reset <id>
git reset --hard <id>
```
## Branching Operations
```bash
git branch
git branch dev
git checkout dev
git checkout -b test
git branch -D checkout
```
## Merging Branches
```bash
git checkout master
git merge dev
```
## Remote Repository Configuration
```bash
git remote add origin [https://github.com/pavanym6/github-actions.git](https://github.com/pavanym6/github-actions.git)
git remote set-url origin [https://pavanym6@github.com/pavanym6/github-actions.git](https://pavanym6@github.com/pavanym6/github-actions.git)
```
## Pushing to GitHub
```bash
git push origin master
git push --set-upstream origin master
git push
git push origin dev
```
## all commands
git init
git add <files>
git status
git commit -m "initial commit"
git log
git checkout <id>
git checkout master
git reset <id>
git reset --hard <id>
git add *
git branch
git branch dev
git checkout dev
git branch checkout
git branch -D checkout # delete branch
git checkout -b test # to create branch and checkout
git merge <branch name> #but checkout to master branch first

# to add local repo to git hub
git remote add origin https://github.com/pavanym6/github-actions.git
git remote set-url https://pavanym6@github.com/pavanym6/github-actions.git
git remote set-url origin https://pavanym6@github.com/pavanym6/github-actions.git
git push origin master
git push --set-upstream origin master
git push

git branch -b dev
git add .
git commit -m "added sections"
git push origin dev
git checkout master
git merge dev
