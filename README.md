# shouju-wang.github.io

Source for Shouju Wang’s academic homepage. It is a lightweight static site—no build step or framework required.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish at `shouju-wang.github.io`

The current repository is owned by `voidreaming`, so GitHub treats it as a *project* site and publishes it at:

```text
https://voidreaming.github.io/shouju-wang.github.io/
```

For the clean root address `https://shouju-wang.github.io/`, GitHub Pages requires both of the following:

1. The repository owner must be `shouju-wang`.
2. The repository name must be `shouju-wang.github.io`.

The recommended path is to rename the GitHub account from `voidreaming` to `shouju-wang`. This repository already has the required name, so its contents do not need to move. If the existing username must remain, create a `shouju-wang` GitHub organization and transfer this repository to it instead.

After the owner changes:

1. In the repository’s **Settings → Pages**, select **Deploy from a branch**, `master`, and `/(root)`; save if necessary.
2. Confirm the new site at `https://shouju-wang.github.io/`.
3. Update the local remote to avoid relying on GitHub’s redirect:

   ```bash
   git remote set-url origin https://github.com/shouju-wang/shouju-wang.github.io.git
   ```

4. Update any external profile links that still point to the old project URL. Do not rely on the old Pages URL redirecting to the new domain.

The site intentionally uses relative paths for local assets, so moving from the old project path to the root domain needs no base-path edits. `.nojekyll` remains in place so GitHub serves the static files as-is.

## Content maintenance

- Edit `index.html` for the homepage, publications, news, and experience.
- Edit `research-statement.html` for the longer research narrative.
- Add posts under `blog/` and link them from `blog/index.html`.
- Keep paper links, author lists, and dates current before publishing.

See GitHub’s [Pages overview](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and [publishing-source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) for the account-side setup.
