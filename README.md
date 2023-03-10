# Max & Unlock
Utility for adjusting amounts, levels and unlocks in The Walking Dead: Saints &amp; Sinners save files.

This utility was originally used to modify PCVR save files, but has been verified to function with save files exported from The Walking Dead: Saints & Sinners Chapter 1 intended for use with the import function of The Walking Dead: Saints & Sinners Chapter 2: Retribution.

This utility will not add ammunition, materials or crafting tables that are not already in the save file. It will only adjust amounts of those which already have entries in the save file.

In order to include and adjust Chapter 2 ammo, materials and table levels you will need a save that already includes these. One can be found described and linked in the video linked below.

**Everything Unlocked Retribution Save for Quest**

https://youtu.be/PNYsY-7tGGc

While this utility will attempt to create a backup, please create your own backups. This utility is provided for use as-is and at own risk.

**Usage:**

  `max-and-unlock.exe -a 100 -r 100 -t 9 -u 2 -s TWDCH1_Data.sav`

**Options:**

  `-s, --save         Required. Path to .SAV file`

  `-a, --ammo         (Default: -1) New ammunition count 0-999,999`

  `-r, --resources    (Default: -1) New resource count 0-999,999`

  `-t, --tables       (Default: -1) New table level 0-9`

  `-u, --unlocks      (Default: -1) 0=none, 1=CH1 unlocks, 2=CH1 & CH2 unlocks`

  `--help             Display this help screen.`

  `--version          Display version information.`
