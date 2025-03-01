# [10.0.0](https://github.com/Alorel/ngforage/compare/9.0.0...10.0.0) (2023-07-31)


### Maintenance

* Update to Angular 16 ([1c9b04b](https://github.com/Alorel/ngforage/commit/1c9b04b4dc182195b85f4dce8b0e585a94e261dc))


### Reverts

* Fix an incorrect version bump ([2344622](https://github.com/Alorel/ngforage/commit/2344622abba5b1e0997d4c5291331b214e5ebe35))


### BREAKING CHANGES

* Angular 15 no longer supported

# [9.0.0](https://github.com/Alorel/ngforage/compare/8.0.1...9.0.0) (2023-01-27)


### Maintenance

* Update for Angular 15 ([366e312](https://github.com/Alorel/ngforage/commit/366e312714cecda2b5faaaca9459d8be72c623f0))
* Update license year & email ([fe858bc](https://github.com/Alorel/ngforage/commit/fe858bc92d2490d009129a1162b2f9df703c6cd4))


### BREAKING CHANGES

* Angular 14 no longer supported

## [8.0.1](https://github.com/Alorel/ngforage/compare/8.0.0...8.0.1) (2022-11-13)


### Bug Fixes

* Include README.md in published npm package ([df9e424](https://github.com/Alorel/ngforage/commit/df9e424a8aebb063366c58445ca1502fe94b4ded))

# [8.0.0](https://github.com/Alorel/ngforage/compare/7.0.0...8.0.0) (2022-11-13)


### Maintenance

* **docs:** Set base href in angular.json ([9d60b7b](https://github.com/Alorel/ngforage/commit/9d60b7b555056049d59053fa72ec4d0f0b57f81f))
* Remove ancient schematics ([b7e048f](https://github.com/Alorel/ngforage/commit/b7e048fa86c8a48cb04f083b4252cd6bc23184c0))
* remove lazy-get-decorator dependency ([ec4f471](https://github.com/Alorel/ngforage/commit/ec4f4717bc1dc538d9865532f4e1138a97c27b6b))
* Update Angular dependencies to the lastest v14 versions ([f807d4a](https://github.com/Alorel/ngforage/commit/f807d4a725778f27f1623b009bfc5f95dc9bab78))
* Update to support Angular 14 using localforage 1.10.0 ([1482ac8](https://github.com/Alorel/ngforage/commit/1482ac8673fdec25e5325125dda4886a56dab57f)), closes [#308](https://github.com/Alorel/ngforage/issues/308)


### BREAKING CHANGES

* Depend on Angular 14 & localforage 1.10

# [7.0.0](https://github.com/Alorel/ngforage/compare/6.0.0...7.0.0) (2022-01-24)


### Maintenance

* Update to support Angular 13 ([78c78a1](https://github.com/Alorel/ngforage/commit/78c78a1d39a9e2030b0bd9ecfc3691bdca2c350c)), closes [#286](https://github.com/Alorel/ngforage/issues/286) [#273](https://github.com/Alorel/ngforage/issues/273) [#247](https://github.com/Alorel/ngforage/issues/247) [#277](https://github.com/Alorel/ngforage/issues/277) [#276](https://github.com/Alorel/ngforage/issues/276)


### BREAKING CHANGES

* Angular <13.0 & ngforage <1.9.0 no longer supported

# [6.0.0](https://github.com/Alorel/ngforage/compare/5.0.1...6.0.0) (2020-06-08)


### Documentation

* Add missing tsdoc for some exported members ([](https://github.com/Alorel/ngforage/commit/442be19))
* Removed extraneous import from a readme example ([](https://github.com/Alorel/ngforage/commit/a5619c0))


### Features

* **schematics:** Added support for ng add ([](https://github.com/Alorel/ngforage/commit/f4af048))


### Maintenance

* Add .idea to git ([](https://github.com/Alorel/ngforage/commit/96f654c))
* add missing comma in karma.conf.js ([](https://github.com/Alorel/ngforage/commit/99318f3))
* Recompile for ng9 ([](https://github.com/Alorel/ngforage/commit/652e124))
* Regenerate lockfile ([](https://github.com/Alorel/ngforage/commit/95c8df7)), closes [#226](https://github.com/Alorel/ngforage/issues/226)
* Removed the Omit type as Typescript now bundles its own. ([](https://github.com/Alorel/ngforage/commit/2753a62))


### Refactoring

* Moved an internal property's initialiser. ([](https://github.com/Alorel/ngforage/commit/2486707))
* Refactored an internal toJSON method ([](https://github.com/Alorel/ngforage/commit/e255c02))
* Removed `Symbol.toStringTag` from all classes. ([](https://github.com/Alorel/ngforage/commit/701c7a3))
* Removed NgForageModule ([](https://github.com/Alorel/ngforage/commit/e419759))


### Tests

* Fix "Setting 5 items should increase length to 5" test consistency ([](https://github.com/Alorel/ngforage/commit/3d134de))
* Fix some clearing issues ([](https://github.com/Alorel/ngforage/commit/52e2161))


### BREAKING CHANGES

* library now requires Angular >=9.0.0
* Removed the Omit type as Typescript now bundles its own. ng update will handle this for you
* `Symbol.toStringTag` was removed from call classes in case you were depending on it for any reason.
* NgForageModule has been removed - see MIGRATING.md

## [5.0.1](https://github.com/Alorel/ngforage/compare/5.0.0...5.0.1) (2019-07-10)


### Bug Fixes

* **tests:** Removed "Length should be 0 initially" test as it was no longer needed and would sometimes fail due to changes in the updated Karma lib ([5122181](https://github.com/Alorel/ngforage/commit/5122181))


### Maintenance

* Add .npmrc to .gitignore ([5eba92e](https://github.com/Alorel/ngforage/commit/5eba92e))

# [5.0.0](https://github.com/Alorel/ngforage/compare/4.0.3...5.0.0) (2019-07-10)


### Bug Fixes

* Updated the library for Angular 8 ([5891c12](https://github.com/Alorel/ngforage/commit/5891c12)), closes [#186](https://github.com/Alorel/ngforage/issues/186) [#187](https://github.com/Alorel/ngforage/issues/187) [#188](https://github.com/Alorel/ngforage/issues/188) [#189](https://github.com/Alorel/ngforage/issues/189) [#192](https://github.com/Alorel/ngforage/issues/192)


### Documentation

* Reduce number of badges in README ([a0ba9a2](https://github.com/Alorel/ngforage/commit/a0ba9a2))


### Maintenance

* **deps:** bump handlebars from 4.1.0 to 4.1.2 ([2827125](https://github.com/Alorel/ngforage/commit/2827125))
* **deps:** bump js-yaml from 3.12.2 to 3.13.1 ([7cf2971](https://github.com/Alorel/ngforage/commit/7cf2971))


### BREAKING CHANGES

* The library's Angular dependencies now require versions ^8.0.0.
