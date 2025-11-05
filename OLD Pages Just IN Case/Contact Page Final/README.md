# EFFA Contact Page - Complete Package

## Overview

This is a professional contact/demo scheduling page that matches the design system across all EFFA pages. It can be used as a standalone page or linked from "Schedule a Demo" buttons throughout the site.

## What's Included

### Files:
- `contact.html` - Complete contact/demo scheduling page
- `images/logos/effalogo.png` - EFFA logo for navigation and footer

## Page Features

### Design Consistency
✅ **Same navigation** as all other pages
✅ **Same footer** as all other pages
✅ **Same color scheme** - Dark hero with orange accents
✅ **Same typography** - Inter font family
✅ **Same button styles** - Orange primary buttons
✅ **Responsive design** - Works on all devices

### Contact Form Features
- **Two-column layout** on desktop (info sidebar + form)
- **Comprehensive form fields:**
  - First Name / Last Name
  - Work Email
  - Phone Number (optional)
  - Organization Name
  - Your Role
  - Organization Type (Employer/University/Consultant/Other)
  - Employee/Student Count
  - Message/Questions
- **Form validation** - Required fields marked with *
- **Privacy note** at bottom of form
- **Submit button** with hover effects

### Contact Information Sidebar
- Email address
- Value propositions for employers
- Value propositions for universities
- Response time commitment

### Hero Section
- Dark gradient background (matches About page)
- Orange accent color for "Transform"
- Clear call-to-action messaging
- "GET IN TOUCH" tag

## Folder Structure

```
contact-page-package/
├── contact.html
├── README.md
└── images/
    └── logos/
        └── effalogo.png
```

## How to Use

### As Standalone Page:
1. Extract the package
2. Open `contact.html` in your browser to preview
3. Upload to your web server maintaining folder structure

### Integration with Existing Site:
1. Upload `contact.html` to your site root
2. Ensure `images/logos/` folder exists with logo
3. Update "Schedule a Demo" links across site to point to `contact.html`

### Form Submission Setup

The form currently includes basic JavaScript that shows an alert on submission. To make it functional:

**Option 1: Backend Integration**
Replace the JavaScript at the bottom of the page to send data to your backend:

```javascript
document.getElementById('demoForm').addEventListener('submit', function(e) {
    e.preventDefault();
    const formData = new FormData(this);
    
    fetch('/api/schedule-demo', {
        method: 'POST',
        body: formData
    }).then(response => response.json())
      .then(data => {
          alert('Thank you! We\'ll be in touch within 24 hours.');
          this.reset();
      });
});
```

**Option 2: Third-Party Form Service**
Update the `<form>` tag's `action` attribute to use services like:
- Formspree: `action="https://formspree.io/f/YOUR_FORM_ID"`
- Netlify Forms: Add `netlify` attribute
- Google Forms: Create form and use iframe embed
- HubSpot: Add HubSpot form embed code

**Option 3: Email Service**
Use a service like EmailJS to send form data directly to your email without a backend.

## Customization Options

### Update Email Address:
Line 325: Change `info@effa.io` to your actual email

### Add Phone Number:
Add a new info-item block in the sidebar with your phone number

### Modify Form Fields:
- Add/remove fields in the `<form>` section
- Update dropdown options for organization type or employee count
- Change required fields by adding/removing `required` attribute

### Change Response Time:
Line 355: Update "within 24 hours" to your actual response time

## Design Notes

### Color Scheme:
- Primary Orange: #F7931E
- Dark Background: #1a202c / #2d3748
- Light Gray Background: #F7FAFC
- Text Gray: #4A5568 / #718096

### Responsive Breakpoints:
- Desktop: >968px (two-column layout)
- Tablet: 640px-968px (single column, nav hidden)
- Mobile: <640px (optimized padding)

### Hover Effects:
- Buttons: Lift and shadow on hover
- Info items: Background color change and slide on hover
- Links: Orange underline on hover

## Testing Checklist

Before deploying:
- [ ] Test form submission
- [ ] Verify all links work (nav, footer)
- [ ] Check responsive design on mobile
- [ ] Test form validation (try submitting empty fields)
- [ ] Verify email link opens mail client
- [ ] Check all images load correctly
- [ ] Test on different browsers

## Integration Points

This page works with these navigation links:
- **Navigation:** "Schedule a Demo" button links to `contact.html`
- **Homepage:** CTA buttons can link to `contact.html`
- **For Employers page:** CTA buttons can link to `contact.html`
- **For Universities page:** CTA buttons can link to `contact.html`
- **Footer:** "Request Demo" link to `contact.html`

## Form Data Captured

When integrated with a backend, you'll receive:
1. First Name
2. Last Name
3. Work Email
4. Phone Number
5. Organization Name
6. Role/Title
7. Organization Type (Employer/University/etc.)
8. Employee/Student Count
9. Message/Specific Questions

This data gives you everything needed to:
- Qualify the lead
- Prepare for the demo
- Route to appropriate team member
- Follow up appropriately

## Support

For questions about customization or integration:
- Refer to the main project context document
- Check inline HTML comments for guidance
- Test changes in a browser before deploying

---

**Ready to deploy!** This page matches your design system perfectly and can be used immediately for demo scheduling.
