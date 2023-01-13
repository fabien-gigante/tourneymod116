# Tourney Mod 1.16
(Formerly MSM3 Mod) This is a general tournament mod for 1.16. Implementation is based on Seedcycle, MSL and Pre1.9 Racemod.

## Features

- Seed-standardized piglin trades, blaze rod drops, zero cycles (angle, 1/8, target node height), flint rates, ender eye breaks
- Zero cycles are also possible on more seeds. Node height ranges from 0-5 blocks above the minimum height, instead of the vanilla range of 0-20. the 1/8 chance of the dragon picking a horizontal node is now 1/16.
- Golems always drop 4 iron
- Removes mining fatigue effect from elder guardians
- Dragon always perches after 2.5 minutes after entering end, resets on relog.
- Removes mob spawns in temples during the daytime 


## Modifying RNG

The seeds are stored in the world file, in /data/[state name].dat. This can be modified using any NBT editor (I use intellij with the Minecraft Developer Plugin to edit these).
