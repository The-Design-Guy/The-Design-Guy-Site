# Royi Berkovitz · The Design Guy (live site)

Static site, no build step.

## Deploy
1. Push this folder to a GitHub repo (the files at the repo root).
2. In Vercel: New Project → import the repo → Framework preset: **Other** → no build command, output directory `.` → Deploy.

## Preview mode
Open `/viewer.html` (for example `your-project.vercel.app/viewer.html`) to see the site in Desktop / Tablet / Mobile frames, with editable sizes and full screen.

## Notes
- `index.html` is the whole site. `support.js` must stay next to it.
- Videos and audio load from Wix; local icons and images are in `icons/` and `images/`.
- Editing tools are switched off in this version. To edit, use the project file, then export again.
