# CubeEngine - VanillaPlus
Improved Vanilla
## Commands
| Command | Description | Permission<br>`cubeengine.vanillaplus.command.<perm>` |
| --- | --- | --- |
| [*unlimited*](#unlimited) | Grants unlimited items | `unlimited.use` |
| [*invsee*](#invsee) | Allows you to see into the inventory of someone else. | `invsee.use` |
| [*seed*](#seed) | Displays the seed of a world. | `seed.use` |
| [*spawnMob*](#spawnmob) | Spawns the specified Mob | `spawnmob.use` |
| [*itemDB*](#itemdb) | Looks up an item for you! | `itemdb.use` |
| [*border*](#border) | border commands | `border` |
| [**border** *add*](#border-add) | Sets the diameter of the worldborder | `border.add.use` |
| [**border** *damage*](#border-damage) | Sets the world border damage per second per block | `border.damage.use` |
| [**border** *damageBuffer*](#border-damagebuffer) | Sets the world border damage buffer | `border.damagebuffer.use` |
| [**border** *generate*](#border-generate) | Generates the chunks located in the border | `border.generate.use` |
| [**border** *info*](#border-info) | Shows information about the world border | `border.info.use` |
| [**border** *setCenter*](#border-setcenter) | Sets the center for the worldborder | `border.setcenter.use` |
| [**border** *setDiameter*](#border-setdiameter) | Sets the diameter of the worldborder | `border.setdiameter.use` |
| [**border** *warningDistance*](#border-warningdistance) | Sets the warning time | `border.warningdistance.use` |
| [**border** *warningTime*](#border-warningtime) | Sets the warning time | `border.warningtime.use` |
| [*near*](#near) | Displays near players(entities/mobs) to you. | `near.use` |
| [*suicide*](#suicide) | Kills yourself | `suicide.use` |
| [*stack*](#stack) | Stacks your items up to 64 | `stack.use` |
| [*more*](#more) | Refills the stack in hand | `more.use` |
| [*clearinventory*](#clearinventory) | Clears the inventory | `clearinventory.use` |
| [*starve*](#starve) | Empties the hunger bar | `starve.use` |
| [*rename*](#rename) | Changes the display name of the item in your hand. | `rename.use` |
| [*weather*](#weather) | Changes the weather | `weather.use` |
| [*lag*](#lag) | Displays chunk, memory and world information. | `lag.use` |
| [*butcher*](#butcher) | Gets rid of mobs close to you. Valid types are:
monster, animal, pet, golem, boss, other, creeper, skeleton, spider etc. | `butcher.use` |
| [*whois*](#whois) | Displays informations from a player! | `whois.use` |
| [*lore*](#lore) | Changes the lore of the item in your hand. | `lore.use` |
| [*stop*](#stop) | Shuts down the server | `stop.use` |
| [*plugins*](#plugins) | Lists all loaded plugins | `plugins.use` |
| [*biome*](#biome) | Displays the biome type you are standing in. | `biome.use` |
| [*item*](#item) | Gives the specified Item to you | `item.use` |
| [*difficulty*](#difficulty) | Changes the difficulty level of the server | `difficulty.use` |
| [*sudo*](#sudo) | Makes a player send a message (including commands) | `sudo.use` |
| [*ping*](#ping) | Pong! | `ping.use` |
| [*god*](#god) | Toggles the god-mode! | `god.use` |
| [*enchant*](#enchant) | Adds an Enchantment to the item in your hand | `enchant.use` |
| [*give*](#give) | Gives the specified Item to a player | `give.use` |
| [*headchange*](#headchange) | Changes a skull to a players skin. | `headchange.use` |
| [*saveall*](#saveall) | Saves all or a specific world to disk. | `saveall.use` |
| [*removeAll*](#removeall) | Removes entities in a world | `removeall.use` |
| [*gamemode*](#gamemode) | Changes the gamemode | `gamemode.use` |
| [*heal*](#heal) | Heals a player | `heal.use` |
| [*depth*](#depth) | Displays your current depth. | `depth.use` |
| [*version*](#version) | Displays the version of the server or a given plugin | `version.use` |
| [*list*](#list) | Displays all the online players. | `list.use` |
| [*seen*](#seen) | Shows when given player was online the last time | `seen.use` |
| [*stash*](#stash) | Stashes or unstashes your inventory to reuse later | `stash.use` |
| [*whitelist*](#whitelist) | Allows you to manage your whitelist | `whitelist` |
| [**whitelist** *add*](#whitelist-add) | Adds a player to the whitelist. | `whitelist.add.use` |
| [**whitelist** *list*](#whitelist-list) | Lists all the whitelisted players | `whitelist.list.use` |
| [**whitelist** *off*](#whitelist-off) | Disables the whitelisting | `whitelist.off.use` |
| [**whitelist** *on*](#whitelist-on) | Enables the whitelisting | `whitelist.on.use` |
| [**whitelist** *remove*](#whitelist-remove) | Removes a player from the whitelist. | `whitelist.remove.use` |
| [**whitelist** *wipe*](#whitelist-wipe) | Wipes the whitelist completely | `whitelist.wipe.use` |
| [*remove*](#remove) | Removes entities in a radius | `remove.use` |
| [*feed*](#feed) | Refills your hunger bar | `feed.use` |
| [*fly*](#fly) | Lets you fly away | `fly.use` |
| [*kill*](#kill) | Kills a player | `kill.use` |
| [*time*](#time) | Changes the time of a world | `time.use` |
| [*walkspeed*](#walkspeed) | Changes your walkspeed. | `walkspeed.use` |
| [*repair*](#repair) | Repairs your items | `repair.use` |
| [*getPos*](#getpos) | Displays your current location. | `getpos.use` |
| [*compass*](#compass) | Displays the direction in which you are looking. | `compass.use` |
#### unlimited  
Grants unlimited items  
**Usage:** `unlimited [unlimited]`  
**Permission:** `cubeengine.vanillaplus.command.unlimited.use`  
  
#### invsee  
Allows you to see into the inventory of someone else.  
**Usage:** `invsee <player> [-force] [-quiet] [-ender]`  
**Permission:** `cubeengine.vanillaplus.command.invsee.use`  
  
#### seed  
Displays the seed of a world.  
**Usage:** `seed [world]`  
**Permission:** `cubeengine.vanillaplus.command.seed.use`  
  
#### spawnMob  
Spawns the specified Mob  
**Usage:** `spawnMob <<mob>[:data][,<ridingmob>[:data]]> [amount] [player]`  
**Permission:** `cubeengine.vanillaplus.command.spawnmob.use`  
  
#### itemDB  
Looks up an item for you!  
**Usage:** `itemDB [item]`  
**Permission:** `cubeengine.vanillaplus.command.itemdb.use`  
  
#### border  
border commands  
**Usage:** `border <command>`  
**Permission:** `cubeengine.vanillaplus.command.border`  
**SubCommands:** `add` `damage` `damageBuffer` `generate` `info` `setCenter` `setDiameter` `warningDistance` `warningTime`  
#### border add  
Sets the diameter of the worldborder  
**Usage:** `border add <size> [time] [in <world>]`  
**Permission:** `cubeengine.vanillaplus.command.border.add.use`  
  
#### border damage  
Sets the world border damage per second per block  
**Usage:** `border damage <damage> <world>`  
**Permission:** `cubeengine.vanillaplus.command.border.damage.use`  
  
#### border damageBuffer  
Sets the world border damage buffer  
**Usage:** `border damageBuffer <blocks> <world>`  
**Permission:** `cubeengine.vanillaplus.command.border.damagebuffer.use`  
  
#### border generate  
Generates the chunks located in the border  
**Usage:** `border generate <world> [-fulltick] [-status]`  
**Alias:** `/generateBorder`  
**Permission:** `cubeengine.vanillaplus.command.border.generate.use`  
  
#### border info  
Shows information about the world border  
**Usage:** `border info <world>`  
**Alias:** `get`  
**Permission:** `cubeengine.vanillaplus.command.border.info.use`  
  
#### border setCenter  
Sets the center for the worldborder  
**Usage:** `border setCenter [x] [z] [in <world>]`  
**Alias:** `center`  
**Permission:** `cubeengine.vanillaplus.command.border.setcenter.use`  
  
#### border setDiameter  
Sets the diameter of the worldborder  
**Usage:** `border setDiameter <size> [seconds] [in <world>]`  
**Alias:** `set`  
**Permission:** `cubeengine.vanillaplus.command.border.setdiameter.use`  
  
#### border warningDistance  
Sets the warning time  
**Usage:** `border warningDistance <blocks> <world>`  
**Permission:** `cubeengine.vanillaplus.command.border.warningdistance.use`  
  
#### border warningTime  
Sets the warning time  
**Usage:** `border warningTime <seconds> <world>`  
**Permission:** `cubeengine.vanillaplus.command.border.warningtime.use`  
  
#### near  
Displays near players(entities/mobs) to you.  
**Usage:** `near [radius] <player> [-entity] [-mob]`  
**Permission:** `cubeengine.vanillaplus.command.near.use`  
  
#### suicide  
Kills yourself  
**Usage:** `suicide `  
**Permission:** `cubeengine.vanillaplus.command.suicide.use`  
  
#### stack  
Stacks your items up to 64  
**Usage:** `stack `  
**Permission:** `cubeengine.vanillaplus.command.stack.use`  
  
#### more  
Refills the stack in hand  
**Usage:** `more [amount] [-all]`  
**Permission:** `cubeengine.vanillaplus.command.more.use`  
  
#### clearinventory  
Clears the inventory  
**Usage:** `clearinventory <player> [-removeArmor] [-quiet] [-force]`  
**Alias:** `ci` `clear`  
**Permission:** `cubeengine.vanillaplus.command.clearinventory.use`  
  
#### starve  
Empties the hunger bar  
**Usage:** `starve [players]`  
**Permission:** `cubeengine.vanillaplus.command.starve.use`  
  
#### rename  
Changes the display name of the item in your hand.  
**Usage:** `rename <name> [lore]`  
**Permission:** `cubeengine.vanillaplus.command.rename.use`  
  
#### weather  
Changes the weather  
**Usage:** `weather <weather> [duration] [in <world>]`  
**Permission:** `cubeengine.vanillaplus.command.weather.use`  
  
#### lag  
Displays chunk, memory and world information.  
**Usage:** `lag `  
**Permission:** `cubeengine.vanillaplus.command.lag.use`  
  
#### butcher  
Gets rid of mobs close to you. Valid types are:
monster, animal, pet, golem, boss, other, creeper, skeleton, spider etc.  
**Usage:** `butcher <types...> [radius] [in <world>] [-lightning] [-all]`  
**Permission:** `cubeengine.vanillaplus.command.butcher.use`  
  
#### whois  
Displays informations from a player!  
**Usage:** `whois <player>`  
**Permission:** `cubeengine.vanillaplus.command.whois.use`  
  
#### lore  
Changes the lore of the item in your hand.  
**Usage:** `lore <lore>`  
**Permission:** `cubeengine.vanillaplus.command.lore.use`  
  
#### stop  
Shuts down the server  
**Usage:** `stop [message]`  
**Alias:** `shutdown` `killserver` `quit`  
**Permission:** `cubeengine.vanillaplus.command.stop.use`  
  
#### plugins  
Lists all loaded plugins  
**Usage:** `plugins `  
**Permission:** `cubeengine.vanillaplus.command.plugins.use`  
  
#### biome  
Displays the biome type you are standing in.  
**Usage:** `biome [world] [block-x] [block-z]`  
**Permission:** `cubeengine.vanillaplus.command.biome.use`  
  
#### item  
Gives the specified Item to you  
**Usage:** `item <material[:data]> [amount] [ench <enchantment[:level]>]`  
**Alias:** `i`  
**Permission:** `cubeengine.vanillaplus.command.item.use`  
  
#### difficulty  
Changes the difficulty level of the server  
**Usage:** `difficulty [difficulty] [world <world>]`  
**Permission:** `cubeengine.vanillaplus.command.difficulty.use`  
  
#### sudo  
Makes a player send a message (including commands)  
**Usage:** `sudo <player> <message>`  
**Permission:** `cubeengine.vanillaplus.command.sudo.use`  
  
#### ping  
Pong!  
**Usage:** `ping `  
**Alias:** `pong`  
**Permission:** `cubeengine.vanillaplus.command.ping.use`  
  
#### god  
Toggles the god-mode!  
**Usage:** `god <player>`  
**Permission:** `cubeengine.vanillaplus.command.god.use`  
  
#### enchant  
Adds an Enchantment to the item in your hand  
**Usage:** `enchant <enchantment> [level] [-unsafe]`  
**Permission:** `cubeengine.vanillaplus.command.enchant.use`  
  
#### give  
Gives the specified Item to a player  
**Usage:** `give <player> <material[:data]> [amount]`  
**Permission:** `cubeengine.vanillaplus.command.give.use`  
  
#### headchange  
Changes a skull to a players skin.  
**Usage:** `headchange [name]`  
**Alias:** `skullchange`  
**Permission:** `cubeengine.vanillaplus.command.headchange.use`  
  
#### saveall  
Saves all or a specific world to disk.  
**Usage:** `saveall [world]`  
**Alias:** `/save-all`  
**Permission:** `cubeengine.vanillaplus.command.saveall.use`  
  
#### removeAll  
Removes entities in a world  
**Usage:** `removeAll <entityType[:itemMaterial]> [in <world>]`  
**Permission:** `cubeengine.vanillaplus.command.removeall.use`  
  
#### gamemode  
Changes the gamemode  
**Usage:** `gamemode [gamemode] <player>`  
**Alias:** `gm`  
**Permission:** `cubeengine.vanillaplus.command.gamemode.use`  
  
#### heal  
Heals a player  
**Usage:** `heal [players]`  
**Permission:** `cubeengine.vanillaplus.command.heal.use`  
  
#### depth  
Displays your current depth.  
**Usage:** `depth `  
**Permission:** `cubeengine.vanillaplus.command.depth.use`  
  
#### version  
Displays the version of the server or a given plugin  
**Usage:** `version [plugin]`  
**Permission:** `cubeengine.vanillaplus.command.version.use`  
  
#### list  
Displays all the online players.  
**Usage:** `list `  
**Permission:** `cubeengine.vanillaplus.command.list.use`  
  
#### seen  
Shows when given player was online the last time  
**Usage:** `seen <player>`  
**Permission:** `cubeengine.vanillaplus.command.seen.use`  
  
#### stash  
Stashes or unstashes your inventory to reuse later  
**Usage:** `stash `  
**Permission:** `cubeengine.vanillaplus.command.stash.use`  
  
#### whitelist  
Allows you to manage your whitelist  
**Usage:** `whitelist <command>`  
**Permission:** `cubeengine.vanillaplus.command.whitelist`  
**SubCommands:** `add` `list` `off` `on` `remove` `wipe`  
#### whitelist add  
Adds a player to the whitelist.  
**Usage:** `whitelist add <player>`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.add.use`  
  
#### whitelist list  
Lists all the whitelisted players  
**Usage:** `whitelist list `  
**Permission:** `cubeengine.vanillaplus.command.whitelist.list.use`  
  
#### whitelist off  
Disables the whitelisting  
**Usage:** `whitelist off `  
**Permission:** `cubeengine.vanillaplus.command.whitelist.off.use`  
  
#### whitelist on  
Enables the whitelisting  
**Usage:** `whitelist on `  
**Permission:** `cubeengine.vanillaplus.command.whitelist.on.use`  
  
#### whitelist remove  
Removes a player from the whitelist.  
**Usage:** `whitelist remove <player>`  
**Alias:** `rm`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.remove.use`  
  
#### whitelist wipe  
Wipes the whitelist completely  
**Usage:** `whitelist wipe `  
**Permission:** `cubeengine.vanillaplus.command.whitelist.wipe.use`  
  
#### remove  
Removes entities in a radius  
**Usage:** `remove <entityType[:itemMaterial]> [radius] [in <world>]`  
**Permission:** `cubeengine.vanillaplus.command.remove.use`  
  
#### feed  
Refills your hunger bar  
**Usage:** `feed [players]`  
**Permission:** `cubeengine.vanillaplus.command.feed.use`  
  
#### fly  
Lets you fly away  
**Usage:** `fly [flyspeed] [player <player>]`  
**Permission:** `cubeengine.vanillaplus.command.fly.use`  
  
#### kill  
Kills a player  
**Usage:** `kill <players> [-force] [-quiet] [-lightning]`  
**Alias:** `slay`  
**Permission:** `cubeengine.vanillaplus.command.kill.use`  
  
#### time  
Changes the time of a world  
**Usage:** `time [time] [in <worlds>] [-lock]`  
**Permission:** `cubeengine.vanillaplus.command.time.use`  
  
#### walkspeed  
Changes your walkspeed.  
**Usage:** `walkspeed <speed> <player>`  
**Permission:** `cubeengine.vanillaplus.command.walkspeed.use`  
  
#### repair  
Repairs your items  
**Usage:** `repair [-all]`  
**Permission:** `cubeengine.vanillaplus.command.repair.use`  
  
#### getPos  
Displays your current location.  
**Usage:** `getPos `  
**Permission:** `cubeengine.vanillaplus.command.getpos.use`  
  
#### compass  
Displays the direction in which you are looking.  
**Usage:** `compass `  
**Permission:** `cubeengine.vanillaplus.command.compass.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.vanillaplus` | Base Permission for vanillaplus |