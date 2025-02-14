# linux-config-wayland-sway

Linux configuration files for a Wayland/Sway based desktop.

# Dependencies

* Waybar
* bemenu
* Victor Mono NerdFont 
* Swaylock

# Fonts

Victor Mono font from [NerdFonts](https://www.programmingfonts.org/#victor-mono).

## Install Steps
```
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts
wget -O VictorMono.zip https://github.com/ryanoasis/nerd-fonts/releases/latest/download/VictorMono.zip

unzip VictorMono.zip -d VictorMono
fc-cache -fv
```
  
`
# Sway

Based on this config:

* https://www.reddit.com/r/unixporn/comments/ptqbay/sway_my_tokyonight_inspired_rice/?rdt=49079
* https://rubjo.github.io/victor-mono/
* https://github.com/coodos/sway-dots

Notes

bemenu config: https://man.archlinux.org/man/extra/bemenu/bemenu.1.en

https://github.com/swaywm/sway/wiki/Useful-add-ons-for-sway

## Waybar

## Wallpapers

Wallpapers are from https://wallhaven.cc

# How to Use

To use these configs, the steps are:

1. Check out the the repo (without files) to a directory on your machine.
2. Configure the repo to use the `~/.config` directory as the working dir for the repo.
3. Checkout the files - use `git reset` to overwrite any existing files in `~./config`.

```

cd ~/config-files
git clone --no-checkout https://github.com/jasperamorgan/linux-config-wayland-sway.git

#Worktree is relative to the ~/config-files/linux-config-wayland-sway/.git directory
git config --local core.worktree "../../../.config"

git reset --hard origin/master
git checkout
```

(See [this expanded explanation](https://www.digitalocean.com/community/tutorials/how-to-use-git-to-manage-your-user-configuration-files-on-a-linux-vps).)


# References

https://github.com/lokesh-krishna/dotfiles?tab=readme-ov-file#the-tokyo-night-setup
https://monokai.pro/
