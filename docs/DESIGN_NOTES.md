# CSVS Underworld — Design Notes
## Ultimate Developer Edition

### 1. Aesthetic Foundation
- **Theme Fusion:** GTA San Andreas (urban street attitude, lowrider culture, warm sunset accents) + GTA V (modern high-density night skyline, realistic asphalt reflections, metallic supercars) + GTA VI (neon coastal aesthetics, dynamic environmental effects, transparent glassmorphism HUD).
- **Dominant Palette:** 70% dark navy (`#06131F`, `#071C2A`), 20% emerald green (`#20E88B`, `#0B694D`) and neon teal (`#00D8C7`), 10% metallic silver (`#DCE7EB`) and sunset gold (`#FFB454`). Strictly no dominant pink or purple.

### 2. Animated Banner Architecture
- **File:** `assets/underworld-banner.gif`
- **Resolution:** 960 × 270 (16:9 ratio)
- **Framerate:** 10 FPS (30 frames, 100ms per frame, seamless 3-second loop)
- **Color Depth:** Quantized 256-color palette tailored to the Underworld color system.
- **Layer Breakdown:**
  1. **Sky & Atmosphere:** Sunset-to-night vertical gradient with warm horizon amber glow.
  2. **Helicopter:** Distant low-flying helicopter with rotating rotor blades, tail boom, cockpit glass, and blinking red aviation beacon.
  3. **Metropolis Skyline:** Fictional coastal skyline with 15 skyscrapers, rooftop antennas with red flashing beacons, and alternating warm amber and cool cyan illuminated windows.
  4. **Highway:** Wet asphalt highway with realistic neon reflection streaks underneath vehicles and amber dashed lane dividers.
  5. **Supercar:** Metallic silver & graphite supercar with aggressive Y-shaped LED taillights, red road reflection, exhaust heat puff, custom license plate `CSVS IT`, and rotating alloy wheels.
  6. **Motorcycle:** Emerald green & carbon-black racing superbike with forward-leaning helmeted rider, dual piercing LED headlights casting beams onto the road, and spinning wheels with green rim tape.
  7. **HUD Brackets:** Corner target markers and "MISSION: ACTIVE" telemetry indicators.

### 3. Glassmorphic HUD & Developer Radar
- **Radar:** `assets/developer-radar.svg` features a tactical HUD radar sweep with concentric range rings, quadrant axes, and target pings for confirmed skills: Python, Django, PostgreSQL, Docker, AWS, TypeScript, Linux, and CI/CD.
- **Footer:** `assets/underworld-footer.svg` features a matching night skyline silhouette and the signature:
  `MARTIN LOURDURAJ // CSVS IT TECH • BUILD SYSTEMS. OWN THE NIGHT.`
