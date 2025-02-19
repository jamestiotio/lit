# Change Log

## 1.0.4

### Patch Changes

- [#3886](https://github.com/lit/lit/pull/3886) [`0c3ce9bd`](https://github.com/lit/lit/commit/0c3ce9bd45c21f5857fcda9c588912f572a2d723) - Fix transforms when scaling to or from zero

- Updated dependencies [[`e2c50569`](https://github.com/lit/lit/commit/e2c50569c48849a9863e31dfd74a71bb4eb4524d), [`8057c78d`](https://github.com/lit/lit/commit/8057c78def09e345e68c3fc009b8ab9d6cf1c0f2)]:
  - lit@2.8.0

## 1.0.3

### Patch Changes

- [#3132](https://github.com/lit/lit/pull/3132) [`2fe2053f`](https://github.com/lit/lit/commit/2fe2053fe04e7226e5fa4e8b730e91a62a547b27) - Added "types" entry to package exports. This tells newer versions of TypeScript where to look for typings for each module.

## 1.0.2

### Patch Changes

- [#2402](https://github.com/lit/lit/pull/2402) [`a638841d`](https://github.com/lit/lit/commit/a638841d8ba76e43cf83a2516e2cfc7a9c2ce27e) - Trivial: reformat markdown files

- [#2410](https://github.com/lit/lit/pull/2410) [`b9a6962b`](https://github.com/lit/lit/commit/b9a6962b84c841eaabd5c4cbf8687ff34dbfe511) - Correct the link path of CONTRIBUTING.md in README.md files

## 1.0.1

### Patch Changes

- [#2186](https://github.com/lit/lit/pull/2186) [`59acf89a`](https://github.com/lit/lit/commit/59acf89ae77612fe1a91577f9ac0361f4e277a17) - Ensures `*.d.ts` files are included in production output.

## 1.0.0

### Patch Changes

- [#2166](https://github.com/lit/lit/pull/2166) [`94dff0a4`](https://github.com/lit/lit/commit/94dff0a4b74877a3de192eb32534c6237bb098a7) - Renamed `animate` option `animateOptions` to `keyframeOptions` and `AnimateController` `animateOptions` to `defaultOptions`

* [#1942](https://github.com/lit/lit/pull/1942) [`c8fe1d4`](https://github.com/lit/lit/commit/c8fe1d4c4a8b1c9acdd5331129ae3641c51d9904) - For minified class fields on classes in lit libraries, added prefix to stable properties to avoid collisions with user properties.

- [#2113](https://github.com/lit/lit/pull/2113) [`5b2f3642`](https://github.com/lit/lit/commit/5b2f3642ff91931b5b01f8bdd2ed98aba24f1047) - Dependency upgrades including TypeScript 4.4.2

* [#2166](https://github.com/lit/lit/pull/2166) [`94dff0a4`](https://github.com/lit/lit/commit/94dff0a4b74877a3de192eb32534c6237bb098a7) - Renamed `flip()` to `animate()`

- [#1964](https://github.com/lit/lit/pull/1964) [`f43b811`](https://github.com/lit/lit/commit/f43b811405be32ce6caf82e80d25cb6170eeb7dc) - Don't publish src/ to npm.

- Updated dependencies [[`15a8356d`](https://github.com/lit/lit/commit/15a8356ddd59a1e80880a93acd21fadc9c24e14b), [`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705), [`5b2f3642`](https://github.com/lit/lit/commit/5b2f3642ff91931b5b01f8bdd2ed98aba24f1047), [`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705), [`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705), [`0312f3e5`](https://github.com/lit/lit/commit/0312f3e533611eb3f4f9381594485a33ad003b74)]:
  - lit@2.0.0

## 1.0.0-rc.4

### Patch Changes

- [#2113](https://github.com/lit/lit/pull/2113) [`5b2f3642`](https://github.com/lit/lit/commit/5b2f3642ff91931b5b01f8bdd2ed98aba24f1047) - Dependency upgrades including TypeScript 4.4.2

- Updated dependencies [[`15a8356d`](https://github.com/lit/lit/commit/15a8356ddd59a1e80880a93acd21fadc9c24e14b), [`5b2f3642`](https://github.com/lit/lit/commit/5b2f3642ff91931b5b01f8bdd2ed98aba24f1047), [`0312f3e5`](https://github.com/lit/lit/commit/0312f3e533611eb3f4f9381594485a33ad003b74)]:
  - lit@2.0.0-rc.4

## 1.0.0-rc.3

### Patch Changes

- [#1942](https://github.com/lit/lit/pull/1942) [`c8fe1d4`](https://github.com/lit/lit/commit/c8fe1d4c4a8b1c9acdd5331129ae3641c51d9904) - For minified class fields on classes in lit libraries, added prefix to stable properties to avoid collisions with user properties.

* [#1964](https://github.com/lit/lit/pull/1964) [`f43b811`](https://github.com/lit/lit/commit/f43b811405be32ce6caf82e80d25cb6170eeb7dc) - Don't publish src/ to npm.

* Updated dependencies [[`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705), [`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705), [`5fabe2b5`](https://github.com/lit/lit/commit/5fabe2b5ae4ab8fba9dc2d23a69105d32e4c0705)]:
  - lit@2.0.0-rc.3

- Included `development` folder in release [#1912](https://github.com/lit/lit/issues/1912).

---

Changes below were based on the [Keep a Changelog](http://keepachangelog.com/) format. All changes above are generated automatically by [Changesets](https://github.com/atlassian/changesets).

---

## [1.0.0-rc.2] - 2021-04-07

### Fixed

- Included `flip-controller` in `package.json` `files` section [#1796](https://github.com/lit/lit/issues/1796).

## [1.0.0-rc.1] - 2021-04-20

### Changed

- Updated dependencies

## [1.0.0-pre.1] - 2020-12-16

### Added

- Adds `flip` directive. The `flip` directive animates a node's layout between renders. It will perform a "tweening" animation between the two states based on the options given. In addition, elements can animate when they initially render to DOM and when they are removed. for making elements move from one render to the next.
- Adds `position` directive that positions and sizes an element relative to a given target element.
