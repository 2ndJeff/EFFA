# TROUBLESHOOTING: Images Not Loading

If images aren't showing when you open index.html, here's how to fix it:

## Most Common Issue: File Location

**Problem:** You moved `index.html` out of the `homepage-package` folder.

**Solution:** 
1. Make sure `index.html` stays INSIDE the `homepage-package` folder
2. The `images` folder must be in the SAME folder as `index.html`

**Correct structure after unzipping:**
```
homepage-package/
  ├── index.html          ← Open THIS file
  ├── README.md
  └── images/
      ├── steps/
      │   ├── step1-quick-setup.png
      │   ├── step2-employee-enrollment.png
      │   ├── step3-automated-compliance.png
      │   └── step4-simple-billing.png
      ├── backgrounds/
      │   └── diverse-professionals.jpg
      └── logos/
          ├── effa-logo.png
          └── effa-logo-white.png
```

## How to Open Correctly

### On Mac:
1. Unzip `homepage-complete-v2.zip`
2. Navigate INTO the `homepage-package` folder
3. Right-click `index.html` → Open With → Browser

### On Windows:
1. Unzip `homepage-complete-v2.zip`
2. Navigate INTO the `homepage-package` folder
3. Right-click `index.html` → Open with → Your browser

### On Linux:
1. Unzip the file
2. Navigate INTO the `homepage-package` folder
3. Open `index.html` with your browser

## What You Should See

When opened correctly:
- ✅ EFFA logo in navigation
- ✅ Orange hero section
- ✅ 4 step screenshots aligned at bottom in "How It Works"
- ✅ Subtle professional background in "Proven Results" section
- ✅ EFFA logo in footer

## If Images Still Don't Load

Check your browser console (F12 or right-click → Inspect → Console tab) for error messages. They'll tell you exactly which files can't be found and why.

Common console errors and fixes:

**Error:** "Failed to load resource: images/steps/step1-quick-setup.png"
**Fix:** Make sure the `images` folder is in the same location as `index.html`

**Error:** "Not allowed to load local resource"
**Fix:** Some browsers block local file access. Try:
- Chrome: Open with "Allow file access" 
- Firefox: Usually works fine
- Safari: Usually works fine
- Or upload to a web server (even localhost)

## Quick Test

If you're still having issues, try this:
1. Open `index.html` in a text editor
2. Search for: `images/steps/step1-quick-setup.png`
3. Make sure that file exists in that exact path relative to index.html

## Need Help?

If images still won't load after following these steps, let me know:
1. What browser you're using
2. What error messages you see in the console (F12)
3. Whether the files are in the correct structure

I can create an alternative version with different image paths if needed!
