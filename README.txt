ROCKET POWER — STRAWBERRY STARDUST / 3D IMAGE-TRACKED WEB AR

WHAT'S INCLUDED
- index.html: MindAR + A-Frame camera tracking with a real 3D procedural astronaut/rocket model, animated exhaust, orbit and particles.
- strawberry-stardust-target.jpg: image used to compile tracking data.

REQUIRED BEFORE IT CAN TRACK THE BAG
1. Use https://hiukim.github.io/mind-ar-js-doc/tools/compile/ with strawberry-stardust-target.jpg.
2. Download the resulting targets.mind.
3. Place targets.mind in THIS SAME folder as index.html (not inside another subfolder).
4. Upload the contents of this folder (index.html, targets.mind, jpg) to the ROOT of your HTTPS web host.
5. Open the HTTPS page on an iPhone in Safari; allow camera; aim at physical bag.

3D Preview button shows the modeled astronaut/rocket without target recognition. This is a stylized procedural 3D mascot, NOT a custom sculpted replica of the illustration. A faithful likeness would require a separately modeled and textured GLB character.

IMPORTANT: This ZIP does not include targets.mind because the compiled file has not been provided. Without it automatic tracking cannot work. Requires network to load A-Frame and MindAR JavaScript from CDNs. If camera shows black, verify HTTPS, browser camera permission, and targets.mind returns 200 (not 404).
