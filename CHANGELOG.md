# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
### Changed
- Cache all calls to `os.getenv` via custom module [PR #231](https://github.com/3scale/apicast/pull/231)
- Bump s2i-openresty to 1.11.2.2-1 [PR #239](https://github.com/3scale/apicast/pull/239)

### Fixed
- [OAuth] Return correct state value back to client

### Removed

## [3.0.0-alpha1] - 2017-01-16
### Added
- A CHANGELOG.md to track important changes
- User-Agent header with APIcast version and system information [PR #214](https://github.com/3scale/apicast/pull/214)
- Try to load configuration from V2 API [PR #193](https://github.com/3scale/apicast/pull/193)

### Changed
- Require openresty 1.11.2 [PR #194](https://github.com/3scale/apicast/pull/194)
- moved development from `v2` branch to `master` [PR #209](https://github.com/3scale/apicast/pull/209)
- `X-3scale-Debug` HTTP header now uses Service Token [PR #217](https://github.com/3scale/apicast/pull/217)

## [2.0.0] - 2016-11-29
### Changed
- Major rewrite using JSON configuration instead of code generation.

[Unreleased]: https://github.com/3scale/apicast/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/3scale/apicast/compare/v0.2...v2.0.0
[3.0.0-alpha1]: https://github.com/3scale/apicast/compare/v2.0.0...v3.0.0-alpha1
