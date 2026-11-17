# Evergreen House — A House for Christmas

An original interactive 3D first-floor Christmas decorating concept. Explore a foyer, living room, dining room and kitchen, or take the guided tour.

## Run
Use any static HTTP server in this folder, for example `python3 -m http.server 4188`, then open http://localhost:4188. Opening index.html directly from Finder is unsupported because JavaScript modules require HTTP.

No build step or package installation is required. Three.js 0.170.0 is vendored locally. Fonts are optionally loaded from Google Fonts; system serif/sans-serif fallbacks work offline. No accounts, analytics or personal data collection.

## Controls
- Step inside or select any room in the bottom navigation.
- Drag to orbit; scroll or use two-finger pinch to zoom.
- Left/right arrows move between rooms; Escape returns to the house view.
- Guided tour automatically changes rooms every 8.5 seconds; manual room navigation stops it.
- Toggle festive lights and optional synthesized ambient sound.
- House view restores the cutaway first-floor layout.

## Design
An original floor plan, not a measured recreation of a real house. No floor plans or photos were supplied. Objects are modeled procedurally; there are no third-party image assets. Full-height rear walls and low front walls make the home readable as a cutaway dollhouse. Interior views are curated orbital views, rather than collision-based first-person walking.

WebGL is required. Audio starts only after the user presses Sound. Reduced-motion preferences disable camera interpolation and snow rotation.

## License
Original application source: MIT. Three.js is MIT licensed; see vendor/LICENSE.three.txt.

## Expanded layout
The concept footprint is now 20 × 16 scene units, compared with the original 12 × 10. A long central hallway separates the larger rooms. The living room includes a widescreen TV displaying original winter artwork, a media console, two larger sofas, an armchair, and a separate fireplace. Dining seats eight; the expanded kitchen island has four stools. Dimensions describe the visualization, not a measured construction plan.

## Colonial inspiration update
The user-supplied Colonial/Federal, cozy sitting-room, and Chris Loves Julia kitchen references informed original modeled details: white arched casings and paneling, a blue-gray fanlight entrance, traditional lanterns, warm dark timber, patterned rugs, blue-and-cream textiles, framed landscapes, and cream cabinetry with an olive island and brass dish pendants. Reference photographs are not bundled or used as textures. All textile patterns, artwork and stone/wood textures are generated locally in canvas. The house remains a stylized concept rather than a photorealistic recreation.
