# To-Do List Web App

A clean, modern To-Do List built with **HTML, CSS, and JavaScript**. Supports add/complete/delete tasks and saves them in **localStorage** so they persist across refreshes.

## ✨ Features
- Add tasks
- Mark tasks complete / undo
- Delete tasks
- Filter: **All / Active / Completed**
- Persistent storage via `localStorage`
- Minimal, responsive UI

---

## 🧑‍💻 Run Locally in VS Code

1. **Download** this project (or clone it) and open the folder in **VS Code**.
2. Open `index.html`:
   - **Option A:** Double-click `index.html` to open in your browser.
   - **Option B (recommended):** Install the VS Code extension **Live Server** → Right-click `index.html` → **Open with Live Server**. The page will auto-refresh when you edit files.

> 💡 If VS Code asks to “Trust the authors of the files”, click **Yes**.

---

## 🚀 Put It on GitHub

### Method 1 — Upload via Website
1. Go to **https://github.com** and log in.
2. Click **New** (create a repository). Name it: `todo-web-app`.
3. Click **Create repository**.
4. On the repo page, click **Add file → Upload files**.
5. Drag-and-drop your files (`index.html`, `README.md`, etc.) → **Commit changes**.

### Method 2 — Using Git (Command Line)
1. Open the project folder in a terminal (in VS Code: **Terminal → New Terminal**).
2. Run:
   ```bash
   git init -b main
   git add .
   git commit -m "Initial commit: To-Do List web app"
   git remote add origin https://github.com/<YOUR_USERNAME>/todo-web-app.git
   git push -u origin main
   ```
3. Replace `<YOUR_USERNAME>` with your GitHub username.

> If `-b main` isn't supported on your Git version, run `git init`, then `git branch -M main` after the first commit.

---

## 🌐 Free Hosting with GitHub Pages

1. Go to your repo **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose **Branch: `main`** and **/ (root)** → **Save**.
4. When GitHub Pages finishes publishing, your site will be available at:
   ```
   https://<YOUR_USERNAME>.github.io/todo-web-app/
   ```

---

## 📁 Project Structure

```
todo-web-app/
├─ index.html
└─ README.md
```

---

## 🧾 License
MIT — feel free to use and modify.
