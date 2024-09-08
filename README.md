# Base Arch Linux Setup

- Arch Linux
- GRUB
- X11
- i3
- kitty
- picom
- networkmanager
- pulseaudio
  - pavucontrol
  - pulseaudio-bluetooth
  - bluez
  - blueman
- yay
- chromium
- nvim
- libreoffice
- udiskie
- flameshot
- optimus-manager (for nvidia gpu switching)
- dunst
- nautilus
- ranger
- gnome-keyring
- Main Theme: <a href="https://github.com/dracula">Dracula</a>
  - Icon Theme: Papirus Icon Theme (dark variant)
  - QT Theming: qt5ct, qt6ct
  - GTK Theming: through the config files (`~/.config/gtk-2.0`, `~/.config/gtk-3.0`,`~/.config/gtk-3.0`)

## Configs

- WM: i3 (<a href="https://github.com/itsRaCl/i3-config">config</a>)
- Compositor: picom (<a href="https://github.com/yshui/picom"> link </a>)
- Shell: zsh (<a href="https://github.com/itsRaCl/zsh-config">config</a>)
  - package manager: antigen
- Terminal: Kitty (<a href="https://github.com/itsRaCl/kitty-config">config</a>)
- Editor: nvim (<a href="https://github.com/itsRaCl/nvim-config">config</a>)
  - package manager: <a href="https://github.com/wbthomason/packer.nvim">packer.nvim</a>
- Terminal Multiplexer: tmux (<a href="https://github.com/itsRaCl/tmux-config">config</a>)
  - package manager: <a href="https://github.com/tmux-plugins/tpm">tpm</a>
  - <a href="https://github.com/tmuxinator/tmuxinator">tmuxinator</a>
- (DOESN'T WORK ONLY for BITS Pilani) WiFi Setup: <a href="https://github.com/itsRaCl/wifi_script">config</a>

## Browser Extensions

<table>
    <tr>
        <th> Name </th>
        <th> Link (Chrome)</th>
        <th> Link (Firefox)</th>
    </tr>
    <tr>
        <td>UBlock Origin</td>
        <td> <a href="https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm">link</a></td>
        <td> <a href="https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/">link</a></td>
    </tr>
    <tr>
        <td>Vimium</td>
        <td> <a href="https://chromewebstore.google.com/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb">link</a></td>
        <td> <a href="https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/">link</a></td>
    </tr>
    <tr>
        <td>Dark Reader</td>
        <td> <a href="https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh">link</a></td>
        <td> <a href="https://addons.mozilla.org/en-US/firefox/addon/darkreader/">link</a></td>
    </tr>
</table>

## Packages Install Command

Please don't use this command unless you understand what you're doing. This is just for my reinstall purposes

```
yay -S zsh kitty neovim tmux chromium tmuxinator papirus-icon-theme rofi ttf-iosevka-nerd ttf-iosevkaterm-nerd libreoffice-fresh flameshot nautilus zathura dunst blueman bluez picom gnome-keyring
```
