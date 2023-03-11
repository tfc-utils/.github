## Overview
This GitHub org is intended to be a starting point for someone looking for utilities relevant to the first-person shooter game [Team Fortress Classic](https://store.steampowered.com/app/20/Team_Fortress_Classic/) (TFC).

## Server log analyzers/parsers
* [Hampalyzer](http://app.hampalyzer.com/):
  * Supports submitting a TFC server log to a web service and outputs a summary web page with detailed statistics of either a single game round or two rounds on the same map in which the teams swapped offensive and defensive roles between rounds. This format is common in the TFC pickup community.
  * Has support for custom server plugins reporting player damage information and flag tosses.
  * Its source is available in the [Hampalyzer github project](https://github.com/bananahampster/hampalyzer).

* [The Blarghalyzer](https://blarghalyzer.com/):
  * Supports submitting a TFC server log to a web service and outputs a summary web page with detailed statistics of a single game round.
  * Each round must be submitted individually.
  * It appears to be closed source.

## Server plugins
For the remaining player base that continues to play TFC, server plugins are used for a variety of scenarios such as managing map changes, displaying the score of the previous round to players in-game, address bugs that [Valve](https://www.valvesoftware.com/) hasn't, and enable new statistics to be recorded in logs for use with log analyzers.

TFC server plugins are typically written as plugins for [AMX Mod X](https://github.com/alliedmodders/amxmodx). The [AlliedModders forum](https://forums.alliedmods.net/forumdisplay.php?f=8) is a popular location for individuals to share their own mods.

### Known server configurations
This list is not (yet?) comprehensive.

* Team Fortress PUGs Discord server (a.k.a. "Coach's"):
  * [Restart game plugin](https://github.com/tfc-utils/amx-plugins/tree/main/restartgame)
