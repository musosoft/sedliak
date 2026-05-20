# Third-party notices

This repository hosts a static browser build made from separately licensed components.

When these files are viewed on the deployed site, repository paths under `public/` are served from the site root.

## Sedliak II / sedl2ak

- Files: `public/sedl2ak-live-fast.jsdos`
- License: GNU General Public License v3.0
- License text: `public/licenses/GPL-3.0-only.txt`
- Upstream source: <https://github.com/aific/sedl2ak>
- Upstream HEAD observed for this release: `19d5d338fe892b94221eeb4c03612dc2cf8c00aa`
- Bundle SHA-256: `0a626b3732679549ac99aaaba12a12a1b8dd4eb77ba480ac0a5f4807b1e1e287`

The `.jsdos` file is a ZIP-format js-dos bundle containing the Sedliak II DOS files needed by the browser runtime.

## js-dos

- Files: `public/js-dos.js`, `public/js-dos.css`, `public/js-dos.js.map`
- License: GNU General Public License v2.0
- License text: `public/licenses/GPL-2.0-only.txt`
- Version/source package: `js-dos@8.3.20` from npm
- npm integrity: `sha512-VkuO9QNy5DnfsBwUuKquWmDBLJNqrk6ZK7aYTrKAMiJRuC5fofVI2n+Y7sed0PJ8mozl5OOAD2xXltZtXM57ug==`
- Upstream release tag observed: `v8.3.20` at `1263c31f0c4d1b3ed83cbb24b586c3d2e52a7228`
- Upstream project: <https://github.com/caiiiycuk/js-dos>
- Documentation: <https://js-dos.com/>
- Runtime asset SHA-256 values:
  - `public/js-dos.js`: `d6316862834616fb120e21616b88bab6b09c1f1a4dd6eaf2b6efa83b346cfa64`
  - `public/js-dos.css`: `fe68ac9154aff78ec3904cacaa6d680003cc7f112debb3f0157ed4b534f91023`
  - `public/js-dos.js.map`: `ac7056f8f4e2ba97bbb26f7d7b4aa653d93c6bd4e4360a2f0a247e48be64a1ac`

## js-dos emulators

- Files: `public/emulators/*`
- License: GNU General Public License v2.0
- License text: `public/licenses/GPL-2.0-only.txt`
- Version/source package: `emulators@8.3.8` from npm, bundled with `js-dos@8.3.20`
- npm integrity: `sha512-bRB4brpzXorsvWQYqGClDEERSJeM9c05OLjEkMu8+HjsvGbe+gOBrKKjyqvbhWl/75djz5nXJOXKJYaJR4t7Wg==`
- Upstream release tag observed: `v8.3.8` at `387f7275010d529c408d9afe684584e6e18bd8c7`
- Upstream project: <https://github.com/js-dos/emulators>
- Runtime asset SHA-256 values:
  - `public/emulators/emulators.js`: `9637c08567c44c4ab1de982008a0710180f5e3ab84b05745fad3fcec945e97c8`
  - `public/emulators/emulators.js.map`: `23eb4bea83f500d7747780f1fff2aa0283f2dfd36c2a98394f34959914540c4e`
  - `public/emulators/wdosbox.js`: `d727efe319d99ceebf4cc8f4e6b392ed0bbb687e4e1878e1261d2f04d9e7b0ba`
  - `public/emulators/wdosbox.wasm`: `6c3e68a2669cbde5a2b9c920e64248b15c23b38c0b6080814aff0542676b6e98`
  - `public/emulators/wlibzip.js`: `c19d0ce2ed8f686637e4abe54b374142c4d8092aa4471fd8153f97abf6436a88`
  - `public/emulators/wlibzip.wasm`: `cff5e8e1600ba7c589e43966613956060b4696924355714faf6b28e4c35db48f`

## Bundled JavaScript dependencies

The minified js-dos and emulator runtimes include or reference JavaScript dependencies with their own permissive licenses. Dependency license texts are collected in `public/licenses/BUNDLED_JS_DEPENDENCY_LICENSES.txt`.

Recorded dependency versions from the `js-dos@8.3.20` dependency tree include:

- `@babel/runtime` 7.29.2 — MIT
- `@reduxjs/toolkit` 1.9.7 — MIT
- `browser-pack` 6.1.0 — MIT (from `emulators@8.3.8` build)
- `classnames` 2.5.1 — MIT
- `core-js` 3.30.0 — MIT (from `emulators@8.3.8` build)
- `hoist-non-react-statics` 3.3.2 — BSD-3-Clause
- `immer` 9.0.21 — MIT
- `js-tokens` 4.0.0 — MIT
- `lodash` 4.18.1 — MIT
- `loose-envify` 1.4.0 — MIT
- `nanoid` 3.3.12 — MIT
- `nipplejs` 0.10.2 — MIT
- `preact` 10.29.2 — MIT
- `prop-types` 15.8.1 — MIT
- `react` 18.3.1 — MIT
- `react-checkbox-tree` 1.8.0 — MIT
- `react-is` 16.13.1 and 18.3.1 — MIT
- `react-redux` 8.1.3 — MIT
- `redux` 4.2.1 — MIT
- `redux-thunk` 2.4.2 — MIT
- `reselect` 4.1.8 — MIT
- `use-sync-external-store` 1.6.0 — MIT

## Warranty

All components are provided as-is, without warranty, under their respective upstream license terms.
