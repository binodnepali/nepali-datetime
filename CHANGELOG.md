# CHANGELOG

## [1.5.0](https://github.com/binodnepali/nepali-datetime/compare/v1.4.0...v1.5.0) (2025-03-31)


### Features

* Add files field in package.json to indicate which files will be ([bc16daa](https://github.com/binodnepali/nepali-datetime/commit/bc16daa225bc9c4ff03dbe17446bc6aa241b4c05))
* add method `formatEnglishDate` and `formatEnglishDateInNepali` ([#94](https://github.com/binodnepali/nepali-datetime/issues/94)) ([6cf9d14](https://github.com/binodnepali/nepali-datetime/commit/6cf9d142e5193e246b546f8599411efbf4e2a014))
* add method `parseEnglishDate` for English date parsing ([#95](https://github.com/binodnepali/nepali-datetime/issues/95)) ([aeabb8d](https://github.com/binodnepali/nepali-datetime/commit/aeabb8dde4903114b19010cfee25b0a61a4fc227))
* add static method `getDaysOfMonth` on NepaliDate ([#96](https://github.com/binodnepali/nepali-datetime/issues/96)) ([c85edfa](https://github.com/binodnepali/nepali-datetime/commit/c85edfa4d40f93061674f6143f6343b23a653bc0))
* add static methods for min and max supported dates ([#102](https://github.com/binodnepali/nepali-datetime/issues/102)) ([6b13079](https://github.com/binodnepali/nepali-datetime/commit/6b130794cbaad396e7e4a648163a346de0f6cdbb))
* Add support for dddd, ddd, dd, d, MMM and MMMM formats for NepaliDate ([8f96239](https://github.com/binodnepali/nepali-datetime/commit/8f962396606c3eeaf0e6e20a97a6701517ef84b7))
* add support for node 22 and remove 16 ([#101](https://github.com/binodnepali/nepali-datetime/issues/101)) ([3254f8d](https://github.com/binodnepali/nepali-datetime/commit/3254f8de6b384c4078117949feb51b3c2a93900d))
* Added method parseFormatTokens [#43](https://github.com/binodnepali/nepali-datetime/issues/43) [#10](https://github.com/binodnepali/nepali-datetime/issues/10) ([6623c7c](https://github.com/binodnepali/nepali-datetime/commit/6623c7c5612c93b82e09fc9bfed2d9c584c03411))
* Added static fromEnglishDate method in NepaliDate ([9e01db2](https://github.com/binodnepali/nepali-datetime/commit/9e01db2b8b68e38cf311cda08f9ee3de03021379))
* **ci:** add prettier check on ci ([314e898](https://github.com/binodnepali/nepali-datetime/commit/314e8980438b78ac91c8c6feee9a052913b77bf2))
* **ci:** add prettier check on ci ([a728ed4](https://github.com/binodnepali/nepali-datetime/commit/a728ed48477139eb3417e0e52ead16c23be8e9ff))
* constructor overloaded docstring added with type validation ([4a17685](https://github.com/binodnepali/nepali-datetime/commit/4a176859e766ee3f607a5014665b9b14a545635d))
* constructor overloaded docstring added with type validation ([367799f](https://github.com/binodnepali/nepali-datetime/commit/367799f209acec2c2c9b9f60e0025ab1b1b89120))
* Convert JS to TS --phase-1 ([1698f73](https://github.com/binodnepali/nepali-datetime/commit/1698f73c0de0e1eb9c737db0233f2eff1bc5a65d))
* format v2 implementaion ([15c8d56](https://github.com/binodnepali/nepali-datetime/commit/15c8d5652258f1d36d3e5efbcc31b89e3c551fbe))
* Incorporate PR review suggestions and add unit tests for seqToRE ([ae4f9f2](https://github.com/binodnepali/nepali-datetime/commit/ae4f9f2b4d908e2e071e123b76dec753fab1c2a5))
* Integrated new format with NepaliDate ([f07c84b](https://github.com/binodnepali/nepali-datetime/commit/f07c84b35d633caefef2a1286722198d92065642))
* parse numeric date time from given format ([e55ab31](https://github.com/binodnepali/nepali-datetime/commit/e55ab31140dea0ece68d68cd174b98e86bd8be3b))
* **parse:** Updated tests with coverage for parsing ([7060fbd](https://github.com/binodnepali/nepali-datetime/commit/7060fbd7266917070550a6cea35b141438db932c))
* reduced package bundle size ([d15e575](https://github.com/binodnepali/nepali-datetime/commit/d15e5750ffdebce5233b0476e95c3db1cc7311e6))


### Bug Fixes

* add types package.json exports ([86b68ca](https://github.com/binodnepali/nepali-datetime/commit/86b68cae5068ea2fd9b2b9edc0dc657670bb67ee))
* add types package.json exports ([e974556](https://github.com/binodnepali/nepali-datetime/commit/e9745560dedb61eced821ce7a5a147214c85f913))
* Fix timezone for +5:30 and +5:45 ([1cc8688](https://github.com/binodnepali/nepali-datetime/commit/1cc868825e82c076d86818f1638af807e4bfed8c))
* Fix timezone for +5:30 and +5:45 ([71f9674](https://github.com/binodnepali/nepali-datetime/commit/71f9674dd0e5370cda19dfcc67014744a3e9a763))
* fixed AM/PM formatting issue of noon ([dec6a42](https://github.com/binodnepali/nepali-datetime/commit/dec6a42a09e93e9f4caa09db0bdab38e3bc89d20))
* fixed AM/PM formatting issue of noon ([57091bc](https://github.com/binodnepali/nepali-datetime/commit/57091bc817f275e07627a0388382f7402f44baff))
* Fixed month mismatched issue on date converter ([3c46a1a](https://github.com/binodnepali/nepali-datetime/commit/3c46a1ae560bb3010034ca0bfe8f90da801cd19e))
* Fixed month mismatched issue on date converter ([39680e0](https://github.com/binodnepali/nepali-datetime/commit/39680e0257ab9d520b8ed960ba28fffbca8b6349))
* remove dist and update gitignore ([70ee526](https://github.com/binodnepali/nepali-datetime/commit/70ee526eeedeca53518845f13f2ac9dfe406e89a))
* remove dist and update gitignore ([9003a73](https://github.com/binodnepali/nepali-datetime/commit/9003a73d011e4789fda437d0d1ce4d3abaff29a4))
* types added ([367799f](https://github.com/binodnepali/nepali-datetime/commit/367799f209acec2c2c9b9f60e0025ab1b1b89120))
* update nepali months data ([#103](https://github.com/binodnepali/nepali-datetime/issues/103)) ([b19d135](https://github.com/binodnepali/nepali-datetime/commit/b19d135f0a7a610a2858e230924b4420cc70f1f9))
* Updated English calendar year, month, day transfer from another NepaliDate object ([d1b9495](https://github.com/binodnepali/nepali-datetime/commit/d1b9495da4a6244f8512515fa5f6b52377b2d3bf))
* updated months data for 2081 ([994d863](https://github.com/binodnepali/nepali-datetime/commit/994d8636526f197b96681f44af332c67bbc7e262))
* updated months data for 2081 ([a49b3d6](https://github.com/binodnepali/nepali-datetime/commit/a49b3d679bcddfdbfc9c5bcf28826ccfedc3a7b9))
* Updated NepaliDate's members to private ([ee4f496](https://github.com/binodnepali/nepali-datetime/commit/ee4f496c8ddbc9b745e0878157cceb56d0d3a1bb))

## [1.4.0](https://github.com/opensource-nepal/node-nepali-datetime/compare/v1.3.0...v1.4.0) (2024-12-25)


### Features

* add static method `getDaysOfMonth` on NepaliDate ([#96](https://github.com/opensource-nepal/node-nepali-datetime/issues/96)) ([c85edfa](https://github.com/opensource-nepal/node-nepali-datetime/commit/c85edfa4d40f93061674f6143f6343b23a653bc0))
* add static methods for min and max supported dates ([#102](https://github.com/opensource-nepal/node-nepali-datetime/issues/102)) ([6b13079](https://github.com/opensource-nepal/node-nepali-datetime/commit/6b130794cbaad396e7e4a648163a346de0f6cdbb))
* add support for node 22 and remove 16 ([#101](https://github.com/opensource-nepal/node-nepali-datetime/issues/101)) ([3254f8d](https://github.com/opensource-nepal/node-nepali-datetime/commit/3254f8de6b384c4078117949feb51b3c2a93900d))


### Bug Fixes

* update nepali months data ([#103](https://github.com/opensource-nepal/node-nepali-datetime/issues/103)) ([b19d135](https://github.com/opensource-nepal/node-nepali-datetime/commit/b19d135f0a7a610a2858e230924b4420cc70f1f9))

## [1.3.0](https://github.com/opensource-nepal/node-nepali-datetime/compare/v1.2.1...v1.3.0) (2024-11-30)


### Features

* add method `formatEnglishDate` and `formatEnglishDateInNepali` ([#94](https://github.com/opensource-nepal/node-nepali-datetime/issues/94)) ([6cf9d14](https://github.com/opensource-nepal/node-nepali-datetime/commit/6cf9d142e5193e246b546f8599411efbf4e2a014))
* add method `parseEnglishDate` for English date parsing ([#95](https://github.com/opensource-nepal/node-nepali-datetime/issues/95)) ([aeabb8d](https://github.com/opensource-nepal/node-nepali-datetime/commit/aeabb8dde4903114b19010cfee25b0a61a4fc227))
* **ci:** add prettier check on ci ([a728ed4](https://github.com/opensource-nepal/node-nepali-datetime/commit/a728ed48477139eb3417e0e52ead16c23be8e9ff))

## [1.2.1](https://github.com/opensource-nepal/node-nepali-datetime/compare/v1.2.0...v1.2.1) (2024-03-06)


### Bug Fixes

* updated months data for 2081 ([a49b3d6](https://github.com/opensource-nepal/node-nepali-datetime/commit/a49b3d679bcddfdbfc9c5bcf28826ccfedc3a7b9))

## [1.2.0](https://github.com/opensource-nepal/node-nepali-datetime/compare/v1.1.2...v1.2.0) (2023-11-16)


### Features

* reduced package bundle size ([d15e575](https://github.com/opensource-nepal/node-nepali-datetime/commit/d15e5750ffdebce5233b0476e95c3db1cc7311e6))

## [1.1.2](https://github.com/opensource-nepal/node-nepali-datetime/compare/v1.1.1...v1.1.2) (2023-10-03)


### Bug Fixes

* fixed AM/PM formatting issue of noon ([57091bc](https://github.com/opensource-nepal/node-nepali-datetime/commit/57091bc817f275e07627a0388382f7402f44baff))

## 1.1.1

-   Updated NepaliDate members to private.
-   Fixed type resolve issue. (#59, #60)

## 1.1.0 - (August 17, 2023)

-   Added husky for running pre-commit hook.
-   Run npm test on pre-commit hook.
-   Added formatting on pre-commit hook.
-   Refactored formatting.
-   Added parse feature in a given format.

## v1.0.1 - (July 14, 2023)

-   Added dateConverter module.
-   Added time/timezone support in NepaliDate.
-   Updated new formatting methods and added time formatting (with moment.js format reference). Added `formatNepali` method.
-   Supported parse for date and time string on `NepaliDate` constructor.
-   Renamed method `getEnglishDate` to `getDateObject`.
-   Added methods for Nepali year, month, date of English calendar.
-   Added `fromEnglishDate` static method for initializing from English calendar date parameters.
-   Updated `toString` format of NepaliDate.

## v0.1.0 - (May 15, 2023)

-   Initial release with the features included in 'nepali-date'.
-   Typescript support.
