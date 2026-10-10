# Michal Žídek

**Software engineer · Go, Rust, and Flutter · Prague, Czech Republic**

I build backend services, Flutter apps, and developer tools. My open-source work covers AI assistants, shipping integrations, reusable mobile packages, and 3D assets for the web.

[LinkedIn](https://www.linkedin.com/in/m1chl) · [npm](https://www.npmjs.com/~m1chlcz) · [Flutter & Dart packages](#flutter--dart-packages) · [Email](mailto:m1chlcz18@gmail.com) · [Telegram](https://t.me/M1chlCZ) · [X](https://twitter.com/M1chl)

![Go](https://img.shields.io/badge/Go-0f766e?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-334155?style=flat-square&logo=rust&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-334155?style=flat-square&logo=flutter&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=white)

## Featured projects

### [Local Coding Assistant](https://github.com/M1chlCZ/local-coding-assistant) · Python / C# / CUDA

A research prototype for local coding models on 16 GB NVIDIA GPUs, with a Windows launcher and a native Training Studio.

- Run coding chat and agent APIs through llama.cpp and CUDA.
- Control WSL fine-tuning with Start, Pause, Resume, and Stop.
- Track GPU use, checkpoints, and matched coding evaluations.

[Source and setup](https://github.com/M1chlCZ/local-coding-assistant#readme) · [Training Studio](https://github.com/M1chlCZ/local-coding-assistant/tree/main/desktop) · [Research and results](https://github.com/M1chlCZ/local-coding-assistant#measured-results)

### [AgentWave](https://github.com/M1chlCZ/agentwave) · Go

An embeddable AI assistant for admin panels, CRMs, and internal tools. It turns a request and the current screen route into one policy-validated suggestion.

- A private Unix socket connects the service to the application backend.
- The Codex CLI generates suggestions with its tools disabled.
- The application controls whether to apply each suggestion.

[Source and integration guide](https://github.com/M1chlCZ/agentwave#readme)

### [nsfw_sherlock](https://github.com/M1chlCZ/nsfw_sherlock)

**An image moderation API in Go.**

NSFW Sherlock classifies images through HTTP and gRPC APIs. The current engine uses ONNX Runtime.

- Multiple models classify photos and anime images and detect explicit regions.
- Optional OCR uses Tesseract to detect text in images.
- Docker images include the models for deployment.

[![NSFW Sherlock CI](https://img.shields.io/github/actions/workflow/status/M1chlCZ/nsfw_sherlock/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/M1chlCZ/nsfw_sherlock/actions/workflows/ci.yml)
[![NSFW Sherlock release](https://img.shields.io/github/v/release/M1chlCZ/nsfw_sherlock?style=flat-square&label=release)](https://github.com/M1chlCZ/nsfw_sherlock/releases)
[![Docker pulls](https://img.shields.io/docker/pulls/m1chl/nsfw-sherlock?style=flat-square)](https://hub.docker.com/r/m1chl/nsfw-sherlock)

[Source and API documentation](https://github.com/M1chlCZ/nsfw_sherlock#readme) · [Docker Hub](https://hub.docker.com/r/m1chl/nsfw-sherlock)

## npm packages

I publish tools for 3D previews, image processing, and localization on [npm](https://www.npmjs.com/~m1chlcz).

| Source | What it does | npm |
| :--- | :--- | :--- |
| **[three-fdm-studio](https://github.com/M1chlCZ/three-fdm-studio)** | A React and three.js studio for 3D print previews, with surface textures, lighting, and part selection. | [![npm version](https://img.shields.io/npm/v/three-fdm-studio?style=flat-square)](https://www.npmjs.com/package/three-fdm-studio) |
| **[step2glb](https://github.com/M1chlCZ/step2glb)** | Converts STEP assemblies to compressed GLB files for the web. | [![npm version](https://img.shields.io/npm/v/step2glb?style=flat-square)](https://www.npmjs.com/package/step2glb) |
| **[layerforge](https://github.com/M1chlCZ/layerforge)** | Composes product previews from a layer manifest. | [![npm version](https://img.shields.io/npm/v/layerforge?style=flat-square)](https://www.npmjs.com/package/layerforge) |
| **[seamless-texture](https://github.com/M1chlCZ/seamless-texture)** | Joins opposite texture edges without mirrored or blended pixels. | [![npm version](https://img.shields.io/npm/v/seamless-texture?style=flat-square)](https://www.npmjs.com/package/seamless-texture) |
| **[localization-drift](https://github.com/M1chlCZ/localization-drift)** | Detects visible text that bypasses translation keys and fails the build. | [![npm version](https://img.shields.io/npm/v/localization-drift?style=flat-square)](https://www.npmjs.com/package/localization-drift) |
| **[glb2svg](https://github.com/M1chlCZ/glb2svg)** | Renders GLB assets as SVG artwork without a browser or GPU. | [![glb2svg on npm](https://img.shields.io/npm/v/glb2svg?style=flat-square)](https://www.npmjs.com/package/glb2svg) |

## Flutter & Dart packages

Reusable packages for API clients, images, app utilities, and user interfaces. Each package name opens its source repository. The version badge opens pub.dev.

| Source | What it does | pub.dev |
| :--- | :--- | :--- |
| **[json_rest_client](https://github.com/M1chlCZ/json_rest_client)** | A JSON HTTP client with typed errors, token storage, and coordinated token refresh. | [![json_rest_client on pub.dev](https://img.shields.io/pub/v/json_rest_client?style=flat-square)](https://pub.dev/packages/json_rest_client) |
| **[balikobot_dart](https://github.com/M1chlCZ/balikobot_dart)** | A client for the Balíkobot shipping API: packages, labels, tracking, and pickups. | [![balikobot_dart on pub.dev](https://img.shields.io/pub/v/balikobot_dart?style=flat-square)](https://pub.dev/packages/balikobot_dart) |
| **[disk_cached_image](https://github.com/M1chlCZ/disk_cached_image)** | Network images with a disk cache, expiration, and cache cleanup. | [![disk_cached_image on pub.dev](https://img.shields.io/pub/v/disk_cached_image?style=flat-square)](https://pub.dev/packages/disk_cached_image) |
| **[qr_scanner_kit](https://github.com/M1chlCZ/qr_scanner_kit)** | A QR scanner screen with a viewfinder, torch, and camera controls. | [![qr_scanner_kit on pub.dev](https://img.shields.io/pub/v/qr_scanner_kit?style=flat-square)](https://pub.dev/packages/qr_scanner_kit) |
| **[lock_screen_pin](https://github.com/M1chlCZ/lock_screen_pin)** | A customizable PIN entry screen with a keypad and biometric entry option. | [![lock_screen_pin on pub.dev](https://img.shields.io/pub/v/lock_screen_pin?style=flat-square)](https://pub.dev/packages/lock_screen_pin) |
| **[atomic_ui_kit](https://github.com/M1chlCZ/atomic_ui_kit)** | Reusable Flutter widgets for buttons, containers, text, and switches. | [![atomic_ui_kit on pub.dev](https://img.shields.io/pub/v/atomic_ui_kit?style=flat-square)](https://pub.dev/packages/atomic_ui_kit) |
| **[core_utils_kit](https://github.com/M1chlCZ/core_utils_kit)** | Secure storage, date formatting, colors, URL handling, and app lifecycle utilities. | [![core_utils_kit on pub.dev](https://img.shields.io/pub/v/core_utils_kit?style=flat-square)](https://pub.dev/packages/core_utils_kit) |

## More projects

| Project | What it does |
| :--- | :--- |
| **[Rust-a-Log](https://github.com/M1chlCZ/Rust-a-Log)** · Rust | A command-line log viewer with filters and live updates. It reads large files in small blocks to limit memory use. |
| **[balikobot-go](https://github.com/M1chlCZ/balikobot-go)** · Go | A client for the Balikobot shipping API. It supports packages, labels, shipment tracking, and carrier services. |
| **[launchgate](https://github.com/M1chlCZ/launchgate)** · Go | A reverse proxy for private site previews. It controls access through invitation links and supports maintenance mode. |

[![Rust-a-Log CI](https://img.shields.io/github/actions/workflow/status/M1chlCZ/Rust-a-Log/ci.yml?branch=main&style=flat-square&label=Rust-a-Log%20CI)](https://github.com/M1chlCZ/Rust-a-Log/actions)
[![Rust-a-Log crate version](https://img.shields.io/crates/v/rust-a-log?style=flat-square&label=crates.io)](https://crates.io/crates/rust-a-log)
[![balikobot-go CI](https://img.shields.io/github/actions/workflow/status/M1chlCZ/balikobot-go/ci.yml?branch=main&style=flat-square&label=balikobot-go%20CI)](https://github.com/M1chlCZ/balikobot-go/actions)

- **[pgmig](https://github.com/M1chlCZ/pgmig)** runs PostgreSQL migrations and detects checksum drift.
- **[pgoutbox](https://github.com/M1chlCZ/pgoutbox)** provides a PostgreSQL job queue with leases, retries, and dead-letter handling.
- **[mfakit](https://github.com/M1chlCZ/mfakit)** provides TOTP codes, encrypted secrets, and recovery codes for Go services.

[All repositories →](https://github.com/M1chlCZ?tab=repositories&type=source)
