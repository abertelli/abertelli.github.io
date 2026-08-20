# Tony Bertelli Quarto starter site

This is a starter Quarto site generated from the WordPress export dated 2026-07-15.

## Design decisions

- No personal photograph.
- The homepage links to the current PDF CV, while a separate Publications page preserves publication links.
- The narrative bio is retained and lightly updated for current positions.
- The old WordPress blog structure is not used in the main navigation.
- An archive page exists in the footer to preserve older research announcements.

## Local preview

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in Positron.
3. In the terminal, run:

```bash
quarto preview
```

4. Edit `.qmd` files and `styles.css`.

## Main files

- `_quarto.yml`: site configuration and navigation
- `index.qmd`: homepage
- `bio.qmd`: narrative biography
- `publications.qmd`: linked books, articles, invited essays, and book reviews
- `books.qmd`: book page
- `research.qmd`: research themes
- `projects.qmd`: current projects
- `archive.qmd`: imported WordPress research announcements, linked only from the footer
- `styles.css`: visual design

## Publishing later

The likely free path is GitHub Pages. Once the site is ready, create a GitHub repository and use Quarto's GitHub Pages publishing workflow. Do not point `tonybertelli.com` at the new host until the preview site is checked.
