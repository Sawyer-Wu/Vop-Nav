# Maintaining the project page

The website is a standalone static page in `docs/`. Open `docs/index.html` directly to preview it. No build or JavaScript dependencies are required.

- Update authors and affiliations in `docs/index.html`.
- Replace the disabled arXiv button with an `<a href="https://arxiv.org/abs/ACTUAL_ID">arXiv</a>` when available.
- When code is released, replace the disabled Code button with a link to its repository.
- Keep the abstract in `README.md` and `docs/index.html` synchronized.
- `docs/assets/framework.png` comes from `VOP-Nav/fig_sync/system_new.png` in the local research workspace.
- `docs/assets/realworld.mp4` comes from the real-world supplementary video. It is remuxed for progressive playback without re-encoding.
- Configure GitHub Pages to publish `main` / `docs` and update the README project URL to the actual repository name.

Only this directory is intended for publication. Research source files, peer reviews, checkpoints, and experiment logs are excluded.
