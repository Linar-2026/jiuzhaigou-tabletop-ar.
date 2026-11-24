# Jiuzhaigou — Living Landscapes V3

## What is included
- Responsive cinematic website with two original **illustrated** scenic backdrops (not real photographs).
- Interactive clickable landmarks (3 per location), three camera-like zoom viewpoints, bilingual English/Chinese, and optional synthesized ambient audio.
- Separate 3D model preview and Apple AR Quick Look entry point.
- Two original simplified GLB models copied from V2.

## Important limitations
- The scenery is **not photorealistic**. The SVG backgrounds are custom illustrations, intentionally labeled as such. For a photorealistic site, replace `assets/lake.svg` and `assets/falls.svg` with properly licensed, location-specific photographs and update the CSS `background-image` URLs.
- The original GLB models have no texture images or animations. They remain simplified; realistic AR requires new, high-quality models and `.usdz` assets.
- AR Quick Look does not display the website's hotspot interface.
- USDZ assets recovered from the prior real-scenes project are included and configured for Apple AR Quick Look. Test on iPhone Safari over HTTPS; AR compatibility is not verified on a physical device.
- The view buttons change crop and zoom, not true 3D camera position.

## Deploy to GitHub Pages
1. Unzip the package.
2. In your GitHub repo `Linar-2026/jiuzhaigou-tabletop-ar`, upload the contents **inside** this folder (index.html, assets/, models/, README.md) to the repository root. Preserve directory paths.
3. GitHub Pages should remain configured for branch `main` / root.
4. Wait for deployment, then open https://linar-2026.github.io/jiuzhaigou-tabletop-ar/ in a private tab.

## Before overwriting
Download your current repository as a ZIP backup. The existing `index.html` will be replaced. The V2 model files at root can remain but are unused by V3.

## Research
UNESCO Jiuzhaigou World Heritage: https://whc.unesco.org/en/list/637

This is a design prototype; verify location-specific facts before academic submission.
