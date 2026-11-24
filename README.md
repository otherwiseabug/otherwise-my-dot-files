# RYOKU 力 — Arch Linux Dotfiles

A minimal, dark-themed Arch Linux desktop setup built on **Hyprland** and **Kitty**.

## 📸 Screenshots
*(Tip: Drag and drop your two screenshots directly into this README editor on GitHub to upload and display them here!)*

## 🛠️ Setup Details
* **OS:** Arch Linux (`x86_64`)
* **Window Manager:** Hyprland (Wayland)
* **Terminal:** Kitty
* **Shell:** Fish
* **System Monitor:** `btop`
* **Fetch Tool:** `fastfetch` (with custom image & layout)
* **Terminal Toys / Widgets:** `asciiquarium`, `cava` (desktop audio visualizer)

## 📦 Included Configs
* **`kitty/`** — Terminal appearance, colors, opacity/blur, and font settings (`kitty.conf`, `current-theme.conf`, `current-font.conf`).
*(Add any other folders you upload here, e.g., `hypr/`, `waybar/`, `fastfetch/`, `fish/`)*

## 🚀 Installation

1. **Install dependencies (Arch Linux):**
   ```bash
   sudo pacman -S kitty fish fastfetch btop asciiquarium cava
   ```
   *(Note: Make sure you also have your Nerd Font installed so icons render properly.)*

2. **Clone this repository:**
   ```bash
   git clone https://github.com/otherwiseabug/otherwise-my-dot-files/tree/main
   cd dotfiles
   ```

3. **Copy the Kitty config:**
   Back up your existing config first, then copy the files over:
   ```bash
   cp -r ~/.config/kitty ~/.config/kitty.bak
   mkdir -p ~/.config/kitty
   cp -r kitty/.config/kitty/* ~/.config/kitty/
   ```
   *(If you uploaded the `.conf` files to the root of your repo instead of subfolders, change the last line to `cp *.conf ~/.config/kitty/`.)*

4. **Reload Kitty:**
   Press `Ctrl + Shift + F5` inside Kitty or restart the terminal.

