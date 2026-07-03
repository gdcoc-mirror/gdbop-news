# gdbop-news — news content for the GDBOP website

This repo holds ONLY the news content edited through Pages CMS.
Editors have access here; they never touch the website code repo (gdbop-mirror).

- `content/news/*.json` — one file per news item (managed by Pages CMS).
- `images/` — news images (uploaded by editors via Pages CMS).
- `.pages.yml` — Pages CMS configuration (defines the editor form).

The website (gdbop-mirror) automatically pulls from this repo and rebuilds
every few minutes, so published news appears on the live site shortly after saving.

Do not add GitHub Actions/workflows or secrets to this repo.
