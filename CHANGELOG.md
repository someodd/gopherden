# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

  * Make gopher links out of posted URIs!
  * Special codes: you can define keys associated with strings in your `config.toml`, if a
    post's entire message is `<somekey>` where `somekey` belongs to an entry in the
    `specialCodes` table, then the post will be presented as the corresponding value.

### Fixed

...

### Changed

...

## [v0.4.0.0] - 2024-03-14

### Fixed

  * Handle blank selector

## [v0.3.0.0] - 2024-03-14

### Added

  * Configurable maximum post length
  * Configuration for client sent an empty query language
  * Config options for spacecookie server
  * (Hopefully) more accessible reply + new thread links

### Fixed

  * Give an error for when a post is too long

## [0.2.0.0] - 2024-03-08

### Added

  * Rate-limiting, now you can only create a thread once per n minutes and create a reply once per x minutes
  * TOML config!

### Changed

  * Timestamps in the database stored with timezone information now

## [0.1.0.0] - 2024-03-04

First release, a proof of concept.

[unreleased]: https://github.com/someodd/gopherden/compare/v0.4.0.0...HEAD
[0.4.0.0]: https://github.com/someodd/gopherden/compare/v0.3.0.0...v0.4.0.0
[0.3.0.0]: https://github.com/someodd/gopherden/compare/v0.2.0.0...v0.3.0.0
[0.2.0.0]: https://github.com/someodd/gopherden/compare/v0.1.0.0...v0.2.0.0
[0.1.0.0]: https://github.com/someodd/gopherden/release/v0.1.0.0
