# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2019-02-12
### Added
- Implemented table transformations at the connector level (breaking change for existing data models).
- Added missing address, email, phone and online presence fields to Constituents entity.

### Changed
- Updated links to developer.blackbaud.com in README.md.
- Changed entity ID naming conventions used by Blackbaud (helps with auto-generation of relationship maps).
- Limit value for supported endpoints has been increased from 500 to 5000.

### Removed
- Redundant fields removed from certain endpoints.

## [1.3.0] - 2019-01-24
### Changed
- Updated links to developer.blakbaud.com on README.md.

### Removed
- Redundant files removed.