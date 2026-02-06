# Stephanie Moore - Personal Website

A professional personal website showcasing Stephanie Moore's work as a Product Manager specializing in health technology, continuous glucose monitoring, and wearable technology.

## Files Included

- `index.html` - Main landing page with all sections (About, Experience, Writing, Research, Contact)
- `garmin-cgm-blog.html` - Blog post about integrating Garmin with CGM
- `mega-meal-review.html` - Detailed competitive analysis of meal tracking apps
- `styles.css` - All styling with earthy blue and green color scheme
- `script.js` - Interactive features (smooth scrolling, animations)

## Features

### Design
- Professional, modern layout with earthy blue and green color palette
- Fully responsive design that works on desktop, tablet, and mobile
- Smooth scrolling navigation
- Fade-in animations on scroll
- Clean, readable typography

### Sections
1. **Hero** - Introduction with professional headshot
2. **About** - Background and core competencies
3. **Experience** - Expertise areas in health tech
4. **Writing** - Published articles and thought leadership (includes links to LinkedIn posts and the new Garmin-CGM blog)
5. **Research** - Product landscape analyses with detailed review pages
6. **Contact** - Multiple ways to connect

### Blog Posts
- **Garmin-CGM Integration** - Original blog post exploring the intersection of fitness tracking and metabolic monitoring
- **Mega-Meal Competitive Review** - Comprehensive analysis from the uploaded document

## How to Use

### Option 1: GitHub Pages (Recommended)
1. Create a new repository on GitHub (e.g., `stephaniemoore14.github.io`)
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from branch" and choose "main" branch
5. Your site will be live at `https://stephaniemoore14.github.io`

### Option 2: Local Testing
1. Simply open `index.html` in a web browser
2. All files will work locally since the image is embedded as base64

### Option 3: Other Hosting
Upload all files to any web hosting service:
- Netlify (free, drag-and-drop deployment)
- Vercel (free, supports GitHub integration)
- Traditional web hosting (upload via FTP)

## Customization

### Colors
The color scheme is defined in `styles.css` using CSS variables. To change colors, edit the `:root` section:

```css
:root {
    --primary-blue: #3d6b7d;
    --secondary-blue: #5a8a9f;
    --primary-green: #5f7a61;
    /* etc. */
}
```

### Content
- Edit text directly in the HTML files
- Update links in the Writing section
- Add new blog posts by creating new HTML files following the existing structure

### Images
The headshot is embedded as base64 data. To replace it:
1. Convert new image to base64
2. Replace the data in the `<img src="data:image/jpeg;base64,...">` attribute

## Contact Information
- Email: sgmoore209@gmail.com
- LinkedIn: linkedin.com/in/stephaniemoore209
- GitHub: github.com/StephanieMoore14

## Browser Compatibility
Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Size Note
The main index.html file is larger than typical HTML files (~350KB) because the professional headshot is embedded as base64 data. This makes the site fully self-contained with no external image dependencies, which is ideal for simple deployment.
