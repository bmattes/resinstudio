# ResinStudio GitHub Pages Site

This folder contains the support website for ResinStudio, ready to deploy to GitHub Pages.

## Setup Instructions

1. **Copy files to your repo:**
   ```bash
   cd /path/to/resinstudio
   cp /Users/bmattes/Documents/Resin8/ResinStudioApp/github-pages/* .
   git add .
   git commit -m "Add support site"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to https://github.com/bmattes/resinstudio/settings/pages
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save
   - GitHub will deploy your site to: `https://bmattes.github.io/resinstudio`

3. **Verify deployment:**
   - Wait 1-2 minutes for GitHub to build
   - Visit: `https://bmattes.github.io/resinstudio`
   - Check all pages load correctly

## URLs for App Store Connect

Once deployed, use these URLs:

- **Support URL:** `https://bmattes.github.io/resinstudio/support.html`
- **Privacy Policy URL:** `https://bmattes.github.io/resinstudio/privacy.html`
- **Marketing URL:** `https://bmattes.github.io/resinstudio`

## Files Included

- `index.html` - Landing page
- `support.html` - Support & FAQ page
- `privacy.html` - Privacy policy (GDPR/CCPA compliant)

## Updating Content

To update any page:
1. Edit the HTML file locally
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update support page"
   git push origin main
   ```
3. Changes will be live in 1-2 minutes

## Before App Store Submission

**Update the App Store link in `index.html`:**
- Line with: `https://apps.apple.com/app/resinstudio/idXXXXXXXXXX`
- Replace `idXXXXXXXXXX` with your actual App Store ID after approval

**Update contact email (if needed):**
- Currently set to: `support@resinstudio.app`
- If using a different email, find/replace in all files
