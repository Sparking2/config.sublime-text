<div align="center">

# ⚡ Sublime Text 4 Configuration

**A sleek, modern, IDE-grade developer experience crafted for high performance.**

[![Sublime Text](https://img.shields.io/badge/Sublime%20Text-4-FF9800?style=for-the-badge&logo=sublimetext&logoColor=white)](https://www.sublimetext.com/)
[![Theme](https://img.shields.io/badge/Theme-Ayu%20Light-E6B450?style=for-the-badge)](https://github.com/dempfi/ayu)
[![LSP](https://img.shields.io/badge/LSP-Enabled-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://github.com/sublimelsp/LSP)
[![Terminal](https://img.shields.io/badge/Terminal-Terminus-4CAF50?style=for-the-badge&logo=gnometerminal&logoColor=white)](https://github.com/randy3k/Terminus)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](#)

<p align="center">
  Featuring <b>Vintage (Vim) mode</b>, <b>OpenGL acceleration</b>, rich <b>LSP language ecosystems</b>, integrated <b>Debugging (DAP)</b>, and embedded terminal workflow.
</p>

---

</div>

## 🌟 Highlights

- 🎨 **Minimal & Modern UI** — Ayu Light palette, smooth caret animation, crisp typography with `A File Icon`, and sidebar anchored to the right for distraction-free coding.
- ⚡ **Maximum Performance** — Hardware OpenGL acceleration enabled, fast indexing, stippled 100-char ruler, and automated cleanup on save (trim whitespace, EOF newlines).
- 🧠 **Full Language Server Protocol (LSP)** — Type hints, formatting on save & paste, code actions, symbol renames, peek definition, and inline diagnostics.
- 🐞 **First-Class Debugging (DAP)** — Integrated debugger with familiar F-key stepping, breakpoints, and inspector panels.
- 💻 **Integrated Terminal** — Instant dropdown/panel terminal via `Terminus` bound to <kbd>Ctrl</kbd> + <kbd>`</kbd>.
- ⌨️ **Vim Emulation** — Vintage mode enabled with clipboard synchronization and control keys.

---

## 🛠️ Stack & Ecosystem

### 🧩 Language Servers & Tooling
| Language / Tech | Server / Extension | Capabilities |
| :--- | :--- | :--- |
| **Rust** | `LSP-rust-analyzer` + `file-watcher-rust` | Diagnostics, hover, auto-complete, inlay hints |
| **Go** | `LSP-gopls` | High-speed Go language server |
| **C / C++** | `LSP-clangd` | Complete C/C++ analysis & indexing |
| **TypeScript / JS** | `LSP-typescript` + `LSP-eslint` | Modern frontend & Node stack linting + checking |
| **C# / .NET** | `LSP-OmniSharp` | Rich .NET analysis |
| **Web (HTML / CSS)** | `LSP-html`, `LSP-css` | Tag completion, CSS property intelligence |
| **Data / Config** | `LSP-json` | Schema-backed validation and autocomplete |

### 📦 Key Packages
- [**Ayu**](https://github.com/dempfi/ayu) — Elegant, clean aesthetic.
- [**Terminus**](https://github.com/randy3k/Terminus) — Full-featured xterm-powered terminal inside Sublime.
- [**Debugger**](https://github.com/daveleroy/sublime_debugger) — Graphical Debug Adapter Protocol client.
- [**GitGutter**](https://github.com/jisaacks/GitGutter) — Real-time git diff markers in the gutter.
- [**Origami**](https://github.com/SublimeText/Origami) — Advanced pane and window splitting flexibility.
- [**SideBarEnhancements**](https://github.com/titoBouzout/SideBarEnhancements) — Contextual filesystem operations from the sidebar.
- [**BracketHighlighter**](https://github.com/facelessuser/BracketHighlighter) — Bracket, tag, and quote matching.
- [**DocBlockr**](https://github.com/spadgos/sublime-jsdocs) — Instant docstring generation.

---

## ⌨️ Essential Keybindings

### 🐞 Debugging (DAP)
| Shortcut | Action |
| :--- | :--- |
| <kbd>F5</kbd> | Open Debugger / Start |
| <kbd>F9</kbd> | Toggle Breakpoint |
| <kbd>F10</kbd> | Step Over |
| <kbd>F11</kbd> | Step Into |
| <kbd>Shift</kbd> + <kbd>F11</kbd> | Step Out |

### 🧠 LSP & Navigation
| Shortcut | Action |
| :--- | :--- |
| <kbd>F12</kbd> | Go to Definition |
| <kbd>Shift</kbd> + <kbd>F12</kbd> | Find Symbol References |
| <kbd>F2</kbd> | Rename Symbol |
| <kbd>Ctrl</kbd> + <kbd>.</kbd> / <kbd>Alt</kbd> + <kbd>Enter</kbd> | Quick Fix / Code Actions |
| <kbd>Ctrl</kbd> + <kbd>K</kbd>, <kbd>Ctrl</kbd> + <kbd>I</kbd> | Hover Documentation |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd> | Toggle Diagnostics Panel |

### 💻 Terminal
| Shortcut | Action |
| :--- | :--- |
| <kbd>Ctrl</kbd> + <kbd>\`</kbd> | Toggle Terminus Panel |

---

## 🚀 Installation & Sync

Clone this repository directly into your Sublime Text `User` packages directory:

### Linux
```bash
git clone git@github.com:Sparking2/config.sublime-text.git ~/.config/sublime-text/Packages/User
```

### macOS
```bash
git clone git@github.com:Sparking2/config.sublime-text.git ~/Library/Application\ Support/Sublime\ Text/Packages/User
```

### Windows (PowerShell)
```powershell
git clone git@github.com:Sparking2/config.sublime-text.git "$env:APPDATA\Sublime Text\Packages\User"
```

> **Note**: Sublime Text's **Package Control** will automatically detect `Package Control.sublime-settings` on startup and begin downloading and installing all required packages and LSP servers.

---

## ⚙️ Configuration Notes

- **Sidebar on Right**: `sidebar_on_right: true` keeps code left-aligned and stable when toggling files.
- **Tab Policy**: Spaces (2-space indent) with tab-to-space translation enabled.
- **Vim Keys**: Vintage mode uses system clipboard (`vintage_use_clipboard: true`) and starts in command mode.
- **Formatting**: Code is automatically formatted on paste and save through active LSP servers.

---

<div align="center">
  <sub>Maintained with ❤️ by <a href="https://github.com/Sparking2">Sparking2</a></sub>
</div>
