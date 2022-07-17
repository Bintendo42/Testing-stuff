# OpenGoal-CheckpointRandomizer
Gives a random checkpoint after X amount of cells, uses OpenGOAL project by the OpenGOAL team.

[Download latest](https://github.com/zedb0t/opengoal-checkpointrandomizer/releases/latest/download/opengoal-checkpointrandomizer-0.06.zip)  

[![Github All Releases](https://img.shields.io/github/downloads/zedb0t/OpenGoal-CheckpointRandomizer/total.svg)]()

Tips/Notes:

- The generated checkpoint list may contain citadel checkpoints at any point, however they will be skipped until you trigger the green sage citadel cutscene (either skipping or watching it). Just in case you hold off citadel till the very last moment, the list should have 96 non-citadel checkpoints, followed by any 5 checkpoints (and then loops back around as a failsafe).
- If you load a fresh file (0 cells), the checkpoint list is regenerated from the random/set seed when you collect the first cell.
- There is only one checkpoint list at a time, so if you load between different files don't expect it to switch back to a previous checkpoint list.
- If you reboot/close/crash the game, just be sure to load the right file. We backup the number of checkpoints used from the list every time you collect a cell, and use it to regenerate the checkpoint list/state in this scenario.
