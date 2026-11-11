# Iqra Maqsood — Portfolio

Static one-page portfolio. No build step.

## Files
- `index.html` — the whole site (styles, content and script in one file)
- `cv.pdf` — downloadable CV (replace this file to update it)
- `netlify.toml` — Netlify settings

## Edit content
Open `index.html` and find the `CONTENT` block near the bottom.
Each project has a title, description, role, approach and a `videos` list:
- YouTube: `{t:"Label", yt:"VIDEO_ID"}` (the part after `v=` or `youtu.be/`)
- Google Drive: `{t:"Label", drive:"FILE_ID"}` (the part after `/file/d/`).
  The Drive file must be shared as "Anyone with the link can view".

## Deploy (GitHub + Netlify)
1. Create a GitHub repository and upload these files to it.
2. In Netlify: Add new site → Import an existing project → GitHub → pick the repo.
3. Leave the build command empty and set the publish directory to `.` (netlify.toml already does this).
4. Deploy. Every push to GitHub redeploys the site.
