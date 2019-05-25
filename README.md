# Lugormod X 
**X version aims to change the core of the Lugormod to bring out its potential and making it compatible with the KotF modification and making it official KotF multiplayer server core.**

# Main features and changes:

## Features which are working now:
- New registration. Username is also character name now.
- AI unlocked. AI is able to use Force user or Mercenary profession.
- Level cap changed up to 120 and added mastery level for Force Users which starts on 40 profession level.
- Reaching mastery level allows to use force of the opposite side and unlocks new power ups.
- Profession change requires a constant credits fee now. (default: 1350 credits)
- Force, health and shield capacity grows per level depending on profession level.

### Added new extern variables usable in server.cfg: 
- lmd_jedi_pickup_weapons - set it to 1 to allow force users to pickup weapons. Force users have ammo capacity penalty which decreases with level.  0 is default - old lugor style.
- lmd_jedi_add_hp_level - set it to 1 to allow Force Users to gain additional HP capacity per level (recommended), set it to 2 to use same algorythm as for Mercenary (op),  0 is default - old lugor style.


### I'm working on:
- Adding new passive-skills to spend additional points on.
- New-Game + after reaching max level capacity.
- Bounty for killing streaks.
- Messages time control.
- Adding extern variable for profession credits fee.
- Bug fixes.

### Main long-terms Goals:
- Full compatibility with all KotF features.
- Adding GUI overlay for console commands.
- More AI improvements.
- Repairing memory leaks.

**Early 3.0.1.0 version Lugor X**

**Compiled files inside ReleaseEnv folder.**

### User Files:
- [Main folder](https://github.com/omatix/Lugor-X)
- [READY SERVER FILES: Compiled server file for Windows](ReleaseEnv/jampgamex86.dll)
- [READY SERVER FILES: Config example with working bots for KotF](__example_config)
- [Compiled whole main folder](ReleaseEnv)
- **Note: you need only [jampgamex86.dll](ReleaseEnv/jampgamex86.dll) to start core server on Windows OS. [Config example](__example_config) is recommended for new users.**

### Credits to:

- Lugor       - for creating early versions of the mod,
- RoboPhred   - for developing the mod for many years,
- Ufo         - for small scale development and producing a linux build.

*Can be compiled using Visual Studio 2013.*
Linux users may use the makefile inside game folder.

Licensed under GPL version 2 or later.

Copyright (C) 2003-2018 RoboPhred.
**Copyright (C) 2019 iomatix.**
