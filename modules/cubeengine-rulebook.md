# CubeEngine - Rulebook
Puts a book in the inventory of new players.

## Features:
 - Provide predefined books to new players

## Commands:

| Command | Description | Permission<br>`cubeengine.rulebook.command.<perm>` |
| --- | --- | --- |
| [*rulebook*](#rulebook) | Shows all commands of the rulebook module | `rulebook` |
| [**rulebook**&nbsp;*add*](#rulebook&nbsp;add) | adds the book in hand as rulebook of the declared language | `rulebook.add.use` |
| [**rulebook**&nbsp;*getRuleBook*](#rulebook&nbsp;getrulebook) | gets the player the rulebook in the inventory | `rulebook.getrulebook.use` |
| [**rulebook**&nbsp;*list*](#rulebook&nbsp;list) | list all available languages of the rulebooks. | `rulebook.list.use` |
| [**rulebook**&nbsp;*modify*](#rulebook&nbsp;modify) | modified the rulebook of the declared language with the book in hand | `rulebook.modify.use` |
| [**rulebook**&nbsp;*remove*](#rulebook&nbsp;remove) | removes the declared language and languagefiles! | `rulebook.remove.use` |

#### rulebook  
Shows all commands of the rulebook module  
**Usage:** `rulebook <command>`  
**Permission:** `cubeengine.rulebook.command.rulebook`  
**SubCommands:** `add` `getRuleBook` `list` `modify` `remove`  

#### rulebook&nbsp;add  
adds the book in hand as rulebook of the declared language  
**Usage:** `rulebook add <language>`  
**Alias:** `/addrules`  
**Permission:** `cubeengine.rulebook.command.rulebook.add.use`  
  

#### rulebook&nbsp;getRuleBook  
gets the player the rulebook in the inventory  
**Usage:** `rulebook getRuleBook [language] [player <player>]`  
**Alias:** `/getrules` `/rules`  
**Permission:** `cubeengine.rulebook.command.rulebook.getrulebook.use`  
  

#### rulebook&nbsp;list  
list all available languages of the rulebooks.  
**Usage:** `rulebook list [-supported]`  
**Alias:** `/listrules`  
**Permission:** `cubeengine.rulebook.command.rulebook.list.use`  
  

#### rulebook&nbsp;modify  
modified the rulebook of the declared language with the book in hand  
**Usage:** `rulebook modify <language>`  
**Alias:** `/modifyrules`  
**Permission:** `cubeengine.rulebook.command.rulebook.modify.use`  
  

#### rulebook&nbsp;remove  
removes the declared language and languagefiles!  
**Usage:** `rulebook remove <language>`  
**Alias:** `/removerules`  
**Permission:** `cubeengine.rulebook.command.rulebook.remove.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.rulebook` | Base Permission for rulebook |