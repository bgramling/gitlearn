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

