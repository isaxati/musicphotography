# Isabel Mwiraria — Photography Portfolio

A simple one-page site: your name, a hero photo, a "Book a Shoot"
button, links to Instagram/email, and a scrolling photo gallery below.

## 1. Swap in your real photos

Unzip `photos.zip` (or use the `photos` folder you already have).
Rename your own photos to match these exact filenames, then drop them
into the `photos` folder, replacing the placeholders:

- `hero.jpg` — your single best/strongest shot (used as the big
  background image behind your name)
- `photo-01.jpg` through `photo-06.jpg` — your gallery images

Filenames must match exactly (all lowercase, `.jpg` ending) or the
site won't find them. If your photos are `.jpeg` or `.png`, rename
the ending to `.jpg` too.

## 2. Double check your info

Open `index.html` in any text editor and confirm these are correct
(they should already say):
- Name: Isabel Mwiraria
- Instagram: @Isaxati
- Email: still needs to be filled in — search for `you@example.com`
  (it appears 3 times) and replace with your real email address

## 3. Put it on GitHub Pages (free hosting)

1. Create a GitHub account if you don't have one: github.com
2. Click the "+" icon (top right) → New repository
3. Name it exactly `yourusername.github.io`, replacing
   "yourusername" with your actual GitHub username. Set it to Public.
4. Click "Create repository"
5. On the new repo page, click "uploading an existing file"
   (or Add file → Upload files)
6. Drag in `index.html`, this `README.md`, and the whole `photos`
   folder (with your real images inside)
7. Scroll down, click "Commit changes"
8. Go to the repo's Settings tab → Pages (left sidebar)
9. Under "Source," choose branch "main," folder "/ (root)" → Save
10. Wait 1-2 minutes, then visit https://yourusername.github.io —
    your site is live

## 4. Updating later

To swap or add photos:
- Go into the `photos` folder inside your GitHub repo
- Click "Add file" → "Upload files" to replace or add images
- If adding a NEW photo (not just replacing one), also open
  `index.html` in the repo, find the `<div class="gallery">` section,
  and add a new line like:
  `<figure><img src="photos/photo-07.jpg" alt="Concert photo 7"></figure>`
- Commit the changes — the live site updates automatically within
  about a minute
