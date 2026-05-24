# Tornado Room

Live construction blueprint and field documentation for a CMU block basement being converted into a tornado shelter (lower level) and utility room / tiny home (upper level).

**Live site → [tornadoroom.vercel.app](https://tornadoroom.vercel.app)**

---

## What's here

| File | Purpose |
|---|---|
| `foundation-blueprint.html` | Interactive, to-scale floor plan — parametric geometry engine, layer toggles, self-check |
| `sill-plate-cutlist.html` | Auto-generated sill plate cut list from the same geometry model |
| `window-detail.html` | Window rough opening detail / installation reference |
| `measurements.md` | Raw field measurements by wall, updated as taken |
| `images/` | Site photos |

## Foundation facts

- **Shape**: Rectangular ~10 ft × 20 ft (exterior out-to-out)
- **Construction**: CMU (concrete masonry unit) block, 8" nominal / 7⅝" actual
- **Openings**: Door (east wall), window (north wall), window (south wall), door (south wall), door (west wall)
- **Datum**: All wall lengths are **exterior**, out-to-out of CMU. Interior clear is derived.
- **Scale**: 2.5 px = 1 inch in plan view

## Blueprint layers (all toggleable)

- **Anchor Bolts** — IRC R403.1.6 layout (≤72" OC, ≤12" from ends), avoiding openings
- **Sill Plates** — 2×6 PT laid flat, flush to exterior face
- **Rim / Box Sill** — 2×8 on edge, flush to exterior
- **Field Joists** — 2×8 @ 16" OC, bearing on sill
- **Subfloor** — ¾" T&G panels, staggered, numbered cut sequence
- **Wall Framing** — 2×6 studs @ 16" OC, 3-stud corner posts, double top plate
- **Openings** — Windows + doors with swing arc
- **Dimensions** — Full perimeter + detail dims

## South patio

10 ft × 10 ft on-grade concrete slab off the south wall, centered at the south door. 4" slab on 4" compacted gravel, control-joint cross, ½" isolation joint at the foundation, ¼"/ft slope away. ~1.4 cu yd concrete. Shown as a toggleable layer.

## Rev log

| Rev | Date | Notes |
|---|---|---|
| 01 | 2026-05-20 | Initial layout from voice transcript |
| 02 | 2026-05-20 | Window moved to N wall (40½" from E). S wall window placeholder. W wall solid. E=238¾", W=240¾" confirmed. |
| 07 | 2026-05-22 | Full parametric rebuild. Single source of truth. Datum corrected to exterior out-to-out. Rim/joist lengths recomputed. |
| 08 | 2026-05-22 | Wall framing layer added (2×6, 3-stud corners, 16" OC) |
| 09 | 2026-05-22 | Subfloor layer added (¾" T&G, staggered, cut sequence) |
| 10 | 2026-05-23 | Door · S (36" R.O.) added, 12" from west corner. South patio layer added. |
| 15 | 2026-05-24 | Door · W (36" R.O.) added on the west wall — left (N) edge on the wall centerline (84⅜" from S corner). Threaded through all layers + self-check. |

---

*Field verify all dimensions before framing.*
