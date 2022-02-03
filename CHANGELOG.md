# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [3.0.0-beta.0](https://github.com/beinformed/chakram-beinformed/compare/v2.0.0...v3.0.0-beta.0) (2022-02-03)


### ⚠ BREAKING CHANGES

* no longer support for node v10

* feat!(update): update dependencies ([d06c40c](https://github.com/beinformed/chakram-beinformed/commit/d06c40cbca144f7ed8f822ef4a4f8525026219f7))

## 2.0.0 (2020-09-21)

-   Removed request and request-debug packages
-   Updated dependencies

#Changelog

###1.5.0

-   Added `responsetime` assertion #58
-   Added `responseTime` to `ChakramResponseObject` #60
-   Introduced `del` alias #61

###1.4.0

-   Added support for expect's second custom message argument #56
-   Exposes tv4's schemaBanUnknown and schemaCyclicCheck options #52
-   Exposes tv4's getSchemaMap method #43

###1.3.0

-   Identifies all schema errors #38
-   Exposes tv4's addFormat method #39
-   Added debugging functionality #30

###1.2.3

-   Updating dependencies
-   Fails schema validation if a referenced schema is missing #32

###1.2.2

-   Updating dependencies

###1.2.1

-   Allows equality checks for NULLs in JSON #24

###1.2.0

-   Added ability to set default options for requests #21

###1.1.0

-   Allowing pre-registration of JSON schemas

###1.0.1

-   Improved schema error messages #14
-   Updated dependencies #15

###1.0.0

-   Added "comprise" and "comprised" chain elements which should be used instead of "include" for subset JSON assertions
-   Simplified plugin interface

###0.1.0

-   Added callback support for JSON and header assertions
