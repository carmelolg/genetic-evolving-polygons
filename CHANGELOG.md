# Changelog

## [0.3.5](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.3.4...carmelolg-gapoly-v0.3.5) (2026-11-21)


### Performance Improvements

* compute the incremental delta in one nogil kernel per shape ([333572f](https://github.com/carmelolg/GAPoly/commit/333572ff9438a8ef923e732b37681d78560e0d63))
* incremental fitness, redraw only the pixels a mutation can change ([8a1b6f3](https://github.com/carmelolg/GAPoly/commit/8a1b6f3711f5168fd17d53fbf5e31e4fd8ee3303))
* mutation in Numba for every shape, faster stroke rasteriser ([6d97732](https://github.com/carmelolg/GAPoly/commit/6d977320643aee6b5482d2a9b916d36a362c12e1))

## [0.3.4](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.3.3...carmelolg-gapoly-v0.3.4) (2026-11-20)


### Documentation

* add Apache-2.0 for code, CC BY-NC-SA 4.0 for works, author link ([4294376](https://github.com/carmelolg/GAPoly/commit/42943768458caa3e9f8076b00eabb842d0376464))

## [0.3.3](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.3.2...carmelolg-gapoly-v0.3.3) (2026-11-20)


### Bug Fixes

* declare supported Python versions ([6966ed5](https://github.com/carmelolg/GAPoly/commit/6966ed5eda19ace8bd1c24247cb74073ad511766))

## [0.3.2](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.3.1...carmelolg-gapoly-v0.3.2) (2026-11-20)


### Bug Fixes

* **site:** mobile header, viewer bar and hero buttons; docs: restructure README ([601e023](https://github.com/carmelolg/GAPoly/commit/601e023bb95a85b2b5ddb029d426708ae0f42318))

## [0.3.1](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.3.0...carmelolg-gapoly-v0.3.1) (2026-11-20)


### Documentation

* add badges to README ([5bde3f5](https://github.com/carmelolg/GAPoly/commit/5bde3f5b978b92d2d96ba03e2c99b03e2d91a8f3))

## [0.3.0](https://github.com/carmelolg/GAPoly/compare/carmelolg-gapoly-v0.2.0...carmelolg-gapoly-v0.3.0) (2026-11-20)


### Features

* add mosaic, glyph and stroke shapes, rename repository to GAPoly ([53158de](https://github.com/carmelolg/GAPoly/commit/53158de74d67a35f354b5162756459a6896b2fca))
* **site:** gallery published on GitHub Pages with the lossless works optimizer ([74bcb01](https://github.com/carmelolg/GAPoly/commit/74bcb01978280f262f0251a2e2d399857193e010))

## [0.2.0](https://github.com/carmelolg/genetic-evolving-polygons/compare/carmelolg-gapoly-v0.1.0...carmelolg-gapoly-v0.2.0) (2026-11-18)


### ⚠ BREAKING CHANGES

* PolygonProblem, Kind, KINDS, COLS and the removed options no longer exist. Use ImageProblem(shape=...), Shape, SHAPES and --elements.

### Features

* add discs, selected with --shape disc ([f8630d4](https://github.com/carmelolg/genetic-evolving-polygons/commit/f8630d4cf82e37f16003ada00acbf8c8ae2142c1))
* add Voronoi points, selected with --shape voronoi ([77a99f8](https://github.com/carmelolg/genetic-evolving-polygons/commit/77a99f867e5c1454779e4b4d374eae9ac13eb85a))


### Code Refactoring

* shapes as a Strategy, drop obsolete options and dead code ([de74dde](https://github.com/carmelolg/genetic-evolving-polygons/commit/de74dde3f616f25affe8ac49aa5489cf6798f0cc))

## 0.1.0 (2026-11-18)


### Features

* gapoly, evolve semi-transparent polygons to approximate a photo ([4f8d1a6](https://github.com/carmelolg/genetic-evolving-polygons/commit/4f8d1a665a4d3768700b96dfef0688c2fa541c8b))
