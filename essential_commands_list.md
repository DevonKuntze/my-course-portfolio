# Setup
git config --global user.name "Name"
git config --global user.email "email"
git init

# Daily workflow
git status
git add .
git commit -m "message"

# Branching
git branch branch-name
git checkout branch-name
git checkout -b branch-name
git merge branch-name
git branch -d branch-name

# GitHub integration
git remote add origin URL
git push -u origin main
git push
git pull
git clone URL
