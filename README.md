# Full-flow anatomy

A 34-second, frame-locked aligned section of a methalox full-flow staged combustion engine. 1,020 frames at 30 fps. Raptor-inspired conceptual model. The drawing states no pressure, shaft speed, gimbal angle, or coaxial pump layout.

The player is the schematic. Cyan is the pathway, gold is work or heat, and violet is state or sensing. Those colors are explanatory overlays, not literal emission. Where a route cannot be drawn from a public engineering drawing, the film labels it as a schematic.

## Run locally

```bash
npm install
npm test
npm run dev
```

Open [http://127.0.0.1:3847](http://127.0.0.1:3847). The essay is at `/article`.

`npm test` checks the frame contract: chapter coverage, camera continuity, the end hold, and that each chapter still shows the hardware that caused it.

## Static build

```bash
npm run build
```

`out/` is a static export. For GitHub project pages under `/full-flow-anatomy`:

```bash
NEXT_PUBLIC_BASE_PATH=/full-flow-anatomy npm run build
```

Publish the contents of `out/` as the `gh-pages` branch.

## Essay

`content/full-flow-staged-combustion-explainer-Cursor.md` is the Medium draft. Use the H1 as the title. The page renders the same file.

## Accuracy limit

Consolidated working brief, not a certified engineering reference. Verify subject-specific details before publication or design use. Sources are listed at the end of the essay.

## About

Frame-locked sectional anatomy of a methalox full-flow staged combustion engine, with no invented performance numbers.

## Topics

`aerospace` `rocket-engine` `full-flow-staged-combustion` `methalox` `propulsion` `explainer` `education` `deterministic-animation` `regenerative-cooling` `raptor-inspired`
