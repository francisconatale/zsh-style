# Powerlevel10k configuration

This repository contains my personal configuration for **Powerlevel10k**, a fast and highly customizable theme for **Zsh**.  
The setup focuses on a **minimalist black and white**

## Requirements

Before using this configuration, make sure you have the following installed:

- **Zsh**  
  Install on Debian/Ubuntu-based systems:
  ```bash
  sudo apt install zsh
  ```

- **Oh My Zsh**  
  Install from [ohmyz.sh](https://ohmyz.sh/) or with:
  ```bash
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```

- **Powerlevel10k Theme**  
  Clone the official theme into your custom themes directory:
  ```bash
  git clone --depth=1 https://github.com/romkatv/powerlevel10k.git   ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
  ```

- **Nerd Font**  
  Powerlevel10k requires a Nerd Font.
  Download it from [Nerd Fonts](https://www.nerdfonts.com/font-downloads) and set it as your terminal font.

## Installation

1. Copy this configuration file into your home directory:
   ```bash
   cp p10k.zsh ~/.p10k.zsh
   ```

2. Edit your `~/.zshrc` to enable the theme and source the config:
   ```bash
   ZSH_THEME="powerlevel10k/powerlevel10k"
   [[ ! -f ~/.p10k.zsh ]] || source ~/.p10k.zsh
   ```

3. Reload Zsh or open a new terminal session:
   ```bash
   exec zsh
   ```
   
## Preview

The prompt is designed for simplicity and readability — no clutter, just essential info like:
- Current directory
- Git branch and status
- Command execution status

<img width="481" height="74" alt="image" src="https://github.com/user-attachments/assets/cdea15ba-9825-46cc-b82c-c983723c8a6e" />

