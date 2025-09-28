# 🐙 Git Basics for Journal Repos  

Here are the most common Git commands you’ll need for managing your journal repository.  

---

## 1. Check your Git version  

```bash
git --version
```

👉 This shows if Git is installed on your computer.  

---

## 2. Configure Git (first time only)  

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

👉 This sets your name and email for commits.  

---

## 3. Clone a repository  

```bash
git clone https://github.com/<your-username>/ftw-de-journal.git
```

👉 This downloads your forked repo to your computer.  

---

## 4. Check status  

```bash
git status
```

👉 Shows what has changed since the last save (commit).  

---

## 5. Add changes  

```bash
git add .
```

👉 Stages all changed files (prepares them to be saved).  
Use `git add filename.md` to add only one file.  

---

## 6. Commit changes  

```bash
git commit -m "Your message here"
```

👉 Saves your work locally with a short message.  
Example:  

```bash
git commit -m "Added Week 1 journal entry"
```

---

## 7. Push to GitHub  

```bash
git push origin main
```

👉 Uploads your commits from your computer to your GitHub repo.  

---

## 8. Pull latest changes (if needed)  

```bash
git pull origin main
```

👉 Gets the latest updates from your GitHub repo into your local folder.  

---

## 9. See commit history  

```bash
git log --oneline
```

👉 Shows a list of your past commits.  

---

## 10. Create a new branch (optional, advanced)  

```bash
git checkout -b new-branch-name
```

👉 Makes a separate “workspace” to try new things without touching `main`.  

---

✅ That’s it! With these commands, you can:  
- Download your repo (clone)  
- Save progress (add + commit)  
- Upload to GitHub (push)  
- Stay updated (pull)  

Keep this as your **cheat sheet** while doing your journals 🚀  
