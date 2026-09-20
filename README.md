# shouju-wang.github.io

Source for Shouju Wang’s academic homepage at [shouju-wang.github.io](https://shouju-wang.github.io/). It is a lightweight static site with no build step or framework.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The repository is owned by the `shouju-wang` GitHub organization and is configured in **Settings → Pages** to deploy from the `master` branch at `/(root)`. Pushes to `master` publish automatically.

The configured remote uses SSH:

```bash
git remote -v
```

## Content maintenance

- `index.html` — homepage, news, research interests, selected publications, and recent experience
- `publications.html` — complete selected-publications list
- `cv.html` — web CV
- `research-statement.html` — research narrative
- `blog/` — optional writing archive
- `css/style.css` — shared academic-site layout and typography

Keep paper links, author order, venues, dates, and current affiliation accurate before publishing. The `CV.pdf` in this repository predates the web CV; replace it only when a newly compiled PDF is ready.
