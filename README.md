# ahbi8358.github.io

Personal site of Ahmed H. Biby, built with Jekyll and hosted on GitHub Pages. GitHub builds it on every push; nothing to install.

## Edit the text
- Home: `index.md` · Research: `research.md` · Publications: `_data/publications.yml` (one entry per paper; DOI links render automatically) · Software and data: `software.md` · CV: `cv.md` and the PDF at `assets/cv/Ahmed_Biby_CV.pdf`.
- Name, email, photo path, link list and menu: `_data/profile.yml`.
- Styles: `assets/css/main.css`. Layout: `_layouts/default.html` and `_includes/`.

## Publish
Settings → Pages → Build and deployment → Source: "Deploy from a branch", branch `main`, folder `/ (root)`. The site appears at https://ahbi8358.github.io within a few minutes of the first push. Check the Actions tab if a page does not update.

## Preview on your computer (optional)
Needs Ruby. `bundle install` once, then `bundle exec jekyll serve` and open http://localhost:4000.
