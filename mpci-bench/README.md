# MPCI-Bench project page

Published at https://shouju-wang.github.io/mpci-bench/ as part of the personal homepage repository. Edit this directory; pushes to `master` publish it automatically.

- `index.html`: narrative, results, authors, resource links, citation, and More Research navigation.
- `static/css/mpci.css`: responsive layout and spacing. `index.css` and `bulma.min.css` preserve the upstream template.
- `static/js/`: figure viewer, citation copying, navigation, and example tabs.
- `static/data/examples.json`: benchmark excerpts, editorial annotations, and provenance. If changed, also synchronize the embedded `example-data` JSON in `index.html`.
- `assets/`: paper figures, plotted results, and original example photographs. Photograph credits and hashes are in `assets/examples/attributions.json`.

The benchmark implementation remains at https://github.com/hpzhang94/MPCI-Bench and its dataset at https://huggingface.co/datasets/Soojuu/mpci-bench. The older website repository retains figure-generation data and scripts at https://github.com/voidreaming/mpci-bench/tree/main/scripts and redirects its published page here.

Content follows arXiv:2601.08235v3. Results reproduce Tables 4 and 5. NeurIPS 2026 Evaluations & Datasets Track acceptance was supplied by the author; no proceedings citation has been invented. Original benchmark excerpts and photo attribution are preserved. See `THIRD_PARTY_NOTICES.md`, `LICENSE`, and `LICENSES/` for source credits and licensing.
