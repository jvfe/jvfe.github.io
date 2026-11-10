# joao.bio.br

Minimal personal website for [joao.bio.br](https://joao.bio.br), built with Markdown, `pandoc`, and `make` (following [Stephen D. Turner's minimal personal website template](https://github.com/markdownhomepage/markdownhomepage.github.io)).

## Usage

Requires [`pandoc`](https://pandoc.org/) and `make`:

```sh
make          # build HTML pages and sitemap.xml
make preview  # build and open index.html
make clean    # remove generated HTML files and sitemap.xml
```

## Structure

- `site.yaml` — site-wide metadata (`url`, `site-name`, OpenGraph/JSON-LD `person` info)
- `index.md` — homepage content and navigation link buttons
- `p/*.md` — subpages (`/p/work`, `/p/projects`)
- `template.html` — shared Pandoc HTML5 template
- `style.css` — responsive light/dark CSS stylesheet
- `files/` — static assets (`files/headshot.png`)
- `CNAME` / `.nojekyll` — GitHub Pages custom domain (`joao.bio.br`) and static file serving
