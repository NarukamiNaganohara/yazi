# My Yazi Repository

## Welcome

Hello! 👋 Welcome to my personal Yazi repository. This contains my TUI file manager configuration using **Yazi** and related tools.

---

## Required Packages and Tools

- **Yazi** — A fast, extensible file manager for the terminal.  
  [Official Documentation](https://yazi-rs.github.io/docs/)

- **Starship** — A minimal, blazing-fast, and customizable prompt for any shell.  
  [Official Documentation](https://starship.rs/guide/)

---

## Installation

Follow these steps to set up the environment:

1. Install Yazi following the [official guide](https://yazi-rs.github.io/docs/).

2. Clone this repository into your Yazi configuration directory:

```bash
git clone https://github.com/NarukamiNaganohara/yazi.git ~/.config/yazi
```

3. Install the required plugins

```bash
ya pkg install yazi-rs/plugins:full-border
ya pkg install yazi-rs/plugins:mount
ya pkg install yazi-rs/plugins:git
ya pkg install Rolv-Apneseth/starship
```

---

# Plugins Overview

- full-border — Adds full borders to panels for better visual separation.

- mount — Provides an interface to mount and unmount drives.

- git — Displays Git status and allows basic Git operations.

- starship — Integrates with shell prompt to show Git and system information.

---

# Keybindings

Custom keybindings configured in this setup:

- Shift + m — Open mount menu

- y — copy file/folder yanky buffer

---

# Thank you for visiting this repository
