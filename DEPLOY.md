# 🚀 How to Deploy Your Portfolio to GitHub

Follow these steps to host your portfolio website for free using **GitHub Pages**.

## Prerequisites
1.  You must have a [GitHub account](https://github.com/).
2.  Your project files (`index.html`, `css/`, `js/`, `assets/`) should be ready.

## Step 1: Create a Repository on GitHub
1.  Log in to GitHub.
2.  Click the **+** icon in the top-right corner and select **New repository**.
3.  Name your repository (e.g., `my-portfolio` or `hemanth-portfolio`).
4.  Make sure it is **Public**.
5.  **Do not** initialize with a README, .gitignore, or license (we already have local files).
6.  Click **Create repository**.

## Step 2: Push Your Code to GitHub
Open your terminal (Command Prompt or PowerShell) inside your project folder `c:/portfolio` and run these commands one by one:

```bash
# 1. Initialize Git (if not done already)
git init

# 2. Add all files to staging
git add .

# 3. Commit your changes
git commit -m "Initial commit - Portfolio Website"

# 4. Link your local repo to GitHub (Replace YOUR-USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/my-portfolio.git

# 5. Rename the default branch to main
git branch -M main

# 6. Push your code
git push -u origin main
```

> **Note**: If `git push` fails, you might need to authenticate. Follow the prompts in the terminal.

## Step 3: Enable GitHub Pages
1.  Go to your repository settings on GitHub.
2.  On the left sidebar, click on **Pages**.
3.  Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4.  Under **Branch**, select `main` and `/ (root)`, then click **Save**.

## 🎉 Done!
Wait a minute or two. GitHub will provide you with a live URL (e.g., `https://your-username.github.io/my-portfolio/`).
Click it to see your live website!
