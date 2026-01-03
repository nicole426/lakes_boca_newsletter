# Lakes Boca Newsletter Landing Page

A professional newsletter landing page for the Edmund Bogen Team at Douglas Elliman Real Estate, featuring the Lakes of Boca Raton luxury real estate communities.

## Overview

This landing page allows potential subscribers to sign up for the Lakes Boca Newsletter, which provides:
- Monthly market updates for Boca Raton luxury communities
- Exclusive new listings and price updates
- Expert real estate insights from the Edmund Bogen Team
- Community-specific information for prestigious neighborhoods

## Features

### Design
- **Brand Consistent**: Uses Edmund Bogen Team brand colors and styling
- **Responsive**: Fully mobile-optimized for all devices
- **Professional**: Clean, modern design that reflects luxury real estate market
- **Accessible**: Semantic HTML with proper form labels and structure

### Sections
1. **Header**: Edmund Bogen Team branding with Douglas Elliman affiliation
2. **Hero Section**: Eye-catching headline and value proposition
3. **Newsletter Signup Form**: Comprehensive form with name, email, phone, and interest checkboxes
4. **Benefits Section**: 4 key benefits of subscribing (Market Updates, Exclusive Listings, Expert Insights, Community Focus)
5. **Featured Communities**: Tag list of covered neighborhoods
6. **Call-to-Action**: Final conversion opportunity
7. **Footer**: Contact information and links

## Brand Colors

- **Primary Blue**: `#00a8e1` - Main brand color for buttons and accents
- **Dark Navy**: `#1a3e5c` - Primary text and headings
- **Light Backgrounds**: `#f5f5f5` and `#f8fbff` - Section backgrounds
- **Accent Colors**: Used for tags and status indicators

## Files

- `index.html` - Main landing page HTML
- `styles.css` - Complete stylesheet with responsive design
- `home property` - Email template (existing)
- `lake at boca edited.jpg` - Property image (existing)

## Usage

### Viewing Locally
Simply open `index.html` in any modern web browser.

### Deploying
This is a static HTML/CSS site and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service
- Your own web server

### Integration

The form currently includes a JavaScript handler that prevents default submission and logs the data to the console. To connect it to your email service provider:

1. **For Email Service Providers** (Mailchimp, ConvertKit, etc.):
   - Update the `action` attribute in the form to point to your provider's endpoint
   - Add any required hidden fields for your provider
   - Modify the form field names to match your provider's API

2. **For Custom Backend**:
   - Update the JavaScript in the `<script>` section
   - Send form data to your API endpoint using fetch/axios
   - Handle success/error responses appropriately

Example integration with Mailchimp:
```html
<form action="https://your-mailchimp-endpoint.com/subscribe" method="POST">
    <!-- Add Mailchimp hidden fields -->
</form>
```

## Customization

### Adding More Communities
Edit the "Featured Communities Section" in `index.html`:
```html
<div class="community-tag">Your Community Name</div>
```

### Changing Colors
Update the CSS variables in `styles.css`:
```css
:root {
    --primary-blue: #00a8e1;
    --dark-navy: #1a3e5c;
    /* etc... */
}
```

### Modifying Benefits
Edit the `.benefit-card` sections in the "Benefits Section" of `index.html`.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact

**Edmund Bogen Team**
Douglas Elliman Real Estate
Phone: (561) 235-7575
Website: [bogenhomes.com](https://bogenhomes.com)
Contact Form: [bogenhomes.com/contact](https://bogenhomes.com/contact/)

## License

© 2025 Edmund Bogen Team. All rights reserved.
