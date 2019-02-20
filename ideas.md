# Plugin Ideas

## ripcord

Get motd players
Loadbalance 

## Lock Doors

- iron doors can not be open
- only through command
  - cancel interact?
  - lock player, hack so door is closed by updating block
  - unlock player

## WorldBrush

- From  WorldEditor
  - Only grab the cut/copy/paste add undo
  - Other commands as needed
- wall, floor ... enter command extends in the direction you are looking at with given block and dimensions.
- cube, box
- pyramid, diamond, sphere
- steps
- pool
- undo/redo?
- show selection


## Syslog Interceptor

- Attach to MainLogger - send UDP logs
  - see [syslog](http://php.net/manual/en/function.syslog.php)
  - [MainLogger](https://github.com/PocketMine/PocketMine-MP/blob/master/src/pocketmine/utils/MainLogger.php#L201)
- [PocketDockConsole](https://github.com/PocketDock/PocketDockConsole/blob/master/src/PocketDockConsole/Attachment.php)

## Add Web Interface to PurePerms

How to use Volt.  Add a collapsable tree.  And look like this:
<http://www.sitepoint.com/role-based-access-control-in-php/>
Add per worl permission.
Add remove user roles
http://code.tutsplus.com/tutorials/an-introduction-to-handlebars--net-27761

## Java Bridge

JavaBridge: http://php-java-bridge.sourceforge.net/pjb/desktop-apps.php


## Creative-PvP

- on-damage:
  - stop: show message and cancel event
  - warn: just show message
  - switch: show message and switch to survival
- on-kill:
  - stop: show message and cancel event
  - warn: show message
  - switch: show message and switch to survival
- creative-pvp:  true|false
   - update health, send tip (with health values)

## MapGen

Port minetest mapgenerator:
[src](https://github.com/minetest/minetest/tree/master/src)

Look for mapgen_v6

- v5 is slow.
- v6 is stable.  We would port this one
- v7 is in development.

Reference:  [MapGen wiki](http://wiki.minetest.net/Mapgen_)
Biomes by mapgen_v6 [biomes](http://wiki.minetest.net/Biomes)

Map is: , the map is a cube with a side length of 61840 node lengths. T
 The coordinates range from −30912 to 30927 in all dimensions.
[Settings](http://wiki.minetest.net/Map_generator/settings)

Minetest minecraft compatibility:

- Bedrock spawns at -64.
- Max build height is 192
- From -64 to 192 is the playing area so 256 blocks high (Anvil).... McRegion is only 128!


