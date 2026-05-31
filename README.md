# Hall Walla - Professional Portfolio Website

## Overview

This is a **professional, cinematic, multi-tab portfolio website** for Muhammad Awais, CEO of Hall Walla - Pakistan's premier marriage bureau platform. The website is built entirely with **pure HTML, CSS, and JavaScript** (no frameworks required).

## Features

### 🎨 **Design & Aesthetics**
- **Cinematic Background Effects**: Animated gradient backgrounds with floating particles
- **Luxury Color Scheme**: Gold (#d4af37) and Crimson (#c41e3a) with elegant neutrals
- **Professional Typography**: Playfair Display for headings, Poppins for body text
- **Smooth Animations**: Fade-in effects, hover transitions, and scroll animations
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

### 📑 **Multi-Tab Navigation**
The website features 5 main sections accessible via tabs:

1. **Home** - Hero section with introduction and call-to-action
2. **About** - Detailed biography, achievements, and professional journey
3. **Portfolio** - Showcase of 6 major projects and initiatives
4. **Services** - 9 comprehensive services offered
5. **Gallery** - Beautiful wedding venue and event photography
6. **Contact** - Complete contact information and inquiry form

### ✨ **Key Components**

#### Navigation Bar
- Fixed, sticky navigation with glass-morphism effect
- Smooth scroll behavior
- Active link indicators
- Mobile-responsive hamburger menu

#### Hero Section
- Large, impactful headline with gradient text
- Profile image with cinematic overlay
- Dual call-to-action buttons
- Social media links
- Location badge

#### About Section
- Professional biography with multiple paragraphs
- Highlight boxes for education, experience, expertise, and vision
- Professional journey narrative
- Responsive image gallery

#### Portfolio Section
- 6 project cards with hover effects
- Project tags and descriptions
- External links to projects
- Gradient backgrounds for visual variety

#### Services Section
- 9 service cards with icons
- Hover animations and transitions
- Why Choose Hall Walla section with 3 key differentiators

#### Gallery Section
- Responsive image grid
- Hover overlay effects
- Professional wedding photography
- Inspirational content

#### Contact Section
- Contact information with icons
- Comprehensive contact form
- Social media links
- Email and phone integration

#### Footer
- Brand information
- Quick navigation links
- Copyright information

## File Structure

```
hall-walla-portfolio/
├── portfolio_website.html          # Main HTML file (complete website)
├── hero_wedding_hall.jpg           # Hero section image
├── bride_groom_portrait.jpg        # About section image
├── wedding_decoration.jpg          # Gallery image
├── wedding_ceremony.jpg            # Gallery image
├── wedding_gallery_1.jpg           # Gallery image
├── WhatsApp Image 2026-05-31...    # Profile image
└── README.md                       # This file
```

## How to Use

### Opening the Website

1. **Simple Method**: Double-click `portfolio_website.html` to open in your default browser
2. **Browser Method**: Right-click the HTML file → "Open with" → Select your browser
3. **Command Line**: 
   ```bash
   # On macOS
   open portfolio_website.html
   
   # On Windows
   start portfolio_website.html
   
   # On Linux
   xdg-open portfolio_website.html
   ```

### Navigation

- **Desktop**: Use the top navigation bar to jump between sections
- **Mobile**: Click the hamburger menu icon to reveal navigation options
- **Tabs**: Click tab buttons to switch between different content sections
- **Smooth Scrolling**: All links use smooth scroll behavior

## Customization Guide

### Changing Colors

Edit the CSS variables in the `<style>` section:

```css
:root {
    --primary-color: #d4af37;        /* Gold - main accent */
    --secondary-color: #1a1a2e;      /* Dark blue - backgrounds */
    --accent-color: #c41e3a;         /* Crimson - secondary accent */
    --light-bg: #f8f7f2;             /* Cream - page background */
    --text-dark: #2c2c2c;            /* Dark text */
    --text-light: #6b6b6b;           /* Light gray text */
}
```

### Updating Content

All text content is easily editable within the HTML. Search for:
- `Muhammad Awais` - Replace with your name
- `Hall Walla` - Replace with your business name
- Contact information - Update phone, email, links
- Social media links - Update with your profiles

### Adding New Images

1. Place image files in the same directory as the HTML file
2. Update image paths in the HTML:
   ```html
   <img src="your-image.jpg" alt="Description">
   ```

### Modifying Services

Each service card follows this structure:
```html
<div class="service-card fade-in">
    <div class="service-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Service Title</h3>
    <p>Service description goes here.</p>
</div>
```

### Adding New Projects

Duplicate a project card and modify:
```html
<div class="project-card fade-in">
    <div class="project-image" style="background: gradient;">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <span class="project-tag">TAG</span>
        <h3>Project Title</h3>
        <p>Project description.</p>
        <a href="#" class="project-link">
            Link Text <i class="fas fa-arrow-right"></i>
        </a>
    </div>
</div>
```

## Browser Compatibility

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Lightweight: Pure HTML/CSS/JavaScript (no heavy frameworks)
- Fast loading: Optimized images and minimal dependencies
- Smooth animations: GPU-accelerated CSS transforms
- Responsive: Mobile-first design approach
- Accessible: Semantic HTML and proper ARIA labels

## JavaScript Features

### Included Functionality

1. **Particle Animation**: Floating background particles for cinematic effect
2. **Navbar Scroll Effect**: Changes appearance on scroll
3. **Mobile Menu**: Hamburger menu for responsive navigation
4. **Tab Switching**: Smooth tab transitions
5. **Scroll Animations**: Fade-in effects on scroll
6. **Form Handling**: Contact form submission
7. **Active Link Detection**: Highlights current section in navigation
8. **Smooth Scrolling**: All navigation links use smooth scroll

### No External Dependencies

The website uses:
- **Font Awesome 6** (CDN) - For icons only
- **Google Fonts** (CDN) - For typography only
- **Pure JavaScript** - No jQuery or other libraries

## SEO Optimization

- Semantic HTML structure
- Meta tags for description and viewport
- Proper heading hierarchy
- Alt text for all images
- Fast loading performance

## Contact Information

- **Email**: muhammadawais777978@gmail.com
- **Phone**: +92 304 9777978
- **Location**: Multan, Pakistan
- **Website**: hallwalla.com
- **LinkedIn**: linkedin.com/in/awais-sheikh-19b254330
- **WhatsApp**: wa.me/923049777978

## Social Media

- Facebook: facebook.com/share/1BzQfTNRNs/
- Instagram: @awais_sheikh._
- LinkedIn: Awais Sheikh

## License

This website is created for Muhammad Awais and Hall Walla. All rights reserved © 2026.

## Support & Customization

For any modifications, customizations, or technical support, please contact:
- **Email**: muhammadawais777978@gmail.com
- **Phone**: +92 304 9777978

---

**Created with ❤️ for Hall Walla - Revolutionizing Wedding Planning in Pakistan**
