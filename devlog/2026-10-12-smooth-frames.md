# Smooth frames

*2026-10-12*

![Main Gate](../misc/screenshots/hub-2.jpg)

The game logic runs at 59.94 Hz, as on the PlayStation. It has to stay at that rate, because the
server runs the same code.

Smooth frames draw the city at your monitor's refresh rate, with movement blended between game
frames. The game logic does not change.

Smooth frames are on by default in the city. F9 turns them off. Domains and battles come later.

Also fixed: an "Attack" label that showed in the top left corner of the battle screen on PC.
