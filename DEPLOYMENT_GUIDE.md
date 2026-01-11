# 🚀 GitHub Pages Deployment Guide

## Quick Setup (5 Minutes)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Use your business email: `info@hnfglobal.co.za`
4. Choose username: `hnfglobal` or `hnf-global-solutions`

### Step 2: Create New Repository
1. Click the **+** icon (top right) → **New repository**
2. Repository name: `hnf-website` or `hnfglobal.github.io`
3. Description: "HNF Global Solutions - Official Website"
4. Keep it **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 3: Upload Your Website Files
You have two options:

#### Option A: Drag & Drop (Easiest)
1. On the repository page, click **uploading an existing file**
2. Drag ALL files/folders from `HNF_webside` folder
3. Important: Upload these files:
   - `index.html`
   - `css/` folder
   - `js/` folder
   - `assets/` folder
   - `README.md`
4. Scroll down, click **Commit changes**

#### Option B: Using Git (Recommended for updates)
Open PowerShell in your project folder and run:

```powershell
# Navigate to your project
cd "C:\Users\User\OneDrive\Documents\HNF_webside"

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - HNF Global Solutions website"

# Add your GitHub repository (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/hnf-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. In your repository, go to **Settings**
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 2-3 minutes for deployment

### Step 5: Access Your Website! 🎉
Your website will be live at:
- **https://[your-username].github.io/hnf-website/**
- Example: `https://hnfglobal.github.io/hnf-website/`

---

## 🎯 Important Notes

### ✅ What's Ready:
- All contact info updated (Phone, Email, WhatsApp)
- BMW image included
- Logo integrated
- All 12 services listed
- Fully responsive design
- WhatsApp floating button working

### 📱 After Going Live:
- Test WhatsApp button on mobile
- Share link with clients
- Test contact form
- Add Google Analytics (optional)

### 🔄 Making Updates Later:
1. Edit files locally
2. Commit and push changes:
```powershell
git add .
git commit -m "Description of changes"
git push
```
3. Changes appear live in 1-2 minutes

---

## 🌐 Optional: Custom Domain

Want `www.hnfglobal.co.za` instead of GitHub URL?

1. Buy domain from:
   - **Afrihost** (R99/year)
   - **XNEELO** (R150/year)
   - **HostAfrica** (R120/year)

2. In GitHub Pages settings:
   - Add custom domain: `www.hnfglobal.co.za`
   - Enable HTTPS (automatic)

3. Update domain DNS records:
   - Type: `CNAME`
   - Host: `www`
   - Value: `[your-username].github.io`

---

## 🆘 Troubleshooting

**Website not showing?**
- Wait 3-5 minutes after enabling Pages
- Check repository is **Public**
- Ensure `index.html` is in root folder

**Images not loading?**
- Verify `assets/images/` folder uploaded
- Check file names match exactly (case-sensitive)

**Want to update content?**
- Edit `index.html` locally
- Push changes to GitHub
- Refresh website (clear cache: Ctrl+Shift+R)

---

## 📊 Next Steps (Optional)

1. **Analytics**: Add Google Analytics tracking code
2. **SEO**: Submit to Google Search Console
3. **Email**: Set up business email with domain
4. **Social Media**: Update social media links in footer
5. **Blog**: Add blog section for thought leadership

---

## 🎓 Need Help?

- GitHub Pages Docs: [docs.github.com/pages](https://docs.github.com/pages)
- Contact your developer if you need assistance
- GitHub support: [support.github.com](https://support.github.com)

**Your website is ready to go live! 🚀**
