# 💅 Ashley's Nails - Hello Kitty Themed Website

Welcome to Ashley's Nails! This is a super cute, girly Hello Kitty themed website for a nail salon business.

## ✨ Features

- 🎀 **Adorable Hello Kitty Theme**: Pink, cute, and kawaii-inspired design
- 💖 **Animated Background**: Floating bow animations for extra cuteness
- 📱 **Fully Responsive**: Looks great on all devices
- 🌸 **Complete Sections**:
  - Hero section with call-to-action
  - Services showcase with pricing
  - Gallery display
  - About section
  - Contact information
- ✨ **Smooth Animations**: Hover effects, bouncing elements, and transitions
- 🎨 **Custom Styling**: Unique fonts (Pacifico & Fredoka) and pink color palette

## 🚀 Quick Start - Deploy to Vercel

### Method 1: GitHub + Vercel (Recommended)

1. **Upload to GitHub**:
   - Create a new repository on GitHub
   - Upload all files from this ZIP to your repository
   - Make sure `index.html` and `vercel.json` are in the root directory

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect the configuration
   - Click "Deploy"
   - Your site will be live in seconds! 🎉

### Method 2: Direct Upload to Vercel

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Select "Upload" tab
4. Drag and drop this entire folder
5. Click "Deploy"

## 📁 File Structure

```
ashleys-nails/
│
├── index.html          # Main website file
├── vercel.json         # Vercel configuration
└── README.md          # This file
```

## 📝 Customization Guide

### Changing Colors
The color scheme is defined in CSS variables at the top of the style section in `index.html`:
```css
:root {
    --pink-primary: #FF69B4;
    --pink-light: #FFB6D9;
    --pink-lighter: #FFE5F1;
    --pink-dark: #FF1493;
}
```

### Updating Services
Find the `services-grid` section in `index.html` and modify the service cards with your own offerings and prices.

### Adding Real Images
Replace the emoji placeholders in the gallery section with actual images:
```html
<div class="gallery-item">
    <img src="your-image.jpg" alt="Nail design" style="width: 100%; height: 100%; object-fit: cover; border-radius: 20px;">
</div>
```

To add images:
1. Create an `images` folder in your repository
2. Upload your nail photos
3. Reference them like: `<img src="images/nail-design-1.jpg">`

### Contact Information
Update the contact section with your real business details:
- Address
- Phone number
- Email
- Business hours

## 🔧 Troubleshooting

### Site not loading on Vercel?
- Make sure `index.html` is in the root directory (not in a subfolder)
- Check that `vercel.json` is also in the root directory
- Clear your browser cache and try again

### Fonts not loading?
- The site uses Google Fonts which require an internet connection
- If fonts don't load, check your internet connection

### Images not showing?
- Make sure image paths are correct
- Images should be in the same repository
- Use relative paths like `./images/photo.jpg`

## 🎨 Tech Stack

- Pure HTML5
- CSS3 with animations
- Google Fonts (Pacifico & Fredoka)
- No JavaScript required (purely CSS animations)
- Vercel-ready configuration

## 💡 Tips for Vercel Deployment

- Vercel automatically deploys every time you push to GitHub
- Your site URL will be: `your-project-name.vercel.app`
- You can add a custom domain in Vercel settings
- Free plan includes unlimited deployments!

## 🌐 Alternative Deployment Options

### GitHub Pages
1. Go to your repository Settings → Pages
2. Select your branch (usually `main`)
3. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the folder to [netlify.com](https://netlify.com)
2. Your site deploys instantly!

## 📞 Need Help?

If you're still having issues with Vercel:
1. Check that all files are in the root directory
2. Make sure there are no special characters in file names
3. Try deploying via the Vercel CLI: `vercel`

---

Made with 💖 for Ashley's Nails | Stay cute! ✨
