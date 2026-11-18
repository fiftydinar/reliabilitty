
## [0.1.9](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.8...v0.1.9) - 2026-11-18

### Documentation

- Refresh benchmarks with six terminals on v0.1.8 ([#10](https://github.com/pkgforge-apps/reliabilitty/pull/10)) - ([879b392](https://github.com/pkgforge-apps/reliabilitty/commit/879b392c0f767fcc51bc4f2a39003530c2ac5ba4))

## [0.1.8](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.7...v0.1.8) - 2026-11-18

### Performance

- *(vt)* Narrow region-scroll damage and rotate lines in place - ([602b167](https://github.com/pkgforge-apps/reliabilitty/commit/602b1679cd657ccd0d8cd9464f87e24c3af13c90))

## [0.1.7](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.6...v0.1.7) - 2026-11-18

### Bug Fixes

- Satisfy CI clippy lints in deque scroll code - ([1d6a701](https://github.com/pkgforge-apps/reliabilitty/commit/1d6a701c003ad8b34ebacb1da4f648968aa5c17d))

## [0.1.6](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.5...v0.1.6) - 2026-11-18

### Performance

- *(vt)* Clear recycled lines lazily and avoid CSI allocations - ([dc961e6](https://github.com/pkgforge-apps/reliabilitty/commit/dc961e667be8d9435ffe0dd89ac7e8e66ffabfa1))

## [0.1.5](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.4...v0.1.5) - 2026-11-18

### Performance

- *(vt)* Use a deque for the screen buffer so full scrolls are O(1) - ([3cef596](https://github.com/pkgforge-apps/reliabilitty/commit/3cef596862c62fb5a61c2a9ebccd999d6aa74dcb))
- Drain PTY before drawing and speed up text and glyph handling - ([d4b0e71](https://github.com/pkgforge-apps/reliabilitty/commit/d4b0e719d933ed147767c2ed73a6e343eee7cc5c))

## [0.1.4](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.3...v0.1.4) - 2026-11-18

### Bug Fixes

- Recognize numpad keys and keep pager scroll content - ([21c7bd2](https://github.com/pkgforge-apps/reliabilitty/commit/21c7bd2bba57728ebff846ebb404618e1ab82c48))

### Documentation

- Update performance results ([#8](https://github.com/pkgforge-apps/reliabilitty/pull/8)) - ([af38a63](https://github.com/pkgforge-apps/reliabilitty/commit/af38a630f24dccb44f72433ceae610e102719929))

## [0.1.3](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.2...v0.1.3) - 2026-11-17

### Performance

- Use mimalloc as the global allocator - ([15d2e3f](https://github.com/pkgforge-apps/reliabilitty/commit/15d2e3ffdd50e891502571da31ee9ec057aa650b))
- Optimize scrolling and text rendering - ([ec90d7b](https://github.com/pkgforge-apps/reliabilitty/commit/ec90d7b31d72a718b87e11eb33c2bd6a5b8a5ae0))

### Miscellaneous Tasks

- Build musl targets with cross for mimalloc - ([b2c9c04](https://github.com/pkgforge-apps/reliabilitty/commit/b2c9c049b79c9b1f711976214860358a6c00f550))

## [0.1.2](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.1...v0.1.2) - 2026-11-17

### Features

- Detect display DPI from X11 properties ([#5](https://github.com/pkgforge-apps/reliabilitty/pull/5)) - ([26281c9](https://github.com/pkgforge-apps/reliabilitty/commit/26281c9978602628ef19f3216d836942ae0216f1))

## [0.1.1](https://github.com/pkgforge-apps/reliabilitty/compare/v0.1.0...v0.1.1) - 2026-11-17

### Documentation

- Fix and extend the feature comparison table - ([de9cff7](https://github.com/pkgforge-apps/reliabilitty/commit/de9cff7269253435e275399b2dabe3fbb8aecd8a))

### Performance

- Draw the window before loading fonts - ([fed95c1](https://github.com/pkgforge-apps/reliabilitty/commit/fed95c103ae5e3cda781f5127a31378fa104015d))
