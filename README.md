# GAO Tianhong (高天鸿) — personal website

Source for the planned website at `https://guesss2022.github.io/`, based on the [Minimal Light Academic](https://github.com/harryrichman/minimal-light-academic) template. The template's CC0 license is retained in `LICENSE`.

## Edit content

- `index.md`: biography, interests, news, experience, education, and honors.
- `_data/publications.yml`: publication entries and links.
- `_config.yml`: site identity and contact links.
- `assets/img/portrait-original.jpg`: original, unretouched profile photo; the visible portrait crop is controlled by `assets/css/style.scss`.
- `assets/img/favicon-cropped.png`: tightly cropped monogram from the supplied artwork.
- `assets/img/favicon-square.png`: square browser tab icon made by adding white padding above and below the cropped monogram, without stretching it.

The public site intentionally excludes work under anonymous review and does not host the current PDF résumé. Revisit both after the review period.

## Local preview

Install the dependencies listed in `Gemfile`, then run `bundle exec jekyll serve` and open `http://localhost:4000`.

## Publish

Create a GitHub repository named `guesss2022.github.io` under the `guesss2022` account, push this source, and enable GitHub Pages. Do not add a link to the résumé until the site is live and checked.
