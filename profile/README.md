<div align="center">
  <img src="https://raw.githubusercontent.com/DotsOS/.github/refs/heads/main/profile/assets/dotsos.png" width="256" alt="DotsOS logo">
  <br/>
  <h1 align="center">DotsOS</h1>
  <p align="center">DotsOS - Arch-based distribution offering an easy installation, several customizations.</p>
</div>
<br />

[DotsOS-Video](https://github.com/user-attachments/assets/ac27173d-74d9-4579-9fe6-887f501ab265)

# DotsOS

> **A complete, elegant, and user-friendly experience on top of Arch Linux.**

**DotsOS** is a fully integrated environment (Dotfiles Setup) built on **Arch Linux**, designed to be ready to use right out of the box without the hassle. It provides stable interfaces and a system that not only looks beautiful but is highly reliable and easy to use, thanks to our heavy focus on bug fixes and system tweaks.

## ✨ Key Features

*   **Arch Linux Based:** Enjoy the latest packages and a rolling release model combined with absolute customization power.
*   **Hyprland Window Manager:** A modern, incredibly smooth Wayland experience featuring gorgeous animations and unparalleled performance.
*   **Caelestia:** Integrates the elegant [caelestia-dots](https://github.com/caelestia-dots) to deliver a visually pleasing, cohesive, and modern user interface.
*   **Caelestia SDDM:** A magical first impression every time you boot your machine, featuring the beautiful [caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm) theme.
*   **User-Friendly:** Say goodbye to hours of configuration! The system is pre-configured to suit both beginners and power users alike.
*   **Bug-Free Experience:** We've implemented **tons of tweaks and bug fixes** for common issues found in Hyprland environments, ensuring a stable, reliable, and crash-free workflow.

## 📸 Screenshots

| Bootloader (Limine) | Login Screen (SDDM) | Lock Screen |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/DotsOS/.github/refs/heads/main/profile/assets/background.png" width="400" alt="Limine Screen"> | <img src="https://github.com/user-attachments/assets/3a21a2d3-542a-42fe-b69c-40978eadd42b" width="400" alt="SDDM Screen"> | <img src="https://github.com/user-attachments/assets/21f984bc-2a4b-41f8-90d8-512a326a0b57" width="400" alt="Lock Screen"> |

| Desktop (Hyprland) | Panels | Notifications |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/22924c33-8105-480a-b16d-12e76c19021f" width="400" alt="Desktop"> | <img src="https://github.com/user-attachments/assets/35648809-2bb7-42c5-bdeb-80d10fc66b93" width="400" alt="Caelestia Shell"> | <img src="https://github.com/user-attachments/assets/3170f3cc-7795-4ad8-8718-21b7c5af404a" width="400" alt="Notifications"> |
## 🚀 Installation

**Coming Soon**

## ⚙️ Configuration

This configuration follows a modular structure to keep the setup organized and easy to maintain. Below is a breakdown of the configuration files:

**Hyprland (Caelestia Dots)**
*   **Variables** `~/.config/hypr/variables.conf` — Defines global constants for colors, sizes, and theme toggles used across the config.
*   **Hyprland** `~/.config/hypr/hyprland.conf` — The main entry point that sources all other modular configuration files.
*   **Animations** `~/.config/hypr/hyprland/animations.conf` — Custom Bezier curves and animation rules for windows, layers, and workspaces.
*   **Decoration** `~/.config/hypr/hyprland/decoration.conf` — Visual styling including corner rounding, background blur effects, and window shadows.
*   **Env** `~/.config/hypr/hyprland/env.conf` — Environment variables for toolkit backends (QT, GTK), XDG specifications, and cursor themes.
*   **Execs** `~/.config/hypr/hyprland/execs.conf` — Autostart applications, background daemons, and system services initialized on login.
*   **General** `~/.config/hypr/hyprland/general.conf` — Core layout settings, window gaps, border sizes, and active/inactive border colors.
*   **Gestures** `~/.config/hypr/hyprland/gestures.conf` — Touchpad workspace swipe settings and multi-finger gesture dispatchers.
*   **Group** `~/.config/hypr/hyprland/group.conf` — Configuration for tabbed window groups, including group bar fonts and colors.
*   **Input** `~/.config/hypr/hyprland/input.conf` — Keyboard layouts (US/Arabic), repeat rates, and touchpad/mouse sensitivity settings.
*   **Keybinds** `~/.config/hypr/hyprland/keybinds.conf` — Comprehensive list of shortcuts for app launching, window management, and media control.
*   **Misc** `~/.config/hypr/hyprland/misc.conf` — Miscellaneous settings for VRR, power management (DPMS), and focus behavior.
*   **Rules** `~/.config/hypr/hyprland/rules.conf` — Specific rules to control how individual apps behave (floating, opacity, workspace assignment).
*   **Scrolling** `~/.config/hypr/hyprland/scrolling.conf` — Configuration for column-based layouts and focus-following behavior.

**Sestem**
*   **Bootloader** ```/boot/limine/limine.conf```

## 🙏 Credits

This project wouldn't be possible without these amazing open-source projects. Special thanks to:

*   **[Arch Linux](https://archlinux.org/)** - For the robust and powerful base operating system.
*   **[caelestia-dots](https://github.com/caelestia-dots/shell)** - For the gorgeous shell, UI components, and the core dotfiles inspiration.
*   **[caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm)** - For the beautiful login manager theme.

## 📜 License

This project is licensed under the **[GNU General Public License v3.0 (GPLv3)](https://github.com/DotsOS/.github/blob/main/LICENSE)**. 

Feel free to use, modify, and share it with the Linux community! *Note: Any modifications or derivative works distributed must also be open-source and licensed under the GPLv3.*
