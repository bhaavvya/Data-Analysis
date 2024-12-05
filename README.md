# Data-Analysis
<h1>This repo containes Data analysis work I performed on different datasets</h1>
<p>It also includes my practice files.</p>

Here’s a **Git Commands for Beginners** section, formatted for a GitHub `README.md` file. You can copy and paste this directly into your `README.md` to provide an easy-to-read reference for Git commands.

---

# Git Commands for Beginners

This is a quick reference for basic Git commands, ideal for beginners to manage their repositories.

## 1. Setup and Configuration
```bash
# Set your name and email for Git commits
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# View your configuration settings
git config --list
```

---

## 2. Basic Commands
```bash
# Initialize a new Git repository
git init

# Clone an existing repository
git clone <repository-url>

# Check the status of your working directory
git status

# Stage a specific file for the next commit
git add <file>

# Stage all files for the next commit
git add .

# Commit staged changes with a message
git commit -m "Commit message"

# View the commit history
git log
```

---

## 3. Branching and Merging
```bash
# List all branches in the repository
git branch

# Create a new branch
git branch <branch-name>

# Switch to a different branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>

# Merge a branch into the current branch
git merge <branch-name>
```

---

## 4. Working with Remote Repositories
```bash
# Add a remote repository named 'origin'
git remote add origin <repository-url>

# Push your local branch to the remote repository
git push origin <branch-name>

# Fetch and merge changes from the remote branch
git pull origin <branch-name>

# Fetch changes from the remote repository (without merging)
git fetch origin
```

---

## 5. Undo Changes
```bash
# Discard changes in a specific file (revert to the last committed state)
git checkout -- <file>

# Unstage a file (remove from the staging area)
git reset HEAD <file>

# Undo the last commit, keeping changes in the staging area
git reset --soft HEAD~1

# Undo the last commit and discard all changes
git reset --hard HEAD~1
```

---

## 6. Viewing Differences
```bash
# Show changes between the working directory and the staging area
git diff

# Show changes between the staging area and the last commit
git diff --staged
```

---

## 7. GitHub-Specific Commands
```bash
# Push changes to the 'main' branch on GitHub
git push origin main

# Pull the latest changes from the 'main' branch on GitHub
git pull origin main

# Clone a GitHub repository to your local machine
git clone <repository-url>
```

---

## 8. Miscellaneous
```bash
# Save changes temporarily and clean the working directory
git stash

# Apply stashed changes back to the working directory
git stash pop

# Apply commits from one branch onto another
git rebase <branch-name>
```

---

## Notes
- Use `git status` frequently to check the status of your files.
- Make sure to add a descriptive commit message while committing changes.
- Be cautious while using `git reset` and `git rebase` as they can modify the commit history.

---
