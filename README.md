# Amiga Juggler — real-time ray-traced remake

A single-page, real-time WebGL2 ray tracer that recreates Eric Graham's 1986 Amiga **Juggler** demo, with an orbit camera.

Open `juggler.html` in any modern browser. No build step or dependencies.

- **Scene:** the original 79-sphere robot, lamp, camera, sky and checkerboard from Graham's `robot.dat`, shaded with the same rules as his raytracer (`pixbrite`, `glint`, `mirror`, `gingham`).
- **Animation:** a 3-ball shower timed from the original 24-frame (0.8 s) loop.
- **Sound:** a synthesized "clink" matched to the original Amiga sound (pitch and decay).
- **Render modes:** `1986 HAM` (320×200 with Graham's Hold-And-Modify encoder), `320×200`, `Auto`, and `Best` (4× anti-aliasing at 30 fps).

**Controls:** drag to orbit · wheel/pinch to zoom · double-click to reset · space to pause · 0–9 for speed (3 = original) · M to mute · R for render mode · H to hide the panel.

## Credits

- **Eric Graham** created the Juggler (1986) and its raytracer. He placed the code in the public domain with attribution.
- The original scene data and source were recovered by AlphaPixel: <https://github.com/AlphaPixel/Eric-Graham-1987-Juggler-Raytracer-1.0>
- **Ernie Wright** preserved the original animation and sound (`juggler.avi`), which served as the reference.

## License

MIT (see `LICENSE`) for this remake. The original Juggler scene and raytracer are by Eric Graham, public domain with attribution.
