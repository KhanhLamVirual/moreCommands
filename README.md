# moreCommands Plugin
**/!\\This plugin need java 12 or greater./!\\** To dowload java 12, follow steps [here](https://www.oracle.com/fr/java/technologies/javase/jdk12-archive-downloads.html) or greater version [here](https://www.oracle.com/java/technologies/downloads/).

### Player Commands
* `/ut` Tells you the name of the unit you are controlling.
* `/vnw [number]` (VoteNewWave) Vote for Sending a new Wave.
* `/maps [page]` List all maps on server.
* `/info-all [ID|username...]` Get all the player information.
* `/rtv [mapName...]` Rock the vote to change map.
* `/rainbow [ID|username...]` RAINBOW!!
* `/msg <ID|username> <message...>` Send a message to a player. (replace all spaces with '_' in the name).
* `/help [page|filter]` Recreate /help to display only commands related to your rank.
* `/effect [list|name|id] [page|ID|username...]` Gives you a particle effect. /!\May cause errors
* `/r <message...>` Reply to the last private message received.
* `/lobby` Switch to lobby server.
* `/switch <list|name>` Switch to another server.

### Admin Commands
* `/team [~|teamname|list|vanish] [filter|username...]` Change team.
* `/am <message...>` Send a message as admin.
* `/kick <filter|ID|username> [reason...]` Kick a person by name or ID.
* `/pardon <ID>` Pardon a votekicked player by ID and allow them to join again.
* `/ban <filter|username|ID> [reason...]`  Ban a person.
* `/unban <ID>` Unban a person.
* `/players <all|online|ban>` Gives the list of players according to the type of filter given.
* `/kill [filter|username...]` Kill a player.
* `/tp <filter|name|x,y> [~|to_name|x,y...]` Teleport to a coordinate or a player.
* `/core <small|medium|big>` Spawn a core to your corrdinate.
* `/chat [on|off]` Enabled/disabled the chat.
* `/spawn <unit> [count] [filter|x,y|username] [~|teamname...]` Spawn a unit.
* `/godmode [filter|username...]` [God]: I'm divine!
* `/mute <filter|username|ID> [reason...]` Mute a person by name or ID.
* `/unmute <filter|username|ID...>` Unmute a person by name or ID.
* `/reset <filter|username|ID...>` Resets a player's data (rainbow, GodMode, muted, ...).

### Server Commands
* `unban-all [y|n]` Unban all ID and IP.
* `auto-pause` Pause the game if no one is connected.
* `chat [on|off]` Enabled/disabled the chat.
* `nice-welcome` Nice welcome for me.
* `commands <list|commandName> [on|off]` Enable/Disable a command. /!\\Requires server restart to apply changes.
* `clear-map [y|n]` Kill all units and destroy all blocks except cores, on the current map.
* `gamemode [name]` Change the gamemode of the current map.
* `blacklist <list|add|remove|clear> <name|ip> [value...]` Players using a nickname or ip in the blacklist cannot connect.
* `anti-vpn [on|off]` Anti VPN service.
* `filters <help|on|off>` Enabled/disabled filters.
* `effect <list|on|off> [id|name]` Enabled/disabled a particles effect.
* `switch <list|add|remove> [ip] [name...]` Configure the list of servers in the switch.

### Feedback
Open an issue if you have a suggestion.

### Releases
Prebuild releases can be found [here](https://github.com/ZetaMap/moreCommands/releases) 

### Building a Jar 
You have just run `build.bat` and the plugin will compile automatically.


### Installing
Simply place the output jar from the step above in your server's `config/mods` directory and restart the server.
List your currently installed plugins by running the `mods` command.

### Thanks to...
This plugin is a grouping of other plugins, with modifications or upgrades.

J-VdS - [TeamPlugin](https://github.com/J-VdS/TeamPlugin)<br>
Phinner - [BetterCommands](https://github.com/Phinner/BetterCommands)<br>
Shadow53 - [MindustryAdminPlugin](https://github.com/Shadow53/MindustryAdminPlugin)<br>
mayli - [RockTheVotePlugin](https://github.com/mayli/RockTheVotePlugin)<br>
OceanPandorum - [PandorumPlugin](https://github.com/OceanPandorum/PandorumPlugin)<br>
Mindurka - [spawnUnit](https://github.com/Mindurka/spawnUnit)
