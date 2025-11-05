# EFFA Contact Page - Project Brief for Claude

Hi Claude! I'm continuing work on the EFFA website redesign project. I need your help creating a Contact Us page.

## Context Files to Review
Please start by reading these files from the project:
1. **EFFA-Design-System-Context_v3.md** - Complete design system and standards (PLEASE READ THIS FIRST)
2. **effalogo.png** - Logo file for navigation and footer

## Project Status
✅ **Completed Pages:**
- Homepage (Employer-focused - dark gradient with orange accents)
- Universities Page (Blue gradient theme)
- About Page (Dark hero with 7 sections)
- Job Ready Podcast Page (Simplified: hero + tagline + footer)

🔄 **Current Task:** Create Contact Us page

## CRITICAL REQUIREMENTS - READ FIRST

**These are non-negotiable requirements that MUST be included:**

1. **Email Address:** demo@effa.io (use this exact email)

2. **Hero Copy:** "Scale Employer Partnerships. Grow Employer-Funded Enrollments."

3. **Bottom Tray Tagline Section:** MUST include a bottom tray section matching the Job Ready page structure:
   - Dark background (#1a202c)
   - Two-line tagline (first line white, second line orange)
   - Gradient divider line below
   - Positioned between content and footer

4. **Purpose of Inquiry Dropdown:** Form MUST include dropdown field with these exact options:
   - Request a Demo
   - Request How It Works PDF
   - Partner with Us

## Contact Page Requirements

### Page Purpose
Create a professional contact page that allows visitors to:
1. Request a demo or consultation
2. Ask general questions
3. Contact the EFFA team
4. Find basic company information

### Page Structure Needed

**Layout:**
```
[Navigation - standard EFFA nav]
↓
[Hero Section]
- Title based on audience (see hero copy requirements)
- Subtitle/body copy about reaching out
- Keep it simple and welcoming
↓
[Contact Form Section]
- Form with required fields (see detailed field list below)
↓
[Company Information Section]
- Email: demo@effa.io
- Additional contact info if available
↓
[Bottom Tray Tagline Section]
- MUST INCLUDE (same style as Job Ready page)
- Dark background, centered text
- Two-line tagline with orange highlight
- Gradient divider
↓
[Footer - Canonical structure]
- Same as About and Job Ready pages
```

### Contact Form Fields Needed

**Form Field Order (Top to Bottom):**

1. **Full Name** (text input, required)
2. **Email Address** (email input, required)
3. **Company/Organization** (text input, required)
4. **Role/Title** (text input, required)
5. **Purpose of Inquiry** (dropdown, required) - MUST INCLUDE THIS FIELD
   - Option 1: Request a Demo
   - Option 2: Request How It Works PDF
   - Option 3: Partner with Us
6. **What Would You Like to Learn About?** (checkboxes, optional)
   - For Employers solution
   - For Universities solution
   - Job Ready Podcast
   - Partnership opportunities
7. **Message/Additional Details** (textarea, optional)

**Submit Button:**
- Text: "Submit" or "Send Message"
- Style: Primary orange button (#F7931E)
- Full width on mobile, standard width on desktop

**Form Actions:**
- Submit button (primary orange style)
- Success message (either on same page or separate thank you page)
- Form validation

### Design Specifications

**Hero Section:**
- Background: Use dark gradient (#1a202c, #2d3748) similar to Homepage and About page
- Or consider a lighter background if that works better for a contact page
- Keep hero simple and welcoming
- No need for stat badges or complex layouts

**Form Section:**
- Clean, modern form design
- Proper spacing and padding
- Clear labels
- Input field styling consistent with brand
- Error states for validation
- Success state after submission

**Color Palette:**
- Use standard EFFA colors (dark grays, orange accents #F7931E)
- Form inputs: Light background, clear borders
- Submit button: Orange (#F7931E)
- Error states: Red or orange tint
- Success states: Green or orange tint

### Navigation & Footer
- **Navigation:** Use standard EFFA navigation (same as all other pages)
  - Home, For Universities, About, Contact, Blog, Log In, Schedule a Demo
- **Footer:** Use EXACT canonical footer structure from About/Job Ready pages
  - Logo centered above
  - 3 columns: Solutions | Company | Resources
  - Copyright line

### Content Suggestions

**Hero Copy Ideas:**
- "Get in Touch"
- "Let's Talk About Your Tuition Assistance Goals"
- "Contact Us"
- "Ready to Transform Your Tuition Assistance Program?"

**SPECIFIC HERO COPY REQUIREMENTS:**

**For Universities Hero Copy (MUST USE THIS):**
"Scale Employer Partnerships. Grow Employer-Funded Enrollments."

### Bottom Tray Tagline Section
**CRITICAL:** The Contact page MUST include a bottom tray tagline section (between form/content and footer) that matches the Job Ready page structure EXACTLY:
- Dark background (#1a202c)
- Centered tagline text
- First line in white
- Second line highlighted in orange (#F7931E)
- Gradient divider line below (100px wide, 4px height, orange gradient)

**Suggested tagline options:**
- "Let's make tuition assistance / Work for everyone"
- "Ready to get started? / Let's talk"
- Or suggest an appropriate alternative

**Form Section Copy:**
- "Send Us a Message" or "How Can We Help?"
- Brief intro about the team being ready to help
- Response time expectation (e.g., "We'll respond within 24 hours")

**Company Info Section:**
- **Email:** demo@effa.io (MUST USE THIS EMAIL)
- If physical address available, include it
- Business hours if relevant
- Social media links if available

### Technical Requirements

**Form Handling:**
- For now, form can be set up with a placeholder action
- Consider options:
  - Action pointing to form processor (Formspree, Netlify Forms, etc.)
  - Action pointing to EFFA's backend endpoint (if you have one)
  - Mailto fallback (simple but not ideal)
- Include basic HTML5 validation (required fields, email format)
- Consider adding simple JavaScript validation for better UX

**Responsive Design:**
- Mobile-first approach
- Form fields stack on mobile
- Comfortable tap targets for mobile
- Form remains usable at all breakpoints

### Design Elements to Include

**Consistent with Other Pages:**
- Section tags/capsules if using multiple sections (optional for Contact page)
- Orange accent color for CTAs and links
- Inter typography
- Proper spacing (rem-based)
- Hover states on buttons and links

**Form-Specific:**
- Input focus states (orange border or glow)
- Placeholder text in light gray
- Required field indicators (asterisks)
- Error message styling
- Success message styling

### Optional Enhancements

Consider adding:
- **Map section** - If you have an office location to showcase
- **FAQ section** - Quick answers to common questions
- **Alternative contact methods** - Chat, phone, social media
- **Office hours** - When the team is available
- **Response time expectation** - Set expectations for reply time

### What I DON'T Need (Yet)
- No backend form processing (we can add that later)
- No complex multi-step forms
- No file upload functionality
- No live chat integration

### Deliverables Requested

1. **Preview of the Contact page** (so we can review together)
2. **After approval**, create a downloadable folder with:
   - HTML file
   - Logo image (effalogo.png)
   - README file for the folder
   - Context document

### Questions for Claude to Consider

Before building, please consider:
1. Should the hero be dark (like Homepage/About) or light?
2. Single column form or two-column layout (if two-column, which fields go where)?
3. Should we include a section tag above the form section?
4. Any additional sections needed beyond hero + form + company info?

## Design System Reminders
- Use standard EFFA navigation with Blog link
- Apply consistent typography (Inter font family)
- Maintain orange accent color (#F7931E) for primary actions
- Keep dark gradient backgrounds where appropriate
- Ensure mobile responsiveness at 768px breakpoint
- Footer MUST match canonical structure EXACTLY (same as About/Job Ready pages)

## Process
1. First, show me a preview of the Contact page
2. We'll review and refine together
3. Once approved, create the final downloadable package with all files

## Important Notes
- I want to see a preview first before creating the downloadable files
- We'll collaborate on the exact copy and form fields
- The footer structure is critical - use EXACTLY as documented in the design system
- Form functionality can be basic for now (we'll enhance later)
- Focus on clean, professional design that matches the rest of the site

## Key Information About EFFA

**Company:** EFFA (Employer-Funded Financial Aid, Inc.)
**Mission:** Making tuition assistance work for employers, universities, and students
**Key Value Prop:** 3.25% fee vs 20-45% TPA fees
**Contact Email:** demo@effa.io (or use appropriate contact email)
**Website:** effa.io

**Target Audiences:**
- Employers looking to offer tuition assistance
- Universities seeking employer partnerships
- Partners and potential collaborators

Ready to proceed when you are! Please start by reviewing the design system context document and confirming you understand the requirements.

---

**Project:** EFFA Website Redesign  
**Page:** Contact Us  
**Status:** Ready to Begin  
**Date:** October 31, 2025
