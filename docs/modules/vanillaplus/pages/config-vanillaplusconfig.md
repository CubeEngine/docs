# VanillaPlusConfig

```yaml
fix: 
  # Allows using & followed by the appropriate color-code or style-code to write colored signs
  styled-signs: true

  # Retains fly-mode on login
  safe-login-fly: true

  # Teleports to spawn when logging in outside of worldborder
  safe-login-border: true

  # Right click on a painting allows switching the painting with the mouse wheel
  painting-switcher: true
  painting-switcher-max-distance: 10

  # Shows the tamer of an animal when rightclicking on it
  show-tamer: true

improve: 
  # Adds /remove as an alternative for killing non living entities only
  command-remove: true
  command-remove-default-radius: 20

  # Also /butcher for living entities only
  command-butcher: true
  command-butcher-default-radius: 20

  # Also adds an alias /spawnmob for living entities only
  command-summon: true
  spawnmob-limit: 20

  # Improves /clear and adds some aliases
  command-clearinventory: true

  # Improves /difficulty
  command-difficulty: true

  # Improves /gamemode e.g. allowing to toggle between survival and creative
  command-gamemode: true

  # Improves /give
  # Adds an alias /item to give an item to yourself
  # Adds /more to refill itemstacks
  # Adds /stack to stack similar items together
  command-item: true

  # Allows stacking tools and other items up to 64 even when they usually do not stack that high
  command-stack-tools: false

  # Improves /enchant
  # Adds /rename and /lore to allow colored ItemNames and Lore
  # Adds /headchange to change any head to a player-head of your choice
  # Adds /repair to refill the durability of tools
  command-item-modify: true

  # Improves /kill
  # Adds an alias /suicide to kill yourself
  command-kill: true

  # Improves /op and /deop
  command-op: true

  # Improves /list
  command-list: true

  # Improves /save-all /save-on /save-off
  command-save: true

  # Improves /stop including a kick reason for the players
  command-stop: true
  command-stop-default-message: Server is shutting down.

  # Improves /time with per World time and adds /ptime for per Player time
  command-time: true

  # Improves /weather with per World weather and adds /pweather for per Player weather
  command-weather: true

  # Improves /whitelist
  command-whitelist: true

  # Improves /worldborder
  command-border-enable: true

  # Maximum world border diameter for generation
  command-border-max: 5000

add: 
  # Adds /god
  command-god: true

  # Adds /heal
  command-heal: true

  # Adds /biome, /seed, /compass, /depth, /getPos, /near, /ping, /lag, /listWorlds
  commands-information: true
  command-near-default-radius: 20

  # Adds /invsee
  command-invsee: true

  # Adds /walkspeed and /fly
  commands-movement: true

  # Adds /feed and /starve
  commands-food: true

  # Adds /seen and /whois
  commands-player-information: true

  # Adds /plugins and /version
  commands-plugins: true

  # Adds /stash
  command-stash: true

  # Adds /sudo
  command-sudo: true

  # Adds /unlimited
  command-unlimited: true

  # Grants unlimited food for players with the permission
  unlimited-food: true

```
