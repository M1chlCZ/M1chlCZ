# Michal Žídek

**Software engineer · Go, Rust, and Flutter · Prague, Czech Republic**

I build backend services, API integrations, and developer tools. My public projects cover image moderation, shipping APIs, log analysis, and 3D assets for the web.

[npm packages](https://www.npmjs.com/~m1chlcz) · [Email](mailto:m1chlcz18@gmail.com) · [Telegram](https://t.me/M1chlCZ) · [X](https://twitter.com/M1chl)

![Go](https://img.shields.io/badge/Go-0f766e?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-334155?style=flat-square&logo=rust&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-334155?style=flat-square&logo=flutter&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=white)

## Featured project: [nsfw_sherlock](https://github.com/M1chlCZ/nsfw_sherlock)

**An image moderation API in Go. My favorite open-source project.**

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

| Package | What it does | Version |
| :--- | :--- | :--- |
| **[three-fdm-studio](https://www.npmjs.com/package/three-fdm-studio)** | A React and three.js studio for 3D print previews, with surface textures, lighting, and part selection. | [![npm version](https://img.shields.io/npm/v/three-fdm-studio?style=flat-square)](https://www.npmjs.com/package/three-fdm-studio) |
| **[step2glb](https://www.npmjs.com/package/step2glb)** | Converts STEP assemblies to compressed GLB files for the web. | [![npm version](https://img.shields.io/npm/v/step2glb?style=flat-square)](https://www.npmjs.com/package/step2glb) |
| **[layerforge](https://www.npmjs.com/package/layerforge)** | Composes product previews from a layer manifest. | [![npm version](https://img.shields.io/npm/v/layerforge?style=flat-square)](https://www.npmjs.com/package/layerforge) |
| **[seamless-texture](https://www.npmjs.com/package/seamless-texture)** | Joins opposite texture edges without mirrored or blended pixels. | [![npm version](https://img.shields.io/npm/v/seamless-texture?style=flat-square)](https://www.npmjs.com/package/seamless-texture) |
| **[localization-drift](https://www.npmjs.com/package/localization-drift)** | Detects visible text that bypasses translation keys and fails the build. | [![npm version](https://img.shields.io/npm/v/localization-drift?style=flat-square)](https://www.npmjs.com/package/localization-drift) |

## More projects

| Project | What it does |
| :--- | :--- |
| **[Rust-a-Log](https://github.com/M1chlCZ/Rust-a-Log)** · Rust | A command-line log viewer with filters and live updates. It reads large files in small blocks to limit memory use. |
| **[balikobot-go](https://github.com/M1chlCZ/balikobot-go)** · Go | A client for the Balikobot shipping API. It supports packages, labels, shipment tracking, and carrier services. |
| **[launchgate](https://github.com/M1chlCZ/launchgate)** · Go | A reverse proxy for private site previews. It controls access through invitation links and supports maintenance mode. |

[![Rust-a-Log CI](https://img.shields.io/github/actions/workflow/status/M1chlCZ/Rust-a-Log/ci.yml?branch=main&style=flat-square&label=Rust-a-Log%20CI)](https://github.com/M1chlCZ/Rust-a-Log/actions)
[![Rust-a-Log crate version](https://img.shields.io/crates/v/rust-a-log?style=flat-square&label=crates.io)](https://crates.io/crates/rust-a-log)
[![balikobot-go CI](https://img.shields.io/github/actions/workflow/status/M1chlCZ/balikobot-go/ci.yml?branch=main&style=flat-square&label=balikobot-go%20CI)](https://github.com/M1chlCZ/balikobot-go/actions)

- **[mfakit](https://github.com/M1chlCZ/mfakit)** provides TOTP codes, encrypted secrets, and recovery codes for Go services.

[All repositories →](https://github.com/M1chlCZ?tab=repositories&type=source)
