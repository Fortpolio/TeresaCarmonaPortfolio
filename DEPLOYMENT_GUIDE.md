# Quick Deployment Guide for GitHub Pages

## Step-by-Step Instructions

### 1. Preview Locally First
- Open `index.html` in your web browser to preview the site
- Check that all information is correct
- Test the mobile menu and navigation

### 2. Initialize Git Repository

Open PowerShell in the project folder and run:

```powershell
git init
git add .
git commit -m "Initial commit: Maria Teresa Halili Portfolio"
```

### 3. Create GitHub Repository

1. Go to https://github.com and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Repository name: `TeresaCarmonaPortfolio` (or any name you prefer)
4. Keep it **Public**
5. **Do NOT** check "Initialize with README"
6. Click **"Create repository"**

### 4. Connect and Push to GitHub

Copy your GitHub username, then run these commands (replace `YOUR_USERNAME`):

```powershell
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/TeresaCarmonaPortfolio.git
git push -u origin main
```

If prompted, enter your GitHub credentials.

### 5. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Scroll down and click **"Pages"** (left sidebar)
4. Under **"Source"**:
   - Branch: Select **"main"**
   - Folder: Keep as **"/ (root)"**
5. Click **"Save"**

### 6. Access Your Live Site

Wait 2-5 minutes for GitHub to build your site.

Your portfolio will be live at:
```
https://YOUR_USERNAME.github.io/TeresaCarmonaPortfolio/
```

## Troubleshooting

### If Git is not installed:
Download from: https://git-scm.com/download/win

### If push fails due to authentication:
Use a Personal Access Token instead of password:
1. GitHub → Settings → Developer settings → Personal access tokens
2. Generate new token with "repo" scope
3. Use token as password when prompted

### If the site doesn't load:
- Wait a few more minutes (can take up to 10 minutes)
- Check Settings → Pages to see deployment status
- Make sure the repository is Public

## Updating Your Portfolio

When you make changes:

```powershell
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Pages will automatically update your live site in a few minutes.

## Next Steps

- Add a professional photo (replace the placeholder in About section)
- Customize colors if desired (edit `styles.css`)
- Connect the contact form to a service like Formspree
- Share your portfolio link on LinkedIn!

## Your Contact Information

- **Email**: mariateresacarmona0408@gmail.com
- **Phone**: 0992-783-0103
- **LinkedIn**: https://www.linkedin.com/in/maria-teresa-3902421aa
- **Location**: Malolos City, Bulacan, Philippines

---

Good luck with your portfolio! 🚀
