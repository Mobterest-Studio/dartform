# Changelog

All notable changes to Dartform are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Releases are also published on the [GitHub Releases page](https://github.com/Mobterest-Studio/dartform/releases) with downloadable DMG assets.

If macOS blocks Dartform on first launch:
1. Right-click Dartform.app → Open → Open
   OR
2. Run in Terminal:
   xattr -dr com.apple.quarantine /Applications/Dartform.app

---

## [Unreleased]

### Planned
- Additional Serverpod module support
- Linux build

---
## [1.0.1] — 2026-04-19

### Added
- Dartform AI - helps you scaffold your backend with a prompt and Dartform automates the rest.

### Bug Fixes
- Initally relations defaulted to N:1
- Endpoint methods were limited to 6, now they show all including custom methods
- Accept configurations to other ports on Dartform other than the default Serverpod ports
- Reset database feature (now applies migrations and starts the server)
- ER AutoLayout feature spaces out evenly
- Endpoint deleted when its model is deleted
- Endpoint Tester were limited to 6 methods,  now they show all including custom methods
- Model Update now reflect to other related models
- Unnecessay addition of 'Id' and '?' concatenated at the end of a field



## [1.0.0] — 2026-03-21

### Added
- Initial public release
- Project dashboard — open and manage multiple Serverpod projects
- Schema & data model visualization
- Endpoint generator and postman-like tester
- Team seat management — invite, revoke, and manage teammates
- Magic-link sign-in via email (no password required) 
- 7-day free trial on all plans

---

[Unreleased]: https://github.com/Mobterest-Studio/dartform/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/Mobterest-Studio/dartform/releases/tag/v1.0.0
