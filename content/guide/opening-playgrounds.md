---
created: 2024-03-13
title: Opening playgrounds
description: Opening a playground with Livecodes Playground, a client-side code editor plugin for Obsidian.md.
updated: 2024-03-13
---

## Open playground

Playgrounds can be opened via:

### Command

### `Open playground`

Opens a playground fuzzy search prompt:

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-17.02.09.png]]

### Ribbon icon

#### `Open playground`

Click the ribbon icon <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#7852ee" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code-2"><path d="M4 22h14a2 2 0 0 0 2-2V7l-5-5H6a2 2 0 0 0-2 2v4"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/><path d="m5 12-3 3 3 3"/><path d="m9 18 3-3-3-3"/></svg> which opens a playground fuzzy search prompt:

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-17.02.09.png]]

### File explorer context menu

#### `Open playground`

Right-click (`ctrl`+`click`) playground config files (`*.JSON`) inside of the `playground` folder (see: [[getting-started#initial=setup|Getting started]]).

  ![[LIVECODES-Obsidian-v1.5.8-2024-03-05-17.10.19.png]]

> [!IMPORTANT]
> The above context menu options are only available when all file extensions are detected by Obsidian. Open `Settings` &gt; `File and links` and enable `Detect all file extensions` ![screenshot of settings](LIVECODES-Obsidian-v1.5.8-2024-03-05-14.34.51.png)

### Obsidian URI

#### Obsidian `URI`

Create a new playground via JSON configuration file path. The Obsidian URL expects 2 parameters, `vault` and `playgroundPath` formatted as `obsidian://playground?vault=VAULTNAME&playgroundPath=VAULT_PATH_TO_JSON` The `URI` needs to be URI encoded (see: [Obsidian Help](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI))

For example: `obsidian://playground?vault=VAULTNAME&playgroundPath=playgrounds/playground.json`
