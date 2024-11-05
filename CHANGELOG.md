# Changelog

## [1.0.1] - 2024-11-05
### Added
- Support for querying enum fields without prefix (e.g., `where(status: :active)` now works alongside `where(_status: :active)`)

## [1.0.0] - 2024-11-05
### Added
- Support for Ruby 2.6 through 3.2
- Support for Mongoid 7.x
- GitHub Actions CI pipeline

### Changed
- Minimum Ruby version requirement is now 2.6.0
- Updated development dependencies

### Removed
- Dropped support for Ruby < 2.6
- Removed Travis CI configuration
