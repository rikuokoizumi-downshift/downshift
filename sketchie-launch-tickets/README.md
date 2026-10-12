# Sketchie Launch Tickets

One-page view of the Sketchie launch plan: 2 epics (L1 Launch Prep, L2 Launch Week) and 25 tickets, each with one owner, one due date and one "done when" line. Launch is Monday, October 19, 2026.

The whole site is `index.html`. It has no build step and no dependencies apart from Google Fonts.

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `sketchie-launch-tickets`.
2. Upload `index.html`, `.nojekyll` and this `README.md` to the root of the repository (Add file > Upload files > Commit changes).
3. Open Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main`, folder `/ (root)`, then Save.
5. Wait about a minute. The site appears at `https://<your-username>.github.io/sketchie-launch-tickets/`.

## Updating it

Replace `index.html` with a new version and commit. Pages redeploys on its own within a minute or two.

## Before you share the link

A GitHub Pages site is public to anyone who has the URL, even if the repository is private (unless your organization is on GitHub Enterprise Cloud with private Pages). The page includes internal owners, dates and launch decisions. The `noindex` tag keeps search engines from listing it, but it does not hide it.
