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

---

## 🧹 Undo & Fix  

| Command | Description |
|----------|-------------|
| `git checkout -- <file>` | Discard local changes (before staging) |
| `git reset HEAD <file>` | Unstage a file |
| `git reset --hard HEAD` | Reset to last commit (⚠ loses changes) |
| `git revert <commit>` | Create a new commit that undoes a previous one |

---

## 📦 Stash  

| Command | Description |
|----------|-------------|
| `git stash` | Save uncommitted changes temporarily |
| `git stash pop` | Reapply last stash |
| `git stash list` | Show list of stashes |

---

## 🏁 Tagging  

| Command | Description |
|----------|-------------|
| `git tag` | List all tags |
| `git tag <tagname>` | Create a new tag |
| `git push origin <tagname>` | Push tag to remote |
| `git push origin --tags` | Push all tags |

---

## 💡 Tips  

- Use `git log --oneline --graph` for a compact history view.  
- Use `git diff` to see unstaged changes.  
- Use `git status` frequently to stay aware of your working state.  

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
