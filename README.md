# Note to self & others who might view this prj
I forked because I'm having frequent app crashing when using this plugin (on Rasberry Pi OS, pi 4), specifically when the buttons have been clicked more than once. Currently (2020-01-06) I've removed it from my local DeaDBeeF. I may someday hack on it to fix it, or maybe not.

## Playback Buttons

It is a plugin with three buttons which displays the current shuffle and loop mode and lets you change it with a mouse click.
The new third button is used to add new playback modes ("Keep Album", "Keep Artist", "Top Rated", "Selection", "Playlist" deactivates the plugin).
To compile the plugin you need to copy the files deadbeef.h and gtkui_api.h from the deadbeef directory.

Copy the compiled plugin to the plugin folder (`~/.local/lib/deadbeef/`) and restart DeadDBeeF, then add the plugin to the gui.





