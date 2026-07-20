<div align="center">

<img src="dartform_logo.svg" alt="Dartform Logo" width="80" />

# Dartform

**The multi-backend Dart developer platform for Dart and Flutter developers**

[![Latest Release](https://img.shields.io/github/v/release/Mobterest-Studio/dartform?style=flat-square&color=38b6ff&label=latest)](https://github.com/Mobterest-Studio/dartform/releases/latest)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux-lightgrey?style=flat-square)](https://github.com/Mobterest-Studio/dartform/releases/latest)
[![Issues](https://img.shields.io/github/issues/Mobterest-Studio/dartform?style=flat-square&color=38b6ff)](https://github.com/Mobterest-Studio/dartform/issues)
[![License](https://img.shields.io/badge/license-Proprietary-lightgrey?style=flat-square)](https://dartform.dev/terms-of-use)

[**Download**](https://github.com/Mobterest-Studio/dartform/releases/latest) · [**dartform.dev**](https://dartform.dev) · [**Report a Bug**](https://github.com/Mobterest-Studio/dartform/issues/new?template=bug_report.yml) · [**Request a Feature**](https://github.com/Mobterest-Studio/dartform/issues/new?template=feature_request.yml) · [**Get Help**](https://github.com/Mobterest-Studio/dartform/discussions)

---

</div>

## What is Dartform?

Dartform is a native desktop application that gives Dart and Flutter developers a **visual interface for their backend projects** — schema visualization, route/endpoint browsing, code generation, migrations, and project scaffolding — without living in the terminal.

Dartform supports three Dart backends today: [Serverpod](https://serverpod.dev), [Dart Frog](https://dartfrog.vgv.dev), and [Shelf](https://pub.dev/packages/shelf). Whichever one your project uses, Dartform gives you the same visual model editor, migration tooling, REST/RPC tester, and database browser.

---

## Features

| Feature | Description |
|---|---|
| 📁 **Project Management** | Open and manage multiple projects — Serverpod, Dart Frog, or Dart Shelf — from a single dashboard |
| 🔍 **Schema Visualization** | Browse and explore your data models visually |
| ⚡ **Endpoint/Route Generator and Tester** | Generate endpoints or REST routes with one click and test them right in Dartform |
| 🔧 **Code Generation** | Scaffold new models and endpoints/routes without touching the CLI |
| 🔐 **Database Tools** | Browse data, run SQL queries, manage migrations — all in one place |

---

## Download

Dartform is available for **macOS** (Apple Silicon & Intel) and **Linux** (x86_64).

### Latest Release

👉 **[Download the latest release →](https://github.com/Mobterest-Studio/dartform/releases/latest)**

| Asset | Platform |
|---|---|
| `dartform-mac.dmg` | macOS Universal (Apple Silicon + Intel) |
| `dartform-linux-x86_64.AppImage` | Linux x86_64 |

### Installation

**macOS:**
1. Download the `.dmg` file
2. Open the DMG and drag **Dartform.app** to your Applications folder
3. On first launch, right-click the app → **Open** (required for unsigned apps on macOS)
4. Sign in with your email — a magic link will be sent to your inbox
5. You're in ✓

> **Note:** Dartform is currently distributed as an unsigned DMG. macOS Gatekeeper will show a security warning on first launch. To bypass it, right-click the app and select **Open**, then confirm in the dialog — a one-time step. Alternatively, run `xattr -dr com.apple.quarantine /Applications/Dartform.app` in Terminal.

**Linux:**
1. Download `dartform-linux-x86_64.AppImage`
2. Make it executable and run it: `chmod +x dartform-linux-x86_64.AppImage && ./dartform-linux-x86_64.AppImage`
3. Sign in with your email — a magic link will be sent to your inbox
4. No installation or root required. Requires Docker Engine (not Docker Desktop) installed separately for the Postgres-backed project features.

---

## Pricing

Dartform is a **one-time purchase** — **Lifetime Access for $25**. No subscription, no recurring payment, and it includes every future update.

👉 **[Get Lifetime Access on Gumroad →](https://mobterestudio.gumroad.com/l/dartform-lifetime-access)**

---

## System Requirements

| Requirement | Minimum |
|---|---|
| Operating System | macOS 13.0 Ventura or later, or Linux x86_64 on a systemd-based distro |
| Dependencies | Docker (Docker Desktop on macOS, Docker Engine on Linux) and the Dart SDK, plus the CLI for whichever framework you use — Serverpod CLI or Dart Frog CLI. Dart Shelf needs neither, just the Dart SDK |
| Disk space | ~200 MB |

---

## This Repository

This is the **public issue tracker** for Dartform. The application source code is not open source.

Use this repository to:

- 🐛 **[Report a bug](https://github.com/Mobterest-Studio/dartform/issues/new?template=bug_report.yml)**
- 💡 **[Request a feature](https://github.com/Mobterest-Studio/dartform/issues/new?template=feature_request.yml)**
- ❓ **[Ask a question or get help](https://github.com/Mobterest-Studio/dartform/discussions)**
- 📦 **[Download releases](https://github.com/Mobterest-Studio/dartform/releases)**
- 📋 **[View the changelog](https://github.com/Mobterest-Studio/dartform/releases)**

### Before opening an issue

- Search [existing issues](https://github.com/Mobterest-Studio/dartform/issues) to avoid duplicates
- Check the [Discussions](https://github.com/Mobterest-Studio/dartform/discussions) tab for Q&A
- Make sure you're running the [latest release](https://github.com/Mobterest-Studio/dartform/releases/latest)

---

## Community & Support

| Channel | Purpose |
|---|---|
| [GitHub Issues](https://github.com/Mobterest-Studio/dartform/issues) | Bug reports and feature requests |
| [GitHub Discussions](https://github.com/Mobterest-Studio/dartform/discussions) | Questions, ideas, and community help |
| [dartform.dev](https://dartform.dev) | Website and documentation |
| [mobterest@gmail.com](mailto:mobterest@gmail.com) | Direct support |
| [YouTube — Mobterest Studio](https://www.youtube.com/@mobtereststudio) | Tutorials and architecture content |

---

## Changelog

See the [Releases page](https://github.com/Mobterest-Studio/dartform/releases) for the full version history and release notes.

---

<div align="center">

Built by [Mobterest Studio](https://mobterest.studio) · [dartform.dev](https://dartform.dev) · [Terms of Use](https://dartform.dev/privacy) · [Privacy Policy](https://dartform.dev/terms-of-use)

</div>
