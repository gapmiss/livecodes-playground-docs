---
created: 2024-03-13
title: Creating playgrounds
updated: 2024-03-13
---

## New playground

New playgrounds can be created via:

### Command

#### `New playground`

Opens a prompt for the playground name, markup language, style language, CSS processors, and script language.

  ![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.41.54.png]]

#### `Quick playground`

Opena a prompt for the playground name. The default markup, style, & script languages can be configured in the settings.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.43.59.png]]

### Ribbon icon

#### `Quick playground`

Click the ribbon icon <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#7852ee" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg> which opens a prompt for the playground name. The default markup, style, & script languages can be configured in the settings.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.43.59.png]]


- `Open starter playground` (*command*) opens a suggestion prompt with a list of simple starter playgrounds. These starter include `_hyperscript`, `Alpine.js`, `Angular`, `Arrow.JS`, `Astro`, `Bootstrap 5`, `Bulma (CSS)`, `C++`, `HTMX`, `Javascript`, `jQuery`, `Lemonade.JS`, `Lit`, `Lua`, `Lua (wasm)`, `Markdown`, `MDX`, `modulo.js`, `Open-props (CSS)`, `Perl`, `PHP`, `PHP (wasm)`, `Python`, `Python (wasm)`, `React`, `React Native`, `Reef.js`, `Riot.js`, `Ruby`, `SCSS`, `Solid.js`, `Stellar`, `Stencil.js`, `Svelte`, `Tailwind CSS`, `Typescript`, `VanJS`, `Vue 2`, `Vue 3 SFC`

- `New playground from Codepen` (*command*) opens a prompt for a Codepen URL and attempts to import the pen and create a new playground. Please note: this command is experimental and is dependent on Codepen's source code for presenting pens. If Codepen's changes their HTML code, the command could stop working
	<details style="margin-block: 1em;"><summary>Screenshots</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-12-08.19.31.png" alt="screenshot of new playground from codepen command" /></p><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-12-08.19.46.png" alt="screenshot of prompt for codepen URL" /></p></details>

- `Open codeblocks in Livecodes` (*command*) Live-preview and Source mode. The command parses the markdown note for codeblocks and will attempt to create a new playground with 1-3 codeblocks (markup, style, script) based on the codeblock's language. Supported languages include `html`, `mdx`, `css`, `scss`, `javascript`, `js`, `jsx`, `typescript`, `ts`, `tsx`, `astro`, `svelte`.
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-12-08.54.16.png" alt="screenshot of open codeblocks in livecodes command" /></p></details>

- `Open in Livecodes` - (*codeblock context menu*) via right-click (`ctrl`+`click`) in supported fenced code blocks. Reading mode ONLY. Supported languages include `html`, `mdx`, `css`, `scss`, `javascript`, `js`, `jsx`, `typescript`, `ts`, `tsx`, `astro`, `svelte`.
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-12.01.55.png" alt="screenshot of open codeblocks in livecodes context menu" /></p></details>

- `Open in Livecodes` - (*file context menu*) via right-click (`ctrl`+`click`) for supported file extensions. Supported extensions include `html`, `mdx`, `css`, `scss`, `js`, `jsx`, `ts`, `tsx`, `astro`, `svelte`.
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-12.35.49.png" alt="screenshot of file context menu" /></p></details>

- `Open in Livecodes` - (*folder context menu*) via right-click (`ctrl`+`click`) for supported file extensions. Supported extensions include `html`, `mdx`, `css`, `scss`, `js`, `jsx`, `ts`, `tsx`, `astro`, `svelte`. To activate the menu, the folder must have 1-3 files with the supported extensions. e.g. (`index.html`, `style.css`, `main.js`)
	<details style="margin-block: 1em;"><summary>Screenshot</summary><p><img src="/assets/img/LIVECODES-Obsidian-v1.5.8-2024-03-05-12.33.31.png" alt="screenshot of file context menu" /></p></details>

- Obsidian `URI` - Create a new playground via importing of a raw JSON configuration file, easily hosted as a Github gist. The Obsidian URL expects 2 parameters, `vault` and `gistUrl` formatted as `obsidian://playground?vault=VAULTNAME&gistUrl=RAW_JSON_URL` The `gistUrl` needs to be URI encoded (see: [Obsidian Help](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI))

	e.g. `obsidian://playground?vault=Playground&gistUrl=https%3A%2F%2Fgist.githubusercontent.com%2Fgapmiss%2Ff558657bcde37c677724004c36ed8dcd%2Fraw%2Ff8a7173bbd17d0886534c2f2017385a5fb3cff48%2FJavascript_starter.json`


---

[[getting-started|Previous: Getting started]] [[opening-playgrounds|Next: Opening playgrounds]]