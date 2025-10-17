# 🧠 GitHub Commands Cheat Sheet  

> Learn Git in a day — from setup to advanced workflow 🚀  

This cheat sheet provides quick reference commands to help you master Git & GitHub from the terminal.  
Perfect for beginners and developers looking to refresh their Git skills.  

---

## ⚙️ Setup & Configuration  

| Command | Description |
|----------|-------------|
| `git config --global user.name "Your Name"` | Set your username |
| `git config --global user.email "you@example.com"` | Set your email address |
| `git config --list` | Check all configurations |

---

## 🧱 Starting a Repository  

| Command | Description |
|----------|-------------|
| `git init` | Initialize a new local repository |
| `git clone <url>` | Clone an existing repo from GitHub |

---

## 🔁 Basic Workflow  

| Command | Description |
|----------|-------------|
| `git status` | Check current status |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all modified files |
| `git commit -m "message"` | Commit staged changes |
| `git log` | Show commit history |

### 💡 Pro Tip: Use short, meaningful commit messages.
---

## 🌿 Branching  

| Command | Description |
|----------|-------------|
| `git branch` | List all branches |
| `git branch <name>` | Create a new branch |
| `git checkout <name>` | Switch to a branch |
| `git checkout -b <name>` | Create & switch to a new branch |
| `git merge <branch>` | Merge a branch into current |
| `git branch -d <name>` | Delete a branch |

### 🌱 Branches keep your main code safe while experimenting.
---

## 🌍 Remote Repositories (GitHub)  

| Command | Description |
|----------|-------------|
| `git remote -v` | View connected remotes |
| `git remote add origin <url>` | Add remote origin |
| `git push -u origin main` | Push the main branch (first time) |
| `git push` | Push latest commits |
| `git pull` | Fetch and merge changes |
| `git fetch` | Fetch branches/tags only |

### 🌐 Always pull before pushing to avoid merge conflicts.
---

## 🧹 Undo & Fix  

| Command | Description |
|----------|-------------|
| `git checkout -- <file>` | Discard local changes (before staging) |
| `git reset HEAD <file>` | Unstage a file |
| `git reset --hard HEAD` | Reset to last commit (⚠ loses changes) |
| `git revert <commit>` | Create a new commit that undoes a previous one |

### 🩹 Revert is safer than reset when working in shared repos.
---

## 📦 Stash  

| Command | Description |
|----------|-------------|
| `git stash` | Save uncommitted changes temporarily |
| `git stash pop` | Reapply last stash |
| `git stash list` | Show list of stashes |

### 📂 Useful when switching branches mid-work.
---

## 🏁 Tagging  

| Command | Description |
|----------|-------------|
| `git tag` | List all tags |
| `git tag <tagname>` | Create a new tag |
| `git push origin <tagname>` | Push tag to remote |
| `git push origin --tags` | Push all tags |

### 🏷️ Tags are great for marking release versions (v1.0, v2.0, etc).
---

## 💡 Pro Tips & Tricks
---

 ✨ Compact commit history
```
git log --oneline --graph
```

🧩 Check unstaged changes
```
git diff
```

👀 Review before commit
```
git status
```
---

## 📚 Author  

**Adarsh Lilhare**  
Developer & Tech Enthusiast | GitHub • Linux • Python • SQL  
📍 [TechCommand-Hub](https://github.com/yourusername/TechCommand-Hub)

---

## 🧩 License  

This resource is open-source and free to use under the [MIT License](LICENSE).

---
> _"Code, Commit, Push, Repeat."_ ✨  
