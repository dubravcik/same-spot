# Same Spot

Retake an old photo from the same spot, fit the new shot onto it, and compare the two with a slider, side by side or a fade.

Single static page, no build step and no server: everything runs in the browser and photos never leave the device.

- Live version: https://dubravcik.github.io/same-spot/
- The live camera overlay needs HTTPS, which GitHub Pages provides.

## How it works

1. Load the old photo.
2. Hold it over the live camera (ghost, edge outline or blink) and shoot when the outlines meet. Pinch to match the zoom.
3. If needed, drag four numbered marks onto matching details in both photos to refine the fit.
4. Compare, then save the aligned photo or the pair.

Aim, tilt and zoom are corrected after the shot with a homography. Standing position is not correctable, so use parallax to find it: pick a near edge and a far edge that touch in the old photo and step sideways until they touch the same way.
