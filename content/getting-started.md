---
created: 2024-03-13
title: "Getting started"
description: "Getting started with Livecodes Playground, a client-side code editor plugin for Obsidian.md."
---

## Installation

### Community plugins

1. [Obsidian.md/plugins](https://obsidian.md/plugins?id=livecodes-playground) or
2. Open *Settings* > *Community Plugins* > *Browse*
3. Search for "livecodes"
4. Install plugin
5. Enable plugin

### BRAT (Beta Reviewer's Auto-update Tool)

1. Ensure [BRAT](https://github.com/TfTHacker/obsidian42-brat) is installed
2. Trigger the command `Obsidian42 - BRAT: Add a beta plugin for testing`
3. Enter this repository, `gapmiss/livecodes-playground`
4. Enable _Livecodes_ plugin in community plugin list

### Manually

1. Download the latest [release archive](https://github.com/gapmiss/livecodes-playground/releases/)
2. Uncompress the downloaded archive
3. Move the `livecodes-playground` folder to `/path/to/vault/.obsidian/plugins/`
4. Settings > Community plugins > reload **Installed plugins**
5. Enable plugin

or:

1. Download `main.js`, `manifest.json` & `styles.css`
2. Create a new folder `/path/to/vault/.obsidian/plugins/livecodes-playground`
3. Move all 3 files to `/path/to/vault/.obsidian/plugins/livecodes-playground`
4. Settings > Community plugins > reload **Installed plugins**
5. Enable plugin

## Usage

### Initial setup

1. Create a folder inside your vault for storing playground configuration files (`*.json`)
	- Default: `playgrounds`
2. Create a folder inside your vault for storing playground markdown notes (`*.md`)
	- Default: `playgrounds/notes`

---

[[index|Previous: Home]]

[[creating-playgrounds|Next: Creating playgrounds]]