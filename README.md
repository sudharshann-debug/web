# Kalam Tuition Centre — website

A 4-page static site: Home, Gallery, Founder, Visit Us (with maps).
No build step — plain HTML/CSS/JS, ready for GitHub Pages.

## Before you publish

1. **Photos** — `gallery.html` currently uses colour placeholders in
   `assets/images/placeholder-1.svg` … `placeholder-9.svg`. Replace the
   `src` on each `<img>` with your real photos (see the comment above the
   grid in `gallery.html`).
2. **Founder** — open `founder.html` and replace `[Founder Name]`, the bio
   and quote with the real details. Swap the initials circle for a real photo
   if you'd like (the comment in the file shows how).
3. **Addresses, phone, hours** — open `contact.html` and replace every
   `[...]` placeholder with the real address, phone number and hours for
   each branch. Also update the two map links: each one is
   `https://www.google.com/maps?q=YOUR+ADDRESS&output=embed` — just swap
   in the exact address for a pin at the right spot.
4. **Email / phone on the contact button** — same file, update the
   `mailto:` and `tel:` links near the bottom.

## Publish to GitHub Pages

1. Create a new repository on GitHub (e.g. `kalam-tuition-centre`).
2. Push this folder's contents to the repo root:
   ```
   git init
   git add .
   git commit -m "Kalam Tuition Centre website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source** → set to
   `Deploy from a branch`, branch `main`, folder `/ (root)` → Save.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/`
   within a minute or two.

## Structure

```
index.html      Home
gallery.html    Gallery
founder.html    Founder
contact.html    Visit Us (branches + maps)
assets/style.css
assets/script.js
assets/images/  placeholder photos — replace with real ones
```
