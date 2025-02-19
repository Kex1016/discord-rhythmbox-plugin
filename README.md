# discord-rhythmbox-plugin

>[!NOTE]
> This fork only adds an album art to the presence's large image. If you want the original, it's at [ToppleKek/discord-rhythmbox-plugin](https://github.com/ToppleKek/discord-rhythmbox-plugin).

A simple plugin for rhythmbox to update your rich presence in discord.
This is based off of the built-in im-status plugin and has some borrowed code; credit where credit is due!

Note: This plugin does not work with Discord installed via Flatpak.

## Usage

1. Install `pypresence`:

    - Arch Linux: `pacman -S python-pypresence`
    - On systems that use python2 and 3: `pip3 install pypresence`
    - Or if not: `pip install pypresence`

2. Clone the repo:

    - `git clone https://github.com/ToppleKek/discord-rhythmbox-plugin.git`
    - Put the `discord-rhythmbox-plugin` folder in `~/.local/share/rhythmbox/plugins`
    - Enable the plugin

> [!NOTE]
> Make sure that Discord is open when you enable the plugin.
