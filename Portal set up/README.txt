Incora Customer Parts Portal - FINAL Netlify Upload Folder
=========================================================

Files:
- index.html       : Main portal page (improved UI, login, search, reserve)
- parts_data.csv   : Data source (must stay in the same folder)
- incora-logo.png  : Logo used in the header (already included if present)

How to deploy on Netlify (Drop):
1. Do NOT upload files one by one.
2. Instead, unzip this package and drag the *entire folder* "incora_portal_final"
   into https://app.netlify.com/drop

3. Netlify will give you a site URL, e.g.:
   https://your-site-name.netlify.app/

4. Your portal will be available directly at that URL
   (because the main file is named index.html).

To update prices/stock:
- Edit parts_data.csv locally (with Excel, etc.)
- Reupload the entire folder via Netlify Drop.
