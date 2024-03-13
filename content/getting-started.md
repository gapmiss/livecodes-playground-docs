---
created: 2024-03-13
title: Getting started
updated: 2024-03-13
---

## Installation

### Community plugins

1. [Obsidian.md/plugins](https://obsidian.md/plugins?id=livecodes-playground) or
2. Open *Settings* > *Community Plugins* > *Browse*
3. Search for "livecodes"

### via BRAT (Beta Reviewer's Auto-update Tool)

1. Ensure [BRAT](https://github.com/TfTHacker/obsidian42-brat) is installed
2. Trigger the command `Obsidian42 - BRAT: Add a beta plugin for testing`
3. Enter this repository, `gapmiss/livecodes-playground`
4. Enable _Livecodes_ plugin in community plugin list

### Manually

1. download the latest [release archive](https://github.com/gapmiss/livecodes-playground/releases/)
2. uncompress the downloaded archive
3. move the `livecodes-playground` folder to `/path/to/vault/.obsidian/plugins/`
4. Settings > Community plugins > reload **Installed plugins**
5. enable plugin

or:

1. download `main.js`, `manifest.json` & `styles.css`
2. create a new folder `/path/to/vault/.obsidian/plugins/livecodes-playground`
3. move all 3 files to `/path/to/vault/.obsidian/plugins/livecodes-playground`
4. Settings > Community plugins > reload **Installed plugins**
5. enable plugin

## Usage

### Initial setup

1. create a folder inside your vault for storing playground configuration files (`*.JSON`)
	- default: `playgrounds`
2. create a folder inside your vault for storing playground markdown notes (`*.MD`)
	- default: `playgrounds/notes`