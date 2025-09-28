# 📓 Journal Guide  

This guide will help you create and manage your own **Journal Repository** on GitHub.  
Don’t worry if you are not techy — just follow step by step. 🚀  

---

## 1. Fork the Repository  

👉 Forking means creating your **own copy** of someone else’s repository.  
You need this so you can work on your journal separately, without changing the original.  

1. Go to the main journal repository: [ftw-de-journal](https://github.com/ogbinar/ftw-de-journal/tree/main).  
2. On the top-right of the page, click the **Fork** button.  
3. Select your GitHub account.  
   - Now you will have your own copy of the repository under your account.  

---

## 2. Clone Your Fork to Your Computer  

👉 Cloning means **downloading your repository to your laptop/PC**, so you can work on it offline.  

1. Go to **your forked repository** (it should look like `https://github.com/<your-username>/ftw-de-journal`).  
2. Click the green **Code** button.  
3. Copy the HTTPS link (example: `https://github.com/<your-username>/ftw-de-journal.git`).  
4. Open your terminal (Command Prompt, PowerShell, or Git Bash).  
5. Run this command:  

   ```bash
   git clone https://github.com/<your-username>/ftw-de-journal.git
   ```

6. Go into the folder:  

   ```bash
   cd ftw-de-journal
   ```

---

## 3. Add or Update Your Journal  

👉 This is where you **write your journal entries**.  

1. Inside the repo folder, open it with your text editor (e.g., VS Code, Notepad, etc.).  
2. Add your journal entries inside your own folder (create one if it doesn’t exist).  
   - Example: `journals/week1.md`  
3. Save your file.  

---

## 4. Commit Your Changes  

👉 A commit is like **saving your progress with a note**.  

1. In the terminal, check what changed:  

   ```bash
   git status
   ```

2. Add your file(s):  

   ```bash
   git add .
   ```

3. Commit your changes:  

   ```bash
   git commit -m "Added Week 1 journal entry"
   ```

---

## 5. Push to Your GitHub  

👉 Pushing means **uploading your changes** from your computer back to GitHub so everyone can see your changes.

```bash
git push origin main
```

---

## 6. Make Sure Your Repo is Public  

👉 Making your repo public means **others can see your journal**.  

1. Go to your forked repo on GitHub.  
2. Click on **Settings**.  
3. Scroll down to **Danger Zone** → Check **Repository visibility**.  
4. If it’s Private, click **Change visibility** → **Public**.  

---

✅ Charan! You now have your own **public journal repository** that you can update each week. 🎉  
