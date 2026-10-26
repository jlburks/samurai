# RONIN — Outer Rim Blues

An original space western first-person combat prototype built with Three.js and Vite. Explore a procedural frontier settlement, switch between a katana and a six-shot revolver, and clear five hostile bounty targets.

## Run

Requires Node.js 22.12+ (validated with Node.js 24).

```sh
npm ci --cache /tmp/samurai-npm
npm run dev -- --port 3000
```

Open the app in a desktop browser with WebGL and click **Enter the Frontier** to capture the mouse. WASD moves, mouse aims, click attacks, Shift sprints, Space jumps, 1/2 selects weapons, R reloads, and Escape pauses. Click the sound button to enable synthesized audio. Clear the contract or retry after defeat through the start button.

`npm run build` creates the production build; `npm run preview` serves it.

No credentials or backend services are required. Google Fonts is optional; system fonts provide a fallback. The scene, models, and sounds are generated locally. This is an initial prototype: melee blocking, advanced enemy navigation, progression, and mobile controls are not implemented.
