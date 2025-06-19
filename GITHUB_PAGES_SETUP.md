# GitHub Pages Hosting Guide

## Quick Setup for GitHub Pages

Your website is perfectly suited for GitHub Pages hosting. Here's how to set it up:

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it something like `trinergy-healing-center` or `healing-center-website`
3. Make it public (required for free GitHub Pages)
4. Initialize with README (optional)

### Step 2: Prepare Files for GitHub Pages

GitHub Pages serves files directly from your repository. You need to put the built files in the root of your repository:

**Files to upload:**
```
your-repository/
├── index.html (from dist/public/index.html)
├── assets/
│   ├── index-DoEXVzXo.css
│   └── index-JnC5CGCn.js
└── README.md (optional)
```

### Step 3: Upload Files

**Option A: Web Interface**
1. Go to your repository on GitHub
2. Click "Add file" → "Upload files"
3. Upload the `index.html` file to the root
4. Create an `assets` folder and upload the CSS and JS files
5. Commit changes

**Option B: Git Commands**
```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
# Copy the files from dist/public/* to this directory
git add .
git commit -m "Add Trinergy Healing Center website"
git push origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository settings
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch
5. Choose "/ (root)" folder
6. Click "Save"

### Step 5: Access Your Website

Your website will be available at:
`https://yourusername.github.io/repository-name`

For example: `https://johndoe.github.io/trinergy-healing-center`

## Custom Domain (Optional)

If you have your own domain:

1. Add a CNAME file to your repository root with your domain name
2. In repository settings → Pages → Custom domain, enter your domain
3. Configure your domain's DNS to point to GitHub Pages

## Benefits of GitHub Pages

- **Free hosting** for public repositories
- **Automatic HTTPS** certificate
- **Global CDN** for fast loading
- **No server maintenance** required
- **Easy updates** via Git

## File Structure for GitHub Pages

Make sure your repository looks like this:
```
├── index.html
├── assets/
│   ├── index-DoEXVzXo.css
│   └── index-JnC5CGCn.js
├── README.md
└── CNAME (if using custom domain)
```

## Important Notes

- Changes take 1-10 minutes to appear on your live site
- GitHub Pages serves static files only (perfect for your website)
- No databases or server-side code needed
- Website will work exactly as it does now

Your website is already optimized for GitHub Pages hosting!