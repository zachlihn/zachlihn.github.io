# Zachary Lihn’s academic website

Public website: https://zachlihn.github.io/

An academic homepage for Zachary Lihn, a PhD student in mathematics at Princeton University. Hosted on GitHub Pages from the existing `master` branch.

## Updating the website

- Edit `index.html` to update the biography, publications, teaching, talks, and background.
- Edit `assets/css/academic.css` to change the layout or colors.
- Replace `images/profile.jpeg` to update the portrait.

Commit changes to `master`; GitHub Pages publishes them automatically. No local package installation or build step is required. To preview locally, run `python3 -m http.server 8000` from this directory and open `http://localhost:8000/`.

The website uses system fonts. MathJax is loaded from jsDelivr for mathematical notation; all navigation and content are otherwise usable without JavaScript. Content is based on the CV supplied in September 2026, with publication metadata checked against arXiv and publisher records.

The previous `/about/`, `/publications/`, `/teaching/`, `/talks/`, `/cv/`, and `/resume/` addresses forward to their new destinations. Legacy Academic Pages source files are retained but excluded from publication in `_config.yml`. Their original license remains in `LICENSE`.

The downloadable CV is intentionally not included. The former CV and résumé addresses now lead to the academic background section.
