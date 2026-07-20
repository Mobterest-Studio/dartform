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

---
## [1.0.3] — 2026-07-20

### Added
- Dart Shelf framework support — visual models, route scaffolding, a live REST tester, and database browsing, alongside Serverpod and Dart Frog.

### Bug Fixes
- Data Browser now surfaces the real database error on a failed add/edit/delete instead of silently reporting success when nothing actually happened.
- Route tester auto-fill for date/time fields now generates a value the server can actually parse, instead of a generic string that produced a 500 error.
- Add/Edit Row dialog now uses a proper date and time picker for timestamp columns, instead of requiring a hand-typed value with the correct timezone offset.
- Fixed a crash when clearing a model's class name immediately after it had auto-populated the table name field.

---
## [1.0.2] — 2026-07-18

### Added
- Dart Frog framework support — visual models, endpoint scaffolding, a live REST tester, and database browsing, alongside Serverpod.
- Linux platform support.

### Changed
- Switched to one-time lifetime pricing — pay once, own it forever, no subscription.

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

[Unreleased]: https://github.com/Mobterest-Studio/dartform/compare/v1.0.3...HEAD
[1.0.3]: https://github.com/Mobterest-Studio/dartform/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/Mobterest-Studio/dartform/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/Mobterest-Studio/dartform/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/Mobterest-Studio/dartform/releases/tag/v1.0.0
