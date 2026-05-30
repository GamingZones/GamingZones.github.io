# GamingZones - Professional Portfolio Website

A modern, professional personal portfolio website built with HTML, CSS, and JavaScript. Hosted on GitHub Pages for free and accessible to anyone on the web.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Professional Layout**: Clean, modern design with smooth animations
- **Multiple Sections**:
  - Hero/Landing section
  - About Me
  - Skills (organized by categories)
  - Projects showcase
  - Contact information
  - Footer with social links
- **Smooth Scrolling**: Navigation with smooth scroll animations
- **Interactive Elements**: Hover effects and scroll-triggered animations
- **Cross-browser Compatible**: Works on all modern browsers

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser to preview locally
3. Customize the content with your own information:
   - Update your name and title
   - Add your bio and experience
   - Modify skills and projects
   - Update contact links

### Customization Guide

#### Edit Your Information
Open `index.html` and modify:
- **Name**: Change "GamingZones" to your name
- **Title**: Update "Professional Web Developer & Tech Enthusiast"
- **About Section**: Update the biography and experience details
- **Skills**: Modify the skill categories and items
- **Projects**: Replace project examples with your own
- **Contact Links**: Update email, LinkedIn, GitHub, Twitter URLs

#### Styling
The website uses CSS variables for easy color customization. Edit `style.css`:
```css
:root {
    --primary-color: #2c3e50;      /* Main color */
    --secondary-color: #3498db;    /* Accent color */
    --accent-color: #e74c3c;       /* Highlight color */
    /* ... other colors ... */
}
```

## Deployment to GitHub Pages (Free Hosting)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a new account
3. Verify your email address

### Step 2: Create a New Repository
1. Click the "+" icon in the top-right corner
2. Select "New repository"
3. **Important**: Name your repository `YOUR-USERNAME.github.io`
   - Replace `YOUR-USERNAME` with your actual GitHub username (all lowercase)
   - Example: `gamingzones.github.io`
4. Add a description (optional)
5. Make it **Public**
6. Click "Create repository"

### Step 3: Upload Your Files
You have two options:

#### Option A: Using GitHub Web Interface (Easiest)
1. Go to your new repository
2. Click "Add file" → "Upload files"
3. Drag and drop or select:
   - `index.html`
   - `style.css`
   - `script.js`
4. Click "Commit changes"

#### Option B: Using Git Command Line (Recommended)
1. Open PowerShell/Command Prompt
2. Navigate to your webpage folder:
   ```bash
   cd Desktop\Webpage
   ```
3. Initialize git and push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```
   Replace `YOUR-USERNAME` with your GitHub username (appears twice)

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (top right)
3. Scroll to "Pages" section in the left sidebar
4. Under "Source", make sure it's set to "main" branch
5. Click "Save"

### Step 5: Access Your Website
Your website is now live at: **https://YOUR-USERNAME.github.io**

It may take a few minutes (usually 2-5 minutes) for GitHub Pages to deploy. 

## Making Updates

After your site is live, you can make updates:

### Via Web Interface:
1. Go to your repository
2. Click on a file (e.g., `index.html`)
3. Click the pencil icon to edit
4. Make your changes
5. Click "Commit changes"

### Via Git Command Line:
```bash
cd Desktop\Webpage
git add .
git commit -m "Update portfolio content"
git push
```

Changes will appear on your live website within minutes.

## File Structure

```
.
├── index.html          # Main website page
├── style.css          # Styling and layout
├── script.js          # Interactivity and animations
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Success

1. **Keep it Updated**: Regularly update your projects and skills
2. **Add Real Content**: Replace placeholder projects with your own work
3. **Professional Email**: Use a professional email address in the contact section
4. **Social Links**: Ensure your LinkedIn and GitHub links are correct and public
5. **Test Responsiveness**: Check your site on mobile devices
6. **Custom Domain (Optional)**: You can later add a custom domain through GitHub Pages settings

## License

This template is free to use and modify for your personal portfolio.

## Support

For GitHub Pages issues, see the official documentation: [GitHub Pages Docs](https://pages.github.com/)

---

**Happy Coding!** 🚀

Once you push this to GitHub and enable Pages, your website will be accessible to anyone on the internet 24/7!
