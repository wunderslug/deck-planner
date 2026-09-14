# Deck Planner

A browser-based deck-board quantity and cut planner.

## Features

- Width and depth inputs
- Selectable decking direction
- Editable board width, gap, trim allowance, and waste
- None, single, or double perimeter picture frame
- Automatic perpendicular breaker boards so field boards never require butt joints
- Optional extra breaker boards for appearance
- Separate field, breaker, and picture-frame quantities
- Optimized 12', 16', and 20' stock list with reusable offcuts
- Scaled top-down layout preview
- Warnings when a proposed board cannot be made from available stock

## Run with Docker / Portainer

Deploy the repository as a Portainer Git stack using `compose.yml`.

The app is exposed on port **3012** by default:

```
http://SERVER-IP:3012
```

Change the host port in `compose.yml` if needed.

## Notes

This planner estimates deck-board materials only. It does not size joists, beams, posts, footings, blocking, or fasteners. Always confirm the final layout and manufacturer-required gaps before ordering.
