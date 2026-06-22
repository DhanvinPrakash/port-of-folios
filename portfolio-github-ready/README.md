# Portfolio GitHub Asset Notes

This folder is ready to commit to a GitHub Pages repository:

- `index.html` is the updated portfolio.
- `assets/` contains the extracted images and texture that used to be embedded as data URLs.
- The HTML uses relative paths like `assets/moveability-home.jpg`, which work locally and on GitHub Pages.

If you prefer raw GitHub URLs instead of relative paths, upload the `assets/` folder and replace each `assets/...` reference with:

`https://raw.githubusercontent.com/<your-github-username>/<repo-name>/main/assets/<filename>`

The LinkedIn card currently uses a search URL because the exported HTML did not include a verified profile URL.
