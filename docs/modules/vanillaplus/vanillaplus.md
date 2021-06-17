# CubeEngine - VanillaPlus [WIP]
Improved Vanilla

## Features:
 - Fixes certain vanilla Minecraft behaviors (see configuration for details)
 - Replaces a set of vanilla commands with more user-friendly versions
 - Adds a small set of commonly wanted commands
 - Everything can be disabled

## Commands:

| Command | Description | Permission<br>`cubeengine.vanillaplus.command.<perm>` |
| --- | --- | --- |
| [*biome*](#biome) | Displays the biome type you are standing in. | `biome.use` |
| [*border*](#border) | border commands |  |
| [**border**&nbsp;*add*](#borderadd) | Sets the diameter of the worldborder | `border.add.use` |
| [**border**&nbsp;*center*](#bordercenter) | Sets the center for the worldborder | `border.setCenter.use` |
| [**border**&nbsp;*damage*](#borderdamage) | Sets the world border damage per second per block | `border.damage.use` |
| [**border**&nbsp;*damagebuffer*](#borderdamagebuffer) | Sets the world border damage buffer | `border.damageBuffer.use` |
| [**border**&nbsp;*get*](#borderget) | Shows information about the world border | `border.info.use` |
| [**border**&nbsp;*set*](#borderset) | Sets the diameter of the worldborder | `border.setDiameter.use` |
| [**border**&nbsp;*warningdistance*](#borderwarningdistance) | Sets the warning time | `border.warningDistance.use` |
| [**border**&nbsp;*warningtime*](#borderwarningtime) | Sets the warning time | `border.warningTime.use` |
| [*butcher*](#butcher) | Gets rid of mobs close to you. Valid types are:<br>monster, animal, pet, golem, boss, other, creeper, skeleton, spider etc. | `butcher.use` |
| [*clearinventory*](#clearinventory) | Clears the inventory | `clearinventory.use` |
| [*compass*](#compass) | Displays the direction in which you are looking. | `compass.use` |
| [*depth*](#depth) | Displays your current depth. | `depth.use` |
| [*difficulty*](#difficulty) | Changes the difficulty level of the server | `difficulty.use` |
| [*enchant*](#enchant) | Adds an Enchantment to the item in your hand | `enchant.use` |
| [*feed*](#feed) | Refills your hunger bar | `feed.use` |
| [*fly*](#fly) | Lets you fly away | `fly.use` |
| [*gamemode*](#gamemode) | Changes the gamemode | `gamemode.use` |
| [*getpos*](#getpos) | Displays your current location. | `getPos.use` |
| [*give*](#give) | Gives the specified Item to a player | `give.use` |
| [*god*](#god) | Toggles the god-mode! | `god.use` |
| [*headchange*](#headchange) | Changes a skull to a players skin. | `headchange.use` |
| [*heal*](#heal) | Heals a player | `heal.use` |
| [*hideenchantments*](#hideenchantments) | Toggles the visibility of enchantments | `hideEnchantments.use` |
| [*invsee*](#invsee) | Allows you to see into the inventory of someone else. | `invsee.use` |
| [*item*](#item) | Gives the specified Item to you | `item.use` |
| [*kill*](#kill) | Kills a player | `kill.use` |
| [*lag*](#lag) | Displays chunk, memory and world information. | `lag.use` |
| [*list*](#list) | Displays all the online players. | `list.use` |
| [*listworlds*](#listworlds) | Displays all loaded worlds | `listWorlds.use` |
| [*lore*](#lore) | Changes the lore of the item in your hand. | `lore.use` |
| [*mobstack*](#mobstack) | Spawning stacks of mobs |  |
| [**mobstack**&nbsp;*build*](#mobstackbuild) | Builds mobstack | `mobstack.build.use` |
| [**mobstack**&nbsp;*clear*](#mobstackclear) | Clears the mobstack | `mobstack.clear.use` |
| [**mobstack**&nbsp;*spawn*](#mobstackspawn) | Spawns a mobstack | `mobstack.spawn.use` |
| [*more*](#more) | Refills the stack in hand | `more.use` |
| [*near*](#near) | Displays near players(entities/mobs) to you. | `near.use` |
| [*ping*](#ping) | Pong! | `ping.use` |
| [*plugins*](#plugins) | Lists all loaded plugins | `plugins.use` |
| [*remove*](#remove) | Removes entities in a radius | `remove.use` |
| [*removeall*](#removeall) | Removes entities in a world | `removeAll.use` |
| [*rename*](#rename) | Changes the display name of the item in your hand. | `rename.use` |
| [*repair*](#repair) | Repairs your items | `repair.use` |
| [*seed*](#seed) | Displays the seed of a world. | `seed.use` |
| [*seen*](#seen) | Shows when given player was online the last time | `seen.use` |
| [*spawnmob*](#spawnmob) | Spawns the specified Mob | `spawnMob.use` |
| [*starve*](#starve) | Empties the hunger bar | `starve.use` |
| [*stash*](#stash) | Stashes or unstashes your inventory to reuse later | `stash.use` |
| [*stop*](#stop) | Shuts down the server | `stop.use` |
| [*sudo*](#sudo) | Makes a player send a message (including commands) | `sudo.use` |
| [*suicide*](#suicide) | Kills yourself | `suicide.use` |
| [*time*](#time) | Changes the time of a world | `time.use` |
| [*unlimited*](#unlimited) | Grants unlimited items | `unlimited.use` |
| [*version*](#version) | Displays the version of the server or a given plugin | `version.use` |
| [*walkspeed*](#walkspeed) | Changes your walkspeed. | `walkspeed.use` |
| [*weather*](#weather) | Changes the weather | `weather.use` |
| [*whitelist*](#whitelist) | Allows you to manage your whitelist |  |
| [**whitelist**&nbsp;*add*](#whitelistadd) | Adds a player to the whitelist. | `whitelist.add.use` |
| [**whitelist**&nbsp;*list*](#whitelistlist) | Lists all the whitelisted players | `whitelist.list.use` |
| [**whitelist**&nbsp;*off*](#whitelistoff) | Disables the whitelisting | `whitelist.off.use` |
| [**whitelist**&nbsp;*on*](#whiteliston) | Enables the whitelisting | `whitelist.on.use` |
| [**whitelist**&nbsp;*rm*](#whitelistrm) | Removes a player from the whitelist. | `whitelist.remove.use` |
| [**whitelist**&nbsp;*wipe*](#whitelistwipe) | Wipes the whitelist completely | `whitelist.wipe.use` |
| [*whois*](#whois) | Displays informations from a player! | `whois.use` |

#### biome  
Displays the biome type you are standing in.  
**Usage:** `biome [world] <x> <z>`  
**Permission:** `cubeengine.vanillaplus.command.biome.use`  
  

#### border  
border commands  
**Usage:** `border`  
**SubCommands:** `add` `center` `damage` `damagebuffer` `get` `set` `warningdistance` `warningtime`  

#### border&nbsp;add  
Sets the diameter of the worldborder  
**Usage:** `border add <size> [time][?]`  
**Permission:** `cubeengine.vanillaplus.command.border.add.use`  
  

#### border&nbsp;center  
Sets the center for the worldborder  
**Usage:** `border center [pos][?]`  
**Alias:** `setcenter`  
**Permission:** `cubeengine.vanillaplus.command.border.setCenter.use`  
  

#### border&nbsp;damage  
Sets the world border damage per second per block  
**Usage:** `border damage <damage> [world]`  
**Permission:** `cubeengine.vanillaplus.command.border.damage.use`  
  

#### border&nbsp;damagebuffer  
Sets the world border damage buffer  
**Usage:** `border damagebuffer <blocks> [world]`  
**Permission:** `cubeengine.vanillaplus.command.border.damageBuffer.use`  
  

#### border&nbsp;get  
Shows information about the world border  
**Usage:** `border get [world]`  
**Alias:** `info`  
**Permission:** `cubeengine.vanillaplus.command.border.info.use`  
  

#### border&nbsp;set  
Sets the diameter of the worldborder  
**Usage:** `border set <size> [seconds][?]`  
**Alias:** `setdiameter`  
**Permission:** `cubeengine.vanillaplus.command.border.setDiameter.use`  
  

#### border&nbsp;warningdistance  
Sets the warning time  
**Usage:** `border warningdistance <blocks> [world]`  
**Permission:** `cubeengine.vanillaplus.command.border.warningDistance.use`  
  

#### border&nbsp;warningtime  
Sets the warning time  
**Usage:** `border warningtime <seconds> [world]`  
**Permission:** `cubeengine.vanillaplus.command.border.warningTime.use`  
  

#### butcher  
Gets rid of mobs close to you. Valid types are:
monster, animal, pet, golem, boss, other, creeper, skeleton, spider etc.  
**Usage:** `butcher types... [radius][?][?][?]`  
**Permission:** `cubeengine.vanillaplus.command.butcher.use`  
  

#### clearinventory  
Clears the inventory  
**Usage:** `clearinventory [player][?][?][?]`  
**Alias:** `ci` `clear`  
**Permission:** `cubeengine.vanillaplus.command.clearinventory.use`  
  

#### compass  
Displays the direction in which you are looking.  
**Usage:** `compass`  
**Permission:** `cubeengine.vanillaplus.command.compass.use`  
  

#### depth  
Displays your current depth.  
**Usage:** `depth`  
**Permission:** `cubeengine.vanillaplus.command.depth.use`  
  

#### difficulty  
Changes the difficulty level of the server  
**Usage:** `difficulty [difficulty][?]`  
**Permission:** `cubeengine.vanillaplus.command.difficulty.use`  
  

#### enchant  
Adds an Enchantment to the item in your hand  
**Usage:** `enchant <enchantment> [level][?]`  
**Permission:** `cubeengine.vanillaplus.command.enchant.use`  
  

#### feed  
Refills your hunger bar  
**Usage:** `feed [players]`  
**Permission:** `cubeengine.vanillaplus.command.feed.use`  
  

#### fly  
Lets you fly away  
**Usage:** `fly [flyspeed][?]`  
**Permission:** `cubeengine.vanillaplus.command.fly.use`  
  

#### gamemode  
Changes the gamemode  
**Usage:** `gamemode [gamemode] [player]`  
**Alias:** `gm`  
**Permission:** `cubeengine.vanillaplus.command.gamemode.use`  
  

#### getpos  
Displays your current location.  
**Usage:** `getpos`  
**Permission:** `cubeengine.vanillaplus.command.getPos.use`  
  

#### give  
Gives the specified Item to a player  
**Usage:** `give <player> <itemstack> [amount]`  
**Permission:** `cubeengine.vanillaplus.command.give.use`  
  

#### god  
Toggles the god-mode!  
**Usage:** `god [player]`  
**Permission:** `cubeengine.vanillaplus.command.god.use`  
  

#### headchange  
Changes a skull to a players skin.  
**Usage:** `headchange [name]`  
**Alias:** `skullchange`  
**Permission:** `cubeengine.vanillaplus.command.headchange.use`  
  

#### heal  
Heals a player  
**Usage:** `heal [players]`  
**Permission:** `cubeengine.vanillaplus.command.heal.use`  
  

#### hideenchantments  
Toggles the visibility of enchantments  
**Usage:** `hideenchantments [hide]`  
**Permission:** `cubeengine.vanillaplus.command.hideEnchantments.use`  
  

#### invsee  
Allows you to see into the inventory of someone else.  
**Usage:** `invsee <player>[?][?][?]`  
**Permission:** `cubeengine.vanillaplus.command.invsee.use`  
  

#### item  
Gives the specified Item to you  
**Usage:** `item <itemstack> [amount]`  
**Alias:** `i`  
**Permission:** `cubeengine.vanillaplus.command.item.use`  
  

#### kill  
Kills a player  
**Usage:** `kill <players>[?][?][?]`  
**Alias:** `slay`  
**Permission:** `cubeengine.vanillaplus.command.kill.use`  
  

#### lag  
Displays chunk, memory and world information.  
**Usage:** `lag`  
**Permission:** `cubeengine.vanillaplus.command.lag.use`  
  

#### list  
Displays all the online players.  
**Usage:** `list`  
**Permission:** `cubeengine.vanillaplus.command.list.use`  
  

#### listworlds  
Displays all loaded worlds  
**Usage:** `listworlds`  
**Alias:** `worlds` `worldlist`  
**Permission:** `cubeengine.vanillaplus.command.listWorlds.use`  
  

#### lore  
Changes the lore of the item in your hand.  
**Usage:** `lore <lore>`  
**Permission:** `cubeengine.vanillaplus.command.lore.use`  
  

#### mobstack  
Spawning stacks of mobs  
**Usage:** `mobstack`  
**SubCommands:** `build` `clear` `spawn`  

#### mobstack&nbsp;build  
Builds mobstack  
**Usage:** `mobstack build <type> [data]`  
**Permission:** `cubeengine.vanillaplus.command.mobstack.build.use`  
  

#### mobstack&nbsp;clear  
Clears the mobstack  
**Usage:** `mobstack clear`  
**Permission:** `cubeengine.vanillaplus.command.mobstack.clear.use`  
  

#### mobstack&nbsp;spawn  
Spawns a mobstack  
**Usage:** `mobstack spawn [at]`  
**Permission:** `cubeengine.vanillaplus.command.mobstack.spawn.use`  
  

#### more  
Refills the stack in hand  
**Usage:** `more [amount][?]`  
**Permission:** `cubeengine.vanillaplus.command.more.use`  
  

#### near  
Displays near players(entities/mobs) to you.  
**Usage:** `near [radius] [player][?][?]`  
**Permission:** `cubeengine.vanillaplus.command.near.use`  
  

#### ping  
Pong!  
**Usage:** `ping`  
**Alias:** `pong`  
**Permission:** `cubeengine.vanillaplus.command.ping.use`  
  

#### plugins  
Lists all loaded plugins  
**Usage:** `plugins`  
**Permission:** `cubeengine.vanillaplus.command.plugins.use`  
  

#### remove  
Removes entities in a radius  
**Usage:** `remove <entityType[:itemMaterial]> [radius][?]`  
**Permission:** `cubeengine.vanillaplus.command.remove.use`  
  

#### removeall  
Removes entities in a world  
**Usage:** `removeall <entityType[:itemMaterial]>[?]`  
**Permission:** `cubeengine.vanillaplus.command.removeAll.use`  
  

#### rename  
Changes the display name of the item in your hand.  
**Usage:** `rename <name> [lore]`  
**Permission:** `cubeengine.vanillaplus.command.rename.use`  
  

#### repair  
Repairs your items  
**Usage:** `repair[?]`  
**Permission:** `cubeengine.vanillaplus.command.repair.use`  
  

#### seed  
Displays the seed of a world.  
**Usage:** `seed [world]`  
**Permission:** `cubeengine.vanillaplus.command.seed.use`  
  

#### seen  
Shows when given player was online the last time  
**Usage:** `seen <player>`  
**Permission:** `cubeengine.vanillaplus.command.seen.use`  
  

#### spawnmob  
Spawns the specified Mob  
**Usage:** `spawnmob <type> [amount] [data] [at]`  
**Permission:** `cubeengine.vanillaplus.command.spawnMob.use`  
  

#### starve  
Empties the hunger bar  
**Usage:** `starve [players]`  
**Permission:** `cubeengine.vanillaplus.command.starve.use`  
  

#### stash  
Stashes or unstashes your inventory to reuse later  
**Usage:** `stash`  
**Permission:** `cubeengine.vanillaplus.command.stash.use`  
  

#### stop  
Shuts down the server  
**Usage:** `stop [message]`  
**Alias:** `killserver` `quit` `shutdown`  
**Permission:** `cubeengine.vanillaplus.command.stop.use`  
  

#### sudo  
Makes a player send a message (including commands)  
**Usage:** `sudo <player> <message>`  
**Permission:** `cubeengine.vanillaplus.command.sudo.use`  
  

#### suicide  
Kills yourself  
**Usage:** `suicide`  
**Permission:** `cubeengine.vanillaplus.command.suicide.use`  
  

#### time  
Changes the time of a world  
**Usage:** `time [time][?][?]`  
**Permission:** `cubeengine.vanillaplus.command.time.use`  
  

#### unlimited  
Grants unlimited items  
**Usage:** `unlimited [unlimited]`  
**Permission:** `cubeengine.vanillaplus.command.unlimited.use`  
  

#### version  
Displays the version of the server or a given plugin  
**Usage:** `version [plugin]`  
**Permission:** `cubeengine.vanillaplus.command.version.use`  
  

#### walkspeed  
Changes your walkspeed.  
**Usage:** `walkspeed <speed> [player]`  
**Permission:** `cubeengine.vanillaplus.command.walkspeed.use`  
  

#### weather  
Changes the weather  
**Usage:** `weather <weather> [duration][?]`  
**Permission:** `cubeengine.vanillaplus.command.weather.use`  
  

#### whitelist  
Allows you to manage your whitelist  
**Usage:** `whitelist`  
**SubCommands:** `add` `list` `off` `on` `rm` `wipe`  

#### whitelist&nbsp;add  
Adds a player to the whitelist.  
**Usage:** `whitelist add <player>`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.add.use`  
  

#### whitelist&nbsp;list  
Lists all the whitelisted players  
**Usage:** `whitelist list`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.list.use`  
  

#### whitelist&nbsp;off  
Disables the whitelisting  
**Usage:** `whitelist off`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.off.use`  
  

#### whitelist&nbsp;on  
Enables the whitelisting  
**Usage:** `whitelist on`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.on.use`  
  

#### whitelist&nbsp;rm  
Removes a player from the whitelist.  
**Usage:** `whitelist rm <player>`  
**Alias:** `remove`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.remove.use`  
  

#### whitelist&nbsp;wipe  
Wipes the whitelist completely  
**Usage:** `whitelist wipe`  
**Permission:** `cubeengine.vanillaplus.command.whitelist.wipe.use`  
  

#### whois  
Displays informations from a player!  
**Usage:** `whois <player>`  
**Permission:** `cubeengine.vanillaplus.command.whois.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.vanillaplus` | Base Permission for VanillaPlus |
| `cubeengine.vanillaplus.changepainting` |  |
| `cubeengine.vanillaplus.command.butcher.all` |  |
| `cubeengine.vanillaplus.command.butcher.alltypes` |  |
| `cubeengine.vanillaplus.command.butcher.flag` |  |
| `cubeengine.vanillaplus.command.butcher.flag.ambient` |  |
| `cubeengine.vanillaplus.command.butcher.flag.animal` |  |
| `cubeengine.vanillaplus.command.butcher.flag.boss` |  |
| `cubeengine.vanillaplus.command.butcher.flag.golem` |  |
| `cubeengine.vanillaplus.command.butcher.flag.hostile` |  |
| `cubeengine.vanillaplus.command.butcher.flag.monster` |  |
| `cubeengine.vanillaplus.command.butcher.flag.npc` |  |
| `cubeengine.vanillaplus.command.butcher.flag.pet` |  |
| `cubeengine.vanillaplus.command.butcher.lightning` |  |
| `cubeengine.vanillaplus.command.clearinventory.force` | Clears an inventory even if the player has the prevent PermissionDescription |
| `cubeengine.vanillaplus.command.clearinventory.notify` | Allows clearing the inventory of other players |
| `cubeengine.vanillaplus.command.clearinventory.other` | Notifies you if your inventory got cleared by someone else |
| `cubeengine.vanillaplus.command.clearinventory.prevent` | Prevents your inventory from being cleared unless forced |
| `cubeengine.vanillaplus.command.feed.other` | Allows feeding other players |
| `cubeengine.vanillaplus.command.fly.other` |  |
| `cubeengine.vanillaplus.command.gamemode.other` | Allows to change the game-mode of other players too |
| `cubeengine.vanillaplus.command.god.other` | Allows to enable god-mode for other players |
| `cubeengine.vanillaplus.command.heal.other` |  |
| `cubeengine.vanillaplus.command.invsee.ender` | Allows to look at someones enderchest |
| `cubeengine.vanillaplus.command.invsee.modify.allow` | Allows to modify the inventory of other players |
| `cubeengine.vanillaplus.command.invsee.modify.force` | Allows modifying an inventory even if the player has the prevent permission |
| `cubeengine.vanillaplus.command.invsee.modify.prevent` | Prevents an inventory from being modified unless forced |
| `cubeengine.vanillaplus.command.invsee.notify` | Notifies you when someone is looking into your inventory |
| `cubeengine.vanillaplus.command.invsee.quiet` | Prevents the other player from being notified when looking into his inventory |
| `cubeengine.vanillaplus.command.kill.all` | Allows killing all players currently online |
| `cubeengine.vanillaplus.command.kill.force` | Kills a player even if the player has the prevent PermissionDescription |
| `cubeengine.vanillaplus.command.kill.lightning` | Allows killing a player with a lightning strike |
| `cubeengine.vanillaplus.command.kill.notify` | Shows who killed you |
| `cubeengine.vanillaplus.command.kill.prevent` | Prevents from being killed by the kill command unless forced |
| `cubeengine.vanillaplus.command.kill.quiet` | Prevents the other player being notified who killed him |
| `cubeengine.vanillaplus.command.starve.other` | Allows starving other players |
| `cubeengine.vanillaplus.command.version.plugins` |  |
| `cubeengine.vanillaplus.command.walkspeed.other` | Allows to change the walkspeed of other players |
| `cubeengine.vanillaplus.effect.unlimited-food` | Grants unlimited food |
| `cubeengine.vanillaplus.sign.colored` |  |
| `cubeengine.vanillaplus.sign.styled` |  |
