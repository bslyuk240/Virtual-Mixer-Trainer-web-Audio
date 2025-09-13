# Virtual Mixer Trainer

A browser-based training mixer built with the Web Audio API. Load your own stems, practice gain staging, EQ, pan, aux-to-reverb, mute/solo, and master balance. Nothing uploads—audio runs locally.

## Quick Start
1. Open `index.html` in Chrome/Edge/Firefox, or host the folder on GitHub Pages/Netlify.
2. Click **Audio File** on each channel to load stems (e.g., Lead Vocal, BGV L/R, Guitar, Keys, Drums).
3. Press **Play All** and practice:
   - Set **TRIM** (pre-gain) first for healthy levels.
   - Use **HPF** on vocals; adjust **EQ** (low shelf, parametric mid, high shelf).
   - **Pan**: lead center, BGVs L/R, instruments spread; bass/kick center.
   - Add **AUX → Reverb** tastefully; adjust **Master** and **Reverb Return**.
4. Try presets in the **Scenario** menu (Worship Band — Live, Pop Vocals — Studio).

## Deploy
- **GitHub Pages**: push this folder, enable Pages in Settings → Pages. Optional: include `.nojekyll` in root.
- **Netlify**: drag-and-drop the folder, or connect your GitHub repo. `build command = (empty)`, `publish = .`

## Notes
- Works entirely client-side. Modern browsers only (mobile Safari requires a tap to unlock audio).
- You can add compressors/gates/delay as future enhancements.
