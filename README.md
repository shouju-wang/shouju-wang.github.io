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

Inspect the configured remote with:

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
- `images/publications/` — original paper-figure previews; `manifest.json` records source URLs, figure numbers, dimensions, and hashes
- `images/icons/` — locally served Noto party-popper emoji and its Apache 2.0 license, so acceptance celebrations display even without an installed emoji font
- `mpci-bench/` — MPCI-Bench project page, figures, benchmark examples, and result data
- `agentprivarena/` — AgentPrivArena project page, manuscript PDF, figures, and result data

Both project pages publish with this repository at `https://shouju-wang.github.io/mpci-bench/` and `https://shouju-wang.github.io/agentprivarena/`. Edit their `index.html`, `static/`, and `assets/` files here; no separate build is required. The original `voidreaming/mpci-bench` and `voidreaming/agentprivarena` repositories retain the old URLs as redirects and preserve existing direct asset links. Their Pages workflows must remain enabled for those links to work. The AgentPrivArena research implementation continues to live in `voidreaming/agentprivarena`; only its project website moved here.

Project-specific provenance and template licenses are recorded in each project directory's `README.md`, `THIRD_PARTY_NOTICES.md`, `LICENSE`, and `LICENSES/`. These licenses apply to the project templates and assets as specified, not to the rest of the personal homepage.

Keep paper links, author order, venues, dates, and current affiliation accurate before publishing. The `CV.pdf` in this repository predates the web CV; replace it only when a newly compiled PDF is ready.

The homepage and publication list use the same four figure previews. Each image preserves the original figure's full aspect ratio and links to its paper or project page. The compact profile and figure/text publication layout are inspired by [Yijia Xiao's homepage](https://yijia-xiao.com/); the site's code, portrait, text, and research figures remain this site's own. Profile markup is shared in appearance across the root pages and `blog/`; update those copies together when contact details change.
