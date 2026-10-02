# Bathurst Archive - Ready to Deploy

This zip is ready for Netlify Drop, Cloudflare Pages, or any static host.

## What's inside
- index.html  <- your full archive (renamed from v3_fixed)
- Programme covers/  <- put your 83 cover images here before uploading

## You also need to add (from your local project)
Copy these files from your local project into the SAME folder as index.html:

- data.js  (your lap data - required)
- race-results-data.js  (bundled race results for 1963-2025 and driver profiles - required)
- style.css  (your main styles - required)
- favicon.svg (optional)
- Cover COLLAGE.jpg (for social sharing, optional)
- lap-chart-research.png (for researching banner, optional)

Then the final structure should be:
/
  index.html
  data.js
  race-results-data.js
  style.css
  favicon.svg
  Programme covers/
    1960 front cover PI.jpeg
    ...
    1988 front cover.JPG  <- you just added
    2026 Front Cover.jpg

## Deploy in 30 seconds

### Netlify Drop (easiest)
1. Go to https://app.netlify.com/drop
2. Drag the ENTIRE folder (with data.js, style.css and Programme covers/) onto the page
3. You get https://bathurst-archive-xxxx.netlify.app instantly

### Cloudflare Pages (fastest in Australia)
1. Go to https://pages.cloudflare.com
2. Create project -> Upload assets -> Drag folder
3. Live in ~20 seconds

### GitHub + Auto-deploy (for live enhancements)
1. Create GitHub repo "bathurst-archive"
2. Upload this folder
3. Connect Netlify/Cloudflare to GitHub repo
4. Now every git push auto-updates live site

## Pro / Paid Tier (when ready)
The index.html already has wrappers ready:
- Driver Career Panel, Car Number History, Lead Change Stats are marked for Pro
- Add Memberstack or Ko-fi script to monetize

Questions: feedback@evansmotorsport.com.au
