# Monster Mail · Delivery Adventure
Original Vue 3 delivery game by John Parker. Nine clue-based parcels, five monster houses, three neighbourhoods, real shortest-path routing, parcel-seal matching, step-based scoring and a local personal best.

## Run
Node 22+. `npm ci`, `npm run dev`, `npm test`, `npm run build`. Vercel preset: Vite; output: dist.

## Play
Read the clue, choose the matching seal, reach the correct house and Hand over parcel. Click a destination to preview a shortest route then Walk route, or use arrows/WASD/on-screen direction buttons. Roadworks block movement. Wrong deliveries show recoverable feedback. Retry resets the current parcel; New shift resets the run. Nine successful deliveries finish the shift. Sound starts only with the sound toggle; reduced-motion skips route animation. No accounts or personal data, fictional world.

Original generated gouache town background integrated with code-native interactive map, houses, courier and postal UI. Game rules in src/game.js are tested for every destination and movement edge case.
