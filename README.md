# Swathi Nadendla - Personal Website

A modern, professional personal website showcasing research, publications, and expertise in bioinformatics and computational biology.

## 🚀 Quick Start - Deploy to GitHub Pages

Follow these steps to get your website live on GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Name your repository: `swathiramakrishnan.github.io` 
   - **IMPORTANT**: Use your GitHub username instead of "swathiramakrishnan"
   - Format must be: `yourusername.github.io`
5. Set the repository to **Public**
6. **DO NOT** initialize with README, .gitignore, or license
7. Click **"Create repository"**

### Step 2: Upload Your Website Files

#### Option A: Using GitHub Web Interface (Easiest)

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Scroll down and click **"Commit changes"**

#### Option B: Using Git Command Line

```bash
# Navigate to the folder containing your website files
cd /path/to/your/website/folder

# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Personal website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top right)
3. Click **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **"Save"**

### Step 4: Visit Your Website! 🎉

Your website will be live at: `https://yourusername.github.io`

It may take 1-2 minutes for the site to deploy. Refresh the page if it doesn't load immediately.

## 📁 File Structure

```
├── index.html          # Main HTML file with all content
├── styles.css          # All styling and animations
├── script.js           # Interactive features and animations
└── README.md          # This file with deployment instructions
```

## 🎨 Customization

### Updating Content

1. Edit `index.html` to update:
   - Contact information
   - Research descriptions
   - Publications
   - Awards

2. To change colors, edit the CSS variables in `styles.css`:
```css
:root {
    --primary: #0A5F5F;        /* Main color */
    --accent: #D4763A;         /* Accent color */
    /* ... other colors */
}
```

### Adding a Custom Domain (Optional)

If you buy a custom domain like `swathiramakrishnan.com`:

1. In your repository, go to **Settings** > **Pages**
2. Under **"Custom domain"**, enter your domain name
3. Click **"Save"**
4. Follow GitHub's instructions to configure DNS settings with your domain provider

## 🔧 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Scroll-triggered fade-ins and hover effects
- **Modern Aesthetics**: Professional, clean design with distinctive typography
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **SEO Friendly**: Semantic HTML structure

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips

- **Update regularly**: Keep your publications and awards current
- **Check mobile**: Always preview on mobile devices
- **Use high-quality**: If adding images, use optimized files
- **Back up**: Keep a copy of your files locally

## 🆘 Troubleshooting

**Website not loading?**
- Wait 2-3 minutes after deployment
- Check that GitHub Pages is enabled in Settings
- Ensure repository name matches `yourusername.github.io`

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Wait a few minutes for GitHub to rebuild

**Styling looks broken?**
- Ensure all three files (HTML, CSS, JS) are in the same folder
- Check file names match exactly (case-sensitive)

## 📞 Need Help?

If you run into issues:
1. Check the GitHub Pages documentation: https://docs.github.com/en/pages
2. Review the troubleshooting section above
3. Make sure all files are in the root directory of your repository

---

**Built with**: HTML5, CSS3, JavaScript
**Fonts**: Crimson Pro, DM Sans (Google Fonts)
**Hosting**: GitHub Pages

Good luck with your new website! 🚀
