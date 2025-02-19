## Change log

**6.0.0 - Refactor!**

- command arguments have been refactored to pass as an object instead of an array (This is not backwards compatible which is why it's a version bump)

**5.0.2 - New commands and docs!**

- added screenshot command
- added weather, blackout, time commands
- added docs at [zfbx.github.io/zdiscord](https://zfbx.github.io/zdiscord)
- updated/fixed chat events and teleport command

**5.0.1 - Exports and ace perms**

- Automatic Ace permission granting by discord role
- new and changed exports for checking if role exist and getting roles

**5.0.0 - Hello discord.js! & Much much more.**

*It should be noted, this is essentially a complete rewrite of the resource and should probably be treated as such.*

- NEW LICENSE - GPL version 3.0
- Replaced eris with discord.js
- replaced commands with slash commands
- added a bunch of new commands
- added a utils file to cleanup the main script
- added client.js for running events client side
- added linting and editorconfig

**4.0.0 - permissions! bye yarn!.. and esx.**

- Dependencies are now embedded libs making the project slimmer on install and not requiring yarn.
- ESX support was dropped, it wasn't getting used and I don't have an esx server for testing.
- translations were slimmed down to fivem messages only.
- `add/removepermissions` merged into `perms` command
-  Convars changed to be more readable using standard FiveM format with `_` spacing

**3.2.0 - Convars everywhere!**

- Convar hooks added for nearly every config option [Read More](https://github.com/zfbx/zdiscord/wiki/Convars)
- Slimmed up locales by removing console log messages
- Added {prefix} to the global variables
- New Add/Remove permissions command for QBCore


**3.1.0 - QBCore (potential ESX) support added**

- Commands starting with `qb-` will load automatically if QBCore is detected.
- Placeholders for `esx-` commands have been added.


**3.0.0 - Modular commands!**

- Commands are now loaded dynamically from the `/commands` folder
- Help command now has sub commands `!help commandName`
- New DM command
- various Error checks and fixes


**2.0.0 - Github Release**

- polished standalone
- Added translation support


**1.0.0 - First unsupported build**

- A lot.
