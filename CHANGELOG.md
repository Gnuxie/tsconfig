# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2024-11-05

### Changed

- Enabled prosewrap in prettier.

## [1.0.0] - 2024-11-04

### Changed

- Breaking: removed dependabot and added renovate instead, based on Draupnir's
  config.
- Updated dependencies

## [0.6.0] - 2024-08-20

### Changed

- Template is now using REUSE.toml rather than dep5.

## [0.5.5] - 2024-07-30

### Added

- Include a github workflow for releasing npm packages.

## [0.5.4] - 2024-07-30

### Added

- Include a changelog templates.
- Include a pre-commit task for linting.

## [0.5.3] - 2024-07-29

### Fixed

- Update references from gnuxie-tsconfig to @gnuxie/tsconfig.

## [0.5.2] - 2024-07-29

### Fixed

- Include source files in the npm package so that we can actually use the thing.

## [0.5.1] - 2024-07-29

### Fixed

- GitHub workflow file for releasing package was in the wrong directory.

## [0.5.0] - 2024-07-29

### Changed

- reuse has been updated.
- dep5 has been migrated to `REUSE.toml` by using `reuse convert-dep5`.
- package name has been changed to `@gnuxie/tsconfig`.
