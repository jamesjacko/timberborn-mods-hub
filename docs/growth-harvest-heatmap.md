# Growth & Harvest Heatmap

A toggleable overlay that recolours growing plants, crops and trees by **life stage**, so you can
see at a glance which fields are ready and which are lagging, without hovering each tile.

**▶ [Get it on the Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3751029877)**

## How to use

Press **H**, or click the heatmap button in the bottom map-overlay toggle cluster (next to the
stockpile and water toggles), to turn the overlay on and open its control panel. Both hotkeys are
rebindable under **Settings → Controls**.

## What the colours mean

Every plant has a **growth** stage. Gatherers (chestnut, blueberry and friends) that keep bearing a
crop after they finish growing get a second **yield** stage for the regrow-to-next-harvest timer.

| Stage | State | Colour |
|-------|-------|--------|
| Growth | Just planted | red |
| Growth | Halfway | yellow |
| Growth | Nearly grown | green |
| Growth | Grown whole-harvest crop | bright lime (a distinct "ready") |
| Yield | Just gathered | green (continues from growth) |
| Yield | Regrowing | green → blue |
| Yield | Ready to gather | vivid azure |

The panel's **Key** shows this legend live, and it updates with whichever palette is active.

## Accessibility mode

A toggle (default **Shift+H**) switches to a colourblind-friendly palette where **hue marks the
stage** and **brightness marks progress** — orange for growth, blue for yield, each lighting up
from dim to bright as the plant approaches ready. No red/green separation needed.

## Filters

The control panel can narrow what the overlay paints. Each axis is independent — a plant shows only
when **both** its type and its source are enabled:

- **Plant types** — Trees, Bushes and Crops, shown independently.
- **Source** — Planted (grown on a planting spot) vs Natural (wild-spawned).

## Bugs & suggestions

[Open an issue](https://github.com/jamesjacko/timberborn-mods-hub/issues/new/choose) — bug reports
and feature ideas both welcome.
