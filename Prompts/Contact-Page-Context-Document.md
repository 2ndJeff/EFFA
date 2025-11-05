# Contact Page - Context Document
**Last Updated:** October 31, 2025  
**Version:** 2.0 (Revised for Universities Focus)  
**Page Status:** Complete and Ready for Deployment

---

## PROJECT OVERVIEW

**Page:** Contact Us / Get in Touch Page  
**Purpose:** Enable universities, employers, and partners to connect with EFFA for demos, information, and partnerships  
**Design Approach:** Universities-focused messaging with streamlined contact form and bottom tray tagline

---

## PAGE STRUCTURE

### Complete Layout
```
[Navigation - Standard EFFA nav with Blog link]
↓
[Hero Section]
- Dark gradient background
- Universities-focused copy
- "GET IN TOUCH" tag
- Clear value proposition
↓
[Contact Section - Two Column Layout]
- Left: Contact info sidebar with key details
- Right: Contact form with 7 streamlined fields
↓
[Bottom Tray Tagline Section]
- Dark background (#1a202c)
- Large tagline text with orange highlight
- Gradient divider line
↓
[Footer - Canonical Structure]
- Logo centered above
- 3 columns: Solutions | Company | Resources
- Copyright notice
```

---

## HERO SECTION

### Hero Design
- **Background:** Dark gradient (#1a202c to #2d3748)
- **Layout:** Centered content, max-width 800px
- **Tag:** "GET IN TOUCH" (orange on semi-transparent background)

### Hero Content
**Title:** "Scale **Employer Partnerships.** Grow Employer-Funded Enrollments."
- "Employer Partnerships" highlighted in orange (#F7931E)
- Line break after first sentence

**Subtitle:** "Connect with us to learn how EFFA can help your institution build stronger employer partnerships and increase employer-funded enrollments."

### Styling
- Title font size: 3rem (desktop), 2.5rem (tablet), 2rem (mobile)
- Title font weight: 700
- Subtitle font size: 1.25rem
- Subtitle color: #CBD5E0
- Max width: 650px

---

## CONTACT SECTION

### Two-Column Layout
- **Desktop:** Side-by-side (1fr | 1.5fr grid)
- **Mobile:** Stacked vertically

### Left Column: Contact Info Sidebar

**Card Design:**
- White background
- 3rem padding
- Border radius: 12px
- Box shadow: subtle

**Header:** "Let's Connect"

**Intro Text:** "Reach out to learn how EFFA can transform your tuition assistance programs and drive measurable results."

**Info Items (4 total):**

1. **Email Us**
   - Icon: ✉️
   - Email: demo@effa.io
   - Clickable mailto link

2. **For Employers**
   - Icon: 💼
   - Text: "Eliminate upfront costs and automate your entire tuition assistance program"

3. **For Universities**
   - Icon: 🎓
   - Text: "Grow partnerships by 25%+ with our 3.25% fee vs 20-45% TPA fees"

4. **Quick Response**
   - Icon: ⚡
   - Text: "We'll respond within 24 hours"

**Info Item Styling:**
- Light gray background (#F7FAFC)
- Padding: 1rem
- Border radius: 8px
- Hover effect: Orange tint + slight movement

### Right Column: Contact Form

**Card Design:**
- White background
- 3rem padding
- Border radius: 12px
- Box shadow: subtle

**Header:** "Send Us a Message"

**Subtitle:** "Complete the form below and we'll be in touch shortly."

**Form Fields (7 total, in order):**

1. **Full Name** (required)
   - Type: text input
   - Single field (not split first/last)

2. **Email Address** (required)
   - Type: email input
   - Validation: HTML5 email format

3. **Company/Organization** (required)
   - Type: text input

4. **Role/Title** (required)
   - Type: text input

5. **Purpose of Inquiry** (required)
   - Type: dropdown select
   - Options:
     - "Select one" (default, disabled)
     - "Request a Demo"
     - "Request How It Works PDF"
     - "Partner with Us"
   - Full width field

6. **What Would You Like to Learn About?** (optional)
   - Type: checkbox group
   - 4 options:
     - For Employers solution
     - For Universities solution
     - Job Ready Podcast
     - Partnership opportunities
   - Layout: 2 columns on desktop, 1 on mobile
   - Full width field

7. **Message/Additional Details** (optional)
   - Type: textarea
   - Min height: 120px
   - Placeholder: "Tell us about your needs, questions, or how we can help..."
   - Full width field

**Form Grid Layout:**
- Fields 1-4: Two-column grid on desktop
- Fields 5-7: Full width (span both columns)
- Mobile: All fields single column

**Submit Button:**
- Text: "Submit"
- Style: Full width, orange (#F7931E)
- Padding: 1rem 2rem
- Border radius: 6px
- Hover: Darker orange + lift + shadow

**Privacy Note:**
"By submitting this form, you agree to our Privacy Policy. We'll only use your information to respond to your inquiry and provide relevant information."
- Font size: 0.875rem
- Color: #718096
- Links in orange

---

## BOTTOM TRAY TAGLINE SECTION

### Design Specifications
- **Background:** Dark (#1a202c) - matches footer
- **Padding:** 5rem vertical, 5% horizontal
- **Text Alignment:** Center
- **Max Width:** 900px container

### Tagline Content
**Line 1:** "Let's make tuition assistance" (white text)  
**Line 2:** "Work for everyone" (orange text #F7931E)

**Styling:**
- Font size: 2.75rem (desktop), 2rem (tablet), 1.75rem (mobile)
- Font weight: 700 (bold)
- Line height: 1.3
- Display: Block elements for line control

### Divider
- Width: 100px
- Height: 4px
- Gradient: #F7931E to #FFA634
- Border radius: 2px
- Margin: 0 auto (centered)
- Position: Below tagline with 2rem spacing

**Note:** Tagline text is open for revision based on messaging preferences

**Alternative Tagline Options:**
1. "Ready to transform tuition assistance? / Let's talk"
2. "Building partnerships / That drive enrollment"
3. "Scale your impact / Grow your partnerships"
4. "Your success is our mission / Let's connect"

---

## FOOTER STRUCTURE

### Canonical Footer (Exact Match to About/Job Ready Pages)

**Logo:**
- File: `effalogo.png`
- Height: 40px
- Position: Centered above columns
- Filter: brightness(0) invert(1) for white appearance
- Margin-bottom: 3rem

**Three-Column Grid:**

**Column 1: Solutions**
- For Employers → `index.html`
- For Universities → `universities.html`

**Column 2: Company**
- About → `about.html`
- Contact → `contact.html`
- Blog → `blog.html`

**Column 3: Resources**
- Log In → `https://www.effa.io/login`
- Schedule a Demo → `contact.html`

**Footer Bottom:**
- Copyright: "© 2025 Employer-Funded Financial Aid, Inc. All rights reserved."
- Centered text
- Border-top separator (1px, rgba white 0.1)
- Padding-top: 2rem

**Styling:**
- Background: #1a202c
- Text color: #CBD5E0
- Headers: Orange (#F7931E), 1.1rem
- Links: #CBD5E0, hover to orange
- Link size: 0.95rem

---

## COLOR PALETTE

### Primary Colors
- **Orange (Brand Accent):** #F7931E
- **Secondary Orange:** #FFA634
- **Dark Background:** #1a202c
- **Dark Gradient:** #2d3748
- **Text Gray:** #4A5568
- **Light Gray:** #CBD5E0
- **Border Gray:** #E2E8F0
- **Background Gray:** #F7FAFC

### Usage by Section
- **Hero:** Dark gradient background, orange accents
- **Contact Section:** Light gray background (#F7FAFC), white cards
- **Bottom Tray:** Dark background (#1a202c), orange text
- **Footer:** Dark background (#1a202c), orange headers

---

## TYPOGRAPHY

### Font Family
- **Primary:** Inter (Google Fonts)
- **Weights Used:** 300, 400, 500, 600, 700
- **Fallback:** -apple-system, BlinkMacSystemFont, sans-serif

### Type Scale
- **Hero H1:** 3rem (desktop), 2.5rem (tablet), 2rem (mobile)
- **Hero Body:** 1.25rem
- **Section H2:** 1.75rem
- **Body Text:** 1rem
- **Small Text:** 0.95rem
- **Tiny Text:** 0.875rem
- **Tagline H2:** 2.75rem (desktop), 2rem (tablet), 1.75rem (mobile)
- **Footer Headers:** 1.1rem
- **Footer Links:** 0.95rem

### Font Weights
- Regular: 400
- Medium: 500
- Semi-bold: 600
- Bold: 700

---

## RESPONSIVE DESIGN

### Breakpoints
- **Desktop:** >968px
- **Tablet:** 641px - 968px
- **Mobile:** ≤640px

### Desktop Layout (>968px)
- Contact section: Two-column (1fr | 1.5fr)
- Form grid: Two columns
- Checkbox grid: Two columns
- Footer: Three columns
- Navigation: Full horizontal
- Tagline: 2.75rem

### Tablet Layout (641-968px)
- Contact section: Single column (stacked)
- Form grid: Single column
- Checkbox grid: Single column
- Footer: Single column, centered
- Navigation: Hidden (mobile menu)
- Tagline: 2rem

### Mobile Layout (≤640px)
- All content: Single column
- Card padding: 3rem → 2rem
- Hero title: 2rem
- Tagline: 1.75rem
- Touch-friendly tap targets
- Increased spacing for readability

---

## NAVIGATION

### Standard EFFA Navigation
Consistent across all pages:
- Home
- For Universities
- About
- Contact
- Blog
- Log In (outline button)
- Schedule a Demo (orange CTA button)

### Mobile Navigation
- Hamburger menu toggle (☰)
- JavaScript-powered show/hide
- Nav links hidden by default on mobile
- Full-width dropdown when active

---

## FORM BEHAVIOR

### Validation
- **Required fields:** Marked with * in label
- **HTML5 validation:** Email format checking
- **Visual feedback:** 
  - Focus state: Orange border + shadow
  - Error state: Red border (browser default)
  - Success state: Handled by JavaScript

### Submission
- **Current behavior:** JavaScript alert + form reset
- **Production needs:** 
  - Backend endpoint integration
  - Form processor (Formspree, Netlify Forms, etc.)
  - Email notification setup
  - Success/error page handling
  - Data validation and sanitization

### Form Action
- Current: `action="#"` (placeholder)
- Replace with actual endpoint or form processor URL

---

## FILE ASSETS

### Images Required
1. **effalogo.png**
   - Used in: Navigation (top) and Footer (centered above columns)
   - Size: 40px height in both locations
   - Footer version: White filter applied
   - Location: Same directory as HTML or in `images/logos/` folder

### File Organization for Deployment

**Option 1: Flat Structure**
```
contact-page/
├── contact.html
└── effalogo.png
```

**Option 2: With Subfolder**
```
contact-page/
├── contact.html
└── images/
    └── logos/
        └── effalogo.png
```

**Note:** Current HTML references flat structure. Adjust path to `images/logos/effalogo.png` if using subfolder.

---

## TECHNICAL SPECIFICATIONS

### HTML Structure
- **DOCTYPE:** HTML5
- **Charset:** UTF-8
- **Viewport:** Responsive meta tag included
- **Language:** en
- **External Dependencies:** Google Fonts (Inter family)

### CSS Architecture
- **Type:** Embedded styles in `<style>` tag
- **Approach:** Mobile-first with min-width media queries
- **Layout:** CSS Grid for sections, Flexbox for components
- **Units:** Rem-based for consistency
- **Custom Properties:** Color variables in :root

### JavaScript
- **Minimal:** Mobile menu toggle + form handling only
- **Dependencies:** None (vanilla JavaScript)
- **Form Handler:** Placeholder alert, needs backend integration
- **Mobile Menu:** Toggle nav visibility

---

## DESIGN SYSTEM COMPLIANCE

### ✅ Follows EFFA Design Standards
- Standard navigation structure with Blog link
- Canonical footer structure (exact match to About/Job Ready)
- Orange accent color usage (#F7931E)
- Inter typography throughout
- Dark gradient hero backgrounds
- Proper responsive breakpoints (968px, 640px)
- Mobile-first CSS approach
- Rem-based spacing units
- Consistent button styles
- Professional card designs

### ✅ Matches Other Pages
- Navigation: Same as all pages (with Blog link added)
- Footer: Exact match to About and Job Ready pages
- Color palette: Consistent with brand guidelines
- Typography: Same Inter font family and weights
- Button styles: Same orange primary CTAs
- Card styling: Same shadows and radius
- Spacing: Same padding and margin scales

---

## CONTENT STRATEGY

### Primary Audience
**Universities** - The hero copy and messaging are tailored to university administrators seeking to:
- Scale employer partnerships
- Grow employer-funded enrollments
- Access better economics (3.25% vs 20-45% TPA fees)

### Secondary Audiences
**Employers** - Sidebar mentions automation and upfront cost elimination

**Partners** - "Partner with Us" option in Purpose dropdown

### User Journey
1. Land on page → See universities-focused hero
2. Choose action:
   - Quick contact via email link
   - Complete form for specific inquiry
3. Select purpose (demo, PDF, or partnership)
4. Optionally select specific interests
5. Add message if needed
6. Submit form
7. Receive confirmation (24-hour response commitment)

### Why This Approach?
- **Clear intent capture:** Purpose dropdown routes inquiries properly
- **Flexibility:** Checkboxes allow multiple interest selections
- **Low friction:** Only 4 required fields, rest optional
- **Universities focus:** Hero speaks directly to target audience
- **Professional:** Consistent design builds trust

---

## KEY MESSAGING

### Hero
"Scale Employer Partnerships. Grow Employer-Funded Enrollments."
- Addresses university pain point (need more employer partners)
- Promises growth in funded enrollments
- Direct and action-oriented

### Contact Info
- **Email focus:** demo@effa.io (clear call to action)
- **Value props:** Specific benefits for each audience
- **Response commitment:** 24-hour turnaround builds trust

### Bottom Tray
"Let's make tuition assistance / Work for everyone"
- Inclusive messaging
- EFFA's mission statement
- Warm and approachable tone

---

## COMPARISON TO PREVIOUS VERSION

### What Changed
1. ✅ Hero copy: Generic → Universities-focused
2. ✅ Email: info@effa.io → demo@effa.io
3. ✅ Form fields: 11 → 7 (streamlined)
4. ✅ Added: Purpose of Inquiry dropdown
5. ✅ Added: Interest checkboxes section
6. ✅ Added: Bottom tray tagline section
7. ✅ Updated: Navigation (added Blog link)
8. ✅ Updated: Footer to canonical structure
9. ✅ Changed: Message field from required to optional
10. ✅ Removed: Phone, org type, employee count fields

### What Stayed the Same
- Two-column contact section layout
- Dark gradient hero design
- Form card styling
- Info sidebar structure
- Orange accent color usage
- Mobile responsive approach
- Form validation approach

---

## FORM FIELD SPECIFICATIONS

### Field Details

**1. Full Name**
- ID: fullName
- Name: fullName
- Type: text
- Required: Yes
- Max length: None specified
- Placeholder: None

**2. Email Address**
- ID: email
- Name: email
- Type: email
- Required: Yes
- Validation: HTML5 email format
- Placeholder: None

**3. Company/Organization**
- ID: company
- Name: company
- Type: text
- Required: Yes
- Max length: None specified
- Placeholder: None

**4. Role/Title**
- ID: role
- Name: role
- Type: text
- Required: Yes
- Max length: None specified
- Placeholder: None

**5. Purpose of Inquiry**
- ID: purposeOfInquiry
- Name: purposeOfInquiry
- Type: select (dropdown)
- Required: Yes
- Options:
  - "" (Select one - default, disabled)
  - "demo" (Request a Demo)
  - "pdf" (Request How It Works PDF)
  - "partner" (Partner with Us)

**6. What Would You Like to Learn About?**
- ID: Various (employers, universities, podcast, partnerships)
- Name: interests (all checkboxes)
- Type: checkbox
- Required: No
- Values:
  - employers (For Employers solution)
  - universities (For Universities solution)
  - podcast (Job Ready Podcast)
  - partnerships (Partnership opportunities)

**7. Message/Additional Details**
- ID: message
- Name: message
- Type: textarea
- Required: No
- Min height: 120px
- Placeholder: "Tell us about your needs, questions, or how we can help..."
- Resize: vertical

---

## ACCESSIBILITY NOTES

### Form Accessibility
- All inputs have associated labels
- Required fields marked with *
- Proper label/input associations (for attribute)
- Keyboard navigable
- Focus states clearly visible
- Logical tab order

### Semantic HTML
- Proper heading hierarchy (h1 → h2 → h3)
- Section elements for major page areas
- Nav element for navigation
- Footer element for footer
- Form element properly structured

### Color Contrast
- White text on dark backgrounds (#1a202c)
- Dark text on light backgrounds
- Orange (#F7931E) meets WCAG AA standards
- Links have sufficient contrast

---

## PERFORMANCE CONSIDERATIONS

### Loading
- Single external dependency (Google Fonts)
- Embedded CSS (no external stylesheet)
- Inline JavaScript (minimal)
- Single logo image
- No heavy libraries or frameworks

### Optimization Opportunities
- Minimize CSS if deploying separately
- Add image lazy loading if more images added
- Consider font subsetting for Inter
- Compress logo image
- Add service worker for offline capability

---

## SECURITY CONSIDERATIONS

### Form Security (For Production)
- **REQUIRED:** Backend validation of all inputs
- **REQUIRED:** CSRF protection
- **REQUIRED:** Rate limiting to prevent spam
- **REQUIRED:** Sanitization of all user inputs
- **RECOMMENDED:** reCAPTCHA or similar spam protection
- **RECOMMENDED:** Email verification for responses
- **RECOMMENDED:** SSL/HTTPS for form submission

### Privacy
- Privacy Policy link included
- Clear data usage statement
- GDPR/CCPA compliance needed if applicable
- User consent for email communication

---

## TESTING CHECKLIST

### Before Deployment
- [ ] Test all form fields accept input
- [ ] Verify required field validation works
- [ ] Test email format validation
- [ ] Check dropdown has correct options
- [ ] Verify checkboxes allow multiple selections
- [ ] Test form submission (should show alert currently)
- [ ] Verify email link (mailto:demo@effa.io) works
- [ ] Test all navigation links
- [ ] Check footer links
- [ ] Test mobile menu toggle
- [ ] Verify responsive breakpoints (968px, 640px)
- [ ] Test on mobile devices
- [ ] Test on tablets
- [ ] Test on different browsers (Chrome, Firefox, Safari, Edge)
- [ ] Verify logo displays correctly
- [ ] Check for any console errors
- [ ] Test keyboard navigation
- [ ] Verify focus states are visible
- [ ] Check color contrast
- [ ] Test with screen reader

---

## DEPLOYMENT INSTRUCTIONS

### Pre-Deployment
1. Review all content for accuracy
2. Update form action URL to actual endpoint
3. Test form submission to backend
4. Set up email notifications
5. Configure spam protection
6. Verify Privacy Policy link
7. Test on staging environment

### Deployment Steps
1. Upload HTML file to web server
2. Upload effalogo.png to same directory (or images/logos/)
3. Ensure file permissions are correct
4. Test live URL
5. Verify form submissions work
6. Check Google Analytics tracking (if implemented)
7. Monitor for any errors

### Post-Deployment
1. Submit test form to verify functionality
2. Check email notifications arrive
3. Test from different devices and browsers
4. Monitor form submission success rate
5. Set up ongoing monitoring for errors
6. Review form submissions regularly

---

## INTEGRATION NOTES

### Form Processor Options

**Option 1: Formspree**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option 2: Netlify Forms**
```html
<form name="contact" method="POST" data-netlify="true">
```

**Option 3: Custom Backend**
```javascript
fetch('/api/contact', {
    method: 'POST',
    body: formData
}).then(response => response.json())
  .then(data => {
      // Handle success
  });
```

### Email Integration
- Set up email templates for confirmations
- Configure auto-responder with next steps
- Set up internal notification system
- Create routing based on Purpose of Inquiry

---

## ANALYTICS TRACKING

### Recommended Events to Track
- Page view
- Form start (user focuses on first field)
- Form field completion
- Form submission attempt
- Form submission success
- Form submission error
- Email link click
- Navigation link clicks
- Footer link clicks
- Purpose dropdown selection
- Checkbox selections

### Example Google Analytics Code
```javascript
// Track form submission
gtag('event', 'form_submit', {
  'event_category': 'Contact',
  'event_label': 'Contact Form',
  'value': 1
});
```

---

## MAINTENANCE NOTES

### Regular Updates Needed
- Review form submissions weekly
- Update response time if changes
- Refresh copy as needed
- Keep footer links current
- Monitor spam and adjust protection
- Review analytics and optimize
- Test form functionality monthly

### Content Updates
- Email address (if changes)
- Phone number (if added)
- Office address (if added)
- Value propositions (as offers change)
- Tagline (if messaging evolves)

---

## KNOWN LIMITATIONS

### Current Version
- Form submission is placeholder (alert only)
- No backend integration
- No spam protection
- No success/error pages
- No email confirmations
- No form progress saving
- No file upload capability
- No multi-step form flow

### Future Enhancements (Optional)
- Add phone number field with formatting
- Add office locations map
- Add FAQ section
- Add live chat integration
- Add estimated response time by inquiry type
- Add form progress indicator if multi-step
- Add file attachment capability
- Add preferred contact method field
- Add preferred contact time field
- Add calendar integration for demo scheduling

---

## VERSION HISTORY

**Version 2.0 - October 31, 2025**
- Revised for universities focus
- Changed email to demo@effa.io
- Updated hero copy
- Added Purpose of Inquiry dropdown
- Added interest checkboxes section
- Added bottom tray tagline section
- Streamlined form (11 → 7 fields)
- Added Blog link to navigation
- Updated footer to canonical structure
- Made message field optional
- Removed phone, org type, employee count fields

**Version 1.0 - [Previous Date]**
- Initial generic contact page
- 11 form fields
- Generic hero copy
- No bottom tray section
- 4-column footer structure

---

## CONTACT INFORMATION

**Primary Contact:** demo@effa.io  
**Response Time:** Within 24 hours  
**Purpose:** Demo requests, PDF downloads, partnership inquiries

---

## RELATED PAGES

**For Context:**
- About Page (about.html) - Footer and design reference
- Job Ready Page (podcast.html) - Bottom tray reference
- Universities Page (universities.html) - Audience focus reference
- Employers Page (index.html) - Alternative audience reference

**For Navigation:**
- Home (index.html)
- For Universities (universities.html)
- About (about.html)
- Blog (blog.html)
- Log In (https://www.effa.io/login)

---

## PROJECT INFORMATION

**Project:** EFFA Website Redesign  
**Page:** Contact Us  
**Status:** ✅ Complete and Ready for Deployment  
**Last Updated:** October 31, 2025  
**Version:** 2.0 (Universities Focus)

---

**This context document contains everything needed to understand, maintain, and deploy the Contact page. When starting work on this page in the future, refer to this document for complete specifications and design rationale.**

---

## QUICK REFERENCE

**Email:** demo@effa.io  
**Tagline:** "Let's make tuition assistance / Work for everyone"  
**Form Fields:** 7 total (4 required, 3 optional)  
**Bottom Tray:** Dark background, orange tagline, gradient divider  
**Footer:** 3 columns, canonical structure, logo centered above  
**Navigation:** Includes Blog link  
**Breakpoints:** 968px (tablet), 640px (mobile)  
**Primary Color:** #F7931E (orange)  
**Font:** Inter (300, 400, 500, 600, 700)

---

**END OF CONTEXT DOCUMENT**
