# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.4] - 2020-07-03

### Changed

- Move CRDs to `crd` subdirectory.
- Correct typo in sources URL.

## [1.1.3] - 2020-06-12

### Added

- Add CA Injector for webhooks

## [1.1.2] - 2020-05-29

### Changed

- Fix Deployment template format.

## [1.1.1] - 2020-05-29

### Changed

- Fix RBAC template format.

## [1.1.0] - 2020-04-14

### Changed

- Push `g8s-cert-manager` app into `control-plane` catalog instead.
- Push `g8s-cert-manager` app CRs into `<platform>-app-collection` repository.

### Deleted

- Delete legacy chart, used by draughtsman.

## [1.0.0] - 2019-08-02

### Added

- Push `g8s-cert-manager` app into `operations-platform` catalog.

[Unreleased]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.1.4...HEAD
[1.1.4]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.1.3...v1.1.4
[1.1.3]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.1.2...v1.1.3
[1.1.2]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/giantswarm/g8s-cert-manager/compare/v1.0.0...v1.1.0

[1.0.0]: https://github.com/giantswarm/g8s-cert-manager/tag/v1.0.0
