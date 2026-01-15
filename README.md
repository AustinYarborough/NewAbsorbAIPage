# Absorb AI Landing Page

A modern, responsive landing page for Absorb AI - your gut health companion app.

## Features

- **Dark Theme Design**: Modern dark theme matching the Appit Social design aesthetic
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Mobile hamburger menu
  - FAQ accordion
  - Pricing tab switcher
  - Smooth scrolling navigation
  - Fade-in animations on scroll

## Setup Instructions

### 1. Add Your Screenshots

Place your app screenshots in the `screenshots/` directory with the following names:

- `home-screen.png` - Your home screen screenshot (used in hero and throughout the page)
- `welcome-screen.png` - Your welcome screen screenshot (used in hero section center)
- `analytics-screen.png` - Your analytics screen screenshot (used in hero section right and capabilities section)

**Recommended screenshot dimensions:**
- Width: 390px (iPhone standard)
- Height: 844px (iPhone standard)
- Or any 9:19.5 aspect ratio for mobile screenshots

### 2. Customize Content

Edit `index.html` to customize:
- App name and branding
- Feature descriptions
- Pricing plans
- Testimonials
- FAQ content
- Contact information

### 3. Update Colors (Optional)

Edit `styles.css` and modify the CSS variables in the `:root` selector:
- `--accent-primary`: Primary accent color (currently green)
- `--accent-secondary`: Secondary accent color (currently blue)
- `--accent-tertiary`: Tertiary accent color (currently orange)

### 4. View the Page

Simply open `index.html` in your web browser, or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## File Structure

```
LandingPageAA/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactivity
├── screenshots/        # Place your app screenshots here
│   ├── home-screen.png
│   └── analytics-screen.png
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The page uses Inter font from Google Fonts (loaded via CDN)
- All icons are inline SVG for better performance
- Images are set to `object-fit: cover` to handle different aspect ratios
- The design is optimized for mobile-first responsive design

## Customization Tips

1. **Change App Store Links**: Update the `href` attributes on the store badge buttons
2. **Add More Sections**: Follow the existing section structure to add new content blocks
3. **Modify Animations**: Adjust animation timings in `script.js` and `styles.css`
4. **Add Analytics**: Insert your analytics code before the closing `</body>` tag
