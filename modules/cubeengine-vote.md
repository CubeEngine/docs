# CubeEngine - Vote
This module integrates into Votifier to provide vote rewards

## Features:
 - Based on votifier
 - Rewards voting players
 - Chat broadcasts on votes
 - Bonus for repeated vites

## Dependencies:
 `nuvotifier` `cubeengine-sql`

## Commands:

| Command | Description | Permission<br>`cubeengine.vote.command.<perm>` |
| --- | --- | --- |
| [*vote*](#vote) | Shows your current vote situation | `vote.use` |

#### vote  
Shows your current vote situation  
**Usage:** `vote `  
**Permission:** `cubeengine.vote.command.vote.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.vote` | Base Permission for Vote |
| `cubeengine.vote.command` | Allows using all commands of Vote |
