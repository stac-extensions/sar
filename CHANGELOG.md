# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.3.0] - 2025-07-16

### Added

- `sar:bandwidth` to describe the range bandwidth

### Changed

- Set exclusive minimum value of 0 for `sar:center_frequency`

## [v1.2.0] - 2025-03-31

### Added

- Added `LH`, `LV`, `RH`, `RV`, `CH` and `CV` enumerations to `sar:polarizations` to support compact polarization.

### Changed

- Required fields are recommended.
- Clarified the scope of the fields.

### Fixed

- Fixed and updated examples
- Updated JSON Schema to the latest version of the template

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

[Unreleased]: <https://github.com/stac-extensions/sar/compare/v1.3.0...main>
[v1.3.0]: <https://github.com/stac-extensions/sar/compare/v1.2.0...v1.3.0>
[v1.2.0]: <https://github.com/stac-extensions/sar/compare/v1.1.0...v1.2.0>
[v1.1.0]: <https://github.com/stac-extensions/sar/compare/v1.0.0...v1.1.0>
[v1.0.0]: <https://github.com/stac-extensions/sar/tree/v1.0.0>
