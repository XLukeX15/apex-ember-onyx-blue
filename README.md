# El Paso West Side Map (79912)

27 addresses in 6 color-coded proximity groups. Stars mark the 3 Lakehurst Rd stops added later.

## Live site

This repo is a static site. Two ways to publish:

### Vercel (same as your other Grok sites)
1. Open https://vercel.com/new
2. Import `XLukeX15/apex-ember-onyx-blue`
3. Deploy. Framework preset: Other. Output: leave blank.

### GitHub Pages
1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder: `/ (root)`
4. Save. Site will be at `https://xlukex15.github.io/apex-ember-onyx-blue/`

## Why the Grok Build export failed
- **Workspace unavailable** — Grok Build could not read the project files when you hit Push. The empty repo was created, then the upload aborted.
- **API KEY REQUIRED** on the map — the Build preview used Carto tiles that now require a key. This page uses OpenStreetMap + Esri streets instead, so it works with no key.
