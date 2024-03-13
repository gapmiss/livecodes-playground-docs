---
created: 2024-03-13
title: Opening playgrounds
updated: 2024-03-13
---

### Open playground

Playgrounds can be opened via:

- `Open playground` - (*command*) and (*ribbon menu*) opens a playground fuzzy search prompt.
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-17.02.09.png" alt="screenshot of livecodes playground fuzzy search prompt" /></p></details>

- `Open playground` - (*context menu*) via right-click (`ctrl`+`click`) for playground config files (`*.JSON`).
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-17.10.19.png" alt="screenshot of file context menu" /></p></details>

- Obsidian `URI` - Create a new playground via importing of a raw JSON configuration file, easily hosted as a Github gist. The Obsidian URL expects 2 parameters, `vault` and `playgroundPath` formatted as `obsidian://playground?vault=VAULTNAME&playgroundPath=VAULT_PATH_TO_JSON` The `playgroundPath` needs to be URI encoded (see: [Obsidian Help](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI))

	e.g. `obsidian://playground?vault=VAULTNAME&playgroundPath=path/to/playground.json`

> [!IMPORTANT]
> The above context menu options are only available when all file extensions are detected by Obsidian. Open `Settings` &gt; `File and links` and enable `Detect all file extensions` ![screenshot of settings](/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-14.34.51.png)