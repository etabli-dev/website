# Établi website

Source of <https://etabli-dev.github.io/website/>: a static Hugo site with its
own templates and stylesheet and no theme module. The only script is the
cookie-free Plausible statistics snippet served from the maintainer's own
analytics server; there are no third-party requests.

## Build locally

Requires Hugo extended ≥ 0.146 (CI pins 0.169.0) and Python 3.

```sh
hugo server                                  # preview at http://localhost:1313/website/
hugo --gc --minify --panicOnWarning          # production build into public/
python3 tools/check_links.py public /website/
```

Pushes to `main` build, check internal links and deploy to GitHub Pages
(`.github/workflows/pages.yaml`). Pull requests build and check without
deploying.

## Layout

```
content/outils/       one page per public tool
content/bientot.md    the "coming soon" page; entries come from site-data/bientot.yaml
site-data/familles.yaml   the four tool families and their order
site-data/bientot.yaml     tools still in private repositories (name and summary only)
site-data/principes.yaml   short principles on the home page
layouts/              templates (home, section, page, outils/page, 404)
assets/css/main.css   the only stylesheet; light and dark follow the system
static/icons/         app tiles: the one-line family from etabli-dev/.github
                      (profile/icons, generator in icons/); Greffe, Indice,
                      Charpente and Secours drawn with the same generator
static/images/        mark, favicons and the social preview image
tools/check_links.py  internal link and anchor check for the built site
```

A tool's front matter sets `family`, `icon`, `repo`, `site`, `platforms`,
`stack`, `licence` and `release` (0 source only, 1 development build on GitHub
Releases, 2 store release). Keep it in step with the repository README and the
organisation profile.

When a private tool opens, remove it from `site-data/bientot.yaml` and add a page
under `content/outils/`. Only tools of the etabli-dev organisation belong here.

`content/impressum.md` and `content/datenschutz.md` hold the Impressum and
privacy notice.

## Licence

Proprietary, all rights reserved. See [LICENSE](LICENSE). Third-party
components keep their own licences. Versions published before 22 November 2026
remain available under their earlier licence (MIT).
