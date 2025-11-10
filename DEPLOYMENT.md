# Quick GitHub Pages Deployment Guide

## 🚀 Quick Start (5 minutes)

### Method 1: Using GitHub Web Interface (Easiest)

1. **Create a New Repository**
   - Go to https://github.com/new
   - Repository name: `tejaaswin-resume` (or any name you prefer)
   - Make it **Public** (required for free GitHub Pages)
   - ✅ Check "Add a README file"
   - Click "Create repository"

2. **Upload Your Files**
   - In your new repository, click "Add file" → "Upload files"
   - Drag and drop ALL these files and folders:
     - `index.html`
     - `styles.css`
     - `script.js`
     - `Tejas.JPG`
     - `Tejaaswin_Raja.pdf`
     - `images/` folder (entire folder)
   - Scroll down, add commit message: "Initial commit - Resume website"
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to your repository
   - Click "Settings" tab (top menu)
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Branch: `main`, Folder: `/ (root)`
   - Click "Save"
   - Wait 1-2 minutes for deployment

4. **Your Website is Live!**
   - Your site will be at: `https://YOUR_USERNAME.github.io/tejaaswin-resume/`
   - Example: `https://terrifictejas25.github.io/tejaaswin-resume/`

### Method 2: Using Git Command Line

```bash
# Navigate to your project folder
cd C:\Temp\poc

# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit - Resume website"

# Add your GitHub repository (replace with your actual repo URL)
git remote add origin https://github.com/YOUR_USERNAME/tejaaswin-resume.git

# Rename branch to main
git branch -M main

# Push to GitHub
git push -u origin main
```

Then follow **Step 3** from Method 1 to enable GitHub Pages.

## 📝 Updating Your Website

### To Update Content:
1. Edit files locally (index.html, styles.css, etc.)
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Updated content"
   git push
   ```
3. Changes will appear on your live site in 1-2 minutes

### Using GitHub Web Interface:
1. Go to your repository on GitHub
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Scroll down, add commit message, click "Commit changes"
6. Site updates automatically!

## 🔗 Custom Domain (Optional)

If you want a custom domain like `tejaaswinraja.com`:

1. In GitHub Pages settings, add your custom domain
2. Follow GitHub's instructions for DNS setup
3. Your site will be available at your custom domain

## ✅ Checklist Before Publishing

- [ ] All images are in the correct folders
- [ ] Profile picture (Tejas.JPG) is in root directory
- [ ] Resume PDF (Tejaaswin_Raja.pdf) is in root directory
- [ ] Test the website locally by opening `index.html` in a browser
- [ ] Check all links work
- [ ] Verify mobile responsiveness

## 🎉 You're Done!

Your resume website is now live on GitHub Pages for free!

**Need Help?**
- GitHub Pages Documentation: https://docs.github.com/en/pages
- GitHub Support: https://support.github.com

