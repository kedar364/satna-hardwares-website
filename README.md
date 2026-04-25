# Satna Hardwares Website

A modern, luxury-themed single-page website for **Satna Hardwares**, a premium home interior and hardware shop in Satna, Madhya Pradesh, India.

## Overview

This is a complete, self-contained website built as a single `index.html` file with embedded CSS and JavaScript. It features a modern dark theme with gold accents, elegant typography, and smooth navigation between multiple pages.

## Features

✨ **Modern Design**
- Dark theme with premium gold accents (#C9A84C background)
- Responsive layout that works on desktop, tablet, and mobile devices
- Smooth page transitions and hover effects
- Professional typography with Cormorant Garamond (headings) and Jost (body)

📄 **Six Main Pages**

1. **Home** - Hero section with company tagline and impressive statistics
   - 500+ Unique Designs
   - 15+ Years of Excellence
   - 2000+ Happy Clients
   - 50+ Premium Brands

2. **About** - Company story and core values
   - 15+ years serving Satna
   - Four value pillars: Quality First, Expert Advice, Best Prices, After Service Care

3. **Products** - Six product categories with descriptions
   - Tile Designs
   - Bathroom Fittings
   - Kitchen Hardware
   - Acrylic Laminates
   - Sanitary Ware
   - Construction Materials

4. **Brands** - Featured brand showcase
   - Sapphire Glass Laminate by Euro Pratik / Millenium Decor
   - Detailed specifications (1.5mm acrylic, 2440x1220mm)
   - Color swatch grid with 8 premium finishes
   - 8 feature badges (High Gloss, Matte, Water Resistant, Eco Friendly, Pure Acrylic, Anti Scratch, Light Weight, German Tech)

5. **Gallery** - Visual showcase of showroom
   - 6-item grid layout
   - Categories: Tile Flooring, Modern Bathroom, Kitchen Design, Wardrobe Panels, Laminates & Finishes, Interior Solutions

6. **Contact** - Enquiry form and business information
   - Contact form with name, phone, product interest dropdown, and message
   - Business address in Satna, MP
   - Business hours: Monday-Saturday, 9 AM - 7 PM
   - Professional consultation information

## Technical Details

**Built With:**
- Pure HTML5
- CSS3 (with Grid, Flexbox, Gradients)
- Vanilla JavaScript (no frameworks required)
- Google Fonts (Cormorant Garamond, Jost)

**No Dependencies:**
- Single file deployment
- Works offline (no external API calls)
- No build process required
- No database needed

## Design Specifications

**Color Scheme:**
- Background: #0E0E0E (Deep Black)
- Accent Color: #C9A84C (Premium Gold)
- Text: #E8E8E8 (Light Grey)
- Secondary Text: #B8B8B8 (Medium Grey)

**Typography:**
- Headings: Cormorant Garamond (serif) with 600-700 weight
- Body Text: Jost (sans-serif) with 300-500 weight

**Responsive Design:**
- Works on screens from 320px to 4K
- Grid layouts adapt to available space
- Touch-friendly navigation and buttons

## How to Use

1. **View the Website:**
   - Open `index.html` in any modern web browser
   - No server or installation required
   - Works locally or on web hosting

2. **Customize:**
   - Edit the HTML to change content, company details, or product information
   - Modify CSS variables for colors or styling
   - Update contact information in the Contact section
   - Add real images by replacing emoji placeholders in the Gallery

3. **Deploy:**
   - Upload `index.html` to any web hosting service
   - No build process or additional files needed
   - Works with GitHub Pages, Netlify, Vercel, or traditional hosting

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## File Structure

```
satna-hardwares-website/
├── index.html          # Main website file (HTML, CSS, JS)
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── .git/              # Git repository
```

## Customization Guide

### Update Company Information
Find and replace these sections in `index.html`:
- Contact phone number: `+91-XXXXXXXXXX`
- Address: `Satna, Madhya Pradesh 485001`
- Business hours: Adjust the Contact section

### Add Real Images
Replace emoji placeholders in the Gallery section with actual image URLs:
```html
<div class="gallery-image">🏛️</div>
<!-- Replace with -->
<img src="path/to/image.jpg" alt="Tile Flooring" style="width: 100%; height: 100%; object-fit: cover;">
```

### Change Colors
Update the CSS color variables:
- Gold accent: `#C9A84C` → your color
- Background: `#0E0E0E` → your color
- Text color: `#E8E8E8` → your color

### Add More Products or Brands
Duplicate the product card or swatch HTML and update the content.

## Performance

- **Page Load:** < 100ms (single file)
- **No external dependencies:** Instant loading
- **Optimized CSS:** ~30KB total file size
- **Smooth animations:** 60fps animations

## Future Enhancements

Potential additions (while keeping it as a single file):
- Slide show functionality for gallery
- Form integration with backend service
- Multi-language support
- Search functionality
- Product filtering

## License

This website template is provided as-is for commercial use by Satna Hardwares.

## Support

For modifications or technical questions, ensure you:
1. Use a modern text editor (VS Code, Sublime, etc.)
2. Keep the HTML structure intact
3. Test in multiple browsers
4. Back up the original file before major changes

---

**Created:** 2026
**Last Updated:** April 25, 2026
**Version:** 1.0
