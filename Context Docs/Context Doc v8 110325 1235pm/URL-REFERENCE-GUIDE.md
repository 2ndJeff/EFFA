# EFFA Website - URL Reference Guide

**Version:** 2.2  
**Date:** November 3, 2025

---

## 🔗 Complete URL Map

### Navigation Links (Top Nav & Footer)

| Navigation Item | Destination URL |
|----------------|-----------------|
| **EFFA Logo** (nav & footer) | `https://www.effa.io/` |
| For Employers | `https://www.effa.io/` |
| For Universities | `https://www.effa.io/university` |
| About | `https://www.effa.io/about` |
| Job Ready Podcast | `https://www.effa.io/jobready` |
| Contact | `https://www.effa.io/contactus` |
| Blog | `https://www.effa.io/blog` |
| Log In | `https://www.effa.io/login` |
| Request Demo | `https://www.effa.io/contactus` |

---

## 🎯 CTA Buttons

### Across All Pages:
- **Request a Demo** → `https://www.effa.io/contactus`
- **Request Demo** (nav button) → `https://www.effa.io/contactus`
- **Partner with us** → `https://www.effa.io/contactus`
- **See How It Works** → `https://www.effa.io/contactus`

### Job Ready Page Specific:
- **Explore Job Ready** → `https://www.jobreadypodcast.com/`
- **Listen on Spotify** → `https://open.spotify.com/show/0Mm2SP7oievqq3hZc4O3Iw`
- **Listen on Apple Podcasts** → `https://podcasts.apple.com/us/podcast/job-ready/id1726097931`

---

## 📄 Page-Specific Link Counts

### Homepage (homepage-updated.html)
- Logo links: 2
- For Universities: 2
- About: 2
- Contact/Request Demo: 8
- Blog: 2
- Job Ready: 2
- Login: 2

### Job Ready (job-ready-updated.html)
- Logo links: 2
- For Universities: 2
- About: 2
- Contact/Request Demo: 4
- Blog: 2
- Job Ready: 2
- Login: 2
- External links: 3 (podcast site, Spotify, Apple)

### About (about-updated.html)
- Logo links: 2
- For Universities: 2
- About: 2
- Contact/Request Demo: 9
- Blog: 2
- Job Ready: 2
- Login: 2

### Universities (universities-updated.html)
- Logo links: 2
- For Universities: 2
- About: 2
- Contact/Request Demo: 8
- Blog: 2
- Job Ready: 2
- Login: 2

### Contact (contact-updated.html)
- Logo links: 2
- For Universities: 2
- About: 2
- Contact/Request Demo: 4
- Blog: 2
- Job Ready: 2
- Login: 2

---

## 🚨 Pages That Need to be Created

These URLs are referenced but don't exist yet on the live site:

1. **`https://www.effa.io/contactus`** ⚠️ **CRITICAL**
   - Referenced by: All "Request Demo" buttons and "Contact" nav links
   - Action: Create this page via GitHub before deployment

2. **`https://www.effa.io/university`**
   - Referenced by: "For Universities" nav links
   - Action: Create this page or redirect to appropriate page

3. **`https://www.effa.io/about`**
   - Referenced by: "About" nav links
   - Action: Deploy the about-updated.html to this URL

4. **`https://www.effa.io/blog`**
   - Referenced by: "Blog" nav links
   - Action: Create blog page or remove from nav if not ready

---

## ✅ URLs That Already Exist

These URLs should already be live:

- ✅ `https://www.effa.io/` (Homepage)
- ✅ `https://www.effa.io/login` (Login page)
- ✅ `https://www.effa.io/jobready` (Job Ready landing)
- ✅ `https://www.jobreadypodcast.com/` (External podcast site)
- ✅ Spotify and Apple Podcasts links (External)

---

## 🔄 URL Structure Notes

### Why Absolute URLs?
All links use absolute URLs (full `https://www.effa.io/...` paths) instead of relative paths (`about.html`) because:

1. **Works in both QA and Production**
   - On `qa.effa.io`: Links correctly point to production
   - On `www.effa.io`: Links work as expected

2. **Consistent Navigation**
   - No broken links due to directory structure
   - Clear destination for every link

3. **Future-Proof**
   - Easy to maintain
   - Works with any hosting setup

### How It Works in QA
When you deploy to `qa.effa.io`:
- Internal content (the HTML files) lives at `qa.effa.io/about.html`
- But links point to production: `https://www.effa.io/about`
- This is intentional - you can test QA content while links point to production

---

## 📋 Pre-Deployment Checklist

Before pushing to production:

### Must Create:
- [ ] `/contactus` page (referenced 30+ times across all pages)
- [ ] `/university` page (or redirect)
- [ ] `/about` page (deploy about-updated.html here)

### Should Verify:
- [ ] `/jobready` page exists and is correct
- [ ] `/login` page is accessible
- [ ] Homepage is at root `/`

### Optional:
- [ ] `/blog` page (or remove from navigation if not ready)

### External Links to Test:
- [ ] https://www.jobreadypodcast.com/ works
- [ ] Spotify link works
- [ ] Apple Podcasts link works

---

## 🛠️ Quick Reference for Claude Code

When working with Claude Code later, use this guide to:
1. Create missing pages (`/contactus`, `/university`, etc.)
2. Set up proper redirects if needed
3. Configure contact form backend for `/contactus`
4. Verify all URLs are accessible

---

## 📊 URL Statistics

- **Total unique production URLs:** 8
- **Total external URLs:** 4
- **Pages that need creation:** 3-4
- **Total link instances across all pages:** 100+

---

**Last Updated:** November 3, 2025  
**Version:** 2.2
