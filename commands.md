
# Commands Guide

## 1. System Update Commands
```bash
sudo apt-get update          # Update package lists for upgrades and new installs
sudo apt-get upgrade         # Upgrade the installed packages
```

## 2. File Management Commands
```bash
mkdir git_Practice           # Create a new directory called 'git_Practice'
cd git_Practice/             # Navigate into the 'git_Practice' directory
pwd                          # Print the current working directory
ls                           # List the files and directories in the current directory
touch test.txt               # Create a new empty file named 'test.txt'
vim hello.txt                # Open or create a file named 'hello.txt' using Vim editor
cat hello.txt                # Display the content of 'hello.txt'
```

## 3. Git Initialization
```bash
git init                     # Initialize a new Git repository in the current directory
git status                   # Check the current status of the repository
git config                   # Display the Git configuration settings
```

## 4. Git File Operations
```bash
git add hello.txt            # Add 'hello.txt' to the staging area
git commit -m "hello"        # Commit staged changes with a message "hello"
git add test.txt             # Add 'test.txt' to the staging area
git commit -m "test"         # Commit staged changes with a message "test"
```

## 5. Branch Management
```bash
git branch -b devops_Practice  # Incorrect command; should use 'git checkout -b devops_Practice'
git checkout -b Devops_practice  # Create and switch to a new branch named 'Devops_practice'
git checkout -b Testing        # Create and switch to a new branch named 'Testing'
git checkout master            # Switch back to the 'master' branch
```

## 6. Viewing Git History
```bash
git log                      # View the full commit history
git log --oneline            # View commit history in a compact format (one line per commit)
```

## 7. Miscellaneous Commands
```bash
clear                        # Clear the terminal screen
history                      # Display the command history
```
