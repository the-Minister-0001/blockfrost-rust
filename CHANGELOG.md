# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## 1.0.0 - 2023-12-18

### Changed

- Implemented pagination for each endpoint.
- Integrated GitHub Continuous Integration for automated testing and deployment.
- Applied Cargo Clippy and rustfmt for code linting and formatting.
- Removed macros.
- Expanded test coverage with additional tests.
- Enhanced data fetching methods.
- Conducted code cleanup and refactoring.
- Refactored settings for improved clarity and efficiency.
- Updated data structures and schemas to the latest standards.
- Provided more comprehensive examples for better user understanding.
- Enhanced unit tests for more robust code testing.
- Implemented additional linting measures for code quality assurance.
- ENDPOINTS.md now contains a table of implemented endpoints.
- Added missing endpoints:
  - `accounts_addresses_total`
  - `addresses_extended`
  - `addresses_utxos_asset`
  - `network_eras`
  - `mempool`
  - `mempool_hash`
  - `mempool_addresses_address`
  - `scripts_hash_json`
  - `scripts_hash_cbor`
  - `scripts_datum_hash`
  - `scripts_datum_hash_cbor`
  - `utils_tx_evaluate`
  - `utils_tx_evaluate_utxos`

## 0.2.1 - 2023-05-02

### Changed

`use_previewnet` -> `use_preview`
`use_preprodnet` -> `use_preprod`

### Fixed

redemeers -> redeemers
