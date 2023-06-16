# Fluent Bit Aggregator Helm Chart Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

<!--
## [UNRELEASED]

### Added - For new features.
### Changed - For changes in existing functionality.
### Deprecated - For soon-to-be removed features.
### Removed - For now removed features.
### Fixed - For any bug fixes.
### Security - In case of vulnerabilities.
-->

## [v0.3.3] - 2023-06-16

### Fixed

- Fixed config mount to support hot-reload.

## [v0.3.2] - 2023-06-15

### Fixed

- Fixed hot-reload volume mounts.

## [v0.3.1] - 2023-06-15

### Fixed

- Fixed args when hot-reload is enabled.

## [v0.3.0] - 2023-06-13

### Added

- Added [hot-reload](https://docs.fluentbit.io/manual/administration/hot-reload) support.

## [v0.2.1] - 2023-06-05

### Fixed

- Fixed volume mount typo.
- Fixed missing fsGroup from pod security context.

## [v0.2.0] - 2023-06-05

### Added

- Added support for HPA behaviour.

## [v0.1.0] - 2023-05-30

### Added

- Added initial release.