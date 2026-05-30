# Quick Start Guide - 5 Minutes to Live Website

## Step 1: Customize Your Content (2 minutes)

Edit `index.html` in a text editor and change:
- Line 9: `<title>GamingZones - Professional Profile</title>` → Your name
- Line 39: `<h1>GamingZones</h1>` → Your name
- Line 40: `<p class="subtitle">Professional Web Developer & Tech Enthusiast</p>` → Your title
- Line 68-70: Update your bio in the about section
- Line 86-94: Update experience details
- Line 118-122: Update your skills in each category
- Line 161-200: Update your projects
- Line 238: `<a href="mailto:your.email@example.com"` → Your email
- Line 243: Update LinkedIn URL (line 243)
- Line 247: Update GitHub URL (line 247)
- Line 251: Update Twitter URL (line 251)

## Step 2: Create GitHub Account (1 minute)
1. Go to github.com and sign up
2. Verify your email

## Step 3: Deploy to GitHub (2 minutes)

Open PowerShell and run:

```powershell
cd C:\Users\GamingZones\Desktop\Webpage
git init
git add .
git commit -m "Portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username (same username appears twice)

## Step 4: Enable GitHub Pages

1. Go to your GitHub repository
2. Click "Settings"
3. Click "Pages" in the left menu
4. Make sure "main" branch is selected
5. Click "Save"

## Done! 🎉

Your website is now live at: `https://YOUR-USERNAME.github.io`

(Wait 2-5 minutes for deployment)

---

**Need Help?**
- Full guide in README.md
- GitHub Pages docs: pages.github.com
- Can't see your site? Check repository Settings → Pages
