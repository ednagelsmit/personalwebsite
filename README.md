# Edna Gelsmit - Professional Portfolio Website

A modern, responsive portfolio website showcasing academic work in early modern art history and religious culture, along with European tour guide experiences.

## Features

- **Professional Design**: Clean, modern aesthetic tailored for academics and cultural experts
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Multiple Sections**:
  - Hero section with professional introduction
  - About section highlighting academic background and tour guide experience
  - Research projects showcase
  - Tour experiences across Europe
  - Publications and downloadable CV
  - Contact form
- **Smooth Navigation**: Sticky navigation bar with smooth scrolling
- **Mobile-Friendly Menu**: Hamburger menu for mobile devices
- **Professional Color Scheme**: Earthy tones reflecting art history and cultural themes

## Files Included

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `script.js` - Interactive features and form handling
- `README.md` - This file

## Setup Instructions

### 1. Add Your Content

Edit the `index.html` file to add your:
- Personal information (email, phone, location)
- Detailed about section content
- Your specific research projects and descriptions
- Tour experience details
- Your actual publications

### 2. Add Your CV

1. Create an `assets` folder in your repository
2. Add your CV PDF file: `assets/CV_Edna_Gelsmit.pdf`
3. Update the download link in the Publications section if needed

### 3. Update Contact Information

Replace the placeholder email addresses and contact details:
- Update `edna.gelsmit@example.com` with your actual email
- Update phone number with your actual contact number
- Update location information

### 4. Add Social Media Links

In the footer section, update the social media links:
- LinkedIn
- Twitter
- GitHub (if applicable)
- ResearchGate (or other academic profiles)

## Deployment (GitHub Pages)

### Enable GitHub Pages:

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select `main` branch as the source
4. Save
5. Your site will be available at: `https://ednagelsmit.github.io/edna-portfolio/`

### Custom Domain (Optional):

If you want to use a custom domain:
1. Add a `CNAME` file to your repository with your domain name
2. Update your domain's DNS settings to point to GitHub Pages

## Customization

### Colors

Edit the CSS variables in `styles.css` to customize the color scheme:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #8b5a3c;
    --accent-color: #d4a574;
    --light-bg: #f5f3f0;
    --text-dark: #2c3e50;
    --text-light: #666;
}
```

### Fonts

The site uses 'Segoe UI' and system fonts. To change fonts, modify the `font-family` in `styles.css`.

### Add More Projects/Tours

Simply copy the card template and update the content:

```html
<div class="project-card">
    <div class="project-header">
        <i class="fas fa-icon"></i>
    </div>
    <h3>Your Project Title</h3>
    <p>Your project description</p>
    <a href="#" class="project-link">Learn More →</a>
</div>
```

## Contact Form

The contact form uses the default email client. To set up proper email handling, consider:

1. **Formspree** - Free form backend service
2. **EmailJS** - JavaScript library for sending emails
3. **Netlify Forms** - If you deploy to Netlify
4. **AWS SES** - For enterprise solutions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Add high-quality images of artworks and tour locations
2. **Add Metadata**: Update Open Graph tags for social media sharing
3. **SEO**: Update meta descriptions and keywords for better search visibility
4. **Analytics**: Add Google Analytics or similar to track visits

## License

This portfolio template is yours to customize and use.

## Next Steps

1. [ ] Update all personal information
2. [ ] Add your CV to the assets folder
3. [ ] Replace placeholder content with your actual research and tour details
4. [ ] Add professional photos/artwork images
5. [ ] Update social media links
6. [ ] Test on mobile devices
7. [ ] Deploy to GitHub Pages
8. [ ] Set up custom domain (optional)
9. [ ] Add Google Analytics for visitor tracking
10. [ ] Share your portfolio!

---

**Created with ❤️ for academic and cultural professionals**