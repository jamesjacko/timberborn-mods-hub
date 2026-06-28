# Tech Tree Hints

> **Beta** — this works and is safe to use (UI-only, nothing is gated), but the feature
> set is still growing. See the [roadmap](#roadmap) and feel free to suggest things.

A gentle, **UI-only** nudge for Timberborn's flat research tree.

Timberborn has no real tech tree: every building is just a flat science cost you can spend
in any order. That freedom causes choice paralysis, especially for new and returning players.
This mod doesn't gate anything and doesn't make research harder — it just **guides**.

**▶ [Get it on the Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3753526698)**

## What it does

- **Fades the buildings you can't supply yet.** A locked building is dimmed when you can't
  actually build or run it — because a good in its construction cost, or somewhere up its
  ingredient chain, comes from a building you haven't unlocked. The buildings you *can* feed
  keep the normal locked colour, so the sensible next unlocks stand out and the rest recede.
- **Names the blocker on hover.** Hovering a faded building tells you exactly which good it's
  still missing (for example treated planks).
- **Toggle with `Ctrl+U`** (rebindable under Settings → Controls → Tech Tree Hints); on by default.

The fade uses brightness and desaturation, not hue alone, so it reads without relying on
red-vs-grey colour vision.

## How it works

Research is flat, so the "tech tree" is *derived* from recipe inputs and outputs. A good is
makeable now if some unlocked building yields or crafts it (raw goods like logs, water and
berries are treated as available from the start). A building fades when it can't be built (a
good in its cost can't be made) or, for factories, can't be run (every recipe needs a good no
unlocked building can produce, following the supply chain).

## Roadmap

- A small tech-tree popup on hover, showing the branching chain of buildings you'd unlock to
  feed the one you're looking at.

## Bugs & suggestions

[Open an issue](https://github.com/jamesjacko/timberborn-mods-hub/issues/new/choose) — bug
reports and ideas both welcome.
