# HelpRush homepage redesign

A static homepage concept for HelpRush. Plain HTML, CSS and JavaScript, so there is nothing to install or build.

## Files

- `index.html` the whole page in one file: layout, styling (chinar leaf, paisley, khatamband pattern, sozni border, shikara on Dal Lake, samovar), the interactive booking card, search box, waitlist form and mobile menu
- `vercel.json` clean URLs and basic security headers

## Deploy on Vercel

Option 1, from the dashboard:
1. Put this folder in a GitHub repo.
2. On vercel.com, click Add New, then Project, and import the repo.
3. Framework preset: Other. Leave build command and output directory empty.
4. Click Deploy.

Option 2, from your terminal:
```
npm i -g vercel
cd helprush-site
vercel
```
Answer the prompts, then run `vercel --prod` for the live URL.

To preview locally, just double-click `index.html`. It works straight from your computer, no server needed.

## Before showing it publicly

- Replace `[DATE]` in the stats footnote.
- Replace the three review placeholders with real customer reviews.
- Swap the initials avatars for real pro photos.
- Confirm the 3.8 second median match figure.
- The waitlist form only shows a thank you message. Connect it to a backend or a form service (see the TODO near the end of `index.html`).
- Arrival times on the booking card are illustrative, and the card is labelled "Example booking".
