# Changelog

All notable changes to the shared Helm template should be documented here.

## [1.2.0] - 2026-04-07
### Added
- optional `ConfigMap` template support
- optional `Secret` template support using `stringData`
- `envFrom` wiring so config and secret values can be injected into the container
- documented example configuration snippets for app consumers

## [1.1.0] - 2026-04-07
### Changed
- improved publishing workflow for GitHub Pages Helm repository usage
- clarified safe versioning and upgrade guidance for dependent apps

## [1.0.0] - 2026-04-05
### Added
- initial reusable `app-template` chart
- `web-service` workload support
- Deployment, Service, and Ingress templates
- values schema for safer upgrades and validation
