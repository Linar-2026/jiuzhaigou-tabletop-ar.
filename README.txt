JIUZHAIGOU — THE UNFOLDING JOURNEY
TABLETOP AR PROTOTYPE 01

WHAT IS INCLUDED
- index.html: responsive interactive bilingual 3D webpage
- spring/summer/autumn/winter.glb: browser preview models
- spring/summer/autumn/winter.usdz: Apple Quick Look AR models
- This README

TEST ON IPHONE 15 PRO MAX (RECOMMENDED: GITHUB PAGES)
1. On a computer, sign in to github.com and create a new PUBLIC repository,
   e.g. jiuzhaigou-tabletop-ar.
2. Upload ALL files from this folder into the ROOT of the repository (not the ZIP).
   Make sure index.html and all eight model files are in the same folder.
3. In repository Settings > Pages, select Deploy from a branch,
   Branch: main, Folder: /(root), then Save.
4. Wait for GitHub Pages to deploy. The website address is typically:
   https://YOUR-USERNAME.github.io/jiuzhaigou-tabletop-ar/
5. On your iPhone 15 Pro Max, open that HTTPS address in SAFARI.
   (Internet is needed for the model-viewer library from Google CDN.)
6. Tap a season, then tap "Place on my table". If Quick Look opens,
   choose AR (rather than Object) if prompted.
7. Point the camera at a well-lit, textured table and move the phone
   slowly to detect a horizontal surface. Tap to place the miniature.
8. Walk around the model. Pinch to adjust size if the viewer allows it.
   Exit AR to return to the webpage and change season.

WEB PREVIEW CONTROLS
- Drag to rotate; pinch/scroll to zoom.
- Spring/Summer/Autumn/Winter buttons change the 3D model.
- Play journey shows each of four station info cards for 2 seconds.
- Tap any station to read its information.
- EN / Chinese language toggle.

LIMITATIONS (PLEASE READ)
- This is a FIRST PROTOTYPE, not a production AR application.
- The 2-second station cards, buttons and animation timeline are HTML UI;
  they DO NOT appear inside native Apple Quick Look AR.
- The paper mountains are stylized 3D layers; they do not yet physically
  unfold or respond to taps in native AR. This requires a different AR runtime.
- The route is schematic, not a real rail map; transport info is draft.
- The USDZ models were programmatically assembled and structurally checked,
  but could NOT be tested in iOS Quick Look in this environment.
- If Quick Look cannot open a USDZ, report the iOS error or screenshot.
  The GLB browser preview remains usable.

TECHNICAL
- model-viewer library loaded from Google's CDN (version 4.0.0).
- No paid services required for this proof of concept.
- GitHub Pages is free for public repositories, subject to GitHub's policies.
- No personal location, camera images or analytics are collected by this page.
- Safari/Quick Look handles camera permission and AR placement.

ACADEMIC INTEGRITY
The model is a design visualization and not verified geographic data.
Credit external assets/libraries in the final report and validate station
information and environmental claims against reliable sources.
