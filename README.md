# ⚡ nvim-devops

A blazing fast, modular, and "batteries-included" Neovim configuration built on top of [LazyVim](https://www.lazyvim.org).

Designed specifically for **DevOps Engineers**, SREs, and Cloud Architects. It comes pre-configured with LSP, formatting, and linting for the modern infrastructure stack.

## 🚀 Features

* **Core:** Based on LazyVim (Fast, Stable, Low-Bloat).
* **Infrastructure as Code:** First-class support for **Terraform** (`terraform-ls`, `tflint`), **Ansible**, and **CloudFormation**.
* **Containers & Orchestration:** Deep integration with **Docker** and **Kubernetes** (YAML schemas, Helm support).
* **Scripting:** Full Python and Bash support (LSP, Debugging, Formatting).
* **Git Integration:** fast git interactions via `lazygit` inside the editor.
* **UI:** Clean interface with `folke/noice`, file tree, and fuzzy finding.

---

## 🛠 Prerequisites

Before installing this config, ensure you have the necessary tools.

### 1. Nerd Font (Crucial)
You **must** use a generic Nerd Font in your terminal emulator for icons to render correctly.
* **Download:** [JetBrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads) (Recommended)
* **Install:** Install the font on your OS and set it as the font in your Terminal settings (iTerm2, Alacritty, Ghostty, etc.).

### 2. Dependencies
Install the required system tools based on your OS.

####  macOS (Homebrew) installation
```bash
brew install neovim ripgrep fd lazygit node npm git



