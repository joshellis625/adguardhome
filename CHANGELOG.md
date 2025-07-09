# Josh's Core DNS Allowlist – Changelog

All notable changes to this project will be documented in this file. This changelog follows semantic versioning: `MAJOR.MINOR.PATCH`.

---

## [1.0.0] – July 9, 2025 at 6:45 PM EDT

### Added
- Initial creation of DNS allowlist
- Organized into the following categories:
  - Work & Infra
  - Big Tech
  - Smart Home
  - CDN & Fonts
  - Dev & API
  - App Infra
  - Media & Social
  - Finance
  - Overrides

### Changed
- Converted all entries from AdGuard custom rule format
- Updated all rules to `@@||domain^` syntax for allowlisting

### Notes
- This allowlist is formatted for AdGuard Home v0.107.63+
- Designed for DNS lockdown setups using block-all + allowlist model
- Compatible with raw GitHub URL syncing
