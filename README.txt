Untitled Folders: RUN//TECH (Temple-Run-style Endless Runner)
=============================================================

How to use
----------
1) Unzip the archive and open `index.html` in a browser (Chrome/Safari/Firefox desktop or mobile).
2) Controls:
   - Desktop: ← → change lane, ↑ jump, ↓ slide.
   - Mobile: swipe left/right to change lanes, swipe up to jump, swipe down to slide.

Notes
-----
- This is a lightweight HTML5 Canvas implementation with lane-based movement, endless procedural spawns,
  increasing speed, score and coin pickup. It is coded from scratch (no third-party code copied) under MIT License.
- All PNG assets are transparent placeholders styled to suggest Untitled Folders techwear themes (cords, chips, dead phones).
  Replace any PNG in `assets/` with your own art (keep the same filename to avoid code changes).
- For a 3D version with turns like Temple Run, consider porting to Three.js or Babylon.js and adding
  tile-based curved track segments and camera yaw on turn inputs.

File list
---------
- index.html               — the complete game (Canvas + JS)
- assets/runner.png        — mannequin runner
- assets/coin.png          — circuit coin
- assets/obstacle_cable.png, obstacle_chip.png, obstacle_phone.png — obstacles
- assets/bg_tile.png       — repeating background grid

License
-------
MIT — Feel free to modify and use commercially. Credit appreciated: "Starter by NextGen Creative Systems / ChatGPT".
