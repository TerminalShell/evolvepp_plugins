# ($>) Terminal Shell - Evolve++ Plugins

# Description
A repository of plugins created for the [Evolve++ admin system](https://github.com/TerminalShell/evolvepp_plugins) for Garry's Mod.

## Installation
Place the contents of this directory in your `/garrysmod/data/evolvepp/` folder, NOT in the addons folder. Specifically, plugins belong in `/garrysmod/data/evolvepp/lua/plugins/`, while menus belong in `/garrysmod/data/evolvepp/lua/menu/`.

To disable a plugin, you can either add the following property to the plugin file `PLUGIN.Disabled = true`, or you can simply place it in a `/disabled/` folder inside `/plugins/`. Folders are used to designate gamemodes, so anything in a folder inside `/plugins/` will only run if your server is on that gamemode.