# Trendora - Premium Daily Blog Website

A modern, elegant, and responsive blog website for daily trending updates in Sports, Entertainment, and Finance.

## 🌟 Features

### Design & Aesthetics
- **Premium Color Palette**: Deep navy, soft gold, and muted teal
- **Elegant Typography**: Inter for headings, Playfair Display for body text
- **Sophisticated Layout**: Clean, minimalist design with subtle shadows and rounded corners
- **Responsive Design**: Mobile-first approach with seamless adaptation across all devices

### Technical Features
- **Fast Loading**: Optimized images and efficient CSS/JS
- **Smooth Animations**: Fade-in effects, hover transitions, and scroll animations
- **Mobile Navigation**: Animated hamburger menu with smooth transitions
- **Accessibility**: WCAG compliant with keyboard navigation and screen reader support
- **SEO Optimized**: Semantic HTML structure and meta tags

### Interactive Elements
- **Smooth Scrolling**: Navigation and anchor links
- **Back to Top Button**: Elegant floating button
- **Card Hover Effects**: Subtle animations and ripple effects
- **Dynamic Navbar**: Changes appearance on scroll
- **Social Media Integration**: Ready-to-use social media links

## 📁 File Structure

```
trendora/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styling
├── script.js           # Interactive JavaScript
└── README.md           # Documentation (this file)
```

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in any modern web browser
2. **Customize content**: Edit the HTML file to add your own articles and content
3. **Modify styling**: Adjust colors, fonts, and layout in `styles.css`
4. **Add functionality**: Extend features in `script.js`

## 🎨 Customization Guide

### Updating Articles

#### Featured Articles Section
Replace the placeholder content in the `.featured-grid` section:

```html
<article class="featured-card main-feature">
    <div class="card-image">
        <img src="YOUR_IMAGE_URL" alt="Your Article Description">
        <span class="category-tag sports">Sports</span> <!-- or entertainment/finance -->
    </div>
    <div class="card-content">
        <h3 class="card-title">Your Article Title</h3>
        <p class="card-excerpt">Your article excerpt...</p>
        <div class="card-meta">
            <span class="date">Today</span>
            <span class="read-time">X min read</span>
        </div>
    </div>
</article>
```

#### Category Sections
Update articles in Sports, Entertainment, and Finance sections:

```html
<article class="article-card">
    <div class="article-image">
        <img src="YOUR_IMAGE_URL" alt="Your Article">
    </div>
    <div class="article-content">
        <h3 class="article-title">Your Article Title</h3>
        <p class="article-excerpt">Your article description...</p>
        <div class="article-meta">
            <span class="date">X hours ago</span>
            <span class="author">By Your Name</span>
        </div>
    </div>
</article>
```

### Color Customization

Update the CSS custom properties in `styles.css`:

```css
:root {
    --primary-navy: #1a2332;      /* Main brand color */
    --accent-gold: #d4af37;       /* Accent color */
    --muted-teal: #5f9ea0;        /* Link color */
    /* Add your custom colors here */
}
```

### Typography Changes

Update font families in the CSS:

```css
:root {
    --font-heading: 'Your-Heading-Font', sans-serif;
    --font-body: 'Your-Body-Font', serif;
}
```

Don't forget to add the font links in the HTML `<head>` section.

## 🖼️ Image Guidelines

### Recommended Image Sizes
- **Featured Article (Main)**: 1000x600px
- **Featured Article (Side)**: 500x300px
- **Category Articles**: 400x240px

### Image Sources
- **Unsplash**: High-quality, free stock photos
- **Pexels**: Free stock photography
- **Your Own Photos**: For authentic, branded content

### Image Optimization
- Use WebP format when possible for better compression
- Compress images to reduce loading times
- Add descriptive alt text for accessibility

## 📱 Mobile Responsiveness

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and up
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Under 480px

## 🔧 Advanced Customization

### Adding New Sections

1. Create HTML structure following existing patterns
2. Add corresponding CSS styles
3. Include in navigation if needed

### SEO Optimization

Update meta tags in the HTML `<head>`:

```html
<title>Your Custom Title</title>
<meta name="description" content="Your description">
<meta name="keywords" content="your, keywords, here">
```

### Social Media Integration

Update social media links in the footer:

```html
<a href="https://twitter.com/yourusername" class="social-link">
    <i class="fab fa-twitter"></i>
</a>
```

## 🎯 Content Management Tips

### Daily Updates
1. Replace featured article with latest trending story
2. Move previous featured articles to category sections
3. Update timestamps and author information
4. Add new category articles regularly

### Content Structure
- **Headlines**: Keep concise and engaging
- **Excerpts**: 2-3 sentences maximum
- **Categories**: Maintain balance across Sports, Entertainment, Finance
- **Meta Information**: Include publication time and author

## 🔒 Best Practices

### Performance
- Optimize images before uploading
- Keep HTML clean and semantic
- Minimize CSS and JavaScript when possible
- Use browser caching for static assets

### Accessibility
- Always include alt text for images
- Maintain proper heading hierarchy (h1, h2, h3)
- Ensure sufficient color contrast
- Test with keyboard navigation

### SEO
- Use descriptive, unique page titles
- Write compelling meta descriptions
- Include relevant keywords naturally
- Create an XML sitemap for larger sites

## 🌐 Browser Support

The website supports all modern browsers:
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📈 Analytics Integration

To add Google Analytics, insert this code before the closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🔄 Regular Maintenance

### Daily Tasks
- [ ] Update featured articles
- [ ] Add new category content
- [ ] Check and fix broken links
- [ ] Monitor website performance

### Weekly Tasks
- [ ] Review and update meta descriptions
- [ ] Optimize new images
- [ ] Check mobile responsiveness
- [ ] Update social media links

### Monthly Tasks
- [ ] Analyze website traffic
- [ ] Update About section if needed
- [ ] Review and improve SEO
- [ ] Backup website files

## 🆘 Troubleshooting

### Common Issues

**Images not loading:**
- Check image URLs are correct
- Ensure images are properly sized
- Verify internet connection

**Mobile menu not working:**
- Check if JavaScript is enabled
- Ensure script.js is properly linked
- Clear browser cache

**Fonts not displaying:**
- Verify Google Fonts links in HTML
- Check font names in CSS
- Ensure stable internet connection

## 📞 Support

For technical issues or customization help:
1. Check this README file first
2. Review the code comments
3. Test in different browsers
4. Validate HTML and CSS

---

**Trendora** - Your premium source for daily trending updates

*Built with modern web standards for optimal performance and user experience.*