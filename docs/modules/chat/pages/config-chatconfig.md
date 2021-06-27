# ChatConfig

```yaml
# The following variables are available:
# - {NAME} -> player name
# - {DISPLAY_NAME} -> display name
# - {WORLD} -> the world the player is in
# - {MESSAGE} -> the message
# - {ROLE.PREFIX} -> a prefix set in the role module
# - {ROLE.SUFFIX} -> a suffix set in the role module
# 
# Usual color/format codes are also supported: &1, ... &f, ... &r
format: '{NAME}: {MESSAGE}'

# This also counts for the format string!
allow-colors: true
auto-afk: 
  # Players will be automatically displayed as afk after this amount of time
  after: 0D0H5M0S

  # How often the server will check for afk players
  # Set to 0 to disable auto-afk
  check: 0D0H0M1S

```
