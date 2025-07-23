# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.1.1] - 2025-07-23

### Added
- Updated dev dependencies

## [4.1.0] - 2025-04-04

### Added

- Add support for node-mailjet 6.0.8
- Remove deprecated function removeUndefined, support for Strapi v5
  
## [4.0.0] - 2022-04-01

### Added
- adapt to strapi v4

## [3.3.5] - 2021-02-23

### Added

- normalization of receiver fields
- empty receiver error only if both to and defaultTo are empty
- case sensitive fix
- normalizeReceiver fix
- fixed cc, bcc and attachments
- Merge pull request ijsto#5 from burlakko/defaultToName_fix
- feat(API): Add updateContact()

## [3.3.0] - 2020-11-21

### Added

- @ScottAgirs: Option to send to multiple recipients addresses issue #2

## [3.2.2] - 2020-11-02

### CHANGED (!BREAKING - if you are currently on 3.2.1)

- renamed subscribeContactFromList() > subscribeContact*To*List()

## [3.2.1] - 2020-11-02

### Added

- subscribeContactFromList()

## [3.2.0] - 2020-11-02

### Added

- removeContactFromList()
- unsubscribeContactFromList()

## [3.1.0] - 2020-09-03

### Changed

- Deprecate Actions API in favour of API Methods.

## [3.0.1] - 2020-08-22

### Added

- Experimental Actions API (depends on [#7560](https://github.com/strapi/strapi/pull/7560))

## [3.0.0] - 2020-08-20

### Added

- README examples and configs
- Changelog file

### 💥BREAKING CHANGES

The provider plugin was has gone through an major rewrite to work with the latest stable versions of Strapi.
There may be breaking changes, please ensure you familiarize yourself with the current README instructions, if you are upgrading from versions 1.x.
