# Git-workflow-practice
Practicing git commands

# Git Command Practice

This repository was created while learning Git.  
I used the VS Code terminal to try different Git commands and understand how version control works.

The purpose of this repository is to practice basic Git operations such as creating a repository, committing changes, working with branches, and connecting to GitHub.

---

## Basic Git Commands

- `git init`  
  Starts a new Git repository in the current folder.

- `git status`  
  Shows the current condition of the repository and files.

- `git add <file-name>`  
  Adds a specific file to the staging area.

- `git add .`  
  Adds all modified files to the staging area.

- `git commit -m "message"`  
  Saves the staged changes with a commit message.

- `git log`  
  Displays the full commit history.

- `git log --oneline`  
  Shows a shorter version of the commit history.

---

## Working with Branches

- `git branch`  
  Displays all branches in the repository.

- `git branch <branch-name>`  
  Creates a new branch.

- `git checkout <branch-name>`  
  Moves from the current branch to another branch.

- `git checkout -b <branch-name>`  
  Creates a branch and switches to it immediately.

- `git branch -d <branch-name>`  
  Removes a branch that is no longer needed.

---

## Merging Changes

- `git merge <branch-name>`  
  Combines the changes from another branch into the current branch.

During practice I also observed:
- Fast-forward merge
- Resolving merge conflicts manually

---

## Connecting to Remote Repository

- `git remote -v`  
  Displays the remote repository linked with the project.

- `git remote add origin <repository-link>`  
  Connects the local repository to GitHub.

- `git push -u origin main`  
  Uploads the commits to the remote repository.

- `git pull origin main`  
  Downloads the latest updates from GitHub.