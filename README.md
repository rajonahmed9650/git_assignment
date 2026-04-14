
# Git DevOps Assignment

## Repository Overview
This project demonstrates Git branching, merging, rebasing, and commit history management.



##  Branches
- main
- develop
- feature/login
- feature/payment
- feature/profile
- bugfix/login-error
- feature/history


##  Commands Used

### Initialize Repo
git init
git branch -M main

### Branching
git checkout -b develop
git checkout -b feature/login
git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error

### Merge
git checkout develop
git merge feature/payment

### Rebase
git rebase feature/profile

### Commit History
git rebase -i HEAD~5



##  Screenshots

###  Git Log
![Git Log](https://github.com/user-attachments/assets/9a1a2cdd-1ea5-4f28-b10f-ae8bd80e7eb2)

###  Branch
![Branch](https://github.com/user-attachments/assets/d75ff41c-85ef-4f13-a9e7-839e130083a9)

###  Merge
![Merge](https://github.com/user-attachments/assets/8ffda5b6-8b29-4461-8f6d-840c050e9b1e)



## Explanation

###  Merge vs Rebase
- Merge creates a new commit and keeps history.
- Rebase rewrites history and keeps it clean.

###  Squash & Reword
- Squash combines multiple commits into one.
- Reword changes commit message.
