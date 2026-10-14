[![Test](https://github.com/dhaliwal8681/triasphere/actions/workflows/test.yml/badge.svg)](https://github.com/dhaliwal8681/triasphere/actions/workflows/test.yml)
[![Deploy to GitHub Pages](https://github.com/dhaliwal8681/triasphere/actions/workflows/deployment.yml/badge.svg)](https://github.com/dhaliwal8681/triasphere/actions/workflows/deployment.yml)

## Penmanship Practice Sheets

Create custom, printable penmanship and calligraphy practice sheets. Design your
own or use standard layouts for Copperplate, Spencerian, and more.

### Attribution

This is a copy of [kylev/pen](https://github.com/kylev/pen) by Kyle VanderBeek,
originally hosted at [kylev.github.io/pen](https://kylev.github.io/pen/). The
upstream repository does not include an open-source license, so all rights to
the original work remain with its author. Changes made in this copy:

- `vite.config.js` / `package.json`: base path and homepage point at this repository.
- `index.html`: upstream Google Analytics tag removed; Open Graph URLs updated.

### Development

Requires Node.js (see `.node-version`).

```sh
npm ci          # install dependencies from the lockfile
npm run dev     # start the Vite dev server
npm test        # run the Vitest suite
npm run build   # production build to dist/
```

### Deployment

`.github/workflows/deployment.yml` builds and publishes `dist/` to GitHub Pages on
every push to `main`. For it to work, enable Pages for this repository with the
source set to **GitHub Actions** (Settings → Pages).

### Bugs

Report bugs and ask questions with [here](https://github.com/dhaliwal8681/triasphere/issues).
