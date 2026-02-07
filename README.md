# Toolabs Engineering Website

**Professional Mechanical Automation & Precision Engineering Website**

## Overview
A modern, professional B2B website for Toolabs Engineering, built with:
- **Theme**: CostingApp enterprise teal color scheme (#0A91A0)
- **Layout**: Furni-1.0.0 Bootstrap template structure
- **Typography**: Inter font family
- **Design Philosophy**: Industrial • Precision • Trust

## Technology Stack
- HTML5
- CSS3 (Custom + Bootstrap 5)
- JavaScript (Bootstrap Bundle, Tiny Slider)
- Font Awesome 6 Icons
- Google Fonts (Inter)

## Color Palette (from CostingApp)
```css
Primary (Teal): #0A91A0
Primary Hover: #087f8d
Secondary (Yellow): #f9bf29
Background: #f8fafc
Card Background: #ffffff
Text Primary: #0f172a
Text Secondary: #475569
Border: #e2e8f0
```

## Website Structure

### Pages
1. **index.html** - Homepage
   - Hero section with value proposition
   - Core services snapshot
   - Why choose us features
   - Industries served preview
   - Call-to-action

2. **about.html** - About Us
   - Company overview
   - Vision & Mission
   - Core values
   - Expertise areas
   - Engineering philosophy

3. **services.html** - Services
   - Mechanical Automation
   - CAD Design & Engineering
   - Special Purpose Machines
   - Precision Engineering
   - System Integration
   - Engineering process overview

4. **industries.html** - Industries
   - Automotive Components Manufacturing
   - Industrial Machinery & Equipment
   - Factory Automation Systems
   - Special Purpose Machine Building
   - Precision Component Manufacturing

5. **contact.html** - Contact
   - Contact form
   - Email, phone, address
   - Social media links
   - Next steps process

### Directory Structure
```
Toolabs Website/
├── index.html
├── about.html
├── services.html
├── industries.html
├── contact.html
├── css/
│   └── main.css (CostingApp theme + custom styles)
├── images/
│   └── README.md (image requirements)
├── Services/ (existing project photos)
│   └── [various service images]
└── furni-1.0.0/ (template assets)
    ├── css/
    │   ├── bootstrap.min.css
    │   ├── tiny-slider.css
    │   └── style.css
    ├── js/
    │   ├── bootstrap.bundle.min.js
    │   ├── tiny-slider.js
    │   └── custom.js
    ├── images/
    └── favicon.png
```

## Key Features

### Design System
- **Consistent Branding**: Teal primary color throughout
- **Professional Typography**: Inter font, optimized hierarchy
- **Modern UI Components**: Cards, buttons, icons
- **Responsive Design**: Mobile-first, fully responsive
- **Accessibility**: Semantic HTML, proper contrast ratios

### UX Excellence
- **Clear Navigation**: Sticky header, intuitive menu
- **Scannable Content**: Short paragraphs, bullet points
- **Visual Hierarchy**: Proper heading structure
- **Call-to-Actions**: Strategic placement throughout
- **Contact Options**: Multiple ways to get in touch

### SEO Optimized
- Proper meta titles and descriptions
- Semantic HTML5 structure
- Optimized heading hierarchy
- Alt text for images
- Clean, descriptive URLs

## Content Strategy

### Tone & Voice
- **Confident**: Engineering expertise and proven results
- **Professional**: B2B focused, technical credibility
- **Clear**: No marketing fluff, direct communication
- **Engineering-Driven**: Process and capability focused

### Target Audience
- Engineering managers
- Procurement teams
- Manufacturing decision-makers
- Industrial automation specialists
- OEM manufacturers

## Customization Guide

### Changing Colors
Edit CSS custom properties in `css/main.css`:
```css
:root {
    --primary: #0A91A0;        /* Main brand color */
    --secondary: #f9bf29;      /* Accent color */
    /* ... other variables */
}
```

### Adding Content
- Company details: Update footer in all HTML files
- Contact info: Edit `contact.html`
- Services: Add sections in `services.html`
- Industries: Expand `industries.html`

### Images
- Place images in `images/` folder
- Reference in HTML with proper alt text
- Use existing Services folder images for actual projects
- See `images/README.md` for specifications

## Deployment

### Local Testing
1. Open `index.html` in a modern web browser
2. Navigate through all pages
3. Test responsiveness (resize browser)
4. Verify all links work

### Production Deployment
1. Upload all files to web server
2. Ensure directory structure is maintained
3. Configure domain and SSL certificate
4. Test all functionality on live server
5. Submit sitemap to search engines

### Hosting Recommendations
- **Static Hosting**: Netlify, Vercel, GitHub Pages
- **Traditional Hosting**: Any web hosting provider
- **Requirements**: Simple HTML/CSS/JS hosting

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization
- Minified Bootstrap CSS/JS
- Optimized images (compress before uploading)
- Efficient CSS (no unused styles in main.css)
- Fast loading times
- Lazy loading for images (can be added)

## Future Enhancements

### Phase 2 Considerations
- [ ] Blog section for industry insights
- [ ] Project portfolio/case studies
- [ ] Client testimonials slider
- [ ] Interactive quote calculator
- [ ] Resource downloads (brochures, technical docs)
- [ ] Multi-language support
- [ ] Live chat integration
- [ ] Video demonstrations
- [ ] News/updates section

### Technical Improvements
- [ ] Add contact form backend (PHP, Node.js, or form service)
- [ ] Implement analytics (Google Analytics)
- [ ] Add schema.org markup for local business
- [ ] Optimize images with WebP format
- [ ] Add service worker for offline support
- [ ] Implement dark mode toggle

## Maintenance

### Regular Updates
- Update project images from completed work
- Add new services as capabilities expand
- Update industry sectors served
- Refresh testimonials/case studies
- Keep contact information current

### Content Review
- Quarterly review of all copy
- Annual update of company information
- Regular blog posts (if implemented)
- Update meta descriptions for SEO

## Support & Documentation

### Resources Used
- **CostingApp Theme**: Teal enterprise color palette
- **Furni Template**: Bootstrap 5 layout structure
- **Bootstrap 5**: Component framework
- **Font Awesome 6**: Icon library
- **Google Fonts**: Inter typography

### Credits
- Design System: CostingApp enterprise theme
- Template Framework: Furni-1.0.0 by Untree.co
- Icons: Font Awesome
- Fonts: Google Fonts (Inter)

## Notes

### Theme Consistency
The website strictly follows the CostingApp color scheme:
- Primary teal (#0A91A0) used consistently
- Secondary yellow (#f9bf29) for accents
- Slate neutrals for text and backgrounds
- No new colors invented unless necessary

### Layout Philosophy
Reuses Furni template structure:
- Header/navigation pattern
- Hero section layouts
- Section spacing and grid system
- Footer organization
- Responsive breakpoints

### Content Source
Based on:
- Toolabs Profile V1.0 (company information)
- Services folder (technical capabilities)
- Engineering best practices for B2B sites

## Contact
For website updates or technical support, refer to the Contact page or reach Toolabs Engineering directly.

---

**Version**: 1.0  
**Last Updated**: February 2026  
**Status**: Production Ready
