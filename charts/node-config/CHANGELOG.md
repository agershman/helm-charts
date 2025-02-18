# Node Config Helm Chart Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

<!-- ## [vX.Y.Z] - UNRELEASED
### Highlights
### All Changes
- Added
- Updated
- Changed
- Fixed
- Deprecated
- Removed -->

## [v0.5.0] - 2023-05-22

### All Changes

- Added `affinity.nodeAffinity`.

## [v0.4.1] - 2023-05-15

### All Changes

- Fixed volume bug.

## [v0.4.0] - 2023-05-12

### All Changes

- Added support for host PID.

## [v0.3.0] - 2023-05-12

### All Changes

- Added a checksum for the script content.

## [v0.2.1] - 2023-05-12

### All Changes

- Fixed script mount logic.

## [v0.2.0] - 2023-05-11

### All Changes

- Added support for attaching additional volumes to the config container via `extraVolumes` & `config.extraVolumeMounts`.

## [v0.1.0] - 2023-05-09

### All Changes

- Initial release.
