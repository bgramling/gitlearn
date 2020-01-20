# Some basic git setup commands

git --version

git config --global user.name "Brian Gramling"

git config --global user.email "bcgramling@gmail.com"

git config --list

# Setting up git repo

git init (from folder)

git remote add origin https://github.com/bgramling/gitlearn

git remote set-url origin https://github.com/bgramling/gitlearn (changed)

# Pushing to repo

git status

git add .

git commit -m 'Test Commit'

git push origin master

# Changes

git diff

git log

# Permanently authenticating with Git Repos

git config credential.helper store

git push https://github.com/bgramling/gitlearn.git

cache expire (seconds)
git config --global credential.helper "cache --timeout 7200"

# Reverting changes

git checkout -- .  (uncommitted)

git revert commit-num (committed)
-- can get from git log
