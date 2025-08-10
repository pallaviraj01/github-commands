# Git & GitHub Command

A quick reference for commonly used Git commands to manage repositories efficiently.

---

## 1. Setup & Configuration

| Command | Description |
|---------|-------------|
| `git config --global user.name "Your Name"` | Set your name for commits. |
| `git config --global user.email "your@email.com"` | Set your email for commits. |
| `git config --list` | View all Git configurations. |

---

## 2. Starting a Repository

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository in the current folder. |
| `git clone <repo-url>` | Clone an existing repository from GitHub. |

---

## 3. Basic Workflow

| Command | Description |
|---------|-------------|
| `git status` | Show the current status of changes. |
| `git add <file>` | Stage a specific file for commit. |
| `git add .` | Stage all changes in the current directory. |
| `git commit -m "message"` | Commit staged changes with a message. |
| `git log` | Show commit history. |

---

## 4. Branching & Merging

| Command | Description |
|---------|-------------|
| `git branch` | List all branches. |
| `git branch <branch-name>` | Create a new branch. |
| `git checkout <branch-name>` | Switch to a branch. |
| `git checkout -b <branch-name>` | Create and switch to a new branch. |
| `git merge <branch-name>` | Merge a branch into the current branch. |

---

## 5. Working with Remote

| Command | Description |
|---------|-------------|
| `git remote -v` | View linked remote repositories. |
| `git remote add origin <url>` | Link a local repo to a remote one. |
| `git push -u origin main` | Push changes to the main branch (first time). |
| `git push` | Push committed changes to remote. |
| `git pull` | Fetch and merge changes from remote. |

---

## 6. Undoing Changes

| Command | Description |
|---------|-------------|
| `git restore <file>` | Discard local changes to a file. |
| `git reset <file>` | Unstage a file but keep changes. |
| `git reset --hard` | Discard all changes and reset to the last commit. |

---

## 7. Extra Helpful Commands

| Command | Description |
|---------|-------------|
| `git diff` | Show changes in tracked files. |
| `git stash` | Temporarily save changes without committing. |
| `git stash pop` | Restore stashed changes. |

---

> 💡 **Tip:** Always commit small, logical changes with clear messages to maintain a clean commit history.
