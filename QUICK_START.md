# Hall Walla Portfolio Website - Quick Start Guide

## ⚡ 30-Second Setup

### Step 1: Download All Files
Place these files in the **same folder**:
- `portfolio_website.html`
- `hero_wedding_hall.jpg`
- `bride_groom_portrait.jpg`
- `wedding_decoration.jpg`
- `wedding_ceremony.jpg`
- `wedding_gallery_1.jpg`
- `WhatsApp Image 2026-05-31 at 4.22.25 PM.jpeg`

### Step 2: Open the Website
**Double-click** `portfolio_website.html` → Opens in your browser ✅

### Step 3: Done! 🎉
Your professional portfolio website is now live!

---

## 🖥️ What You Get

### 5 Main Sections (Tabs)
1. **Home** - Hero introduction with profile image
2. **About** - Professional biography and achievements
3. **Portfolio** - 6 showcase projects
4. **Services** - 9 service offerings
5. **Contact** - Contact form and information

### Visual Features
- ✨ Cinematic animations and effects
- 🎨 Luxury gold and crimson color scheme
- 📱 Fully responsive (desktop, tablet, mobile)
- ⚡ Fast loading (pure HTML/CSS/JavaScript)
- 🎯 Professional, elegant design

---

## 🎨 Quick Customization

### Change Your Name
Find and replace:
```
Muhammad Awais → Your Name
```

### Change Business Name
Find and replace:
```
Hall Walla → Your Business Name
```

### Update Contact Info
Find these lines and update:
```html
<!-- Phone -->
+92 304 9777978

<!-- Email -->
muhammadawais777978@gmail.com

<!-- Website -->
hallwalla.com
```

### Update Social Links
Find and replace URLs:
```html
<!-- LinkedIn -->
https://www.linkedin.com/in/awais-sheikh-19b254330

<!-- WhatsApp -->
https://wa.me/923049777978

<!-- Facebook -->
https://www.facebook.com/share/1BzQfTNRNs/

<!-- Instagram -->
https://www.instagram.com/awais_sheikh._
```

---

## 📸 Using Your Own Images

### Replace Profile Image
1. Prepare your image (square, 1248x1248px recommended)
2. Name it: `profile.jpg`
3. Find this line in the HTML:
   ```html
   <img src="WhatsApp Image 2026-05-31 at 4.22.25 PM.jpeg" alt="Muhammad Awais portrait">
   ```
4. Change to:
   ```html
   <img src="profile.jpg" alt="Your Name portrait">
   ```

### Replace Gallery Images
1. Prepare 4 images (square, 1248x1248px each)
2. Name them: `gallery1.jpg`, `gallery2.jpg`, etc.
3. Find gallery section and update paths

---

## 🎯 Navigation Guide

### Desktop Users
- Click navbar links to jump to sections
- Click tab buttons to switch content
- Smooth scrolling to all sections

### Mobile Users
- Tap hamburger menu (☰) to open navigation
- Tap any link to navigate
- Tap tab buttons to switch content

---

## 📝 Editing Content

### Edit Text Content
1. Open `portfolio_website.html` with a text editor (Notepad, VS Code, etc.)
2. Find the text you want to change
3. Edit it directly
4. Save the file (Ctrl+S)
5. Refresh your browser (F5)

### Add New Service
Find the services section and duplicate:
```html
<div class="service-card fade-in">
    <div class="service-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Service Title</h3>
    <p>Service description goes here.</p>
</div>
```

### Add New Project
Find the portfolio section and duplicate:
```html
<div class="project-card fade-in">
    <div class="project-image" style="background: linear-gradient(...);">
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

---

## 🎨 Change Colors

### Find the Color Variables
At the top of the `<style>` section:
```css
:root {
    --primary-color: #d4af37;        /* Gold */
    --secondary-color: #1a1a2e;      /* Dark Blue */
    --accent-color: #c41e3a;         /* Crimson */
    --light-bg: #f8f7f2;             /* Cream */
    --text-dark: #2c2c2c;            /* Dark Text */
    --text-light: #6b6b6b;           /* Light Text */
}
```

### Change Primary Color (Gold)
Replace `#d4af37` with your color code:
- `#FF6B6B` - Red
- `#4ECDC4` - Teal
- `#95E1D3` - Mint
- `#F38181` - Pink

---

## 🚀 Deploy Your Website

### Option 1: Free Hosting (Netlify)
1. Go to netlify.com
2. Drag and drop your folder
3. Your website is live! (free URL provided)

### Option 2: GitHub Pages
1. Create GitHub account
2. Upload files to repository
3. Enable GitHub Pages
4. Website is live!

### Option 3: Traditional Hosting
1. Upload files to your web host
2. Website is live at your domain!

---

## ✅ Browser Testing

Your website works on:
- ✅ Chrome, Firefox, Safari, Edge
- ✅ Mobile phones (iOS, Android)
- ✅ Tablets
- ✅ All modern browsers

---

## 🆘 Troubleshooting

### Images Not Showing?
- Make sure all image files are in the **same folder** as the HTML file
- Check file names match exactly (case-sensitive)
- Verify image file extensions (.jpg, .jpeg)

### Styling Looks Wrong?
- Clear browser cache (Ctrl+Shift+Delete)
- Refresh page (Ctrl+F5)
- Try a different browser

### Links Not Working?
- Check URLs are correct
- Make sure phone number format: `+92 304 9777978`
- Email format: `name@email.com`

### Mobile Menu Not Working?
- Try refreshing the page
- Clear browser cache
- Test in different browser

---

## 📚 Additional Resources

### Font Awesome Icons
Browse icons at: https://fontawesome.com/icons

### Google Fonts
Browse fonts at: https://fonts.google.com

### Color Picker
Find colors at: https://colorpicker.com

### Image Optimization
Optimize images at: https://tinypng.com

---

## 📞 Support

For help or customization:
- **Email**: muhammadawais777978@gmail.com
- **Phone**: +92 304 9777978
- **WhatsApp**: wa.me/923049777978

---

## 🎓 Learning Resources

### HTML/CSS/JavaScript
- MDN Web Docs: https://developer.mozilla.org
- W3Schools: https://www.w3schools.com
- CSS-Tricks: https://css-tricks.com

### Web Hosting
- Netlify: https://netlify.com
- GitHub Pages: https://pages.github.com
- Vercel: https://vercel.com

---

## ✨ Pro Tips

1. **Backup Your Files** - Keep a copy before making changes
2. **Test Changes** - Refresh browser after each edit
3. **Mobile First** - Always test on mobile
4. **Keep Images Optimized** - Use TinyPNG to compress
5. **Update Regularly** - Keep content fresh
6. **Monitor Analytics** - Track visitor behavior
7. **Collect Feedback** - Ask users for suggestions

---

## 🎉 You're All Set!

Your professional Hall Walla portfolio website is ready to impress!

**Next Steps:**
1. ✅ Open the website
2. ✅ Customize with your information
3. ✅ Test on mobile
4. ✅ Deploy online
5. ✅ Share with the world!

---

**Happy Hosting! 🚀**

Created with ❤️ for Muhammad Awais & Hall Walla
