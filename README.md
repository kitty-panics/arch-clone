# Arch Clone

Clones and creates a bootable iso from an existing Arch installation

Install by git cloning this repo somewhere
<br /><i>(I usually place it in /tmp so that it isn't 'picked up' during the cloning process)</i>

```Bash
git clone https://github.com/kitty-panics/arch-clone
```

Then make sure to view and edit to your liking at least the 2 included config files:

- settings.conf, which handles the basic config options/paths
- exclude.conf, which lists the files/folders excluded during creation of the iso

When you have the settings to your liking just run it

```Bash
sudo ./arch-clone
```
