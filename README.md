# Sailsfly · Hà Giang

The full Sailsfly website: index.html (Home) plus Trips, Motorbikes, Transportation, Info, the Hà Giang Loop page and all Info articles.

## Replacing the live site on GitHub

1. Open the repo on github.com.
2. Delete the old files from the previous version (keep CNAME and .nojekyll): index.html, ha-giang-loop.html, support.js, styles.css, _ds_bundle.js, ri-ri.png, favicon.svg, README.md.
3. Click Add file > Upload files and drag in everything from this folder at once, including the assets folder.
4. Click Commit changes.

GitHub Pages republishes within a minute or two. Hard-refresh (Ctrl+Shift+R / Cmd+Shift+R) to see the new version.

## Plan a trip form

Submissions are sent to the Make webhook (hook.us2.make.com/vihdcb1puudu7nwj5zf9gnl2gv2d8e7t) with these fields:
name, whatsapp, email, travel_date, travellers, inquiring_about, choice, from, to, interests, notes, summary, page, submitted_at.
`summary` is the whole enquiry as one ready-to-send message.

## Still to do

- The booking forms on the Transportation, Trips and Motorbikes pages only show a confirmation message; only the Home page form is connected to Make.
- Tour names, trip lengths and the food list are placeholders to confirm.
