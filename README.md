# Muhammad Usman Amin Siddiqi — Academic website

Quarto academic website for:

https://usman-a-siddiqi.github.io

## Site structure

- `index.qmd` — homepage, research focus, recognition and selected work
- `research.qmd` — research themes, projects, current research and methods
- `publications.qmd` — publication record with paper summaries and journal/PDF links
- `teaching.qmd` — teaching, mentoring and selected academic service
- `talks.qmd` — invited talks, panels and selected presentations
- `cv.qmd` — concise web CV
- `files/Muhammad-Usman-Amin-Siddiqi-CV.pdf` — downloadable full academic CV
- `styles.css` — visual design
- `_quarto.yml` — navigation, metadata and site settings
- `.github/workflows/publish.yml` — GitHub Pages deployment

## Publication cards

Recent publication cards use three possible actions:

- **About the paper** — expands a short plain-language overview in the card.
- **Read article** — opens the journal article page.
- **Author PDF / PDF** — shown when a separate manuscript or PDF route is useful.

When adding a new publication, copy a current card and update the title, citation, summary and links.

## Updating the CV

Replace `files/Muhammad-Usman-Amin-Siddiqi-CV.pdf` with the newest PDF while keeping the same filename. The website links will continue to work automatically.

## Publishing

1. Review wording, dates, links and works in progress.
2. Commit the files to the `main` branch of `usman-a-siddiqi/usman-a-siddiqi.github.io`.
3. In GitHub, set **Settings → Pages → Source → GitHub Actions** if not already configured.
4. The included workflow builds and deploys the Quarto site.
