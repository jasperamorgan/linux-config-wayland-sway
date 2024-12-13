# linux-config-wayland-sway

Linux configuration files for a Wayland/Sway based desktop.

# How to Use

To use these configs, the steps are:

1. Check out the the repo (without files) to a directory on your machine.
2. Configure the repo to use the `~/.config` directory as the working dir for the repo.
3. Checkout the files - use `git reset` to overwrite any existing files in `~./config`.

```

cd ~/config-files
git clone --no-checkout https://github.com/jasperamorgan/linux-config-wayland-sway.git

cd ~/config-files
git config --local core.worktree "../../"

git reset --hard origin/master
git checkout
```

(See [this expanded explanation](https://www.digitalocean.com/community/tutorials/how-to-use-git-to-manage-your-user-configuration-files-on-a-linux-vps).)
