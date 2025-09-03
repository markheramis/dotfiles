# Dotfiles

A curated collection of configuration files (dotfiles) for Unix-like systems, designed to provide a consistent, powerful, and beautiful development environment across multiple machines.

## What Are Dotfiles?

Dotfiles are plain text configuration files used on Unix-like systems (such as Linux and macOS) to customize the behavior of your shell, editor, and various command-line tools. These files typically begin with a dot (e.g., `.bashrc`, `.vimrc`, `.gitconfig`), which makes them hidden by default.

This repository provides a centralized location to store, version, and manage your personal configuration files. By keeping your dotfiles under version control, you can easily synchronize your environment across multiple machines, back up your settings, and share your setup with others.

## Available Configurations

| Configuration | Description | Documentation |
|---------------|-------------|---------------|
| **nvim** | Neovim editor configuration | [README](./nvim/README.md) |
| **tmux** | Terminal multiplexer configuration | [README](./tmux/README.md) |
| **zsh** | Shell configuration and setup | [README](./zsh/README.md) |

## Prerequisites

- [Git](https://git-scm.com/downloads)
- Unix-like system (Linux, macOS, or Windows with WSL)

## Installation

Each configuration can be installed independently. Navigate to the desired configuration directory and run the installation script:

```bash
# Example: Install tmux configuration
cd tmux/
./install.sh
```

Each configuration automatically backs up your existing files before installation.

## Structure

```
dotfiles/
├── README.md      # This file
├── nvim/          # Neovim editor configuration
├── tmux/          # Terminal multiplexer configuration
└── zsh/           # Shell configuration
```

## Usage

1. Browse available configurations above
2. Navigate to the desired configuration directory
3. Follow the installation instructions in its README
4. Each configuration can be used independently or together

## License

Each configuration may have its own license. Check individual directories for details.
