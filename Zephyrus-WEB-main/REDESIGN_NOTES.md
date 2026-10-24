# Zephyrus monochrome redesign

This is an independent visual redesign of the supplied Zephyrus website project. It keeps the existing Astro/React structure, page sections, navigation, scripts, assets, and interaction components in place.

## Visual direction

- Strict monochrome palette: near-black surfaces, off-white text, and restrained gray borders.
- Editorial display typography for headings, with compact monospaced metadata and labels.
- Framed specimen-card sections, finer outlines, subtle grain, grayscale image treatments, and restrained hover motion.
- Responsive adjustments for narrow screens and visible keyboard-focus states.
- Reduced-motion support retained and reinforced.

## Run locally

Use Node.js 22 or newer and pnpm as specified by `package.json`.

```bash
corepack pnpm install
corepack pnpm dev
```

Open the local URL printed in the terminal. To check the production build, run:

```bash
corepack pnpm build
```

The source environment used to prepare this ZIP could not download packages from the npm registry, so a fresh dependency install and production build could not be verified here. No dependency versions or application logic were changed as part of the visual pass.
