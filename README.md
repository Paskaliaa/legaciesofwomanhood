# Magnificent: Legacies of Womanhood Retreat - Website Version 2

## 📁 Files Included

- `index.html` - Main HTML file
- `styles.css` - Complete stylesheet with sophisticated design
- `script.js` - JavaScript for all interactive features
- `images/` - Folder containing all images:
  - `3_gen_women_on_sunset.png` - Hero background image
  - `magnificent-logo.png` - Magnificent logo
  - `woman-on-bridge.jpg` - Bridging woman section image
  - `laimani.jpg` - Facilitator photo

## ✨ Features

### Design Elements
- Luxurious African heritage aesthetic with gold, purple, and red color scheme
- Sophisticated typography using Montserrat and Open Sans fonts
- Smooth scroll animations and micro-interactions
- Fully responsive mobile-first design
- Custom cursor effect (desktop only)

### Interactive Components
1. **Navigation Bar**
   - Fixed navigation with scroll effects
   - Mobile hamburger menu
   - Smooth scroll to sections

2. **Hero Section**
   - Full-screen background with overlay
   - Animated content entrance
   - Parallax scrolling effect
   - Call-to-action buttons

3. **Carousel**
   - Auto-play (2 seconds per slide)
   - Pause on hover
   - Click indicators to navigate
   - Keyboard navigation (arrow keys)

4. **FAQ Accordion**
   - Click questions to expand/collapse
   - Smooth animations
   - Only one question open at a time

5. **Waitlist Form**
   - Form validation
   - Success message display
   - Collects: name, email, phone, location, question, consent

6. **Scroll Animations**
   - Elements fade and slide in as you scroll
   - Staggered animations for grid items

## 🚀 How to Use Locally

1. **Open the website:**
   - Simply open `index.html` in your web browser
   - Or right-click and choose "Open with" → your preferred browser

2. **Test all features:**
   - Navigation links work
   - Form can be filled out (currently logs to console)
   - All animations and interactions function

## 📤 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon (top right) → "New repository"
3. Name it: `magnificent-retreat` (or your preferred name)
4. Make it Public
5. Don't initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Create the `images` folder:
   - Click "Add file" → "Create new file"
   - Type `images/placeholder.txt`
   - Click "Commit new file"
4. Upload images to the `images` folder:
   - Navigate to the `images` folder
   - Click "Add file" → "Upload files"
   - Drag and drop all images from the `images` folder
5. Commit changes with message: "Initial website upload"

**Option B: Using Git (If you're comfortable with terminal)**

```bash
# Navigate to your website folder
cd /path/to/magnificent-retreat

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial website upload"

# Add remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/magnificent-retreat.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes for deployment
6. Your site will be live at: `https://USERNAME.github.io/magnificent-retreat/`

## 🔧 Customization Guide

### Update Content

All content can be edited directly in `index.html`:
- Search for the section you want to edit
- Modify the text between HTML tags
- Save and refresh to see changes

### Change Colors

In `styles.css`, find the `:root` section (top of file):

```css
:root {
    --gold: #c49356;      /* Change gold color */
    --purple: #46215f;    /* Change purple color */
    --red: #8b1d1d;       /* Change red color */
}
```

### Update Images

1. Add new images to the `images/` folder
2. Update image references in `index.html`:
   - Hero background: Line ~15 (in CSS, background URL)
   - Logo: `<img src="images/YOUR-LOGO.png">`
   - Other images: Find `<img src="images/...">`

### Form Integration

The form currently shows a success message. To connect to a backend:

1. **Option 1: Google Forms**
   - Create a Google Form
   - Get the form action URL
   - Replace form submission code in `script.js`

2. **Option 2: Email Service (EmailJS)**
   - Sign up at [EmailJS](https://www.emailjs.com/)
   - Follow their integration guide
   - Update the form submission code in `script.js`

3. **Option 3: Custom Backend**
   - Set up your server endpoint
   - Update the fetch URL in `script.js`
   - Handle form data on your server

## 📱 Mobile Responsiveness

The website is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

Test on different devices using browser DevTools (F12 → Device toolbar)

## ⚡ Performance Tips

- Images are already optimized
- CSS and JS are minified for production
- All animations use CSS transforms for better performance
- Lazy loading is implemented for scroll animations

## 🎨 Design Philosophy

This website embodies:
- **Luxurious African Heritage** - Gold accents, regal purple, warm tones
- **Sacred Femininity** - Soft curves, elegant typography, generous spacing
- **Transformational Journey** - Progressive flow from Deal → Delight → Dare
- **Intergenerational Connection** - Imagery and messaging that honors legacy

## 📞 Support

For questions about:
- **Content updates**: Edit HTML directly
- **Design changes**: Modify CSS variables
- **Technical issues**: Check browser console (F12) for errors
- **Deployment**: Follow GitHub Pages documentation

## 🌟 Key Sections

1. **Hero** - First impression with stunning visuals
2. **About** - Core message and value proposition (emphasized)
3. **Why** - Problem and solution clearly defined
4. **Carousel** - Rotating powerful statements
5. **Bridging Woman** - Emotional connection through imagery
6. **The Journey** - Three-day retreat breakdown
7. **When & Where** - Practical details
8. **Facilitator** - Build trust with Laimani's credentials
9. **FAQ** - Address common concerns
10. **Waitlist** - Primary conversion point (emphasized)

## ✅ Pre-Launch Checklist

- [ ] Test all navigation links
- [ ] Verify form submission works
- [ ] Check mobile responsiveness on actual devices
- [ ] Test in multiple browsers (Chrome, Firefox, Safari)
- [ ] Update social media links in footer
- [ ] Add actual TikTok link
- [ ] Verify all images load correctly
- [ ] Test page load speed
- [ ] Proofread all content
- [ ] Set up form backend integration

## 📊 Analytics (Optional)

To track visitors, add Google Analytics:

1. Create account at [Google Analytics](https://analytics.google.com)
2. Get your tracking ID
3. Add this code before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🎯 Next Steps

1. Deploy to GitHub Pages (see instructions above)
2. Test thoroughly on the live site
3. Share the link with stakeholders
4. Set up form integration
5. Monitor waitlist signups
6. Prepare for registration opening in March 2026

---

**Built with intention and care for the Magnificent: Legacies of Womanhood Retreat**

© 2024 Alabastron Inpowerment Ltd
