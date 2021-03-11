# Achaea-Nexus-Patrolling
A reflex package for Achaea's Nexus client

## Background
If you aren't familiar with it, [Achaea](https://www.achaea.com) is a text-based MUD (multi-user dungeon). Due to being text based, it offers a high degree of customizability in the way of writing scripts to assist with various tasks, which is what this is.

## Background for Achaeans
This is a port for Nexus of Gavriil's missing plants script, which was written in Lua. If you're a part of the Wildwalkers clan, check the "scripts" scroll for more info.

# Installation
Download the .nxs.json file. Then, in the Nexus settings under "Reflex Packages", drag and drop it into the large box.

# Miscellaneous notes
* There's a little bit of Don't Repeat Yourself violation in some portions of the code, but it's not something I think I care enough to fix.
* At some point I want to ignore missing plants in rooms that are known to be unable to grow any. I just need their room IDs and it should be a pretty easy change.
* I also want to add in a "patrol report" command, similar to what Irissa's reporting script does.
* I still need to add in gagging of the plant output. This is a bit of a pain with Nexus's API, and mildly buggy when using its Simplified Scripting System for some reason.
