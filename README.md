# Muhammad Usman Amin Siddiqi — Academic website

A Quarto academic website prepared for deployment at:

https://usman-a-siddiqi.github.io

## Site structure

- `index.qmd` — homepage
- `research.qmd` — research themes and current work
- `publications.qmd` — publication record
- `teaching.qmd` — teaching, service and presentations
- `cv.qmd` — web CV
- `styles.css` — visual design
- `_quarto.yml` — navigation and site settings
- `.github/workflows/publish.yml` — automatic GitHub Pages deployment

## Before publishing

1. Add a professional headshot if you want one. Put it at `assets/profile.jpg` and replace the monogram block in `index.qmd` with an image.
2. Review wording, dates and publication details, especially works in progress.
3. If you have a PDF CV, place it at `files/Muhammad-Usman-Amin-Siddiqi-CV.pdf`.
4. Commit all files to the `main` branch of `usman-a-siddiqi/usman-a-siddiqi.github.io`.
5. In GitHub: **Settings → Pages → Source → GitHub Actions**.
6. The included workflow will build the Quarto site automatically.

## Editing later

Most updates only require editing the `.qmd` files. For example, to add a publication, copy one publication card in `publications.qmd`, change the text and DOI, save, commit and push.

## Optional PDF CV button

After adding the PDF, you can add this line to the homepage or CV page:

```html
<a class="btn-academic" href="files/Muhammad-Usman-Amin-Siddiqi-CV.pdf">Download CV</a>
```
