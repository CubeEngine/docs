# CubeEngine - Conomy
Economy API and basic commands
## Features:
 - Implementation of the standard Economy interface
 - Individual user accounts
 - Banks
 - Configurable currencies
## Commands
| Command | Description | Permission<br>`cubeengine.conomy.command.<perm>` |
| --- | --- | --- |
| [*eco*](#eco) | Administrative commands for Conomy | `eco` |
| [**eco** *give*](#eco-give) | Gives money to one or all players. | `eco.give.use` |
| [**eco** *hide*](#eco-hide) | Hides the account of a given player | `eco.hide.use` |
| [**eco** *reset*](#eco-reset) | Reset the money from given user | `eco.reset.use` |
| [**eco** *set*](#eco-set) | Sets the money of a given player | `eco.set.use` |
| [**eco** *take*](#eco-take) | Takes money from given user | `eco.take.use` |
| [**eco** *unhide*](#eco-unhide) | Unhides the account of a given player | `eco.unhide.use` |
| [*money*](#money) | Manage your money | `money` |
| [**money** *balance*](#money-balance) | Shows your balance | `money.balance.use` |
| [**money** *pay*](#money-pay) | Transfer the given amount to another account. | `money.pay.use` |
| [**money** *top*](#money-top) | Shows the players with the highest balance. | `money.top.use` |
#### eco  
Administrative commands for Conomy  
**Usage:** `eco <command>`  
**Permission:** `cubeengine.conomy.command.eco`  
**SubCommands:** `give` `hide` `reset` `set` `take` `unhide`  
#### eco give  
Gives money to one or all players.  
**Usage:** `eco give <*|<players>> <amount>`  
**Alias:** `grant`  
**Permission:** `cubeengine.conomy.command.eco.give.use`  
  
#### eco hide  
Hides the account of a given player  
**Usage:** `eco hide <*|<players>>`  
**Permission:** `cubeengine.conomy.command.eco.hide.use`  
  
#### eco reset  
Reset the money from given user  
**Usage:** `eco reset <*|<players>>`  
**Permission:** `cubeengine.conomy.command.eco.reset.use`  
  
#### eco set  
Sets the money of a given player  
**Usage:** `eco set <*|<players>> <amount>`  
**Permission:** `cubeengine.conomy.command.eco.set.use`  
  
#### eco take  
Takes money from given user  
**Usage:** `eco take <*|<players>> <amount>`  
**Alias:** `remove`  
**Permission:** `cubeengine.conomy.command.eco.take.use`  
  
#### eco unhide  
Unhides the account of a given player  
**Usage:** `eco unhide <*|<players>>`  
**Permission:** `cubeengine.conomy.command.eco.unhide.use`  
  
#### money  
Manage your money  
**Usage:** `money <command>`  
**Permission:** `cubeengine.conomy.command.money`  
**SubCommands:** `balance` `pay` `top`  
#### money balance  
Shows your balance  
**Usage:** `money balance <account>`  
**Alias:** `/balance` `/moneybalance` `/pmoney`  
**Permission:** `cubeengine.conomy.command.money.balance.use`  
  
#### money pay  
Transfer the given amount to another account.  
**Usage:** `money pay <*|<players>> <amount> [as <source>]`  
**Alias:** `give` `/pay`  
**Permission:** `cubeengine.conomy.command.money.pay.use`  
  
#### money top  
Shows the players with the highest balance.  
**Usage:** `money top [[fromRank-]toRank]`  
**Alias:** `/toplist` `/balancetop` `/topmoney`  
**Permission:** `cubeengine.conomy.command.money.top.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.conomy` | Base Permission for conomy |