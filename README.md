# Sedliak II for the browser

Static GitHub Pages build of Sedliak II running in the browser through [js-dos](https://js-dos.com/).

## Play locally

```bash
python3 -m http.server 8000 --directory public
```

Then open <http://localhost:8000/>.

## Deploy

This repo is configured for GitHub Pages with `.github/workflows/pages.yml`.

- No build step is required.
- Published files live in `public/`.
- `public/sedliak.html` is kept as a legacy alias for `public/index.html`.

Cloudflare Pages can also host the same folder if needed:

```bash
wrangler pages deploy public --project-name sedliak
```

## Project layout

```text
public/
  index.html                 Browser entry point
  sedliak.html               Legacy alias
  sedl2ak-live-fast.jsdos    DOS game bundle
  js-dos.js                  js-dos browser runtime
  js-dos.css                 js-dos styles
  js-dos.js.map              js-dos source map / source correspondence
  emulators/                 DOSBox/WebAssembly runtime files
  licenses/                  GPL license texts
  THIRD_PARTY_NOTICES.md     Notices served with the deployed site
```

## Licensing

This repository is an aggregate distribution of separately licensed components. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for details, exact component versions, checksums, and source links. The same notices are also included in `public/` so they are available from the deployed site.

The bundled Sedliak II game files are from the public `aific/sedl2ak` project and are licensed upstream under GPLv3. The bundled js-dos runtime/emulator assets are licensed upstream under GPLv2.

All components are provided without warranty.
