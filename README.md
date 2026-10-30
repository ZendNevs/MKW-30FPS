# MKW-30FPS
30 FPS mod for Mario Kart World (no slowdown) 
Eglantine - unofficial build with Mario Kart World 30 FPS mode
===============================================================

Based on Eglantine (https://github.com/Djihads80/Eglantine), branch nx2, commit 6e7edd7462325ee18a0db6fdc29ff7698ac108cc,
with the changes in SOURCE-CHANGES.patch (source code of this build, GPL-3.0).

What's new:
- Graphics > Advanced > "Mario Kart World: 30 FPS mode": keeps Mario Kart World in its own 30 fps
  mode (steady 30 fps at normal game speed). Game version build id 9E244438C3D8EF1C703A6A85EF99C4F0.
  No mod files needed. Takes effect at the next game launch.
- The emulator now honors the game's present interval (needed for the 30 FPS mode).
- Small GPU thread optimizations; Release build with LTO and AVX2 (needs a CPU with AVX2).

Recommended per-game settings for Mario Kart World:
  GPU accuracy: Low, ASTC recompression: BC3, Async shaders: on, Async presentation: on,
  Reactive flushing: off, Force max clocks: on.

Not included: keys, firmware, games, Lossless Scaling. Use your own dumps.
