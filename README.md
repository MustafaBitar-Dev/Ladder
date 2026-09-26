# Ladder

A single-page tool for ranking things by dragging them into place — like a tier list, but you control the exact order.

## Use it

Open `index.html` in any browser. No install, no server, nothing to set up.

## How it works

- **Options** — the pool of unranked items at the bottom.
- **Ladder** — the ranked list at the top, numbered 1 (best) downward.
- Drag a box from Options into the Ladder to rank it. Drag within the Ladder to reorder. Drag a Ladder item back down (or hit the ×) to unrank it.
- Dragging near the top/bottom edge of the screen auto-scrolls, so long ladders are still a one-move drag.

## Adding items

- **Add options** — paste a plain list, one item per line. Added to the pool.
- **Add to ladder** — paste a *numbered* list (`1. Item`, `2. Item`, ...), 1 through X with no gaps. It's validated before anything changes, then placed at the top of the ladder, pushing existing items down.
- Either action skips anything that's already in the ladder or options (case-insensitive), so you won't end up with duplicates.

## Getting your ranking out

**Copy numbered** / **Copy plain** at the bottom copies the current ladder to your clipboard — numbered (`1. Item`) or as a plain list.

## Editing the code

Everything is in one file: `index.html`. All HTML, CSS and JS are inline — no dependencies to install, no build step. Open it in a text editor to tweak colors, fonts, or behavior directly.


Done using AI :)
