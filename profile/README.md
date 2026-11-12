# ArkDeck

Open-source tools for developing on real OpenHarmony devices: flashing, debugging, tracing, and trace viewing, usable from a desktop app, a CLI, or an AI agent.

| Repository | What it is |
| --- | --- |
| [ArkDeck](https://github.com/ArkDeck/ArkDeck) | The main toolkit: a macOS app, a CLI, and a per-user daemon sharing one Rust runtime for device adoption, HAP debugging, diagnostics, flashing, and trace analysis. A Windows 11 client is in development. |
| [ArkForge](https://github.com/ArkDeck/ArkForge) | Device-neutral firmware flashing in Rust: the `arkforge` CLI and the `arkforged` daemon, with native RockUSB for the DAYU200 (RK3568). ArkDeck uses it as its flashing layer. |
| [ArkTrace](https://github.com/ArkDeck/ArkTrace) | Trace capture and analysis: a native macOS timeline viewer and the `arktrace` CLI, built on a pinned TraceStreamer. ArkDeck uses it as its trace engine. |

All projects are in development. There are no tagged releases yet; each repository's README explains how to build from source.

- [Code of Conduct](https://github.com/ArkDeck/.github/blob/main/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/ArkDeck/.github/blob/main/SECURITY.md)
