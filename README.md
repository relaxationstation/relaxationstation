# Relaxation Station Website

A beautiful, production-grade website for the Relaxation Station YouTube channel—featuring nature ASMR videos and peaceful walks from New Zealand.

## 🌿 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Elegant Aesthetic**: Forest-inspired color palette with smooth animations
- **Optimized Performance**: Fast-loading with lazy image loading
- **SEO-Friendly**: Meta tags and structured content for search engines
- **Accessibility**: Semantic HTML and keyboard navigation support
- **GitHub Pages Ready**: Deploy instantly with zero configuration

## 📁 File Structure

```
your-repo/
├── index.html          # Main website (contains all styles)
├── images/             # Image assets folder
│   ├── nz-bush.jpg
│   ├── ben-image-2.jpg
│   ├── ben-portrait.png
│   └── logo.jpg
└── README.md          # This file
```

## 🚀 Deployment to GitHub Pages

### Method 1: Quick Setup (Recommended)

1. **Create a GitHub Repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it: `your-username.github.io` (or any name)
   - Set to Public
   - Click "Create Repository"

2. **Upload Your Files**
   - Clone the repository: `git clone https://github.com/your-username/your-repo.git`
   - Copy `index.html` and the `images/` folder into the cloned directory
   - Navigate to the folder: `cd your-repo`
   - Add files: `git add .`
   - Commit: `git commit -m "Initial website upload"`
   - Push: `git push -u origin main`

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll to "Pages" section
   - Set Source to "Deploy from a branch"
   - Select "main" branch
   - Your site will be live at: `https://your-username.github.io/your-repo`

### Method 2: Direct Upload (No Git Required)

1. Go to your GitHub repository
2. Click "Add file" → "Upload files"
3. Upload `index.html` and the entire `images/` folder
4. Click "Commit changes"
5. Go to Settings → Pages and enable GitHub Pages

## 🎨 Customization

### Change Colors
Edit the CSS variables in `index.html` (lines 20-30):
```css
:root {
    --forest-dark: #1a3a2e;      /* Primary dark color */
    --forest-medium: #2d5a47;    /* Secondary dark */
    --accent-green: #7cb342;     /* Accent color */
    --cream: #f5f1e8;            /* Text on dark */
    /* ... other colors ... */
}
```

### Update Content
- Search and replace "Ben Crossland" with your name
- Update the YouTube link (currently: `https://www.youtube.com/@Official-RelaxationStation/featured`)
- Modify the bio and channel story sections
- Change copyright year in footer

### Optimize Images
Images are embedded as file references. To replace them:
1. Add new images to the `images/` folder
2. Update the `src` attributes in `index.html` to point to your new images

## 📱 Responsive Breakpoints

The site is optimized for:
- Desktop (1200px and up)
- Tablet (768px to 1199px)
- Mobile (below 768px)

All sections stack nicely on smaller screens.

## ⚡ Performance

- **Single HTML file**: No extra HTTP requests for stylesheets or scripts
- **Lazy loading**: Images load only when needed
- **Optimized images**: Pre-compressed and formatted
- **Smooth animations**: CSS-only, no JavaScript overhead
- **Fast load times**: Perfect for all network speeds

## 🔍 SEO Features

The site includes:
- Meta descriptions for search engines
- Open Graph tags for social media sharing
- Semantic HTML structure
- Mobile-friendly viewport settings
- Proper heading hierarchy

## 🎯 Key Sections

1. **Navigation**: Fixed header with smooth scrolling links
2. **Hero**: Eye-catching introduction with CTA buttons
3. **About**: Personal bio and quick stats
4. **Story**: Deep dive into channel history and mission
5. **Gallery**: Visual showcase of nature photography
6. **CTA**: Call-to-action to YouTube channel
7. **Footer**: Links, social media, and copyright

## 💡 Tips for Success

- Keep content updated regularly
- Add new images to the gallery as you create videos
- Update the story section with new milestones
- Test on mobile before publishing
- Share the link across your social media

## 🛠️ Troubleshooting

**Images not showing?**
- Check that the `images/` folder is in the same directory as `index.html`
- Verify file names match exactly (case-sensitive on GitHub Pages)

**Links not working?**
- Make sure to deploy to GitHub Pages (not just a regular repository)
- Check that your repository is public

**Styles look broken?**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check that you didn't accidentally modify the `<style>` section

## 📞 Support

For GitHub Pages issues:
- Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
- Review your repository Settings → Pages

## 📄 License

This website was created for Relaxation Station. Feel free to customize and deploy!

---

**Created with peace and passion for nature.** 🌿

Remember: Your website is a reflection of your channel. Keep it updated, keep it authentic, and let your passion for nature shine through.
