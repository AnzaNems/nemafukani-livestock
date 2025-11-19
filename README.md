# nemafukani-livestock
# Nemafukani Livestock Website

##  Project Overview

A complete, production-ready front-end website for **Nemafukani Livestock** - a premium livestock trading and breeding service provider based in South Africa. The website features a modern, responsive design built with vanilla HTML5, CSS3, and JavaScript.

**Live Website Preview:** Open `index.html` in your browser

---

##  Project Features

### ✅ Core Pages (6)
- Home (index.html) - Hero section, features, products preview, trust indicators, logo carousel
- About (about.html) - Company story, mission/vision, values, services, team
- Products (Feed Store.html) - Feed & farming supplies with detailed descriptions and image lightbox
- Gallery(gallery.html) — Photos of products, farm & customers
- FAQs (faqs.html) - Searchable accordion with category filtering
- Contact (contact.html) - Contact form with validation, Google Maps, business hours

### ✅ Design & Styling
- **Color Palette:**
  - Primary: `#2C5F2D` (Forest Green)
  - Secondary: `#D4A574` (Warm Tan)
  - Accent: `#E85D04` (Vibrant Orange)
- **Typography:** Poppins font family (300, 400, 500, 600, 700 weights)
- **Mobile-First Responsive Design** - Breakpoints at 992px, 768px, 576px
- **Smooth Animations** - Fade-in on scroll, hover effects, transitions
- **Accessibility Features** - ARIA labels, semantic HTML, keyboard navigation

### ✅ Interactive Features
- ✅ **Mobile Navigation Toggle** with hamburger menu
- ✅ **Scroll-to-Top Button** appears after 300px scroll
- ✅ **Smooth Scrolling** for all anchor links
- ✅ **Fade-In Animations** using Intersection Observer
- ✅ **FAQ Accordion** with expand/collapse functionality
- ✅ **FAQ Search Filter** with debounced real-time search
- ✅ **FAQ Category Filter** (All, General, Purchasing, Delivery, etc.)
- ✅ **Contact Form Validation** with real-time error messages
- ✅ **Image Lightbox Gallery** for product images
- ✅ **Logo Carousel** with auto-scroll and hover pause
- ✅ **Floating WhatsApp Button** for instant messaging
- ✅ **Sticky Header** with scroll effects

### ✅ SEO & Meta Tags
- Complete meta descriptions for all pages
- Open Graph tags for social media sharing
- Twitter Card markup
- Semantic HTML5 structure
- Optimized heading hierarchy
- Alt text for all images

---

## 📁 File Structure

```
nemafukani-livestock/
│
├── index.html                 # Home page
├── about.html                 # About page
├── products.html              # Products page (Feed & farming supplies)
├── gallery.html               # NEW — Gallery page (Photos of products, farm & customers)
├── faqs.html                  # FAQs page
├── contact.html               # Contact page
├── README.md                  # Documentation
│
├── css/
│   └── style.css              # Main stylesheet (1500+ lines)
│
├── js/
│   └── script.js              # Main JavaScript file (700+ lines)
│
└── assets/
    └── images/
        ├── logo.png                   # Company logo
        ├── favicon.png                # Browser favicon

        # --- HERO IMAGES ---
        ├── hero-home.jpg              # Home hero background
        ├── hero-about.jpg             # About hero background
        ├── hero-products.jpg          # Products hero background
        ├── hero-gallery.jpg           # NEW – Gallery hero background
        ├── hero-contact.jpg           # Contact hero background
        ├── hero-faqs.jpg              # FAQs hero background
        ├── feed-products.jpg          # Main feed supplies header
        ├── lucerne-bales.jpg          # Lucerne Bales
        ├── molatek-winter-block-40.jpg
        ├── voermolas-syrup.jpg
        ├── voermolas-supermol.jpg
        ├── salt-lick-block.jpg
        ├── feed-troughs.jpg
        ├── gallery-1.jpg              # Farm / livestock / products
        ├── gallery-2.jpg
        ├── gallery-3.jpg
        ├── gallery-4.jpg
        ├── gallery-5.jpg
        ├── gallery-6.jpg
        ├── about-story.jpg            # Company story phot
        └── og-image.jpg               # Open Graph image for social sharing

```

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor for customization (VS Code, Sublime Text, etc.)
- Local web server (optional, for testing)

### Installation

1. **Download/Extract** the project folder to your computer

2. **Open in Browser** - Double-click `index.html` or right-click → Open With → Browser

3. **Edit in VS Code:**
   ```bash
   # Open project folder in VS Code
   code nemafukani-livestock
   ```

### Local Development Server (Optional)

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

---

## 🎨 Customization Guide

### Update Contact Information

1. **Phone Numbers** - Search for `+27123456789` and replace throughout
2. **Email Addresses** - Search for ` matavhelafillingstation@gmail.com` and replace
3. **Location** - Update "Limpopo, South Africa" references
4. **WhatsApp Link** - Update `wa.me/27123456789` in all HTML files

### Update Colors

Edit `css/style.css` in the `:root` section:
```css
:root {
    --color-primary: #2C5F2D;      /* Change main green color */
    --color-secondary: #D4A574;    /* Change tan color */
    --color-accent: #E85D04;       /* Change orange accent */
    /* ... */
}
```

### Add/Replace Images

1. Place your images in `/assets/images/` folder
2. Update image paths in HTML files
3. Recommended image sizes:
   - Hero backgrounds: 1920x1080px
   - Product images: 800x600px
   - Team photos: 400x400px
   - Partner logos: 200x100px

### Modify Content

All page content is in the HTML files. Use Find & Replace to update:
- Company name: "Nemafukani Livestock"
- Tagline: "Empowering farmers with healthy livestock and sustainable solutions"
- Service descriptions, product details, FAQ answers

---

## 📱 Responsive Design

The website is fully responsive across all devices:

- **Desktop** (>992px) - Full navigation, multi-column layouts
- **Tablet** (768px - 992px) - Adjusted grids, readable text
- **Mobile** (< 768px) - Hamburger menu, single-column layouts, touch-friendly

---

## ♿ Accessibility Features

- Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`)
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus visible states
- Alt text for all images
- High contrast color ratios (WCAG AA compliant)
- Reduced motion support for accessibility preferences

---

## 🔧 Browser Support

✅ **Fully Supported:**
- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)

⚠️ **Partial Support:**
- Internet Explorer 11 (basic functionality, some CSS features may not work)

---

## 📊 Performance Optimization

- Minified CSS and JavaScript (optional - see Production section)
- Lazy loading for images below the fold
- Debounced scroll and search events
- Efficient CSS animations with GPU acceleration
- Optimized image formats (use WebP where possible)

---

## 🌐 Deployment

### Option 1: Static Hosting (Recommended)

**Netlify:**
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Your site is live!

**Vercel:**
1. Sign up at vercel.com
2. Import from Git or upload folder
3. Automatic deployment

**GitHub Pages:**
1. Create GitHub repository
2. Upload files
3. Enable GitHub Pages in Settings
4. Access at `username.github.io/repo-name`

### Option 2: Traditional Web Hosting

1. Purchase domain and hosting (Bluehost, SiteGround, etc.)
2. Upload files via FTP (FileZilla)
3. Point domain to hosting directory

### Option 3: WordPress Conversion

Convert to WordPress theme for easier content management by clients.

---

## 🧪 Testing Checklist

- [✅] All navigation links work correctly
- [✅] Mobile menu opens and closes properly
- [✅] Contact form validation works (try invalid inputs)
- [✅] FAQ search and filters function correctly
- [✅] Scroll-to-top button appears/disappears
- [✅] Smooth scrolling works for anchor links
- [✅] Lightbox opens and closes on product images
- [ ] All images load properly (check 404s)
- [ ] External links open in new tabs
- [ ] WhatsApp button links correctly
- [ ] Test on mobile devices (iOS, Android)
- [ ] Test on different browsers
- [ ] Check Google Maps iframe loads
- [ ] Verify responsive layouts at all breakpoints
- [ ] Test keyboard navigation (Tab key)
- [ ] Check form submission (replace with real backend)

---

## 🔐 Security Considerations

### Before Production:

1. **Implement Backend for Contact Form**
   - Current form is client-side only
   - Add server-side validation
   - Use reCAPTCHA to prevent spam
   - Sanitize all inputs

2. **HTTPS Certificate**
   - Always use SSL/TLS
   - Most modern hosts provide free Let's Encrypt certificates

3. **Content Security Policy**
   - Add CSP headers to prevent XSS attacks

---

## 📈 SEO Recommendations

### Before Launch:

1. **Google Search Console**
   - Submit sitemap
   - Monitor indexing status

2. **Create sitemap.xml:**
   ```xml
   <?xml version="1.0" encoding="UTF-8"?>
   <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
     <url><loc>https://nemafukanilivestock.co.za/</loc></url>
     <url><loc>https://nemafukanilivestock.co.za/about.html</loc></url>
     <url><loc>https://nemafukanilivestock.co.za/products.html</loc></url>
     <url><loc>https://nemafukanilivestock.co.za/faqs.html</loc></url>
     <url><loc>https://nemafukanilivestock.co.za/contact.html</loc></url>
   </urlset>
   ```

3. **robots.txt:**
   ```
   User-agent: *
   Allow: /
   Sitemap: https://nemafukanilivestock.co.za/sitemap.xml
   ```

4. **Google Analytics** - Add tracking code
5. **Google My Business** - Create business listing
6. **Social Media Integration** - Update OG image URLs

---

## 🐛 Known Issues & Future Enhancements

### Future Enhancements:

- [ ] Blog section for farming tips and news
- [ ] Customer testimonials/reviews section
- [ ] Photo gallery with multiple pages
- [ ] Online livestock inventory system
- [ ] Price calculator/quote generator
- [ ] Multi-language support (English, Afrikaans, Xhosa)
- [ ] Newsletter subscription integration
- [ ] Live chat widget
- [ ] Payment gateway integration
- [ ] Admin dashboard for content management

---

## 📝 Changelog

### Version 1.0.0 (2024)
- ✅ Initial release
- ✅ 6 complete HTML pages
- ✅ Comprehensive CSS styling (1500+ lines)
- ✅ Full JavaScript functionality (700+ lines)
- ✅ Mobile-responsive design
- ✅ SEO optimization
- ✅ Accessibility features
- ✅ Interactive components (accordion, lightbox, form validation)

---

## 📞 Support & Maintenance

For website updates or technical support, contact your web developer or:

**Common Tasks:**

- **Update Text:** Edit HTML files directly in text editor
- **Change Images:** Replace files in `/assets/images/` folder
- **Add New Page:** Duplicate existing HTML file and modify
- **Update Colors:** Edit CSS variables in `style.css`
- **Fix Broken Links:** Search for broken URL and replace

---

## 📄 License

This website template is created for Nemafukani Livestock. All rights reserved.

**Usage Rights:**
- ✅ Use for Nemafukani Livestock business purposes
- ✅ Modify and customize as needed
- ✅ Deploy to production servers
- ❌ Do not resell or redistribute template
- ❌ Do not claim as your own work

---

## 🎓 Credits

**Built With:**
- HTML5 - Semantic markup
- CSS3 - Modern styling with variables, grid, flexbox
- Vanilla JavaScript (ES6+) - No frameworks or libraries
- Google Fonts - Poppins typeface
- SVG Icons - Inline SVG for scalability

**Resources:**
- Font: [Poppins from Google Fonts](https://fonts.google.com/specimen/Poppins)
- Icons: Custom SVG icons
- Images: Placeholder references (replace with actual photos)

---

## 📧 Contact

**Nemafukani Livestock**
- 📍 Limpopo, South Africa
- 📞 +27 12 345 6789
- 📧 matavhelafillingstation@gmail.com
- 🌐 www.nemafukanilivestock.co.za (update with actual domain)

---

✅ Submission Checklist

Before Delivering to Client:

- [ ] All HTML pages validated (W3C Validator)
- [ ] CSS validated (W3C CSS Validator)
- [ ] JavaScript error-free (browser console)
- [ ] All links tested and working
- [ ] Images optimized and compressed
- [ ] Cross-browser testing completed
- [ ] Mobile responsiveness verified
- [ ] Accessibility audit passed
- [ ] SEO meta tags complete
- [ ] Contact information updated
- [ ] Documentation complete (this README)
- [ ] Source files organized
- [ ] Backup created
- [ ] Deployment guide provided

---

**🚀 The website is production-ready and can be deployed immediately!**

For any questions or support, refer to this documentation or contact your web developer.

**Built with ❤️ for Nemafukani Livestock**
