# Sway Dotfiles



## 📦 Dependencies

Install the required packages before applying these configs:

* **WM & Compositor:** `sway`, `swaylock`, `swayidle`
* **Bar & Launcher:** `waybar`, `rofi-wayland`
* **Terminal:** `alacritty`
* **Logout Menu:** `wlogout`
* **Font:** `JetBrains Mono Nerd Font, Iosevka Nerd Font`

### Install on Arch
```bash
sudo pacman -S sway waybar rofi-wayland alacritty wlogout
```

### Install on Fedora
```bash
sudo dnf install sway waybar rofi-wayland alacritty wlogout
```

### Install on Debian
```bash
sudo apt install sway waybar rofi-wayland alacritty wlogout
```

### Install on NixOS
Add these to your configuration.nix file
```nix
environment.systemPackages = with pkgs; [
  sway
  waybar
  rofi-wayland
  alacritty
  wlogout
  nerd-fonts.jetbrains-mono
];
```
