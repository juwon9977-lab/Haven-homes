# Haven Homes

A static property website. No install or build step.

## Run it in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Double-click `index.html` to open it in your browser, or install the "Live Server" extension and choose "Open with Live Server".

Keep `index.html` and the `images` folder together in the same folder.

## Before going live
- Open `index.html`, find `FORM_ENDPOINT` near the top of the script, and set it to your form service URL (for example from Formspree). Until you do, inquiries are not delivered.
- Replace the listings, agents, addresses and phone numbers, which are placeholders.
- Replace the photos in `images/` with your own, or change the photo lists in the `PHOTOS` object.
- Confirm you have permission to use the photos.

## Deploy
Push this folder to GitHub, then import the repository in Vercel. No build settings are needed.
