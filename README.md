# Untitled Energy

A 3D, scroll-driven landing page for a placeholder energy-drink brand. Built as a single `index.html` with three.js (r128, loaded from cdnjs) and Google Fonts. No build step.

## Scenes
1. **Hero** – seven cans float in an arc; the selected can hovers between two glowing pads with a floor reflection. Change flavour with the arrows, a swipe, arrow keys, or by clicking a can.
2. **Flavour zoom** – the other cans fly off and the chosen one fills the screen with its story and specs.
3. **Ingredients** – the can turns black and rotates through four glowing callouts printed on it; a side rail tracks the step.
4. **Lineup** – all seven cans on a reflective floor, with flavour chips.
5. **FAQ** – extruded 3D-style title and an accordion.
6. **Footer** – sign-up form, links, and a single standing can.

## Run locally
Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Customise
- Brand name: search for `UNTITLED` / `Untitled` (the can label is drawn in `drawLabel()`).
- Flavours: edit the `FL` array (name, colour, description, sugar, kcal).
- Ingredient callouts: edit the `FEAT` array and the matching `#f1`–`#f4` sections.
