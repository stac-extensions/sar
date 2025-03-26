# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added `LH`, `LV`, `RH`, `RV`, `CH` and `CV` enumerations to `sar:polarizations` to support compact polarization.
- Best practices for `altm:instrument_mode` and `altm:instrument_type`

### Deprecated

- `sar:instrument_mode` in favor of `altm:instrument_mode`

### Fixed

- Fixed and updated examples

## [v1.1.0] - 2024-12-18

### Added

- `sar:beam_ids` property to describe the swath in the SAR acquisition.

### Changed

- Required properties of type `string` require a minimum length of `1`.

### Deprecated

- `sar:product_type` in favor of `product:type`

### Fixed

- JSON Schema checks `stac_extensions` field in Collections
- Updates examples to STAC v1.0.0

## [v1.0.0] - 2021-03-04

### Added

- Best practices and asset roles

[Unreleased]: <https://github.com/stac-extensions/sar/compare/v1.1.0...main>
[v1.1.0]: <https://github.com/stac-extensions/sar/compare/v1.0.0...v1.1.0>
[v1.0.0]: <https://github.com/stac-extensions/sar/tree/v1.0.0>
