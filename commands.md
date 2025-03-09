# Git Commands by Topic

## 1. Setup and Initialization
Initialize a new Git repository and set up the project directory.
```bash
git init  # Initialize a new Git repository
mkdir git-devops  # Create a new directory
cd git-devops  # Change into the directory
pwd  # Print the working directory
ls -a  # List all files, including hidden ones
```

## 2. File Operations
Create, edit, and remove files in the repository.
```bash
touch file1.txt file2.txt  # Create multiple files
vim hello.txt  # Open a file in Vim editor
rm file1.txt  # Remove a file
ls  # List files in the directory
```

## 3. Staging and Unstaging Files
Manage the staging area before committing changes.
```bash
git status  # Check the status of the working directory
git add .  # Stage all changes
git rm --cached file2.txt  # Unstage file2.txt
git add file2.txt  # Stage file2.txt again
```

## 4. Committing Changes
Record changes to the repository with meaningful messages.
```bash
git commit -m "adding 3 files"  # Commit changes with a message
git commit -m "added new changes to hello.txt"
git commit -m "changes to file1.txt"
```

## 5. Branching and Switching Branches
Create and switch between different branches.
```bash
git branch  # List all branches
git checkout -b dev  # Create and switch to a new branch
git checkout master  # Switch back to the master branch
git checkout dev  # Switch to the dev branch
```

## 6. Viewing Commit History
Examine the commit history of the repository.
```bash
git log  # Show commit history
git log --oneline  # Show commit history in one line
git log --oneline --graph  # Show commit history as a graph
```

## 7. Restoring and Undoing Changes
Revert or recover deleted files.
```bash
git restore file1.txt  # Restore a deleted file
```

## 8. Checking Repository Status
Check the current status of files in the repository.
```bash
git status  # Check the current status of the repository
```

## 9. Viewing Command History
View the history of commands executed in the terminal.
```bash
history  # Show command history
```

