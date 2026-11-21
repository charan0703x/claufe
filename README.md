# CLAUFE — Pre-Launch Website

Minimal black-and-white scribbled pre-launch landing page for **CLAUFE**.

## Files
- `index.html` — Self-contained landing page
- `apps-script/Code.gs` — Google Apps Script webhook for your **CLAUFE Waitlist** Google Sheet

## Connect Your Google Sheet
1. Open your **CLAUFE Waitlist** Google Sheet.
2. Go to **Extensions → Apps Script** and paste the contents of `apps-script/Code.gs`.
3. Click **Deploy → New deployment → Web app**, set **Who has access** to **Anyone**, and copy the Web App URL.
4. Paste that URL into `GOOGLE_SCRIPT_URL` inside `index.html`.

## Deploy
Push this folder to a Git repository and deploy directly on GitHub Pages, Netlify, or Vercel.
