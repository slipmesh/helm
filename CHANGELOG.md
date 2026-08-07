# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and follows [Semantic Versioning](https://semver.org/).

## [0.4.1] - 2026-08-07

### Miscellaneous 🧹

- Sync images with slipmesh-operators v0.3.1

## [0.4.0] - 2026-08-05

### Added ✨

- Replace implicit full-mesh generation with an explicit mesh.links list

### Fixed 🐛

- Regenerate CRDs with valid integer formats, fix stale RBAC comment
- Regenerate crds/*.yaml with a leading document separator
- Validate mesh.links pairs and meshLabel uniqueness

## [0.3.0] - 2026-08-05

### Added ✨

- Move roadwarriors/router's remaining tuning-knob env vars into CRDs

### Fixed 🐛

- Address Copilot review feedback on the config CRD templates

## [0.2.1] - 2026-08-05

### Added ✨

- Sync chart with slipmesh-operators v0.2.0

### Fixed 🐛

- Silence PodSecurity warn/audit on the chart-managed namespace

### Miscellaneous 🧹

- Bump to v0.2.1, sync with slipmesh-operators v0.2.1
- Update repository/image URLs to the slipmesh org
- Drop gitleaks from CI
- Rename chart from slipmesh-network to slipmesh

### Release

- V0.2.1

## [0.1.1] - 2026-08-03

### Added ✨

- Initial implementation of slipmesh-network Helm chart

### Documentation 📚

- Add initial CHANGELOG.md

### Fixed 🐛

- Address code-review findings on roadwarriors defaults and CI validation

### Miscellaneous 🧹

- Bump chart to 0.1.1, images to v0.1.1

### Release

- V0.1.1
