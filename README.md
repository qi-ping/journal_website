# ISEP - International Scientific and Educational Publishing

A static website for International Scientific and Educational Publishing (ISEP) Inc.

## Overview

This is a fully static HTML/CSS/JavaScript website with no server-side processing required.

## Files

- `index.html` - Main website markup
- `styles.css` - Styling
- `script.js` - Interactive features (mobile menu, dynamic year)

## Local Development

Simply open `index.html` in your browser to view the website locally.

For a better local experience with proper MIME types, you can use a simple HTTP server:

### Using Python 3
```bash
python -m http.server 8000
```

### Using Node.js (with http-server)
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Deployment

This is a static site and can be deployed to any static hosting service:

- **GitHub Pages** - Push to a GitHub repository
- **Netlify** - Connect your Git repository
- **Vercel** - Connect your Git repository
- **AWS S3 + CloudFront**
- **Any web server** (Apache, Nginx, etc.)

No build process or server-side dependencies required.

## Features

- Responsive design
- Mobile-friendly navigation with toggle menu
- Semantic HTML
- Professional typography with Google Fonts
- Contact information and journal links
- Footer with dynamic year

## Sections

1. **Hero** - Introduction and call-to-action
2. **About** - Publisher information
3. **Journals** - Publication listings
4. **Publishing Standards** - Editorial principles
5. **Contact** - Contact information and location
