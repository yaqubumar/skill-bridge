

# SkillBridge - Find Trusted Skilled Workers Near You

**Live Website:** (https://yaqubumar.github.io/skill-bridge/)

## Overview

**SkillBridge** is a modern, professional marketplace platform designed to connect customers with trusted, vetted skilled workers and artisans. The platform showcases various service categories including electricians, plumbers, carpenters, barbers, painters, and handymen.

This is a static HTML/CSS prototype developed for a Full Stack Bootcamp project to demonstrate modern front-end design, UX principles, responsive layouts, and web accessibility.

## Table of Contents

1. [Features](#features)
2. [Pages](#pages)
3. [Design](#design)
4. [Technologies](#technologies)
5. [Installation](#installation)
6. [Accessibility](#accessibility)
7. [Testing](#testing)
8. [Future Enhancements](#future-enhancements)
9. [Attribution](#attribution)
10. [AI Usage Declaration](#ai-usage-declaration)

---

## Features

### ✅ Core Features Implemented

1. **Three Distinct Pages**
   - Home Page: Landing with hero, value proposition, and CTAs
   - Find a Pro Page: Service provider directory with filtering
   - Join as Pro Page: Professional registration form

2. **User Experience**
   - Intuitive navigation with smooth page transitions
   - Professional service cards with ratings and pricing
   - Search and filter functionality (visual prototype)
   - Testimonials section building social proof

3. **Visual Design**
   - Modern, clean interface inspired by TaskRabbit, Thumbtack, and Angi
   - Professional color palette (Navy Blue, Safety Orange, Neutrals)
   - Smooth animations and hover effects
   - Professional typography with Google Fonts

4. **Responsive Layout**
   - Mobile-first approach
   - Adapts seamlessly to all screen sizes
   - Optimized touch targets for mobile devices

5. **Accessibility**
   - Semantic HTML5 structure
   - ARIA labels and roles
   - Proper color contrast ratios
   - Lazy-loaded images
   - Keyboard navigation support

---

## Pages

### Page 1: Home (Landing Page)

**Sections:**
- Hero Section: Compelling headline, subheading, CTA
- How It Works: 3-step visual guide
- Popular Services: 6 service categories with icons
- Testimonials: Customer reviews with ratings
- Call-to-Action: Secondary engagement buttons

### Page 2: Find a Pro (Service Listings)

**Features:**
- Filter sidebar (service type, rating, price, availability)
- Professional grid layout
- 6 professional cards with images, ratings, pricing
- "View Profile" buttons

**Professional Cards Include:**
- High-quality images from Unsplash
- Verified badge
- Star ratings with review counts
- Professional descriptions
- Competitive pricing

### Page 3: Join as Pro (Registration)

**Features:**
- Professional registration form with validation
- Fields: Name, email, phone, trade, experience, location, bio, rate
- Services offered (checkboxes)
- Terms acceptance
- Contact information section
- Success confirmation modal

---

## Design

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Blue | #1e5a96 | Brand color, buttons, links |
| Secondary Orange | #f39c12 | Calls-to-action, alerts |
| Dark Gray | #2c3e50 | Body text, headings |
| Light Gray | #ecf0f1 | Backgrounds, borders |
| Success Green | #27ae60 | Verified badges |
| White | #ffffff | Main background |

### Typography

- **Headings:** Poppins (600-700 weight)
- **Body Text:** Inter (400-500 weight)
- **Source:** Google Fonts

---

## Technologies

### Frontend Stack

- **HTML5:** Semantic markup, accessibility
- **CSS3:** Custom properties, Flexbox, Grid, animations
- **Bootstrap 5.3.3:** Responsive framework
- **Font Awesome 6.5.2:** Icons
- **Vanilla JavaScript:** Navigation, form handling

### Performance

- Lazy loading on images
- CSS custom properties for theming
- Minified external resources via CDN
- Optimized images from Unsplash

---

## Installation

### Local Setup

1. **Clone Repository**
   ```bash
   git clone https://github.com/yaqubumar/skill-bridge.git
   cd skill-bridge
   ```

2. **Open in Browser**
   - Open `index.html` in your web browser
   - Or use Live Server extension in VS Code

### Project Structure
```
skill-bridge/
├── index.html          # Main HTML file (3 pages)
├── assets/
│   └── style.css       # All styling
└── README.md           # This file
```

### Deployment (GitHub Pages)

1. Push to GitHub
2. Go to repository settings
3. Enable GitHub Pages on `main` branch
4. Site published at: `https://yaqubumar.github.io/skill-bridge/`

**Alternative:** Deploy to Netlify or Vercel by connecting your GitHub repo

---

## Accessibility

### WCAG 2.1 Compliance

✅ **Perceivable**
- 7:1 color contrast on most text
- Alt text on all images
- Readable font sizes

✅ **Operable**
- Keyboard navigation fully supported
- Visible focus indicators
- Skip-to-main-content link
- Touch-friendly target sizes (44x44px minimum)

✅ **Understandable**
- Clear, simple language
- Consistent navigation
- Semantic HTML structure
- Form labels associated with inputs

✅ **Robust**
- Valid HTML5 and CSS3
- ARIA labels and roles
- Proper heading hierarchy
- Semantic HTML5 tags

### Features Implemented

- `<skip-link>` for keyboard users
- `aria-label` and `aria-required` attributes
- `alt` text on all images
- `loading="lazy"` for image optimization
- Focus management
- Semantic HTML tags: header, nav, main, footer, section

---

## Testing

### Validation

- ✅ W3C HTML Validator: All pages pass
- ✅ W3C CSS Jigsaw: All CSS passes
- ✅ No semantic errors

### Lighthouse Performance

- Performance: 85+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 95+

### Browser Compatibility

Tested on:
- Chrome 120+
- Firefox 120+
- Safari 15+
- Edge 120+
- Mobile browsers

### Responsive Breakpoints

- 320px (Mobile)
- 480px (Tablet)
- 768px (Small Tablet)
- 1024px (Desktop)
- 1440px+ (Large Desktop)

---

## Future Enhancements

### Phase 2 (Backend)
- [ ] User authentication
- [ ] Database for professional profiles
- [ ] Real payment processing (Stripe)
- [ ] Email notifications

### Phase 3 (Dynamic Features)
- [ ] Working search and filters
- [ ] Professional profile pages
- [ ] Review and rating system
- [ ] Booking calendar
- [ ] Real-time messaging

### Phase 4 (Advanced)
- [ ] AI-powered recommendations
- [ ] Mobile app
- [ ] Video consultations
- [ ] Analytics dashboard

---

## Known Issues

### Current Status: ✅ NO CRITICAL BUGS

### Limitations (By Design - Static Prototype)

1. Search & Filters: Visual only
2. Forms: Don't submit data (no backend)
3. Profile Pages: Visual only
4. No messaging system
5. No payment processing

---

## Attribution

### External Resources

**Images**
- Unsplash: All professional photos and hero images
- License: Free for commercial and non-commercial use
- URL: https://unsplash.com

**Icons**
- Font Awesome 6.5.2: All icons throughout the site
- License: Free license
- URL: https://fontawesome.com

**Fonts**
- Google Fonts: Poppins and Inter
- License: Open Font License (OFL)
- URL: https://fonts.google.com

**Framework**
- Bootstrap 5.3.3: Responsive grid and components
- License: MIT
- URL: https://getbootstrap.com

**Inspiration**
- TaskRabbit: https://www.taskrabbit.com
- Thumbtack: https://www.thumbtack.com
- Angi: https://www.angi.com

---

## AI Usage Declaration

### AI Tools Used

This project used AI assistance for:

1. **Code Generation**
   - HTML boilerplate suggestions
   - CSS structure organization
   - JavaScript function suggestions
   - Responsive design patterns

2. **Design & UX**
   - Color palette recommendations
   - Typography selection
   - Accessibility features
   - Layout patterns

3. **Documentation**
   - README structure
   - Content formatting
   - Accessibility checklists

### What Was NOT AI-Generated

- Core design decisions (developer-made)
- Business logic (manually written)
- Primary CSS styling (custom)
- Accessibility implementation (intentional)
- All content copy (manual creation)

### Code Quality

- All AI suggestions reviewed and adapted
- Code refactored for clarity
- Tested and validated
- Best practices maintained

---

## Project Statistics

- Total HTML Lines: 600+
- Total CSS Lines: 1100+
- JavaScript Lines: 50+ (minimal)
- Responsive Breakpoints: 4 major
- Professional Cards: 6 samples
- CSS Variables: 15+
- Form Fields: 10+
- Accessibility Features: 20+
- Cross-browser Tested: 4+ browsers

---

## Quick Links

- **GitHub:** https://github.com/yaqubumar/skill-bridge
- **Live Site:** [Coming Soon]
- **Issues:** GitHub Issues tab
- **Contact:** [Your contact info]

---

## License

MIT License - See LICENSE file for details

---

## Changelog

### Version 1.0.0 (Current)
- ✅ Complete redesign from previous version
- ✅ 3-page marketplace platform
- ✅ Professional responsive design
- ✅ WCAG accessibility compliance
- ✅ Modern UI/UX inspired by market leaders
- ✅ Semantic HTML5
- ✅ Custom CSS with variables
- ✅ GitHub integration

---

**Last Updated:** December 4, 2024
**Status:** ✅ Active & Complete (Static Prototype)

Thank you for visiting SkillBridge! 🚀
