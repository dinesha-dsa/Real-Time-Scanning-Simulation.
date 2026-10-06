# 3D Vision & Depth Sensing Virtual Laboratory — Version 1.2

This release adds a **real-time animated scanning process** to the existing Module 4 teaching laboratory.

## New in v1.2
- Animated airport-luggage X-ray scanner
- Conveyor motion, X-ray source, luggage and detector visualization
- Step highlighting:
  `X-ray source → attenuation → detector → ADC → digital image → AI review`
- Interactive Beer–Lambert attenuation model: `I = I0 exp(-μx)`
- Material, thickness and photon-energy controls
- Live detector-signal animation
- Three illustrative frames:
  1. visible luggage
  2. raw X-ray-style transmission
  3. processed / AI region-of-interest view
- Upload your own image and generate an **illustrative pseudo-X-ray**
- Animated MRI/CT slice acquisition and accumulating volume
- Existing stereo-depth relationship `Z = fB/d`
- OpenCV/Python processing example

## Important educational note
The X-ray and medical modules are conceptual educational simulations. They do not reproduce calibrated airport-security hardware, infer true material composition from photographs, or provide medical diagnosis.

## GitHub Pages
Upload these files to the repository root:
- `index.html`
- `style.css`
- `app.js`
- `README.md`
- `LICENSE`

Then use **Settings → Pages → Deploy from a branch → main → /(root)**.

Prepared by **Prof. Dinesh S. Auti | Department of EXCP**.
