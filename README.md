# Things to install
To make it work, we need to install some tools.

```bash
    sudo apt-get install i3wm
    sudo apt-get install alsa-utils lm_sensors speedtest-cli
```

## Monitor tool
This tool can be used to change the monitor\\display.
It's just a wrapper for `xrandr`, may help you to get used with this.
```bash
    sudo apt-get install arandr
```

## Bluetooth utils
`bluetooth-wizard`

sudo dnf config-manager --add-repo https://download.docker.com/linux/fedora/docker-ce.repo
sudo dnf config-manager --set-enabled docker-ce-edge

cargo install --git https://github.com/jwilm/alacritty
cargo install --git https://github.com/greshake/i3status-rust.git

Font Awesome, for icons="awesome". Version 5 of the font is causing some issues (see #130), so for now we recommend version 4.
powerline-fonts