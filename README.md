<div align="center">

# life.json

Portable digital identity specification

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)

</div>

## Overview

life.json is a composable JSON schema for capturing your digital identity. Designed to be owned by the individual and consumed by any compatible platform, enabling true data portability and anti-vendor-lock-in.

## Services

| Service | Description |
|---------|-------------|
| [life-json-schema](https://github.com/omnidotdev/life-json-schema) | JSON Schema specification |
| [life-json-site](https://github.com/omnidotdev/life-json-site) | Landing page at [life.omni.dev](https://life.omni.dev) |

## Quick Start

```bash
# Clone with services
git clone https://github.com/omnidotdev/life-json
cd life-json
git clone https://github.com/omnidotdev/life-json-schema services/life-json-schema
git clone https://github.com/omnidotdev/life-json-site services/life-json-site
```

## Relationship to persona.json

| Spec | Describes | Owned by |
|------|-----------|----------|
| life.json | Human identity | The user |
| [persona.json](https://persona.omni.dev) | Non-human identity | The operator/developer |

They meet in the middle: life.json's `assistants` slice stores the relationship between a specific human and a specific persona (learned facts, permissions, preferences).

## License

The code in this repository is licensed under Apache 2.0, &copy; [Omni LLC](https://omni.dev). See [LICENSE.md](LICENSE.md) for more information.
