# RNGS_SPAWN_MOD

Updated spawns for Stay in Tarkov using the build in spawn system. This is still in beta, please report any issues found with this on discord to rngenerous.

There are 2 versions of this, standard and FPS+.

- Standard: Made to feel as close to live as possible.
- FPS+ (Alpha): Should still feel closer to live, but has a number of changes to increase FPS, use this if you are having FPS issues.

Additionally there is a folder for 'vanilla bosses' for each of these where the boss spawns have not been changed.

## Installation

- Backup '<SIT_SERVER_DIR>/Aki_Data/Server/database/locations'
- Copy and paste the contents of 'RNGS_SPAWN_MOD/\<VERSION\>/standard/' into '<SIT_SERVER_DIR>/Aki_Data/Server/database/locations' and override
- Delete the 'jsonCache.json' and 'modCache.json' files in '<SIT_SERVER_DIR>/user/cache'
- Restart the server

## Todo

- Finish FPS+
- Missing folders is because they are not finished yet

## Changes

- General changes
  - Nerfed Goon Spawn %
  - Made waves feel a lot better, should feel more live like then live
  - Raised Bot Cap
  - Fixed
    - "BotStart"
    - "BotStartPlayer"
    - "BotStop":
- Customs
  - PMCBOT 5%
  - BOSSANITAR 10%
  - BOSSGLUHAR 10%
  - sectantPriest 10%,
- Factory day/night
  - BOSSKILLA 5%
  - PMCBOT 10%
  - GOONS 1%, 2x at night
- Interchange
  - BOSSTAGILLA 10%
  - PMCBOT 5%
  - BOSSBULLY 10%
- Labs
  - BOSS SANITAR 10%
  - BOSSTAGILLA 25%
  - BOSSKILLA 15%
  - REWORKED PMCBOT AKA RAIDER SPAWN SYSTEM have fun ;)
- Lighthouse
  - CRAZYASSULTEVENT 25%
  - REWORKED EXUSEC SPAWN SYSTEM
- Reserve
  - Reworked PMCBOT SPAWN SYSTEM
- Shoreline
  - ADDED BOSS EXUSEC 10%
  - ADDED BOSSKOJANIY 15%
  - ADDED GOONS 10%
  - ADDED CRAZYASSUALTEVENT
- Streets
  - SECTANTPREIST 15%
  - PMCBOT 30%
  - BOSSSANITAR 15%
  - BOSSKILLA 10%
  - BOSSGLUHAR 15%
  - BOSSBULLY 20%
- Woods
  - BOSSKOJANIY 30%
  - ADDED CRAZYASSUALTEVENT

## Rules

- (Normal: = default scavs will fight pmc, pmc wont fight same faction )
- (AvoidOwnPMC: ?? test this i didnt have time)
- (AvoidAllPMC: ALL PMC HOSTILE TO SAME FACTION/OPPOSITE FACTION & SCAVS)

## Credits

- rngenerous - Making and maintaining this mod
