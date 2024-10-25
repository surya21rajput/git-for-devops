Git Commands
1. Basic Git Setup
Set up username and email:

bash
Copy code
git config --global user.name "your_username"
git config --global user.email "your_email@example.com"
2. Initializing a Repository
Initialize a new Git repository:

bash
Copy code
git init
3. Checking Status and Listing Files
Show the status of the working directory:

bash
Copy code
git status
List all files, including hidden (.git) files:

bash
Copy code
ls -a
4. Adding and Removing Files
Add a single file to the staging area:

bash
Copy code
git add filename.txt
Add multiple files:

bash
Copy code
git add file1.txt file2.txt
Remove a file from the working directory:

bash
Copy code
rm filename.txt
Remove a file only from staging (cached):

bash
Copy code
git rm --cached filename.txt
5. Committing Changes
Commit changes with a message:

bash
Copy code
git commit -m "your commit message"
Amend the last commit with a new message:

bash
Copy code
git commit --amend -m "updated commit message"
6. Working with Branches
List all branches:

bash
Copy code
git branch
Create a new branch:

bash
Copy code
git checkout -b branch_name
Switch to an existing branch:

bash
Copy code
git checkout branch_name
7. Viewing Commit History
Show detailed commit history:

bash
Copy code
git log
Show commit history in one line per commit:

bash
Copy code
git log --oneline
8. Restoring and Reverting Changes
Restore a file from the last commit:

bash
Copy code
git restore filename.txt
Unstage a file:

bash
Copy code
git reset filename.txt
9. Merging Branches
Merge branch_name into the current branch:

bash
Copy code
git merge branch_name
10. Working with Remote Repositories
Add a remote repository:

bash
Copy code
git remote add origin https://github.com/username/repository.git
Push changes to the remote repository:

bash
Copy code
git push origin branch_name
Pull changes from the remote repository:

bash
Copy code
git pull origin branch_name
