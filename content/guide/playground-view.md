---
created: 2024-03-15
title: Playground view
---

![[LIVECODES-Obsidian-v1.5.8-2024-03-15-18.10.58.png]]

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-eye"><path d="M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7Z"/><circle cx="12" cy="12" r="3"/></svg> Watching</h2>

Indicates that watching is enabled, which watches for playground changes, then updates and saves the corresponding playground configuration file (JSON).

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="red" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-eye-off"><path d="M9.88 9.88a3 3 0 1 0 4.24 4.24"/><path d="M10.73 5.08A10.43 10.43 0 0 1 12 5c7 0 10 7 10 7a13.16 13.16 0 0 1-1.67 2.68"/><path d="M6.61 6.61A13.526 13.526 0 0 0 2 12s3 7 10 7a9.74 9.74 0 0 0 5.39-1.61"/><line x1="2" x2="22" y1="2" y2="22"/></svg> Not watching</h2>

Indicates that watching is disabled.                                                                                                   

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-square-pen"><path d="M12 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"/><path d="M18.375 2.625a2.121 2.121 0 1 1 3 3L12 15l-4 1 1-4Z"/></svg> Create note</h2>

Create a markdown note using the markdown template configured in the settings.

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-code-2"><path d="M4 22h14a2 2 0 0 0 2-2V7l-5-5H6a2 2 0 0 0-2 2v4"/><path d="M14 2v4a2 2 0 0 0 2 2h4"/><path d="m5 12-3 3 3 3"/><path d="m9 18 3-3-3-3"/></svg> Save as new playground</h2>

The new playground will be opened in a new playground view.

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code-xml"><path d="m18 16 4-4-4-4"/><path d="m6 8-4 4 4 4"/><path d="m14.5 4-5 16"/></svg> Save as HTML</h2>

Save playground results to HTML. A prompt will ask where to save the HTML file on your device.

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"/><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"/></svg> Copy HTML to clipboard</h2>

Copy playground results HTML to the clipboard.

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg> Copy share URL to clipboard</h2>

The generated URL encodes the playground configuration in a base-64-encoded compressed query string. This step is generated locally without sending the code to any server. However, depending on the size of the playground, the URL can be very long.

If **Short share URL** is enabled in settings, a short share URL will be generated.

This requires sending the playground configuration (**including source code**) to a server that saves the code and provides a short Id which can be used to retrieve the playground.

See [Livecodes documentation](https://livecodes.io/docs/features/share) page on sharing for further up-to-date details.


<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-github"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg> Create Github gist</h2>

Create a gist which optionally consists of a Livecodes.io playground link and 3 files.

1. The HTML results (`.html`)
2. The playground configuration file (`.json`)
3. A markdown file (`.md`) using the markdown template configured in the settings.

3 URLs are copied to your clipboard and printed to the developer console.

1. link to the gist
2. link to the Livecodes' PUBLIC url which can be used to share your playground.
3. link to open the playground in Obsidian

![[LIVECODES-Obsidian-v1.5.8-2024-03-16-14.05.25.png]]

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-sun"><circle cx="12" cy="12" r="4"/><path d="M12 2v2"/><path d="M12 20v2"/><path d="m4.93 4.93 1.41 1.41"/><path d="m17.66 17.66 1.41 1.41"/><path d="M2 12h2"/><path d="M20 12h2"/><path d="m6.34 17.66-1.41 1.41"/><path d="m19.07 4.93-1.41 1.41"/></svg> <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-moon"><path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"/></svg> Set theme mode</h2>

Sets the playground theme to light/dark mode.

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-folder-cog"><circle cx="18" cy="18" r="3" /><path d="M10.3 20H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h3.9a2 2 0 0 1 1.69.9l.81 1.2a2 2 0 0 0 1.67.9H20a2 2 0 0 1 2 2v3.3" /><path d="m21.7 19.4-.9-.3" /><path d="m15.2 16.9-.9-.3" /><path d="m16.6 21.7.3-.9" /><path d="m19.1 15.2.3-.9" /><path d="m19.6 21.7-.4-1" /><path d="m16.8 15.3-.4-1" /><path d="m14.3 19.6 1-.4" /><path d="m20.7 16.8 1-.4" /></svg> External resources</h2>


URLs to external CSS **stylesheets** and JS **scripts** can be added to the playground. URLs to stylesheets/scripts should be added each in a separate line. Stylesheets and scripts are loaded in the result page before editor codes. Thus, CSS properties defined in external stylesheets can be overriden in the style editor. Global javascript variables defined in external scripts are available to code in the script editor.

Choice of **CSS presets**, currently [Normalize.css](https://necolas.github.io/normalize.css/) and [Reset CSS](https://meyerweb.com/eric/tools/css/reset/).

![[LIVECODES-Obsidian-v1.5.8-2024-03-16-14.05.40.png]]

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-info"><circle cx="12" cy="12" r="10" /><path d="M12 16v-4" /><path d="M12 8h.01" /></svg> Playground settings</h2>

1.  Title: used in result title tag and meta/title tag.
2. Description: used in result meta/description tag.
3. Tags: used when creating a playground note.
4. `<head>` content added to the result `<head>` element.

Default:  
`<meta charset="UTF-8" />`
`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`

5. **htmlAttrs:** attributes added to the result pane `<html>` element. It can be an object or a string.

Example:  
`{ lang: 'en', class: 'dark' }` or `lang="en" class="dark"` 
becomes  
`<html lang="en" class="dark">`

Default: `lang="en" class=""`

![[LIVECODES-Obsidian-v1.5.8-2024-03-16-14.05.57.png]]

<h2><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-help"><circle cx="12" cy="12" r="10" /><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3" /><path d="M12 17h.01" /></svg> Help</h2>


In-app help modal with the same above information.



---

[[opening-playgrounds|Previous: Opening playgrounds]]

[[plugin-settings|Next: Plugin settings]]
