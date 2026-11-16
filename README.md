# Fadli Aulawi Al Ghiffari

Academic profile using [Minimal Light](https://github.com/yaoyao-liu/minimal-light), with the theme's layouts, styles, and license included locally. No remote theme or JavaScript build is required.

## Edit

- `index.md`: biography, research, projects, experience, education, and honors.
- `_config.yml`: name, affiliation, contact links, and theme settings.
- `assets/img/profile.jpg`: profile photo.
- `assets/files/cv.pdf`: downloadable CV (copied from the October 2026 CV).

Content was adapted from `../cv.tex` and the sections it includes. BioDyad is labeled as an ICLR 2027 submission, not an accepted publication. Unused example sections from the original CV template are excluded.

## Preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`. For a production check, run `bundle exec jekyll build`.

## GitHub Pages

Push this repository to GitHub. In **Settings → Pages**, select **Deploy from a branch**, the intended branch, and **/(root)**. GitHub Pages builds the Jekyll site. The intended URL is https://fadliaulawi.github.io/.

The upstream Minimal Light MIT license is retained in `LICENSE`.
