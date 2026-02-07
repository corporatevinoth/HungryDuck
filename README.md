# HungryDuck – Misty Ocean Duck Adventure

A relaxing 3D exploration game built with **Three.js** where you play as a brave little duck swimming through a dreamy, misty ocean world filled with floating rocky islands, glowing waterfalls, ethereal fog, and collectible shiny feathers.

Live demo:  
→ https://corporatevinoth.github.io/HungryDuck/

https://github.com/corporatevinoth/HungryDuck/assets/xxxxxxxxxxxxxx/xxxxxxxxxxxxxxxxxxxx (optional: you can later record a short 10–15 sec gameplay clip and attach it here via GitHub's "Attach files" when editing README)

## Features

- Beautiful dawn-lit sky with realistic **procedural sky** (using Three.js Sky)
- Dynamic water surface with waves and reflections (Three.js Water)
- Simple but charming low-poly duck model with swimming bob animation
- Floating rocky islands with small waterfalls
- Collect shiny glowing feathers (with subtle pulsing effect)
- Atmospheric misty fog that enhances the dreamy vibe
- Narrative subtitles that appear as you explore (e.g. "Quack, I've reached the Misty Pond!")
- Smooth keyboard controls (WASD + mouse look via OrbitControls)
- High-clarity rendering with tone mapping and environment lighting

## Controls

- **W** / **S** – Swim forward / backward  
- **A** / **D** – Swim left / right  
- **Mouse drag** – Look around / rotate camera  
- Get close to shiny feathers to collect them!

## Technologies

- **Three.js** (latest via CDN – no build step needed)
- Three.js built-in: Water, Sky, PMREM environment
- Pure HTML + JavaScript (module type)
- No external frameworks or bundlers

## How to Run Locally

1. Just open `index.html` (or `Duck.html` if not yet renamed) in any modern browser  
   → Chrome, Firefox, Edge all work great

2. Or serve it with a simple local server (recommended to avoid CORS issues with textures):
   ```bash
   # Using Python (one-liner)
   python -m http.server 8000

   # Then visit: http://localhost:8000
