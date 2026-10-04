# Changelog

## 1.0.0 (2026-10-04)


### ⚠ BREAKING CHANGES

* Normalize repository, dropping node <10.13 support ([#76](https://github.com/FotoVerite/gulp-glob-watcher/issues/76))

### Features

* Drop just-debounce from dependencies ([cbb4b18](https://github.com/FotoVerite/gulp-glob-watcher/commit/cbb4b18513ddaa3849692912c252c2e4eb33f0b4))


### Bug Fixes

* Ensure the `add` method of gaze is being called properly ([c3c27ee](https://github.com/FotoVerite/gulp-glob-watcher/commit/c3c27ee3e90eb1a0afe2c38858e8f81dc77cb0c0))
* Improve negative globbing with cwd option (fixes [#46](https://github.com/FotoVerite/gulp-glob-watcher/issues/46)) ([5062520](https://github.com/FotoVerite/gulp-glob-watcher/commit/5062520783d1f33d01a73e61e42c5671d376cadc))
* Match glob handling to vinyl-fs (fixes gulpjs/gulp[#2192](https://github.com/FotoVerite/gulp-glob-watcher/issues/2192)) ([b274b50](https://github.com/FotoVerite/gulp-glob-watcher/commit/b274b508ddcc6b0d746096390cd50b1760a99e75))
* Merge `opt.ignored` and our custom ignore function (fixes [#40](https://github.com/FotoVerite/gulp-glob-watcher/issues/40)) ([4fca711](https://github.com/FotoVerite/gulp-glob-watcher/commit/4fca711c6adfa4fe7ae7d87462aeb1cc4cf9592c))
* Move normalize-path to dependency ([dbfabfd](https://github.com/FotoVerite/gulp-glob-watcher/commit/dbfabfd206750658f0ad74d638ca5fcedba08cff))
* Only attach our custom ignore function if there are negative globs ([5681c11](https://github.com/FotoVerite/gulp-glob-watcher/commit/5681c11c80589e05387ffcd0b654ddc4bbfa70d5))
* Only emit `error` events when there is a listener (fixes [#35](https://github.com/FotoVerite/gulp-glob-watcher/issues/35)) ([#36](https://github.com/FotoVerite/gulp-glob-watcher/issues/36)) ([ad96e3f](https://github.com/FotoVerite/gulp-glob-watcher/commit/ad96e3f50ad71d7b4ad2b89b591b7ebaa4f36825))
* Proxy `remove` on gaze correctly (closes [#16](https://github.com/FotoVerite/gulp-glob-watcher/issues/16)) ([cb82894](https://github.com/FotoVerite/gulp-glob-watcher/commit/cb8289450cd2427ba1087f0c02c73ab685e6e814))
* Rollback gaze due to breaking changes ([8909d97](https://github.com/FotoVerite/gulp-glob-watcher/commit/8909d979aeadd430d32c387f1af72cc4984331ef))


### Miscellaneous Chores

* Normalize repository, dropping node &lt;10.13 support ([#76](https://github.com/FotoVerite/gulp-glob-watcher/issues/76)) ([cbb4b18](https://github.com/FotoVerite/gulp-glob-watcher/commit/cbb4b18513ddaa3849692912c252c2e4eb33f0b4))

## [6.0.0](https://www.github.com/gulpjs/glob-watcher/compare/v5.0.5...v6.0.0) (2023-05-31)


### ⚠ BREAKING CHANGES

* Normalize repository, dropping node <10.13 support (#76)

### Features

* Drop just-debounce from dependencies ([cbb4b18](https://www.github.com/gulpjs/glob-watcher/commit/cbb4b18513ddaa3849692912c252c2e4eb33f0b4))


### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#76](https://www.github.com/gulpjs/glob-watcher/issues/76)) ([cbb4b18](https://www.github.com/gulpjs/glob-watcher/commit/cbb4b18513ddaa3849692912c252c2e4eb33f0b4))
