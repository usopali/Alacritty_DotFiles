# Alacritty DotFiles

Configuration files for [Alacritty](https://github.com/alacritty/alacritty), a fast and lightweight terminal emulator. These dotfiles include custom settings for themes, fonts, keybindings, and more, to enhance your terminal experience.

## Features

- **Custom Theme**: Aesthetic color schemes for a better visual experience.
- **Font Settings**: Configured for readability and style.
- **Keybindings**: Custom shortcuts for efficient navigation and use.
- **Performance Tweaks**: Settings optimized for speed and low resource usage.

## Installation

1. **Clone this repository**:

   ```bash
   git clone https://github.com/usopali/Alacritty_DotFiles.git

2.  **Navigate to the directory**:
   ```
cd Alacritty_DotFiles
```
3. **Backup your existing configuration (if any)**:
```bash
mv ~/.config/alacritty/alacritty.yml ~/.config/alacritty/alacritty_backup.toml
```
4. **Copy the configuration file to your Alacritty config directory**:
```
cp alacritty.yml ~/.config/alacritty/alacritty.toml
```


Customization:

Feel free to tweak the alacritty.toml file according to your preferences. Below are some commonly modified settings:

- Change Theme: Modify the colors section for custom color schemes.
- Adjust Font: Change font.family and font.size for different font styles and sizes.
- Modify Keybindings: Update the key_bindings section to customize shortcuts.
