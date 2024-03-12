# My Dotfiles

This repository contains my personal dotfiles and configurations for Zsh, Neovim, and automated setup scripts using Ansible. It's designed to quickly set up a macOS environment to my preferences but can be adapted for other Unix-like systems.

## Contents

- `.zshrc`: Zsh configuration file.
- `nvim/`: Neovim configuration as a git submodule.
- `ansible/`: Ansible scripts for automating the setup as a git submodule.

## Getting Started

To use these dotfiles, clone this repository to your home directory:

```bash
git clone --recurse-submodules https://github.com/yourusername/dotfiles.git ~/dotfiles
```

## Prerequisites

- [Homebrew](https://brew.sh/)
- Install Ansible using Homebrew:

```bash
brew install ansible
```

## Running the setup

To set up the environment, run the following command:

```bash
cd ~/dotfiles/ansible
ansible-playbook macos-setup.yml
ansible-playbook setup-dotfiles.yml
```
