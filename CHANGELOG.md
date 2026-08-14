# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Run the sync script automatically on Renovate vendir branches and push the result for review.
- Add a check which fails a pull request if the sync script was not run.
- Add shared helpers file to sync dir.

## [0.3.2] - 2026-08-03

### Changed

- CircleCI: Do not override app version.

## [0.3.1] - 2026-07-30

### Changed

- Chart: Fix icon URL.

## [0.3.0] - 2025-03-14

### Changed

- Run container with a read-only filesystem.

## [0.2.0] - 2025-02-25

### Changed

- Push app to default and default-test catalogs.

## [0.1.0] - 2025-02-20

### Added

- Initial release which tracks upstream version `0.0.10`.

[Unreleased]: https://github.com/giantswarm/kube-vip-cloud-provider-app/compare/v0.3.2...HEAD
[0.3.2]: https://github.com/giantswarm/kube-vip-cloud-provider-app/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/giantswarm/kube-vip-cloud-provider-app/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/giantswarm/kube-vip-cloud-provider-app/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/giantswarm/kube-vip-cloud-provider-app/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/giantswarm/kube-vip-cloud-provider-app/releases/tag/v0.1.0
