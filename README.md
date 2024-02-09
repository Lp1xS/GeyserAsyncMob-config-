# GeyserAsyncMob-config
Config from the project "GeyserMX", the kernel could not cope with this, had to do it myself.

# async.yml

settings:
 spawnDelay: 4
 spawnPersDelay: 3.25
 spawnDistanceMob: 20
 maxSpawning: 200
 mobClearTime: 10 # minute

messages:
 help: -|
  - "&fReload plugin: /gasync reload" # gasync.admin
  - "&fEnable/disabler notifer: /gasync (world name) off/on" # gasync.notifer
  - "&f"
 permission: "&cYou dont have permission, &agasync.admin"
 reloaded: "&aPlugin reloaded"
 mobAmountNotifer: "World %world% amount mob %mobs%"
 mobClearNotifer: "Mobs remove: %time%"
 
