# 🌌 Configs: Dotfiles of Silvaire's Arch Linux

Welcome to the **Configs** repository! This project houses the dotfiles that I use on my Arch Linux setup. Here, you will find configurations for various tools and environments, optimized for a smooth workflow.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/andritefy/Configs/releases)

## 📁 Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Configuration Files](#configuration-files)
   - [Shell Configuration](#shell-configuration)
   - [Neovim Configuration](#neovim-configuration)
   - [WezTerm Configuration](#wezterm-configuration)
   - [Hyprland Configuration](#hyprland-configuration)
   - [Starship Configuration](#starship-configuration)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## 🛠️ Introduction

This repository contains my personal dotfiles tailored for Arch Linux. The configurations aim to enhance productivity and provide a streamlined user experience. Whether you are a beginner or an experienced user, you can adapt these files to fit your needs.

## 🚀 Installation

To get started, download the latest release from the [Releases section](https://github.com/andritefy/Configs/releases). Once downloaded, execute the setup script to apply the configurations to your system. This will help you set up your environment quickly.

### Steps to Install

1. Visit the [Releases section](https://github.com/andritefy/Configs/releases).
2. Download the latest release.
3. Extract the files.
4. Open a terminal and navigate to the extracted directory.
5. Run the setup script:

   ```bash
   ./setup.sh
   ```

6. Follow the on-screen instructions to complete the installation.

## 📝 Configuration Files

This section provides an overview of the various configuration files included in this repository.

### Shell Configuration

The shell configuration is designed for Zsh, a powerful shell that offers features like improved tab completion and better scripting capabilities. The configuration includes:

- Custom prompts
- Aliases for common commands
- Environment variables for enhanced functionality

To use the shell configuration, simply copy the `.zshrc` file to your home directory:

```bash
cp .zshrc ~/
```

### Neovim Configuration

Neovim is a modern text editor that enhances the traditional Vim experience. The configuration includes:

- Plugins for improved editing
- Custom keybindings
- Aesthetic themes

To set up Neovim, copy the `init.vim` file to the appropriate directory:

```bash
mkdir -p ~/.config/nvim
cp init.vim ~/.config/nvim/
```

### WezTerm Configuration

WezTerm is a GPU-accelerated terminal emulator. The configuration focuses on performance and aesthetics. It includes:

- Custom colors
- Font settings
- Keybindings for efficiency

To apply the WezTerm configuration, copy the `wezterm.lua` file to the configuration directory:

```bash
mkdir -p ~/.config/wezterm
cp wezterm.lua ~/.config/wezterm/
```

### Hyprland Configuration

Hyprland is a dynamic tiling window manager. The configuration optimizes window management and provides a clean interface. It includes:

- Keybindings for window manipulation
- Layout settings
- Custom scripts for enhanced functionality

To set up Hyprland, copy the configuration file to the appropriate directory:

```bash
cp hyprland.conf ~/.config/hypr/
```

### Starship Configuration

Starship is a cross-shell prompt that is fast and customizable. The configuration allows you to set up a unique prompt style. It includes:

- Custom prompt symbols
- Configuration for various programming languages
- Theme settings

To use Starship, copy the configuration file to your home directory:

```bash
cp starship.toml ~/.config/starship.toml
```

## 💡 Usage

Once you have set up the configurations, you can start using your new environment. Here are some tips for getting the most out of your setup:

- **Zsh**: Use the `source ~/.zshrc` command to load the new shell configuration.
- **Neovim**: Open Neovim by typing `nvim` in the terminal. Explore the plugins and custom keybindings.
- **WezTerm**: Launch WezTerm to experience the GPU-accelerated terminal.
- **Hyprland**: Start Hyprland to manage your windows efficiently.
- **Starship**: Enjoy the sleek prompt while navigating through your terminal.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request. Please ensure that your contributions align with the overall goals of this repository.

## 📜 License

This project is licensed under the GNU General Public License v3.0. You can freely use, modify, and distribute the code as long as you adhere to the terms of the license.

## 📬 Contact

For any inquiries or feedback, please reach out to me through my GitHub profile. I appreciate your interest in my dotfiles and hope you find them useful!

---

Thank you for visiting the **Configs** repository! If you have any questions or need assistance, don't hesitate to check the [Releases section](https://github.com/andritefy/Configs/releases) for the latest updates and downloads. Enjoy customizing your Arch Linux experience!