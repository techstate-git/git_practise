# 📘 Git Cheat Sheet for Students

### 🔧 Setup
```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```

### 📦 Basics
```bash
git init               # Initialize a new repo
git clone URL          # Clone from GitHub
git status             # Check current changes
git add file           # Stage file for commit
git commit -m "msg"    # Commit staged changes
git push               # Push to remote
git pull               # Pull latest changes
```

### 🌿 Branching
```bash
git branch             # List branches
git checkout -b NAME   # Create and switch branch
git checkout main      # Switch to main
```

### 🧙 Conflict & History
```bash
git pull               # Fetch & merge
git log --oneline      # Short log
git diff               # Show changes
git reset HEAD~1       # Undo last commit (soft)
git revert COMMIT_ID   # Revert a specific commit
git stash              # Save local uncommitted changes
git stash pop          # Restore stashed changes
```

### 🏷️ Tags
```bash
git tag v1.0           # Create tag
git push origin v1.0   # Push tag
```

> 🧠 Pro Tip: Commit often with clear messages. Pull before you push. Resolve conflicts with curiosity, not fear.
