# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Run the sync script automatically on Renovate vendir branches and push the result for review.
- Add a check which fails a pull request if the sync script was not run.
- Add shared helpers file to sync dir.
- Add Github action to create an issue in `giantswarm/giantswarm` for Team Rocket on vendir updates.

### Changed

- Create the vendir update issue as the `giantswarm-project-automation` GitHub App instead of architectbot's `ISSUE_AUTOMATION` token (giantswarm/giantswarm#38800).
- Use the `giantswarm-release` GitHub App instead of the taylorbot personal access token to push sync commits.
- Update architect to v10.10.0 (giantswarm/kube-vip-cloud-provider-app#85)
- Update architect to v10.12.0 (giantswarm/kube-vip-cloud-provider-app#86)
- Update architect to v10.12.1 (giantswarm/kube-vip-cloud-provider-app#88)
- Update architect to v10.12.2 (giantswarm/kube-vip-cloud-provider-app#90)
- Update architect to v10.13.0 (giantswarm/kube-vip-cloud-provider-app#94)
- Update architect to v10.13.2 (giantswarm/kube-vip-cloud-provider-app#96)
- Update architect to v10.13.4 (giantswarm/kube-vip-cloud-provider-app#98)
- Use Linux tools to manipulate chart label instead of an inscrutable Perl command.
- Update architect to v10.14.7 (giantswarm/kube-vip-cloud-provider-app#103)
- Update carvel-dev/vendir to v0.46.3 (giantswarm/kube-vip-cloud-provider-app#109)
- Update actions/create-github-app-token to v3.3.0 (giantswarm/kube-vip-cloud-provider-app#114)
- Update architect to v10.14.18 (giantswarm/kube-vip-cloud-provider-app#115)
- Update architect to v10.15.1 (giantswarm/kube-vip-cloud-provider-app#116)
- Update architect to v10.16.3 (giantswarm/kube-vip-cloud-provider-app#117)
- Update architect to v10.16.5 (giantswarm/kube-vip-cloud-provider-app#119)
- Update architect to v10.16.6 (giantswarm/kube-vip-cloud-provider-app#121)
- Update architect to v10.16.7 (giantswarm/kube-vip-cloud-provider-app#122)

### Fixed

- The `helm.sh/chart` label is valid for long chart versions: the 63-character cut trims the whole trailing run of `-`, `.` and `_`.
- Fix changelog generation script.

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
