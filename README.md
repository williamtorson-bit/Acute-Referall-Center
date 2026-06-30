# Acute Referral Centre App - Vercel Ready

This folder is ready to upload to GitHub and deploy on Vercel.

Important file layout:

- index.html
- manifest.json
- arc-logo.svg
- service-worker.js
- vercel.json

Do not place these files inside a subfolder unless you set that subfolder as the Vercel Root Directory.

Recommended Vercel settings:

- Framework Preset: Other
- Build Command: leave blank
- Output Directory: leave blank or use .
- Install Command: leave blank

If Vercel shows 404 NOT_FOUND, check that index.html is at the repository root, or set Root Directory to the folder that contains index.html.
