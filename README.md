# 💻 Damian's Terminal Configs

This repository contains a fully modular and cross-platform setup for configuring your terminal environment across **Windows** and **Linux**. Whether you're using **PowerShell**, **CMD**, **WSL**, **Termux**, or **pure Linux terminals**, this repo has optimized configs for a consistent, powerful, and visually appealing developer experience.

---

## 📦 What's
---

## 🚀 Features

- ⚡ **Minimal yet powerful prompt** using [Starship](https://starship.rs)
- 🎯 Fully **modular dotfiles** per platform (Windows/Linux)
- 🔄 **Universal aliases** and command enhancements
- 🌐 Optimized for **cross-terminal consistency**
- 📦 Ready for **version control & portability**
- 🧠 Designed for **developers, researchers, and system engineers**

---

## 🧩 Included Configurations

### 🔹 PowerShell
- Custom aliases for Git, SSH, file navigation
- Color-enhanced prompt
- Auto-run profile script

### 🔹 Neovim
- Lightweight, fast editing environment
- File explorer, syntax highlighting, plugin manager
- Compatible with both init.vim and init.lua

### 🔹 Starship Prompt
- Cross-shell, high-speed prompt
- Clean and informative segments (Git status, Node, Python, etc.)
- Works on Bash, Zsh, PowerShell, CMD

### 🔹 Termux
- Aliases and enhancements for Android CLI
- `.bashrc` optimizations
- Lightweight setup for portable dev work

---

## ⚙️ Installation

Clone and apply the WindowLinuxConfig setup in your terminal:

```bash
# Clone the repository
git clone https://github.com/Damianworkk/windowlinuxconfig.git

# Navigate into the project directory
cd windowlinuxconfig

# Apply .bashrc and optional Starship prompt config
cp .bashrc ~/.bashrc
mkdir -p ~/.config && cp starship.toml ~/.config/starship.toml

# Reload terminal configuration
source ~/.bashrc

# (Optional) Install Starship prompt
curl -sS https://starship.rs/install.sh | sh

# (Optional) Install Neovim if using its config
pkg install neovim -y
