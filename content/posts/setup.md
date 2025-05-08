+++
title = "setup"
date = "2025-05-07"
description = "My preferred development environment configuration."

[extra]
cmd = "bat"
cmd_arg = "setup.md"
+++

This page outlines my preferred development environment configuration.

---

### Core Setup

- **Dotfiles Repository**: [nextonesfaster/dotfiles](https://github.com/nextonesfaster/dotfiles)
- **Editors**: Visual Studio Code, IntelliJ IDEA
- **Theme**: [Rosé Pine][rose-pine]
- **Editor Font**: [Ligalex Mono][ligalex-mono]  
  - Weight: *Text*  
  - Size: *13.5 pt*
- **Terminal Font**: [BlexMono Nerd Font][blex-mono-nerd]  
  - Size: *14 pt*

You can view my full [VSCode `settings.json` configuration on GitHub Gist][settings.json].

---

### Shell & Prompt Tools

- [Oh My Zsh](https://ohmyz.sh/) — Framework for managing Zsh configuration
- [Starship](https://starship.rs) — Cross-shell minimal, blazing-fast prompt
- [zoxide](https://github.com/ajeetdsouza/zoxide) — Smarter directory jumping
- [skim](https://github.com/skim-rs/skim) — Fast fuzzy finder (`fzf`-like)
- [delta](https://github.com/dandavison/delta) — Git diff formatter
- [lsd](https://github.com/lsd-rs/lsd) — A modern `ls` with icons and colors

---

### Frequently Used CLI Tools

- [homebrew](https://brew.sh) — Package manager for macOS
- [ripgrep](https://github.com/BurntSushi/ripgrep) — Fast recursive search
- [fd](https://github.com/sharkdp/fd) — A simple, fast alternative to `find`
- [bat](https://github.com/sharkdp/bat) — `cat` with syntax highlighting
- [neovim](https://neovim.io) — Minimal, fast terminal editor
- [opentag](https://github.com/nextonesfaster/opentag) — Tag-based file and link manager
- [qalc](https://qalculate.github.io/) — Versatile command-line calculator

---

[rose-pine]: https://marketplace.visualstudio.com/items?itemName=mvllow.rose-pine  
[ligalex-mono]: https://github.com/ToxicFrog/Ligaturizer/releases  
[blex-mono-nerd]: https://www.nerdfonts.com/font-downloads  
[settings.json]: https://gist.github.com/nextonesfaster/b6f86b9e48daf76a99bf208015aa3fd1
