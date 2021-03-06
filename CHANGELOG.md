# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [3.0.0-beta.7] - 2019-11-05

### Added

- support get authorization from sign server
- support miniprogram environment
- API specification

## [3.0.0-beta.3] - 2019-10-29

### Added

- Support default export
- Add Chinese version README

## [3.0.0-beta.2] - 2019-10-25

### Changed

- Only bundle files for script-tag usage case
- Export SDK through global namespace instead of different files in dist folder

## [3.0.0-beta.0] - 2019-10-18

### Changed

- Alter callback style methods to promise style
- Module import path, please refer to [README.md](./README.md) for more details

## [2.2.16] - 2018-10-17

### Added

- Add support for Cache-Control

## [2.2.15] - 2018-09-25

### Fixed

- template: Fix bug results in "X is not defined"
- Fix ParameterValueNotAllowedError is not a constructor
- Fix X-QS-Storage-Class value undefined is not allowed
- Fix Buffer() is deprecated

## [2.2.14] - 2018-09-25

### Added

- Add missing response headers for GetObject
- Add storage class support
- Add lifecycle support
- Add notification support
- Add content encoding support

## [2.2.13] - 2018-05-29

### Changed

- Do not calculate content length for JSON body

## [2.2.12] - 2018-05-14

### Fixed

- Fix error not handled correctly

## [2.2.11] - 2018-04-25

### Fixed

- Fix import error on React

## [2.2.10] - 2017-11-20

### Fixed

- Add `@babel/polyfill` into webpack entry to fix dependence missing
- Fix `package.json` typo

## [2.2.9] - 2017-11-19

### Changed

- `qingstor_sdk` exported to `windows` on browser

### Fixed

- Fix url can't be set in browser
- Fix bug that content-lenght miscalculated

## [2.2.8] - 2017-10-30

### Added

- Add image process API
- Add advanced client of image process

### Changed

- Force the zone ID to be lowercase

### Fixed

- Fix BUG that JSON length calculates not correctly
- Fix BUG that toLowerCase is not a function
- Fix BUG that missing dependence statement

## [2.2.7] - 2017-06-15

### Fixed

- Fix promise not returned by operation

## [2.2.6] - 2017-06-13

### Added

- Add promise support
- Add multipart copy and range support

### Fixed

- Fix bug which cause browser can't handle reponse

### Breaking Change

- Reponse body changed into a Readable Stream, no more a String

## [2.2.5] - 2017-04-09

### Fixed

- Fix \n will be escaped at browser side

## [2.2.4] - 2017-04-07

### Changed

- Change xhr withCredentials to false

## [2.2.3] - 2017-04-07

### Fixed

- Fix browser side compatible issue

## [2.2.2] - 2017-03-15

### Added

- signer: Add calculateSignature

### Changed

- Export Request and Signer class
- signer: Assign query signature to request params

## [2.2.1] - 2017-03-15

### Added

- Add the Request class

### Changed

- Remove extra space in User-Agent

### Fixed

- Fix error when load config from file
- Fix crash when sending request failed

## [2.2.0] - 2017-03-09

### Added

- Add list multipart uploads API
- Allow user to customize User-Agent

### Changed

- Refactor with ES6
- Empty options no more needed
- User input params will be converted into string

### Fixed

- Fix bug while handle utf-8 keys
- Resource is not mandatory in bucket policy statement

## [2.1.3] - 2017-02-08

### Fixed

- Fix bug in handling encryption api

## [2.1.2] - 2017-01-07

### Fixed

- Fix bug in get operation body

## [2.1.1] - 2017-01-07 [YANKED]

### Added

- Allow using ReadStream as body in object put

### Fixed

- Fix bug in query sign uri build

## [2.1.0] - 2016-12-26

### Added

- Add request parameters for GET Object
- Add IP address conditions for bucket policy

### Changed

- Fix signer bug
- Add more parameters to sign

## 2.0.0 - 2016-12-15

### Added

- Provide Official Qingstor SDK for Javascript

[3.0.0-beta.7]: https://github.com/yunify/qingstor-sdk-js/compare/3.0.0-beta.3...3.0.0-beta.7
[3.0.0-beta.3]: https://github.com/yunify/qingstor-sdk-js/compare/3.0.0-beta.2...3.0.0-beta.3
[3.0.0-beta.2]: https://github.com/yunify/qingstor-sdk-js/compare/3.0.0-beta.0...3.0.0-beta.2
[3.0.0-beta.0]: https://github.com/yunify/qingstor-sdk-js/compare/v2.2.16...3.0.0-beta.0
[2.2.16]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.15...v2.2.16
[2.2.15]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.14...2.2.15
[2.2.14]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.13...2.2.14
[2.2.13]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.12...2.2.13
[2.2.12]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.11...2.2.12
[2.2.11]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.10...2.2.11
[2.2.10]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.9...2.2.10
[2.2.9]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.8...2.2.9
[2.2.8]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.7...2.2.8
[2.2.7]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.6...2.2.7
[2.2.6]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.5...2.2.6
[2.2.5]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.4...2.2.5
[2.2.4]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.3...2.2.4
[2.2.3]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.2...2.2.3
[2.2.2]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.1...2.2.2
[2.2.1]: https://github.com/yunify/qingstor-sdk-js/compare/2.2.0...2.2.1
[2.2.0]: https://github.com/yunify/qingstor-sdk-js/compare/2.1.3...2.2.0
[2.1.3]: https://github.com/yunify/qingstor-sdk-js/compare/2.1.2...2.1.3
[2.1.2]: https://github.com/yunify/qingstor-sdk-js/compare/2.1.1...2.1.2
[2.1.1]: https://github.com/yunify/qingstor-sdk-js/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/yunify/qingstor-sdk-js/compare/2.0.0...2.1.0
