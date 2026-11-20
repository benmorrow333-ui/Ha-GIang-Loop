# Sailsfly · Hà Giang

The full Sailsfly website. index.html is the Home page; every other page, photo and video sits next to it in this one folder (no subfolders).

## Replacing the live site on GitHub

1. Open the repo on github.com.
2. Delete all of the old site files. Keep CNAME and .nojekyll if you have them.
3. Click Add file > Upload files and drag in every file from this folder at once.
4. Click Commit changes.

GitHub Pages republishes within a minute or two. Hard-refresh (Ctrl+Shift+R / Cmd+Shift+R) to see the new version.

## Forms

The Plan a Trip form and the enquiry form at the bottom of the Hà Giang Loop page send to the Make webhook
(hook.us2.make.com/vihdcb1puudu7nwj5zf9gnl2gv2d8e7t). `summary` holds the whole enquiry as one message.
