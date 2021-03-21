# Achaea-Nexus-Patrolling
A reflex package for Achaea's Nexus client

## Background
If you aren't familiar with it, [Achaea](https://www.achaea.com) is a text-based MUD (multi-user dungeon). Due to being text based, it offers a high degree of customizability in the way of writing scripts to assist with various tasks, which is what this is.

## Background for Achaeans
This is a port for Nexus of Gavriil's missing plants script, which was written in Lua. If you're a part of the Wildwalkers clan, check the "scripts" scroll for more info.

# Installation
Download the .nxs.json files that you want to use. Then, in the Nexus settings under "Reflex Packages", drag and drop it into the large box.

- "Patrol completion" is a package that tracks which rooms you've visited in a certain area. Keep in mind it doesn't know about unmapped rooms. 
- "Patrolling" is the plant tracking part, and will also notify you of any shrines or totems in forests or jungles (as long as the shrine isn't to Lady Gaia).

# Miscellaneous notes
* There's a little bit of Don't Repeat Yourself violation in some portions of the code, but it's not something I think I care enough to fix.
* At some point I want to ignore missing plants in rooms that are known to be unable to grow any. I just need their room IDs and it should be a pretty easy change.
* I also want to add in a "patrol report" command, similar to what Irissa's reporting script does.
* I still need to add in gagging of the plant output. This is a bit of a pain with Nexus's API, and mildly buggy when using its Simplified Scripting System for some reason.
