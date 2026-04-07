# Commands

> Synced from the new wiki page: <https://docs.phoenixdevt.fr/mmocore/general/commands.html>

Below is a list of available MMOCore commands. You can also explore these in-game with tab completion.

## General

| Command | Usage |
| --- | --- |
| `/mmocore` | Displays the main help page. |
| `/mmocore reload` | Reloads the plugin after editing config files (no server restart needed). |

## Currency

| Command | Usage |
| --- | --- |
| `/mmocore note` | Gives players a note worth `$X`, depositable in banks. |
| `/mmocore coins` | Gives players gold coins based on the input amount. |

## Quests

| Command | Usage |
| --- | --- |
| `/mmocore quest start` | Force starts a quest for a player. |
| `/mmocore quest cancel` | Force cancels a player's current quest. |

## Waypoints

| Command | Usage |
| --- | --- |
| `/mmocore waypoints unlock` | Manually unlocks a waypoint for a player. |
| `/mmocore waypoints lock` | Manually locks a waypoint for a player. |
| `/mmocore waypoints teleport` | Manually teleports a player to a waypoint. |
| `/mmocore waypoints open` | Opens waypoint menu and checks if the player is standing on a waypoint. |

## Admin

| Command | Usage |
| --- | --- |
| `/mmocore admin exportdata` | Exports player data from yml files to SQL. |
| `/mmocore admin attr-realloc-points <give/set>` | Gives attribute reallocation points. |
| `/mmocore admin attribute-points <give/set>` | Gives attribute points. |
| `/mmocore admin attribute <give/take>` | Increases or decreases a player's attribute. |
| `/mmocore admin force-class` | Force-sets a player's class without updating related class data. |
| `/mmocore admin class-points` | Gives class points to a player. |
| `/mmocore admin exp give <player> <profession/main> <value> <split>` | Gives profession/class experience. |
| `/mmocore admin exp set <player> <profession/main> <value>` | Sets profession/class EXP. |
| `/mmocore admin exp take <player> <profession/main> <value>` | Removes profession/class EXP. |
| `/mmocore admin hideab <player> <ticks>` | Hides a player's action bar for X ticks. |
| `/mmocore admin info` | Shows a level summary for a player. |
| `/mmocore admin level <profession/main>` | Gives levels using EXP-like parameters. |
| `/mmocore admin nocd` | Tests skills without cooldown and mana usage. |
| `/mmocore admin reset <player>` | Hard-resets player data (class, level, EXP, etc.). |
| `/mmocore admin resource-health <give/set/take>` | Modifies player health resource. |
| `/mmocore admin resource-mana <give/set/take>` | Modifies player mana resource. |
| `/mmocore admin resource-stamina <give/set/take>` | Modifies player stamina resource. |
| `/mmocore admin resource-stellium <give/set/take>` | Modifies player stellium resource. |
| `/mmocore admin skill-points <give/set>` | Gives skill points. |
| `/mmocore admin skill-realloc-points <give/set>` | Gives skill reallocation points. |
| `/mmocore admin skill <give/set>` | Gives points directly to a skill. |
| `/mmocore admin skill <lock/unlock>` | Locks/unlocks a skill. |
| `/mmocore admin slot <lock/unlock>` | Locks/unlocks a slot. |
| `/mmocore admin slot bind <slot> <skill>` | Binds a skill to a slot. |
| `/mmocore admin slot unbind <slot>` | Unbinds a skill from a slot. |

## Classes

| Command | Usage |
| --- | --- |
| `/mmocore class force <player> <class>` | Forcefully sets class without loading class data. |
| `/mmocore class select <player> <class>` | Sets class and loads class data. |
| `/mmocore class check <player>` | Prints the current class of a player. |

## EXP Boosts

| Command | Usage |
| --- | --- |
| `/mmocore booster create <profession/main> (player)` | Creates an EXP booster with configured power and duration. |
| `/mmocore booster list` | Displays active EXP boosters. |
| `/mmocore booster remove` | Removes a booster by ID. |
