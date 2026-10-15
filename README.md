# Hà Giang Loop with Ri Ri

A one-page site for Ri Ri's Hà Giang Loop motorbike tours.

## Publish on GitHub Pages

1. Create a new **public** repository on github.com (for example `ha-giang-loop`). Leave "Add a README" unticked.
2. On the new repo page, click **uploading an existing file**.
3. Select **all the files in this folder** and drag them in together (index.html, support.js, styles.css, _ds_bundle.js, ri-ri.png, favicon.svg, .nojekyll, README.md). There are no subfolders, so they all sit side by side.
   - .nojekyll is a hidden file. On a Mac press Cmd+Shift+. in Finder to see it; on Windows turn on "Hidden items" in File Explorer.
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
6. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/ha-giang-loop/`. The link appears at the top of the Pages settings.

To update the site later, upload the changed file again to the same repo; Pages republishes automatically.

## Custom domain (optional)

Settings → Pages → Custom domain, enter the domain, then add the DNS records GitHub shows you at your domain registrar. Tick **Enforce HTTPS** once it's available.

## What loads from the internet

The site needs a connection for: React (unpkg.com), the Inter font (Google Fonts), the hero video clips (Pixabay), scenery photos (Wikimedia Commons) and the TikTok embed. Ri Ri's photo, the favicon and all styling are in this folder.

## Things to finish before sharing

- **Enquiry form** only shows a thank-you message; it doesn't send anything yet. A free service like Formspree can make it email you: create a form there, then set the form's `action` to your Formspree URL and `method="POST"`.
- **Follower and like counts** are typed in by hand; update them in index.html when they change.
- **Tour details** (names, prices, dates) are placeholders.
