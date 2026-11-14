# Shattered Abyss: Awakening

A fast-paced 3D third-person fantasy action platformer game built with Three.js, WebGL, Web Audio API, and packaged with Electron.

## Features
- **Third-Person Over-the-Shoulder Controls**: Free mouse-look with dynamic shoulder offset, smooth follow, and screen shake.
- **Dynamic Traversal**: Sprinting, stamina management, climbing vertical runic walls, and pendulum grappling hook.
- **Collapsing World**: Terrain shakes, fractures, and crumbles into the bottomless abyss beneath your feet.
- **Supernatural Unlock**: Acquire the ancient **Void Blink** mid-run to warp across dimensional tears.
- **Colossal Boss Fight**: Awakens Gorgon the Colossus at the grand arena with shockwave slams and void barrages.
- **Audio & Visual Juice**: Procedural sound synth (zero external audio dependencies), particle trails, bloom lighting, and minimal HUD. No gore.

## Controls
- **W / A / S / D**: Move
- **Shift**: Sprint (uses stamina)
- **Space**: Jump / Climb
- **F**: Grapple Hook / Swing
- **E** or **Right Click**: Void Blink (after unlocking)
- **Left Click**: Arc Blast (ranged attack)

## Desktop Electron App (Windows / Mac / Linux)
\`\`\`bash
# Run locally
npm install
npm start

# Build for Windows (NSIS installer & ZIP)
npm run pack:win

# Build for Mac (DMG & ZIP)
npm run pack:mac
\`\`\`
