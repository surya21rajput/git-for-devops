# Git Commands

## 1. Basic Git Setup

Set up username and email:  
git config --global user.name "your_username"  
git config --global user.email "your_email@example.com"  

## 2. Initializing a Repository

Initialize a new Git repository:  
git init  

## 3. Checking Status and Listing Files

Show the status of the working directory:  
git status  

List all files, including hidden (.git) files:  
ls -a  

## 4. Adding and Removing Files

Add a single file to the staging area:  
git add filename.txt  

Add multiple files:  
git add file1.txt file2.txt  

Remove a file from the working directory:  
rm filename.txt  

Remove a file only from staging (cached):  
git rm --cached filename.txt  

## 5. Committing Changes

Commit changes with a message:  
git commit -m "your commit message"  

Amend the last commit with a new message:  
git commit --amend -m "updated commit message"  

## 6. Working with Branches

List all branches:  
git branch  

Create a new branch:  
git checkout -b branch_name  

Switch to an existing branch:  
git checkout branch_name  

## 7. Viewing Commit History

Show detailed commit history:  
git log  

Show commit history in one line per commit:  
git log --oneline  

## 8. Restoring and Reverting Changes

Restore a file from the last commit:  
git restore filename.txt  

Unstage a file:  
git reset filename.txt  

## 9. Merging Branches

Merge branch_name into the current branch:  
git merge branch_name  

## 10. Working with Remote Repositories

Add a remote repository:  
git remote add origin https://github.com/username/repository.git  

Push changes to the remote repository:  
git push origin branch_name  

Pull changes from the remote repository:  
git pull origin branch_name  
