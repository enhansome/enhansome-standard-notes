# Awesome Standard Notes with stars

A curated list of tools and information relating to [Standard Notes](https://standardnotes.com/).

[Contribution guidelines](CONTRIBUTING.md) · [Official plugins](https://github.com/standardnotes/plugins) ⭐ 124 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-05 · [Discord](https://discord.gg/9VNW3kK554)

## Contents

* [Guides](#guides)
* [Extensions](#extensions)
  * [Themes](#themes)
  * [Editors](#editors)
  * [Components](#components)
  * [Fonts](#fonts)
* [Tools](#tools)
  * [Browser](#browser)
  * [Command Line](#command-line)
  * [Importers, Exporters, and Converters](#importers-exporters-and-converters)
* [Libraries](#libraries)
* [Servers](#servers)
* [Clients](#clients)
* [Status Labels](#status-labels)

## Guides

* [Self-Hosting on ARM / Raspberry Pi](https://github.com/antonheitz/standard-notes-arm) ⭐ 10 | 🐛 0 | 📅 2023-01-22 - Run Standard Notes on ARM hardware.
* [Editor Extension Template](https://github.com/nienow/sn-extension-template) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-01 - Starter template for building editor extensions.
* [Standard Notes Help](https://standardnotes.com/help) - Official help center.
* [Self-Hosting Standard Notes](https://standardnotes.com/help/47/can-i-self-host-standard-notes) - Official self-hosting guide.
* [Introduction to Plugins](https://standardnotes.com/help/plugins/intro) - Official plugin development overview.
* [Building a Theme Plugin](https://standardnotes.com/help/plugins/themes) - Official guide to creating themes.
* [Self-Hosting Extensions with Docker Compose](https://return2.net/dockerize-standard-notes-extensions/) - Host community extensions with Docker.
* [Install Standard Notes (AppImage) on Linux](https://www.tekbyte.net/integrating-standard-notes-into-linux/) - Integrate the AppImage desktop client on Linux.
* [How to Host Standard Notes Themes](https://blog.gunderson.tech/29891/how-to-host-standard-notes-themes) - Host and install custom themes.
* [Creating Editor Extensions](https://randombits.dev/standard-notes/creating-extensions) - Walkthrough for building editor extensions.
* [Installing Extensions](https://randombits.dev/standard-notes/installing-extensions) - How to install third-party extensions.

## Extensions

> Install custom extensions via Preferences → General → Advanced Options. Many project READMEs still show outdated install steps.

### Themes

* [Gruvbox Dark](https://github.com/christianhans/sn-gruvbox-dark-theme) ⭐ 67 | 🐛 4 | 🌐 SCSS | 📅 2024-07-10 - Based on the gruvbox Vim theme.
* [Pure Black](https://github.com/christianhans/sn-pure-black-theme) ⭐ 32 | 🐛 1 | 🌐 SCSS | 📅 2024-06-12 **\[Unmaintained]** - OLED-friendly pure black theme.
* [Dracula](https://github.com/dracula/standard-notes) ⭐ 24 | 🐛 1 | 🌐 SCSS | 📅 2022-07-30 - Dark theme based on the Dracula color scheme.
* [Muted Dark](https://github.com/ntran/sn-theme-muteddark) ⭐ 19 | 🐛 2 | 🌐 SCSS | 📅 2022-12-06 - Dark theme with muted, non-vivid colors.
* [Callisto](https://github.com/lissy93/callisto-theme-standard-notes) ⭐ 16 | 🐛 3 | 🌐 CSS | 📅 2026-09-13 - Dusty navy and teal palette.
* [VS Code Dark](https://github.com/marcolaux/sn-theme-vscode) ⭐ 14 | 🐛 3 | 🌐 CSS | 📅 2026-03-26 - Inspired by the VS Code Dark theme.
* [Markdown Monospace](https://github.com/DanielNetoP/markdown-monospace) ⚠️ Archived **\[Archived]** - Monospace font overlay for markdown editors.
* [Writer](https://github.com/eenpadvinder/standardnotes-writer) ⭐ 11 | 🐛 1 | 📅 2020-08-21 - Distraction-free writing look with word count styling.
* [One Dark Darker](https://github.com/eenpadvinder/standardnotes-theme-one-darker) ⭐ 10 | 🐛 1 | 📅 2020-08-21 - Based on One Dark Darker for VS Code, with colored headings.
* [Horizon Dark](https://github.com/luisstd/sn-theme-horizon-dark) ⭐ 8 | 🐛 0 | 🌐 SCSS | 📅 2022-11-18 - Based on the Horizon VS Code theme.
* [Monochrome Dark](https://github.com/Parkertg/sn-theme-monochrome-dark) ⭐ 6 | 🐛 1 | 🌐 CSS | 📅 2022-11-11 - Near-monochrome dark theme.
* [Slate](https://github.com/yithian/slate-theme/) ⭐ 6 | 🐛 2 | 🌐 Go Template | 📅 2026-05-27 - Shady grey with mossy green highlights.
* [Cobalt](https://github.com/PASSK3YS/cobalt) ⭐ 4 | 🐛 0 | 🌐 CSS | 📅 2026-08-02 - Blue-inspired theme.
* [Serendipity Dark](https://github.com/luisstd/sn-theme-serendipity-dark) ⭐ 3 | 🐛 0 | 🌐 SCSS | 📅 2023-12-17 - Dark theme based on Serendipity.
* [Subtle Light](https://github.com/Parkertg/sn-theme-subtle-light) ⭐ 2 | 🐛 0 | 📅 2023-12-28 - Low-contrast light theme.
* [Tangerine](https://github.com/shompoe/sn-orange) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2023-03-23 - Orange-accented theme (updated for SN 3.9.15+).
* [Dark Sense](https://github.com/xzrelay/sn-theme-dark-sense) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2026-03-09 - Dark theme tuned for low-light writing.
* [Subtle Dark](https://github.com/Parkertg/sn-theme-subtle-dark) ⭐ 1 | 🐛 0 | 🌐 SCSS | 📅 2023-12-28 - Low-contrast dark theme.
* [Overcast](https://github.com/nienow/sn-theme-overcast) ⭐ 1 | 🐛 1 | 🌐 CSS | 📅 2025-12-08 - Simple grayscale theme.
* [Moss](https://github.com/TheMany172/SN-Moss-Theme) ⭐ 1 | 🐛 0 | 🌐 SCSS | 📅 2024-10-25 - Mossy green with orange accents.
* [Horizon Light](https://github.com/luisstd/sn-theme-horizon-light) ⭐ 0 | 🐛 0 | 🌐 SCSS | 📅 2022-03-14 - Light variant of the Horizon VS Code theme.
* [One Light Lighter](https://github.com/arturolinares/standardnotes-theme-one-lighter) ⭐ 0 | 🐛 0 | 📅 2021-02-23 - Light counterpart to One Dark Darker.
* [Catppuccin](https://github.com/JoeC-Dev/SN-catppuccin-mocha) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-05-30 - Catppuccin flavors: [Mocha](https://github.com/JoeC-Dev/SN-catppuccin-mocha) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-05-30, [Latte](https://github.com/JoeC-Dev/SN-catppuccin-latte) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-05-30, [Frappe](https://github.com/JoeC-Dev/SN-catppuccin-frappe) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-05-30, [Macchiato](https://github.com/JoeC-Dev/SN-catppuccin-macchiato) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-05-30.

### Editors

Compare selected editors in the [editor comparison](https://github.com/dataprolet/standard-notes-editor-comparison) ⭐ 0 | 🐛 0 | 📅 2026-09-15.

#### General

* [Rich Markdown Editor](https://github.com/arturolinares/sn-rme) ⭐ 147 | 🐛 18 | 🌐 JavaScript | 📅 2022-01-19 - Outline-based editor with tables, embeds, and highlights.
* [Official Plugins](https://github.com/standardnotes/plugins) ⭐ 124 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-05 - Official and community plugins directory.
* [Append Editor](https://github.com/theodorechu/append-editor) ⚠️ Archived - Append-focused Markdown editor with Textarea, CodeMirror, Outline RME, and Monaco modes.
* [Indent Editor](https://github.com/MaxLap/standard-notes-indent-editor) ⭐ 48 | 🐛 4 | 🌐 JavaScript | 📅 2026-01-10 - Outliner-style indenting editor.
* [Org Mode](https://github.com/ryanpcmcquen/standardnotes_org_mode_editor) ⭐ 39 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-12 - Org mode editor for Standard Notes.
* [Cosmos](https://github.com/nienow/cosmos) ⭐ 19 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Split a note into multiple areas, each with its own editor.
* [Quill](https://github.com/nienow/sn-quill) ⭐ 12 | 🐛 2 | 🌐 CSS | 📅 2026-08-01 - Rich text editor based on Quill.
* [TUI Markdown Editor](https://github.com/MortalHappiness/sn-tui.editor) ⚠️ Archived **\[Archived]** - Markdown editor built on Toast UI Editor.
* [Nimble Editor](https://hub.darcs.net/jandrew/sn-nimble-editor) **\[May be unavailable]** - Lightweight text editor.
* [Scratch](https://dylanonelson.github.io/sn-scratch-editor/) **\[May be unavailable]** - Rich text notes with lists, checkboxes, and hotkeys.

#### Boards and diagrams

* [Marp Editor](https://github.com/TheodoreChu/marp-editor) ⚠️ Archived **\[Archived]** - Presentation slides with Marp / Marpit Markdown.
* [Whiteboard](https://github.com/antonheitz/sn-whiteboard) ⭐ 35 | 🐛 7 | 🌐 SCSS | 📅 2023-01-11 - Freeform drawing and sticky notes via TLDraw.
* [Kanban Editor](https://github.com/corvec/sn-kanban-editor) ⭐ 33 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-02 - Kanban board that stores notes as Markdown.
* [Kanban Board](https://github.com/tryonlinux/kanban-board-sn) ⚠️ Archived **\[Archived]** - Simple Kanban board editor.
* [Mermaid](https://github.com/nienow/sn-mermaid) ⭐ 17 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-01 - Diagram editor for flow, sequence, Gantt, and more.
* [Excalidraw](https://github.com/nienow/sn-excalidraw) ⭐ 16 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-01 - Sketching editor based on Excalidraw.

#### Specialty

* [Music Editor](https://github.com/TheodoreChu/music-editor) ⚠️ Archived **\[Archived]** - Write music with VexTab and VexFlow.
* [Home Inventory](https://github.com/tryonlinux/Home-Inventory-sn) ⚠️ Archived - Catalog home inventory securely.
* [Savings Goal Tracker](https://github.com/tryonlinux/savings-goals-editor-sn) ⚠️ Archived - Prioritize and track savings goals.
* [Coin Inventory](https://github.com/tryonlinux/Coin-Inventory-sn) ⚠️ Archived - Catalog coin collections.
* [IronCalc](https://github.com/iamanaws/sn-ironcalc) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-28 - Spreadsheet editor powered by IronCalc.
* [Precious Metals](https://github.com/tryonlinux/Precious-Metals-Inventory-sn) ⚠️ Archived - Track precious metal holdings and values.

### Components

* [Pomodoro Timer](https://github.com/tryonlinux/pomodoro-sn/) ⚠️ Archived - Pomodoro timer in the editor bottom bar.

### Fonts

* [SF Pro Text](https://github.com/christianhans/sn-sf-pro-text-font) ⭐ 16 | 🐛 0 | 📅 2022-01-25 - Apple SF Pro Text font package.
* [JetBrains Mono](https://github.com/aiFdn/SN-JetBrains-Mono) ⭐ 6 | 🐛 0 | 🌐 CSS | 📅 2024-12-16 - JetBrains Mono font package.

## Tools

### Browser

* [Page Link & Title → Note](https://github.com/mllocs/standard-notes-chrome-extension) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2020-12-05 **\[Unmaintained]** - Create a note from the current page title and URL.

### Command Line

* [Open Extended](https://github.com/kylejbrk/standard-notes-open-extended) ⭐ 106 | 🐛 2 | 🌐 Python | 📅 2022-11-04 - Community-hosted catalog of installable extensions.
* [sn-cli](https://github.com/jonhadfield/sn-cli) ⭐ 94 | 🐛 0 | 🌐 Go | 📅 2026-09-22 - Manage notes, tags, and account operations from the terminal.
* [sn-dotfiles](https://github.com/jonhadfield/sn-dotfiles) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-09-25 - Sync and manage dotfiles with Standard Notes.
* [Extensions Server](https://github.com/sentriz/standardnotes-extensions) ⭐ 20 | 🐛 3 | 🌐 Go | 📅 2023-02-25 - Auto-updating Docker/Go host for extensions.
* [MCP Standard Notes](https://github.com/lozit/mcp-standardnotes) ⭐ 9 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-08 - MCP server with end-to-end encryption.

### Importers, Exporters, and Converters

* [Yarle](https://github.com/akosbalasko/yarle) ⭐ 1,807 | 🐛 91 | 🌐 TypeScript | 📅 2026-03-31 - Configurable Evernote → Markdown desktop converter.
* [evernote2md](https://github.com/wormi4ok/evernote2md) ⭐ 1,108 | 🐛 17 | 🌐 Go | 📅 2026-09-25 - Convert Evernote `.enex` exports to Markdown files.
* [Jimmy](https://github.com/marph91/jimmy) ⭐ 533 | 🐛 14 | 🌐 Python | 📅 2026-09-13 - Convert notes from many apps (including Standard Notes) to Markdown.
* [Folder Export CLI](https://github.com/BrunoBernardino/standardnotes-folder-export-cli#standard-notes-folder-export-cli---deno) ⚠️ Archived **\[Archived]** - Turn a decrypted backup into `<tag>/<note>.<ext>` folders.
* [onestandard](https://github.com/oxhacks/onestandard) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2026-04-21 - Convert OneNote notebooks to Standard Notes format.
* [Export to Folder](https://github.com/danielnetop/sn-export-to-folder) ⭐ 6 | 🐛 4 | 🌐 Go | 📅 2023-11-25 - Extract a decrypted export into tag folders and note files.
* [Day One Importer](https://github.com/ArneTR/standardnotes_day_one_importer) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2019-09-02 - Import Day One JSON exports.
* [Google Keep Converter](https://github.com/vantezzen/Google-Keep-to-Standardnotes-Converter) ⚠️ Archived **\[Archived]** - Convert Google Keep Takeout archives.
* [simplenote2standardnote](https://github.com/edas/simplenote2standardnote) ⚠️ Archived **\[Archived]** - Port Simplenote backups with dates and tags.
* [notexfr](https://github.com/rafaelespinoza/notexfr) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2026-09-02 - Convert and adapt data between note-taking services.
* [BB10 Remember Converter](https://github.com/jayb-g/bbrem2sn) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-07-18 - Convert BlackBerry 10 Remember backups to Standard Notes import format.
* [Official Google Keep Import](https://standardnotes.com/help/35/how-can-i-import-my-notes-from-google-keep) - Official Keep → Standard Notes conversion help.
* [Aegis to TokenVault](https://gist.github.com/kahnwong/e94933bb80888e4b7f75df4d90645cbe) - Format Aegis exports for the TokenVault editor.

## Libraries

* [gosn-v2](https://github.com/jonhadfield/gosn-v2) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-09-21 - Go client library for Standard Notes.
* [Standard File Client Library](https://pkg.go.dev/github.com/mdouchement/standardfile/pkg/libsf) - Go client library for the Standard File protocol.

## Servers

* [Official Sync Server](https://github.com/standardnotes/server) ⭐ 480 | 🐛 71 | 🌐 TypeScript | 📅 2026-09-21 - Official self-hostable sync server.
* [Yet Another Standardfile](https://github.com/mdouchement/standardfile) ⭐ 83 | 🐛 10 | 🌐 Go | 📅 2026-05-30 - Standard Notes–compatible server written in Go.

## Clients

* [Official App](https://github.com/standardnotes/app) ⭐ 6,635 | 🐛 95 | 🌐 TypeScript | 📅 2026-09-24 - Official web, desktop, and mobile clients.
* [Iridium](https://codeberg.org/baarkerlounger/Iridium) - Local-first Rust/GTK client (Codeberg fork; original GitHub repo is archived).
* [Flatpak](https://flathub.org/en/apps/org.standardnotes.standardnotes) - Unofficial Flatpak package.

## Status Labels

Projects may include a maintenance label:

* **\[Archived]** — Read-only; no longer maintained by the original author.
* **\[Unmaintained]** — Dormant but still accessible; may work, receives no updates.
* **\[v003 only]** — Only compatible with the legacy protocol (pre-November 2020). See [VERSIONS.md](VERSIONS.md).
* **\[May be unavailable]** — Link may be intermittently unavailable or moved.

## Related

* [standardnotes.com](https://standardnotes.com/) — Product site and apps.
* [Protocol versions](VERSIONS.md) — Client/protocol compatibility notes.
* [Discord](https://discord.gg/9VNW3kK554) — Community chat.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-26._
