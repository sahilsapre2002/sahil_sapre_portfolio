# Quick Deployment Guide

## 🚀 Deploy to Netlify in 3 Steps

### Option 1: Drag & Drop (Easiest - 2 minutes)

1. **Go to Netlify**
   - Visit [https://app.netlify.com/drop](https://app.netlify.com/drop)
   - Sign up/Login (free account)

2. **Drag & Drop**
   - Drag the entire "portfolio website" folder to the Netlify drop zone
   - Wait 10-20 seconds for deployment

3. **Done!** 
   - Your site is live!
   - Netlify will give you a URL like: `https://random-name-123456.netlify.app`
   - You can customize the URL in site settings

### Option 2: GitHub + Netlify (Recommended for Updates)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio website"
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Connect to Netlify**
   - Go to [https://app.netlify.com](https://app.netlify.com)
   - Click "New site from Git"
   - Choose GitHub and select your repository
   - Click "Deploy site"

3. **Auto-Deploy**
   - Every time you push to GitHub, Netlify auto-deploys
   - Your updates go live automatically!

### Option 3: Netlify CLI (For Developers)

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy (from project folder)
netlify deploy --prod
```

## 🌐 Custom Domain (Optional)

1. In Netlify Dashboard → Domain Settings
2. Add your custom domain
3. Follow DNS configuration instructions
4. Your site will be live at your domain!

## 📸 Before Deployment

✅ Replace `profile-photo.jpg` with your actual photo
✅ Update GitHub and LinkedIn URLs in `index.html`
✅ Test locally by opening `index.html` in browser
✅ Check all links work correctly

## 🔧 After Deployment

1. **Test your live site** - Click through all sections
2. **Check mobile responsiveness** - Test on phone
3. **Share your portfolio** - Add URL to LinkedIn, resume, etc.
4. **Update regularly** - Keep content fresh

## 💡 Tips

- **Custom URL**: Change random Netlify URL to something like `sahilsapre.netlify.app`
- **HTTPS**: Netlify provides free SSL certificate automatically
- **Performance**: Site loads in < 2 seconds globally
- **Analytics**: Enable Netlify Analytics to track visitors (optional, paid feature)

## 🐛 Troubleshooting

**Issue**: Site not loading
- **Fix**: Check if all files are uploaded (index.html, styles.css, script.js)

**Issue**: Images not showing
- **Fix**: Ensure profile-photo.jpg is in the same folder

**Issue**: Styling looks broken
- **Fix**: Clear browser cache and refresh

## 📧 Support

Need help? Contact: Sahil.Sapre@ibm.com

---

**Your portfolio will be live in minutes! 🎉**