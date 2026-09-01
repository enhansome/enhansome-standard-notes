# Awesome Standard Notes with stars

A curated list of tools and information relating to [Standard Notes](https://standardnotes.com/).

Please take a look at the [contribution guidelines](CONTRIBUTING.md) before suggesting any changes. You can also have your extension hosted by the [official plugins directory](https://github.com/standardnotes/plugins) ⭐ 123 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-05.

## Status Labels

This list includes projects in various maintenance states. Labels help you understand project availability:

* **\[Archived]** - Read-only repository, no longer maintained by the original author
* **\[Unmaintained]** - Repository is dormant but still accessible; may work but receives no updates
* **\[v003 only]** - Only compatible with legacy Standard Notes protocol (pre-November 2020)
* **\[May be unavailable]** - Link may be intermittently unavailable or moved

### Contents

* [Awesome Standard Notes](#awesome-standard-notes)
  * [Contents](#contents)
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
  * [Listed](#listed)
    * [Themes](#themes-1)

## Guides

* [Standard Notes Help](https://standardnotes.com/help)
* [Self-Hosting Standard Notes](https://standardnotes.com/help/47/can-i-self-host-standard-notes)
* [Self-Hosting Standard Notes on your own ARM Server like the Raspberry Pi](https://github.com/antonheitz/standard-notes-arm) ⭐ 10 | 🐛 0 | 📅 2023-01-22
* [Self-Hosting Standard Notes Extensions with Docker-Compose](https://return2.net/dockerize-standard-notes-extensions/)
* [Install Standard Notes (AppImage) on Linux](https://tekbyte.net/2020/integrating-standard-notes-into-linux/)
* [How to Host Standard Notes Themes](https://blog.gunderson.tech/29891/how-to-host-standard-notes-themes)
* [Creating Editor Extensions](https://randombits.dev/standard-notes/creating-extensions)
* [Installing Extensions](https://randombits.dev/standard-notes/installing-extensions)

## Extensions

> Many of the extensions have outdated instructions in their README for where to install extensions. Go to Preferences -> General -> Advanced Options to install  extensions.

### Themes

* [Gruvbox Dark Theme](https://github.com/christianhans/sn-gruvbox-dark-theme) ⭐ 67 | 🐛 5 | 🌐 SCSS | 📅 2024-07-10 - Based on colors from the gruvbox theme for Vim.
* [Pure Black Theme](https://github.com/christianhans/sn-pure-black-theme) ⭐ 32 | 🐛 1 | 🌐 SCSS | 📅 2024-06-12 **\[Unmaintained]** - Theme for Standard Notes. Optimized for OLED devices such as iPhone X.
* [Dracula theme](https://github.com/dracula/sn-theme-dracula) ⭐ 24 | 🐛 1 | 🌐 SCSS | 📅 2022-07-30 - A dark theme for Standard Notes.
* [Muted Dark Theme](https://github.com/ntran/sn-theme-muteddark) ⭐ 19 | 🐛 2 | 🌐 SCSS | 📅 2022-12-06 - Standard Notes dark theme with non-vivid, muted colors
* [vscode-theme](https://github.com/hyphone/sn-theme-vscode) ⭐ 14 | 🐛 3 | 🌐 CSS | 📅 2026-03-26 **\[Unmaintained]** - A theme for Standard Notes inspired by the VS Code Dark theme that is easy on the eyes.
* [Monospace for Markdown Editors](https://github.com/DanielNetoP/markdown-monospace) ⚠️ Archived - Monospace font for Standard Notes markdown editors (Toggle on top of other themes)
* [Standard Notes Writer](https://github.com/eenpadvinder/standardnotes-writer) ⭐ 11 | 🐛 1 | 📅 2020-08-21 - Distraction free writing with word count
* [One Dark Darker](https://github.com/eenpadvinder/standardnotes-theme-one-darker) ⭐ 10 | 🐛 1 | 📅 2020-08-21 - Based on the One Dark Darker theme for VS Code, with colored headings and some UI tweaks.
* [Horizon Dark Theme](https://github.com/luisstd/sn-theme-horizon-dark) ⭐ 8 | 🐛 0 | 🌐 SCSS | 📅 2022-11-18 - Based on colors from the Horizon theme for VSCode.
* [Monochrome Dark Theme](https://github.com/Parkertg/sn-theme-monochrome-dark) ⭐ 6 | 🐛 1 | 🌐 CSS | 📅 2022-11-11
* [Slate Theme](https://github.com/yithian/slate-theme/) ⭐ 6 | 🐛 2 | 🌐 Go Template | 📅 2026-05-27 - A Standard Notes theme with shady grey and mossy green highlights.
* [Serendipity Dark Theme](https://github.com/luisstd/sn-theme-serendipity-dark) ⭐ 3 | 🐛 0 | 🌐 SCSS | 📅 2023-12-17 - Dark theme based on the Serendipity theme.
* [Subtle Light Theme](https://github.com/Parkertg/sn-theme-subtle-light) ⭐ 2 | 🐛 0 | 📅 2023-12-28
* [Tangerine Theme](https://github.com/shompoe/sn-orange) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2023-03-23 - Newly updated for SN 3.9.15 onward. New installation link. Please re-install
* [Dark Sense Theme](https://github.com/rsharuru/sn-theme-dark-sense) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2026-03-09 - Perfect for writing in the dark.
* [Subtle Dark Theme](https://github.com/Parkertg/sn-theme-subtle-dark) ⭐ 1 | 🐛 0 | 🌐 SCSS | 📅 2023-12-28
* [Overcast Theme](https://github.com/nienow/sn-theme-overcast) ⭐ 1 | 🐛 1 | 🌐 CSS | 📅 2025-12-08 - A simple grayscale theme.
* [Moss Theme](https://github.com/TheMany172/SN-Moss-Theme) ⭐ 1 | 🐛 0 | 🌐 SCSS | 📅 2024-10-25 - Mossy green with orange accents - dark theme.
* [Horizon Light Theme](https://github.com/luisstd/sn-theme-horizon-light) ⭐ 0 | 🐛 0 | 🌐 SCSS | 📅 2022-03-14 - Based on colors from the Horizon Theme for VSCode.
* [One Light Lighter](https://github.com/arturolinares/standardnotes-theme-one-lighter) ⭐ 0 | 🐛 0 | 📅 2021-02-23 - Based on One Dark Darker (listed above), but with a light background.

### Editors

> A comparison of selected text editors can be found [here](https://github.com/dataprolet/standard-notes-editor-comparison) ⭐ 0 | 🐛 0 | 📅 2025-08-15.

* [Rich Markdown Editor](https://github.com/arturolinares/sn-rme) ⭐ 146 | 🐛 18 | 🌐 JavaScript | 📅 2022-01-19 - The awesome editor developed by [Outline](https://www.getoutline.com/). Supports tables, YouTube embeds and text highlights.
* [Official Extensions](https://github.com/standardnotes/plugins) ⭐ 123 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-05
* [Append Editor](https://github.com/theodorechu/append-editor) ⚠️ Archived - Append to your notes. Write GitHub Flavored Markdown via four different editing modes: Plain Textarea with spell check, in-line formatting provided by [CodeMirror](https://github.com/codemirror/codemirror) ⚠️ Archived, what-you-see-is-what-you-get live formatting provided by the [Rich Markdown Editor](https://github.com/outline/rich-markdown-editor) ⚠️ Archived developed by [Outline](https://www.getoutline.com/), and in-line syntax highlighting provided by the [Monaco Editor](https://github.com/microsoft/monaco-editor) ⭐ 46,632 | 🐛 848 | 🌐 JavaScript | 📅 2026-08-27. In addition to GFM, the Plain Textarea, CodeMirror, and Monaco modes support KaTeX, table of contents, footnotes, in-line HTML, and emoji codes. The Monaco mode also supports autocompletion, search and replace, and syntax highlighting for over 60 programming languages. The Append Editor has built-in support for printing notes and per-note font sizes, font families, and custom CSS.
* [Standard Notes Indent Editor](https://github.com/MaxLap/standard-notes-indent-editor) ⭐ 48 | 🐛 4 | 🌐 JavaScript | 📅 2026-01-10
* [Org mode for Standard Notes](https://github.com/ryanpcmcquen/standardnotes_org_mode_editor) ⭐ 39 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-12
* [Marp Editor](https://github.com/TheodoreChu/marp-editor) ⚠️ Archived - Create presentation slides with [Marp](https://marp.app) and [Marpit Markdown](https://marpit.marp.app/markdown).
* [Whiteboard](https://github.com/antonheitz/sn-whiteboard) ⭐ 35 | 🐛 7 | 🌐 SCSS | 📅 2023-01-11 - This editor utilizes TLDraw to enable you to freely draw and write, add sticky notes and shapes. Works on Desktop and Mobile.
* [Kanban Editor](https://github.com/corvec/sn-kanban-editor) ⭐ 32 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-02 - Kanban Editor for Standard Notes. It integrates rcdexta/react-trello, a Kanban board editor, and saves your notes in Markdown so that you can easily read them, export them to Listed, etc.
* [Cosmos](https://github.com/nienow/cosmos) ⭐ 19 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Split a note into multiple areas. Each area can use a different editor. Install new editors more easily.
* [Kanban Board](https://github.com/tryonlinux/kanban-board-sn) ⚠️ Archived **\[Archived]** - A simple Kanban style board editor for Standard Notes.
* [Mermaid](https://github.com/nienow/sn-mermaid) ⭐ 17 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-01 - A diagram editor. Create Flow, Sequence, Class, State, Gantt, Pie, ER, User Journey, Git, Mindmap, or Quadrant diagrams.
* [Excalidraw](https://github.com/nienow/sn-excalidraw) ⭐ 16 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-01 - A drawing/sketching editor that uses the Excalidraw library.
* [Quill](https://github.com/nienow/sn-quill) ⭐ 12 | 🐛 2 | 🌐 CSS | 📅 2026-08-01 - A rich text editor that uses the Quill library.
* [Music Editor](https://github.com/TheodoreChu/music-editor) ⚠️ Archived - Write music with [VexTab](https://github.com/0xfe/vextab) ⭐ 650 | 🐛 67 | 🌐 JavaScript | 📅 2026-04-15 and [VexFlow](https://github.com/0xfe/vexflow) ⭐ 4,366 | 🐛 52 | 🌐 TypeScript | 📅 2025-03-05.
* [Home Inventory](https://github.com/tryonlinux/Home-Inventory-sn) ⚠️ Archived - An extension editor for Standard Notes to catalog home inventory (great for insurance purposes) in a solid and secure way.
* [Savings Goal Tracker](https://github.com/tryonlinux/savings-goals-editor-sn) ⚠️ Archived - This is an editor for Standard Notes that allows you to track your savings goals within the app. You can add your goals and prioritize them by dragging and dropping them in the order you wish.
* [Coin Inventory](https://github.com/tryonlinux/Coin-Inventory-sn) ⚠️ Archived - An extension editor for Standard Notes to catalog coin inventory in a solid and secure way. Numismatists rejoice!
* [Tui Markdown Editor](https://github.com/MortalHappiness/sn-tui.editor) ⚠️ Archived - A markdown editor using [Toast UI Markdown Editor](https://github.com/nhn/tui.editor) ⭐ 18,026 | 🐛 643 | 🌐 TypeScript | 📅 2024-08-01.
* [Precious Metals](https://github.com/tryonlinux/Precious-Metals-Inventory-sn) ⚠️ Archived - An extension editor for Standard Notes to keep track of what precious metals you have and their values.
* [Standard Notes Nimble Editor](https://hub.darcs.net/jandrew/sn-nimble-editor) **\[May be unavailable]**
* [Flashcard Editor](https://github.com/TheodoreChu/flashcard-editor)
* [Scratch](https://dylanonelson.github.io/sn-scratch-editor/) **\[May be unavailable]** - Scratch includes most of the text editing features you would expect for taking notes, like lists, checkboxes, basic text formatting, smart copy/paste, and hotkeys.

### Components

* [Pomodoro Timer](https://github.com/tryonlinux/pomodoro-sn/) ⚠️ Archived - Pomodoro timer for Standard Notes in the Editor Bottom Bar

### Fonts

* [SF Pro Text](https://github.com/christianhans/sn-sf-pro-text-font) ⭐ 16 | 🐛 0 | 📅 2022-01-25
* [JetBrains Mono](https://github.com/aiFdn/SN-JetBrains-Mono) ⭐ 6 | 🐛 0 | 🌐 CSS | 📅 2024-12-16

## Tools

### Browser

* [Standard Notes Clipper](https://github.com/johnjones4/Standard-Notes-Clipper) ⚠️ Archived **\[Archived]** - A browser add-on (Firefox and Chrome) that allows you to clip web pages to your Standard Notes account. 🔻Please note this reported [issue](https://github.com/johnjones4/Standard-Notes-Clipper/issues/34) ⚠️ Archived
* [Page Link & Title → Note](https://github.com/mllocs/standard-notes-chrome-extension) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2020-12-05 **\[Unmaintained]** - Takes the title and link of a web page and creates a note using the same title and inserts the link into the body.

### Command Line

* [Extensions Repository Builder](https://github.com/iganeshk/standardnotes-extensions) ⚠️ Archived **\[Archived]** - Host Standard Notes extensions on your own server.
* [standardnotes-fs](https://github.com/tannercollin/standardnotes-fs) ⚠️ Archived **\[Archived]** - Mount your Standard Notes account as a filesystem and edit your notes as plain text files. **Note: No longer functional.** <sub><sup>([SN version 003 only](VERSIONS.md "Not compatible with version 004 accounts: those created or upgraded after Nov 2020"))</sub></sup>
* [sn-cli](https://github.com/jonhadfield/sn-cli) ⭐ 95 | 🐛 14 | 🌐 Go | 📅 2026-05-23 - Manage notes, tags, and other account operations
* [sn-dotfiles](https://github.com/jonhadfield/sn-dotfiles) ⭐ 27 | 🐛 3 | 🌐 Go | 📅 2026-08-31 - Sync and manage dotfiles using Standard Notes

### Importers, Exporters, and Converters

* [Yarle - The ultimate converter of Evernote notes to Markdown](https://github.com/akosbalasko/yarle) ⭐ 1,797 | 🐛 85 | 🌐 TypeScript | 📅 2026-03-31 - A fully configurable cross-platform desktop application to convert your Evernote notebooks (enex files) to Markdown format.
* [evernote2md](https://github.com/wormi4ok/evernote2md) ⭐ 1,107 | 🐛 16 | 🌐 Go | 📅 2026-08-28 - Evernote2md is a CLI tool to convert Evernote notes exported in \*.enex format to a directory with markdown files.
* [Standard Notes Folder Export CLI](https://github.com/BrunoBernardino/standardnotes-folder-export-cli#standard-notes-folder-export-cli---deno) ⚠️ Archived **\[Archived]** - Simple CLI script to convert a decrypted Standard Notes Backup/Export into a structure of `<tag>/<note-title>.<file-extension>`.
* [onestandard](https://github.com/oxhacks/onestandard) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2026-04-21 - Convert notebooks from OneNote into Standard Notes format.
* [Standard Notes export to folder](https://github.com/danielnetop/sn-export-to-folder) ⭐ 6 | 🐛 4 | 🌐 Go | 📅 2023-11-25 - CLI tool to extract info from the Standard Notes decrypted export and transform it into folder based tags and notes. After the tool runs the tags will be folders and each note will be inside the respective folder.
* [Day One => Standard Notes Importer](https://github.com/ArneTR/standardnotes_day_one_importer) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2019-09-02 - Day One JSON Export Importer for Standard Notes
* [Google Keep™ to StandardNotes Converter](https://github.com/vantezzen/Google-Keep-to-Standardnotes-Converter) ⚠️ Archived **\[Archived]** - Convert Google Keep Takeout archive into Standardnotes archive
* [simplenote2standardnote](https://github.com/edas/simplenote2standardnote) ⚠️ Archived **\[Archived]** - Port a SimpleNote backup to a StandardNote one, keeping dates and tags
* [notexfr](https://github.com/rafaelespinoza/notexfr) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2025-04-23 - notexfr is a tool to convert and adapt data for transfer between note-taking services
* [BB10 Remember → Standard Notes plaintext(/super note) import format Converter](https://github.com/jayb-g/bbrem2sn) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-07-18 - A simple python program to convert BlackBerry10 Remember Notes backup(backed-up using Runisoft Ultimate Backup on BB10) to Standard Notes importable format with preserved formatting, attachments and timestamps.
* [Google Keep to Standard Notes nodeJS converter](https://standardnotes.com/help/35/how-can-i-import-my-notes-from-google-keep) - Simple NodeJS script to convert a Google Keep Takeout export into a decrypted Standard Notes backup (Now part of StandardNotes).
* [Aegis to TokenVault](https://gist.github.com/kahnwong/e94933bb80888e4b7f75df4d90645cbe) - Export secret keys and account info from Aegis, then use this python script to format it into something the TokenVault Editor can use.

## Libraries

* [gosn-v2](https://github.com/jonhadfield/gosn-v2) ⭐ 18 | 🐛 4 | 🌐 Go | 📅 2026-08-31 - A library written in Go
* [Standard File Client Library](https://godoc.org/github.com/mdouchement/standardfile/pkg/libsf) - A library written in Go

## Servers

* [Yet Another Standardfile](https://github.com/mdouchement/standardfile) ⭐ 83 | 🐛 10 | 🌐 Go | 📅 2026-05-30 - A Standard Notes Server implementation written in Go
* [Standard Notes & Docker](https://github.com/mdouchement/standardnotes) ⚠️ Archived - Dockerization of Standard File server. Used for running your own Standard Notes server

## Clients

* [Iridium](https://github.com/standardnotes/forum/issues/1135) ⭐ 220 | 🐛 618 | 📅 2023-09-30 - A local-first client written in Rust and GTK, with support for any server and offline editing <sub><sup>([SN version 003 only](VERSIONS.md "Not compatible with version 004 accounts: those created or upgraded after Nov 2020"))</sub></sup>
* [Flatpak](https://flathub.org/apps/details/org.standardnotes.standardnotes) - An unofficial Flatpak build.

## Listed

### Themes

* [Marcokai Theme](https://github.com/marcoceppi/listed-marcokai) ⭐ 5 | 🐛 0 | 🌐 CSS | 📅 2021-03-16 - A dark theme with modified monokai syntax highlighting
* [Dracula Styled Theme](https://github.com/cameronldn/sn-listed-theme-dracula) ⭐ 4 | 🐛 0 | 🌐 CSS | 📅 2020-02-24 - A Dracula Styled theme for your listed blog.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
