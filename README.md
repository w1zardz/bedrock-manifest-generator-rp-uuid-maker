# Bedrock Manifest Generator

Free online tool to generate valid `manifest.json` files with UUID v4 for Minecraft Bedrock Edition resource packs and behavior packs.

**[Use the Generator](https://w1zardz.github.io/bedrock-manifest-generator-rp-uuid-maker/)**

## Features

- Generates cryptographically random **UUID v4** identifiers
- Supports **Resource Packs** and **Behavior Packs**
- Format version 1 (legacy) and 2 (1.16.100+)
- Custom pack name, description, author, and version
- Configurable `min_engine_version`
- One-click **copy to clipboard** or **download** `manifest.json`
- Regenerate UUIDs without re-entering pack info
- Fully **mobile-optimized** — works great on phones and tablets
- No server, no tracking, no dependencies — runs 100% in the browser
- Works offline after first load

## Who is this for?

- **PocketMine-MP** plugin and resource pack developers
- **Bedrock Edition** addon and texture pack creators
- **MCPE / Pocket Edition** modders
- Anyone who needs a quick, valid `manifest.json`

## What is manifest.json?

Every Minecraft Bedrock resource pack and behavior pack needs a `manifest.json` in its root directory. It contains:

- **Two unique UUID v4 identifiers** — one for the pack header, one for the module
- Pack name, description, and version
- Module type (`resources` or `data`)
- Minimum engine version

Manually creating UUIDs and writing JSON is tedious and error-prone. This tool does it instantly.

## Usage

1. Enter your pack name (required)
2. Optionally fill in description, author, pack type, and versions
3. Click **Generate manifest.json**
4. Copy the JSON or download the file
5. Place `manifest.json` in your resource pack root folder

## Tech Stack

Single-page static HTML/CSS/JS. Zero dependencies. Hosted on GitHub Pages.

## License

MIT
