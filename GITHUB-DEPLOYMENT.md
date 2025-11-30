# Quick GitHub Pages Deployment Guide

## 🎯 Goal
Get your Magnificent website live on the internet in under 10 minutes!

## 📋 What You'll Need
- A GitHub account (free) - [Sign up here](https://github.com/signup)
- Your website files (you already have these!)

## 🚀 Step-by-Step Instructions

### STEP 1: Create a New Repository (2 minutes)

1. **Log into GitHub**
   - Go to [github.com](https://github.com)
   - Sign in with your username and password

2. **Create New Repository**
   - Click the **"+"** button (top right corner)
   - Select **"New repository"**

3. **Fill in Repository Details**
   - **Repository name**: `magnificent-retreat`
   - **Description**: "Magnificent: Legacies of Womanhood Retreat Website"
   - **Public** ✓ (select this option)
   - **Do NOT** check any boxes (no README, no .gitignore, no license)
   - Click **"Create repository"**

### STEP 2: Upload Your Files (3 minutes)

1. **Upload Main Files First**
   - You should now see an empty repository
   - Click **"uploading an existing file"** (blue link in the middle)
   - Drag and drop these files from your computer:
     - `index.html`
     - `styles.css`
     - `script.js`
   - In the commit message box at bottom, type: "Add main website files"
   - Click **"Commit changes"** (green button)

2. **Create Images Folder**
   - Click **"Add file"** → **"Create new file"**
   - In the name box, type: `images/temp.txt`
   - This creates the images folder
   - Type anything in the file content (like "temp")
   - Click **"Commit new file"**

3. **Upload Images**
   - Click on **"images"** folder (to go inside it)
   - Click **"Add file"** → **"Upload files"**
   - Drag and drop ALL images from your `images` folder:
     - `3_gen_women_on_sunset.png`
     - `magnificent-logo.png`
     - `woman-on-bridge.jpg`
     - `laimani.jpg`
   - Type commit message: "Add images"
   - Click **"Commit changes"**

4. **Delete Temporary File** (optional cleanup)
   - Go back to images folder
   - Click on `temp.txt`
   - Click the trash icon (top right)
   - Confirm deletion

### STEP 3: Enable GitHub Pages (2 minutes)

1. **Go to Settings**
   - Click **"Settings"** (top menu of your repository)

2. **Find Pages Section**
   - Look for **"Pages"** in the left sidebar
   - Click on it

3. **Configure GitHub Pages**
   - Under **"Source"**:
     - Select **"Deploy from a branch"**
   - Under **"Branch"**:
     - Select **"main"** from the first dropdown
     - Select **"/ (root)"** from the second dropdown
   - Click **"Save"**

4. **Wait for Deployment**
   - A blue box will appear saying "GitHub Pages source saved"
   - Wait about 1-2 minutes
   - Refresh the page
   - You'll see a green box with your live website URL!
   - It will look like: `https://your-username.github.io/magnificent-retreat/`

### STEP 4: Test Your Website (2 minutes)

1. **Click the Live Link**
   - Click the URL in the green box
   - Your website should load!

2. **Test Everything**
   - ✓ Navigation works
   - ✓ Images load correctly
   - ✓ Carousel auto-plays
   - ✓ FAQ accordion expands
   - ✓ Form displays
   - ✓ Mobile menu works (try on phone)

## 🎉 You're Done!

Your website is now live on the internet! Share this link:
`https://your-username.github.io/magnificent-retreat/`

## 🔧 Making Updates Later

Whenever you want to update your website:

1. Go to your repository on GitHub
2. Click on the file you want to edit (like `index.html`)
3. Click the pencil icon (✏️ Edit)
4. Make your changes
5. Scroll down and click "Commit changes"
6. Wait 1-2 minutes and your changes will be live!

## 📱 Custom Domain (Optional Advanced Step)

Want to use your own domain like `magnificent-retreat.com`?

1. Buy a domain from [Namecheap](https://namecheap.com) or [Google Domains](https://domains.google)
2. In GitHub Pages settings, add your custom domain
3. In your domain provider, point DNS to GitHub Pages
4. Full instructions: [GitHub Custom Domain Guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## ❓ Troubleshooting

**Problem: "404 - File not found" error**
- Solution: Make sure `index.html` is in the root folder, not in a subfolder

**Problem: Images not loading**
- Solution: Check that images are in the `images/` folder
- Check that image names in HTML match exactly (case-sensitive!)

**Problem: CSS not working**
- Solution: Make sure `styles.css` is in the same folder as `index.html`

**Problem: Can't find GitHub Pages settings**
- Solution: Make sure repository is Public (check Settings → General → Danger Zone)

**Problem: Changes not showing**
- Solution: Wait 2-3 minutes after committing
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)

## 📞 Need More Help?

- GitHub Pages Docs: https://docs.github.com/pages
- GitHub Community: https://github.community
- YouTube: Search "GitHub Pages tutorial"

## 🎯 Pro Tips

1. **Always test locally first** - Open `index.html` on your computer before pushing to GitHub
2. **Commit messages matter** - Write clear messages like "Fix contact form" not just "update"
3. **Keep a backup** - Save a copy of all files on your computer
4. **Test on mobile** - Most visitors will be on phones!
5. **Monitor traffic** - Set up Google Analytics (see main README)

---

**You've got this! 💪**

Your website is beautiful and professional. Trust the process and take it one step at a time.
