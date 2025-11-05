# EFFA Website Project - Current Context & Status

**Last Updated:** November 4, 2025  
**Project:** Converting EFFA marketing pages from static HTML to Next.js components  
**Project Owner:** Jeff Nelder (2ndJeff on GitHub)

---

## 📋 Project Overview

This project involves converting 5 static HTML marketing pages into Next.js components and deploying them to EFFA's QA and production sites.

**Goal:** Replace old static pages with new, modern designs while maintaining the Next.js platform architecture.

---

## 🎯 Current Status

**Phase:** Phase 0 - Preparing to upload HTML files to GitHub repository

**What's Complete:**
- ✅ All 5 HTML pages finalized with latest content
- ✅ All images collected and organized in package folders
- ✅ Claude Code CLI installed and authenticated
- ✅ HTML files consolidated into single folder for easy upload
- ✅ VS Code installed and configured locally

**Next Steps:**
- 🔲 Create EFFA repository on GitHub (under 2ndJeff account)
- 🔲 Initialize Git in local project folder
- 🔲 Connect local folder to GitHub repository
- 🔲 Upload HTML files to conversion-source/ directory
- 🔲 Upload images to repository
- 🔲 Begin Next.js conversion process

---

## 💻 Local Environment Setup

### File Locations
**Local Project Directory:**
```
/Users/jeffnelder/Documents/NewCo./New EFFA Site/
```

**HTML Files (Consolidated):**
```
/Users/jeffnelder/Documents/NewCo./New EFFA Site/html-files/
├── homepage-updated.html
├── about-updated.html
├── universities-updated.html
├── job-ready-updated.html
└── contact-updated.html
```

**Original Package Folders:**
- `Homepage Package 103125/` - Contains homepage HTML + images + README
- `About Page Package 103125/` - Contains about HTML + images + README
- `Contact Package 103125/` - Contains contact HTML + images + README
- `For Universities Page Package 103125/` - Contains universities HTML + images + README
- `Job Ready Package 103125/` - Contains job-ready HTML + images + README

### Tools Installed
- ✅ **VS Code** - Code editor with `code` command in PATH
- ✅ **Claude Code CLI v2.0.33** - Command-line AI assistant
- ✅ **Terminal** - Using bash shell (`/bin/bash`)
- ✅ **Node.js & Command Line Developer Tools** - Required dependencies

---

## 🔧 GitHub Repository Information

### Current State
- **GitHub Username:** 2ndJeff
- **Existing Repository:** `https://github.com/2ndJeff/2ndJeff` (profile config)
- **EFFA Repository:** Does not exist yet - needs to be created

### Target Repository Structure
Once created, the EFFA repository will be:
- **URL:** `https://github.com/2ndJeff/EFFA`
- **Purpose:** EFFA website project
- **Branch Strategy:** 
  - `main` - production code
  - Feature branches for development work

### Site URLs
- **Production:** https://effa.io
- **QA:** https://qa.effa.io

---

## 📄 HTML Files Status (v2.4 - Latest)

### 1. homepage-updated.html
**Route:** `/`  
**Recent Changes (Nov 4, 2025):**
- Updated hero stat boxes:
  - "100% Quantifiable ROI - Instant insight with real time data"
  - "95% Faster Setup - No Integration Required"
  - "Zero Cost to Employers - Schools pay 3.25% transaction fee"

### 2. about-updated.html
**Route:** `/about`  
**Recent Changes (Nov 4, 2025):**
- Solution Section: Changed "See How It Works" to "Request a Demo"
- Final CTA Section: Removed "Partner With Us" button

### 3. universities-updated.html
**Route:** `/university`  
**Status:** Original version, ready for conversion

### 4. job-ready-updated.html
**Route:** `/jobready`  
**Status:** Original version, ready for conversion

### 5. contact-updated.html
**Route:** `/contactus` ⚠️ (Note: NOT `/contact`)  
**Recent Changes (Nov 4, 2025):**
- Removed "Purpose of Inquiry" dropdown field
- Updated response time to "24-48 hours"

---

## 🖼️ Images Required

Each page package contains images that need to be uploaded to the repository:

**Common Images (Used on Multiple Pages):**
- `effalogo.png` - Main EFFA logo
- `effalogowhite.png` - White version for footer

**Homepage Images:**
- `herolaptop.png`
- `step1quicksetup.png`
- `step2employeeenrollment.png`
- `step3automatedcompliance.png`
- `step4simplebilling.png`
- `diverseprofessionals.jpg`

**About Page Images:**
- Team headshots (8 files):
  - `Doug_Sellers_Headshot.jpg`
  - `James_Oliverio_Headshot.png`
  - `Gary_Bolles_Headshot_copy.png`
  - `Joseph_Clay_Headshot.jpeg`
  - `Matt_Ankrum_Headshot.png`
  - `Norm_Allgood_Headshot.png`
  - `Rob_Wrubel_Headshot.png`
  - Plus additional team members

**Job Ready Page Images:**
- `EFFA_logo_EVT_circle_JobReady__1_.png` - Podcast logo
- `Job_Ready_the_EFFA_Podcast_Logo_Square.png`

---

## 🗺️ Project Roadmap

### Phase 0: Upload Files to Repository (CURRENT)
**Status:** Ready to begin  
**Tasks:**
1. Create EFFA repository on GitHub
2. Initialize Git in local project folder
3. Create `conversion-source/` directory in repository
4. Upload 5 HTML files to `conversion-source/`
5. Create `public/` directory in repository
6. Upload all images to `public/`

### Phase 1: Git Setup & Safety
**Tasks:**
- Verify main branch exists
- Create feature branch for conversion work
- Establish Git workflow

### Phase 2: Understand Conversion Strategy
**Tasks:**
- Review Next.js project structure
- Identify shared components needed
- Plan conversion approach

### Phase 3: Create Shared Components
**Tasks:**
- Extract Navigation component
- Extract Footer component
- Test components render correctly

### Phase 4: Convert Individual Pages
**Tasks:**
- Convert homepage to Next.js
- Convert about page to Next.js
- Convert universities page to Next.js
- Convert job-ready page to Next.js
- Convert contact page to Next.js

### Phase 5: Comprehensive Testing
**Tasks:**
- Test locally (npm run dev)
- Verify all links work
- Verify all images load
- Test responsive design
- Check for console errors

### Phase 6: Commit Changes to Git
**Tasks:**
- Stage all changes
- Create meaningful commit messages
- Push to feature branch

### Phase 7: Deploy to QA
**Tasks:**
- Merge feature branch to main
- Deploy to qa.effa.io
- Test on QA environment
- Fix any issues found

### Phase 8: Deploy to Production
**Tasks:**
- Final QA approval
- Deploy to effa.io
- Monitor for issues
- Verify all functionality

### Phase 9: Cleanup
**Tasks:**
- Delete feature branch (optional)
- Archive old HTML files
- Document any custom changes
- Update team on new structure

---

## 🔑 Critical Technical Details

### Important URLs & Routes
- **Contact Page MUST be:** `/contactus` (not `/contact`)
- **Universities Page:** `/university` (singular, not plural)
- **Job Ready Page:** `/jobready` (one word, no hyphen)

### Technology Stack
- **Framework:** Next.js with TypeScript
- **Styling:** Tailwind CSS (convert from inline styles)
- **Components:** React functional components with hooks
- **UI Library:** shadcn/ui
- **Images:** Next.js Image component (optimized)
- **Links:** Next.js Link component (fast navigation)

### Key Conversion Requirements
1. All images must be in `/public` directory
2. Navigation links use Next.js `<Link>` component
3. Convert inline CSS to Tailwind utility classes
4. Maintain exact visual design from HTML versions
5. Ensure mobile responsive design
6. Set proper page metadata (titles, descriptions)

---

## 👤 User Profile

### Experience Level
- **Git:** First-time user (learning CLI workflow)
- **Next.js:** First-time converting HTML to components
- **Claude Code CLI:** Just learned and set up
- **VS Code:** Just installed and configured
- **Deployment:** Will be first time deploying to QA/production
- **Command Line:** Learning as we go

### Working Style
- Detail-oriented and thorough
- Appreciates clear, step-by-step instructions
- Asks good clarifying questions
- Prefers to understand "why" behind actions
- Values learning over just getting things done quickly

### Communication Preferences
1. Confirm understanding before proceeding
2. Explain what each command does
3. Provide expected results for verification
4. Offer troubleshooting if issues arise
5. Break complex tasks into smaller steps

---

## 🛠️ Current Workflow Setup

### Three-Window Workflow
When working on the project, have these open:

1. **Claude.ai Chat (Web Browser)**
   - Main guidance and strategy
   - Step-by-step instructions
   - Troubleshooting assistance
   - This is where Jeff gets overall direction

2. **Terminal with Claude Code CLI**
   - AI coding assistant
   - Executes Git commands
   - Creates/modifies files
   - Runs development server
   - Navigate here: `cd "/Users/jeffnelder/Documents/NewCo./New EFFA Site"`
   - Start Claude Code: `claude`

3. **VS Code**
   - View project files and structure
   - Review code changes
   - Make manual edits if needed
   - Open to project folder: `/Users/jeffnelder/Documents/NewCo./New EFFA Site`

---

## 📚 Documentation Files

### Available in Project
- `EFFA Website Conversion Guide.docx` - Comprehensive conversion guide
- `EFFA Website Deployment FAQ with JC.docx` - Deployment Q&A
- Individual README files in each package folder
- Context documentation in `Context Docs/` folder

### Available in Claude.ai Project Knowledge
- Original PROJECT-CONTEXT.md (outdated - being replaced by this document)
- EFFA-Website-Context-v2.4.md
- URL-REFERENCE-GUIDE.md
- QUICK-REFERENCE-CARD.md
- Various other reference documents

---

## ⚠️ Common Issues & Solutions

### Issue: `claude: command not found`
**Solution:** Add to PATH and source profile:
```bash
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bash_profile && source ~/.bash_profile
```

### Issue: Git repository not initialized
**Solution:** Will be fixed when we create and connect to GitHub repository in Phase 0

### Issue: Claude Code indexes entire computer
**Solution:** Always navigate to project folder BEFORE starting Claude Code:
```bash
cd "/Users/jeffnelder/Documents/NewCo./New EFFA Site"
claude
```

### Issue: Terminal doesn't recognize new commands
**Solution:** Close and reopen Terminal, or source the profile:
```bash
source ~/.bash_profile
```

---

## ✅ Success Criteria

The project will be successful when:

**Technical Success:**
- ✅ All 5 pages converted to Next.js components
- ✅ All images loading correctly
- ✅ Navigation consistent across all pages
- ✅ Footer consistent across all pages
- ✅ Mobile responsive design working
- ✅ All links functional
- ✅ Contact form submitting properly
- ✅ No console errors in browser
- ✅ Pages work on QA site: https://qa.effa.io
- ✅ Pages deployed to production: https://effa.io

**Learning Success:**
- ✅ Jeff understands Git workflow
- ✅ Jeff can use Claude Code CLI for future projects
- ✅ Jeff understands Next.js component structure
- ✅ Jeff can deploy updates independently

---

## 🎯 Immediate Next Actions

**When resuming this project, follow these steps:**

### Step 1: Create EFFA Repository on GitHub
1. Go to https://github.com/2ndJeff
2. Click "New" repository button
3. Name: `EFFA`
4. Description: "EFFA website - employer-funded financial aid platform"
5. Make it Public or Private (your choice)
6. Do NOT initialize with README (we have files already)
7. Click "Create repository"

### Step 2: Connect Local Folder to GitHub
In Terminal (with Claude Code):
```
Initialize this directory as a Git repository and connect it to the new GitHub repository at https://github.com/2ndJeff/EFFA
```

### Step 3: Create Repository Structure
```
Create a folder called conversion-source and move all the HTML files from html-files/ into conversion-source/
```

### Step 4: Commit and Push
```
Commit all the HTML files with the message "Add source HTML files for conversion" and push to GitHub
```

### Step 5: Upload Images
Extract and upload all images from the package folders to the repository

---

## 📝 Notes for Future Claude Sessions

When continuing this project in a new session:

1. **Read this context document first** - It contains the accurate, current state
2. **Check the "Current Status" section** - See what's been completed
3. **Follow the "Immediate Next Actions"** - Clear next steps
4. **Remember the three-window workflow** - Chat, Terminal, VS Code
5. **Jeff is learning** - Explain commands and why we're doing things
6. **Verify before acting** - Confirm understanding before running commands

---

## 🔄 Version History

**v3.0 - November 4, 2025 (This Version)**
- Complete rewrite with accurate information
- Corrected GitHub username (2ndJeff, not jeff-creighton)
- Corrected local paths (actual Mac paths)
- Added Claude Code CLI setup details
- Documented current file organization
- Added three-window workflow
- Clarified immediate next actions

**v2.0 - November 4, 2025 (Previous Version)**
- Updated homepage hero stat boxes
- Modified about page buttons
- Updated contact page form and response time
- Contained incorrect repository information

**v1.0 - November 3, 2025 (Original Version)**
- Initial HTML pages created
- Conversion guide written
- Package structure prepared
- Contained incorrect repository information

---

## 💡 Tips for Success

**For Jeff:**
- Take breaks when needed - this is a learning process
- Ask "why" questions - understanding beats just following steps
- Keep all three windows organized on your screen
- Don't worry about making mistakes - Git lets us undo anything
- Claude Code CLI will ask permission before running commands - read them first

**For Claude (AI Assistant):**
- Always explain what commands do before asking Jeff to run them
- Provide expected results so Jeff can verify success
- Break complex tasks into small, manageable steps
- If something fails, explain why and offer alternative approaches
- Remember Jeff is learning - patience and clear explanations are key

---

**This document should be uploaded to Claude.ai project knowledge to replace the outdated PROJECT-CONTEXT.md file.**

**Last verified accurate:** November 4, 2025, 2:00 PM PST
