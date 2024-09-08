# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.0.0] - 2024-09-08

### Added

- `sar:beam_ids` property to describe the swath in the SAR acquisition.

### Changed

- Required properties of type `string` require a minimum length of `1`.

### Deprecated

- `sar:product_type` in favor of `product:type`

### Removed

### Fixed

- JSON Schema checks `stac_extensions` field in Collections
- Updates examples to STAC v1.0.0

## [v1.0.0] - 2021-03-04

### Added
- Best practices and asset roles

[Unreleased]: <https://github.com/stac-extensions/sar/compare/v1.0.0...HEAD>
[v1.0.0]: <https://github.com/stac-extensions/sar/tree/v1.0.0>
