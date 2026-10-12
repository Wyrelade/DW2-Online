# Smooth frames and a busy Main Gate

*2026-10-12*

![Main Gate](../misc/screenshots/hub-2.jpg)

The game logic of Digimon World 2 runs at the PlayStation's 59.94 Hz, and it has to stay there:
the server runs the same code, and its timing is part of the rules. Monitors today run at 120 Hz,
144 Hz and more.

**Smooth frames** draw the city at your monitor's refresh rate anyway. Every game frame is
packaged with where each 3D point was in the frame before, and the window draws the newest
package blended by time. Walking, running and the camera move smoothly, the name tags follow
along, and the game logic never notices.

Smooth frames are on by default in the city. F9 or the settings window (F1) turn them off.
Domains and battles are next.

## Also new

- A bug from the original game: a stray label in the top left corner of the battle screen during
  the interrupt prompt is gone.
- A tamer who quits now leaves the other players' view at once.
