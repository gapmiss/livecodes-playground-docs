---
created: 2024-03-13
title: Creating playgrounds
updated: 2024-03-14
---

## New playground

New playgrounds can be created via:

### Command

#### New playground

Opens a prompt for the playground name, markup language, style language, CSS processors, and script language.

  ![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.41.54.png]]

#### Quick playground

Opena a prompt for the playground name. The default markup, style, & script languages can be configured in the settings.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.43.59.png]]

#### Open starter playground

Opens a suggestion prompt with a list of simple starter playgrounds. These starter include : `_hyperscript`, `Alpine.js`, `Angular`, `Arrow.JS`, `Astro`, `Bootstrap 5`, `Bulma (CSS)`, `C++`, `HTMX`, `Javascript`, `jQuery`, `Lemonade.JS`, `Lit`, `Lua`, `Lua (wasm)`, `Markdown`, `MDX`, `modulo.js`, `Open-props (CSS)`, `Perl`, `PHP`, `PHP (wasm)`, `Python`, `Python (wasm)`, `React`, `React Native`, `Reef.js`, `Riot.js`, `Ruby`, `SCSS`, `Solid.js`, `Stellar`, `Stencil.js`, `Svelte`, `Tailwind CSS`, `Typescript`, `VanJS`, `Vue 2`, `Vue 3 SFC`

#### New playground from Codepen

Opens a prompt for a Codepen URL and attempts to import the pen and create a new playground.

![[LIVECODES-Obsidian-v1.5.8-2024-03-12-08.19.31.png]]

![[LIVECODES-Obsidian-v1.5.8-2024-03-12-08.19.46.png]]

> [!attention]+ Notice:
> The `New playground from Codepen` command is experimental and is dependent on Codepen's source code for presenting pens. If Codepen's changes their HTML code, the command could stop working.

#### Open codeblocks in Livecodes

Live-preview and Source mode. The command parses the markdown note for codeblocks and will attempt to create a new playground with 1-3 codeblocks (markup, style, script) based on the codeblock's language. Supported languages include `html`, `mdx`, `css`, `scss`, `javascript`, `js`, `jsx`, `typescript`, `ts`, `tsx`, `astro`, `svelte`.

![[LIVECODES-Obsidian-v1.5.8-2024-03-12-08.54.16.png]]

### Ribbon icon

#### Quick playground

Click the ribbon icon <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#7852ee" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg> which opens a prompt for the playground name. The default markup, style, & script languages can be configured in the settings.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.43.59.png]]

### File explorer context menu

#### Open in Livecodes

Via right-click (`ctrl`+`click`) for supported file extensions. Supported extensions include `html`, `mdx`, `css`, `scss`, `js`, `jsx`, `ts`, `tsx`, `astro`, `svelte`.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.35.49.png]]

### Codeblock context menu

#### Open in Livecodes

Via right-click (`ctrl`+`click`) in supported fenced codeblocks. Reading mode ONLY. Supported languages include `html`, `mdx`, `css`, `scss`, `javascript`, `js`, `jsx`, `typescript`, `ts`, `tsx`, `astro`, `svelte`.

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.01.55.png]]

### File explorer folder context menu

#### Open in Livecodes

Via right-click (`ctrl`+`click`) for folders containing supported files. Supported file extensions include `html`, `mdx`, `css`, `scss`, `js`, `jsx`, `ts`, `tsx`, `astro`, `svelte`. To activate the menu, the folder must have 1-3 files with the supported extensions. e.g. (`index.html`, `style.css`, `main.js`)

![[LIVECODES-Obsidian-v1.5.8-2024-03-05-12.33.31.png]]


### Obsidian URI

#### `gistUrl`

Create a new playground via importing of a raw JSON configuration file, easily hosted as a Github gist. The Obsidian URI expects 2 parameters, `vault` and `gistUrl` formatted as `obsidian://playground?vault=VAULTNAME&gistUrl=RAW_JSON_URL` The `URI` needs to be URI encoded (see: [Obsidian Help](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI))

For example: `obsidian://playground?vault=Playground&gistUrl=https%3A%2F%2Fgist.githubusercontent.com%2Fgapmiss%2Ff558657bcde37c677724004c36ed8dcd%2Fraw%2Ff8a7173bbd17d0886534c2f2017385a5fb3cff48%2FJavascript_starter.json`


---

[[getting-started|Previous: Getting started]]

[[opening-playgrounds|Next: Opening playgrounds]]