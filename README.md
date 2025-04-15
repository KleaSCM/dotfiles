![Typing SVG](https://readme-typing-svg.demolab.com?lines=🌒+Klea's+Dotfiles;Darkmode+Gremlin+Dev+Theme)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/klea/dotfiles?style=social)](https://github.com/klea/dotfiles/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/klea/dotfiles?style=social)](https://github.com/klea/dotfiles/network)
[![GitHub issues](https://img.shields.io/github/issues/klea/dotfiles)](https://github.com/klea/dotfiles/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/klea/dotfiles)](https://github.com/klea/dotfiles/commits/main)
[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat&logo=arch-linux&logoColor=white)](https://archlinux.org)

> 🧪 **Built for chaos. Optimized for clarity.**

![Darkmode Gremlin Theme](https://placehold.co/1200x300/0F0F0F/FFF?text=PLACEHOLDER+HEADER+IMAGE)

Welcome to my dotfiles — carefully curated chaos built on [Arch Linux](https://archlinux.org) with Plasma 6, zsh, kitty, neovim, and rofi.

## 🗂️ Structure

```
dotfiles/
├── bashrc/                  # Custom bash config dir
├── kdeglobals               # KDE global theme/colors
├── kglobalshortcutsrc       # KDE global shortcut keys
├── kitty/                   # kitty terminal config
├── nvim/                    # Neovim full config (init.lua, lua/, plugins, etc.)
├── ohmyposh/                # OhMyPosh prompt config
├── rofi/                    # Rofi theme + launcher
├── scripts/                 # All custom .sh launcher scripts
├── wallpaper/               # Static wallpapers (jpg/png)
├── zshrc/                   # ZSH config dir
└── .git/                    # Git tracking
```

## 🔗 Symlink Restore Guide

```bash
ln -sf ~/.config/nvim/              ~/dotfiles/nvim
ln -sf ~/.config/rofi/              ~/dotfiles/rofi
ln -sf ~/Documents/Scripts/         ~/dotfiles/scripts
ln -sf ~/.config/zshrc/             ~/dotfiles/zshrc
ln -sf ~/.config/bashrc/            ~/dotfiles/bashrc
ln -sf ~/.config/kitty/             ~/dotfiles/kitty
ln -sf ~/.config/ohmyposh/          ~/dotfiles/ohmyposh
ln -sf ~/.config/kdeglobals         ~/dotfiles/kdeglobals
ln -sf ~/.config/kglobalshortcutsrc ~/dotfiles/kglobalshortcutsrc
ln -sf ~/Pictures/wallpaper/        ~/dotfiles/wallpaper
```

## 🎨 Preview Screenshots

- 🔹 Terminal + Kitty
- 🔹 Neovim (init.lua + custom lua modules)
- 🔹 Rofi Launcher

## 🛠️ Scripts

### 📂 Directory Structure
```
scripts/
├── rofi_launcher.sh         # Main launcher — script selector, wallpaper mode switcher
├── fix_script_paths.sh      # Dev utility to bulk-rewrite hardcoded paths
├── Keybinds.lua             # Lua config for hotkey mapping
└── wallgremlin.sh           # Gremlin script for managing wallpapers via rofi
```

### 📂 Sorted Scripts
```
scripts/sorted/
├── admin/              # system & terminal UI mgmt tools (dashboard, cleaner, tabs, etc.)
├── apps/               # launchers for app menus and terminal apps
├── config/             # default launcher config
├── dev/                # project templates for Go, Python, C++
├── lib/                # shared functions (common.sh)
├── logs/               # execution metrics (CPU, MEM, duration)
├── tests/              # test harness for launcher validation
├── uncategorized/      # misc utilities like ClipH, SQLite, sorting
├── utils/              # permissions, troubleshooter, wallgremlin UI
└── web/                # dev tools for Flask, HTML, web menus
```

### 🔧 Execution Example
Run from rofi, or directly:
```bash
~/Documents/Scripts/rofi_launcher.sh
```

📸 [PLACEHOLDER_IMG] Gremlin Launcher UI Screenshot Here

## 🛠️ Tech Stack

- a 6.3.4 Wayland
- 🐚 ZSH + OhMyZsh + OhMyPosh
- 🧬 Kitty Terminal
- 🧠 Neovim (Lua-first)
- 🚀 Rofi with fuzzy launcher modes
- 🎨 KDE Configs: kdeglobals, kglobalshortcutsrc
- 🎭 Wallpapers via qdbus + rofi menu integration

## 📦 Install & Setup

Clone the chaos into your home:

```bash
git clone https://github.com/KleaTheGremlin/klea-dotfiles.git ~/dotfiles
```

Link your soul (and configs):

```bash
ln -s ~/dotfiles/nvim ~/.config/nvim
ln -s ~/dotfiles/rofi ~/.config/rofi
ln -s ~/dotfiles/zshrc ~/.config/zshrc
ln -s ~/dotfiles/bashrc ~/.config/bashrc
ln -s ~/dotfiles/ohmyposh ~/.config/ohmyposh
ln -s ~/dotfiles/kitty ~/.config/kitty
ln -s ~/dotfiles/kdeglobals ~/.config/kdeglobals
ln -s ~/dotfiles/kglobalshortcutsrc ~/.config/kglobalshortcutsrc
ln -s ~/dotfiles/scripts ~/Documents/Scripts
ln -s ~/dotfiles/wallpaper ~/Pictures/wallpapers
```

Optional Install supporting goodies:

```bash
sudo pacman -S rofi kitty feh mpv xwinwrap zsh oh-my-posh
yay -S plasma-hud-git
```

### Give Rofi life:

Launch the script menu with:

```bash
~/Documents/Scripts/rofi_launcher.sh
```

Or bind it to a hotkey for on demand

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3500&pause=800&color=00FF00&center=true&vCenter=true&width=700&lines=Set+up+a+systemd+user+service+(if+you're+fancy);to+launch+dynamic+wallpapers+or+plasma-hud+at+login)


Set up a systemd user service (if you're fancy) to launch dynamic wallpapers or plasma-hud at login.


## 📌 Notes

- 🧪 Uses qdbus to control Plasma shell for wallpaper changes.
- 🧵 Rofi menus dynamically detect categories.
- 🐉 Whole system thrives on chaos, synergy, and your preferred terminal emulator (defaults to kitty, of course).

## 📅 Last Updated
2025-04-15

## 🧙‍♀️ Badge Generator

Placeholder auto-badges coming in future pipeline. Imagine them. They sparkle.✨

## 💖 License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

MIT, because.


