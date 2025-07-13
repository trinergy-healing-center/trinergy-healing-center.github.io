# trinergy-healing-center.github.io


# GitHub Pages Hosting Guide

## Quick Setup for GitHub Pages

Your website is perfectly suited for GitHub Pages hosting. Here's how to set it up:

### Step 1: Create GitHub Repository

You've already created a GitHub repository named:

```
trinergy-healing-center.github.io
```

This naming convention (`username.github.io`) tells GitHub to treat it as a **user site**, and it will be served directly from the repository root.

> ✅ Since your repo is already set, you can skip this step.

---

### Step 2: Prepare Files for GitHub Pages

Place your website files directly in the root of the repository. Your current file structure is:

```
trinergy-healing-center.github.io/
├── index.html
├── README.md
├── script.js
└── style.css
```

This is perfect for GitHub Pages.

---

### Step 3: Upload or Push Files

#### Option A: Web Interface (Skip if already done)
1. Go to your GitHub repository
2. Click **"Add file" → "Upload files"**
3. Upload `index.html`, `script.js`, and `style.css`
4. Commit the changes

#### Option B: Git Commands
If you want to upload via Git from your local machine:

```bash
git clone https://github.com/yourusername/trinergy-healing-center.github.io.git
cd trinergy-healing-center.github.io

# Copy your site files into this folder if not already there
git add .
git commit -m "Initial commit of Trinergy Healing Center website"
git push origin main
```

---

### Step 4: GitHub Pages is Already Active

Since your repository is named `trinergy-healing-center.github.io`, GitHub automatically serves it as a **user site**.

No need to manually enable Pages in the settings.

---

### Step 5: Access Your Website

Your live website is available at:

```
https://trinergy-healing-center.github.io
```

> It may take 1–10 minutes to reflect any new changes.

---

## Optional: Custom Domain

If you have your own domain (e.g. `trinergyhealing.com`):

1. Create a file named `CNAME` (no extension) in your repo root
2. Put your domain name inside it (e.g. `www.trinergyhealing.com`)
3. Go to **Settings → Pages → Custom domain**
4. Enter your domain name
5. Update your domain DNS settings to point to GitHub Pages

---

## Benefits of GitHub Pages

- ✅ Free hosting
- 🔐 Automatic HTTPS
- 🌍 Global CDN
- 🚫 No server maintenance
- 🔁 Easy updates with Git

---

## Notes

- GitHub Pages serves **static files only**
- Your current setup with HTML, CSS, and JS works perfectly
- No backend, database, or server code is supported
- Perfect for personal, business, and informational websites