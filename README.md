# Orbit Clicker

A student-built cosmic clicker game, presented as a bilingual product site.

**Live site:** https://sirhauingtonthethird.github.io/solar-clicker/

**Created by:** 3E Hau Wing Hei Hayson

## What is this?

Orbit Clicker is a free, silent browser game about momentum and discovery. Tap the core to collect stardust, build a chain multiplier, and spend it on five upgrade modules. Rare **Solar Surges** turn the screen border to fire and multiply clicks by **×3.5**; every 500 clicks opens the **Singularity**, a 30-second purple-chaos event with a black-hole core and **×10** final click power.

## Pages

- `index.html` — the bilingual commercial site (English / 繁體中文), with an overview, feature breakdown, event showcase, how-to-play, creator section, FAQ, and calls to play.
- `game.html` — the complete playable game. It keeps autosave, offline progress, solar surges, the singularity event, keyboard controls, responsive layouts, and the English / 繁體中文 switch.
- `.github/workflows/deploy-pages.yml` — deploys both pages to GitHub Pages on every push or merge to `main`.

## Local development

Open `index.html` in a browser, then use the **Play** button to open `game.html`. There is no build step, framework, or external dependency.

All audio and voiceover have been removed; the experience is intentionally silent.
