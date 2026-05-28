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
- **Wood Stove** — Lower-level (basement) stove on the EAST wall (north of the E door): footprint, hearth pad, and a straight-up Class-A chimney that exits near the high ridge (framed floor opening → upper level → roof)
- **Laundry** — Lower-level (basement) washer + dryer, side-by-side on the WEST wall near the north corner (footprint only; drawn below the floor deck)

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
| 16 | 2026-05-24 | Wood Stove layer added — small (~24"×20") stove on the basement EAST wall, a few feet north of the E door, squared to the wall. Backing the high (E) side lets a straight-up Class-A flue exit near the ridge → only ~3 ft of pipe above the roof. Hearth pad + framed floor opening (lands in a joist bay, no joist cut) → upper level → roof (flashing + storm collar). South elevation shows the near-ridge flue to NFPA 211 3-2-10. Parametric CFG.stove (wall 'E'/'W') + self-check. Footprint only — confirm listed clearances. |
| 17 | 2026-05-25 | Laundry layer added — washer + dryer side-by-side on the basement WEST wall, up near the NORTH corner (north of the W door). Each ~27"×31"; ~55" run, 6" off the N wall. Drawn below the floor deck (dashed). Parametric CFG.laundry (wall 'W'/'E') + self-check (in interior clear, backs to wall, clears W door, no stove overlap). Footprint only — confirm hookups/drain/vent/clearances. |
| 18 | 2026-05-25 | West eave overhang increased 18" → 30". N/S eaves remain 18". Within IRC R802.4.5 1/3-span limit (~36" max for 9'-2" rafter span). Rafter tails 12" longer; fascia/soffit/gutter position moves out accordingly. No structural hardware changes required. |
| 19 | 2026-05-25 | Plan-view window framing added to the **N wall window** — king studs (outside the R.O.) + jack/trimmer studs (inside), with the N-wall field studs now interrupted through the opening, matching how the S/W doors are framed in plan. Header, rough sill & cripples already shown on the N elevation. Added self-check INVARIANT 4c (N window kings/jacks clear the corner posts). HTML rev labels bumped 17 → 19. |
| 20 | 2026-05-25 | Plan-view framing added to the **E wall door** (basement door) — previously the E door showed on the East elevation and in the Openings layer but the Wall Framing layer ran field studs straight through it (no king/jack studs, no plate break), so the door "disappeared" in plan. Now framed exactly like the S/W doors: king studs (outside R.O.) + jack/trimmer studs (inside), E-wall field studs interrupted through the opening, and the bottom plate split at the door. Added self-check INVARIANT 4d (E door fits + kings/jacks clear the corner posts). HTML rev labels bumped 19 → 20. |

---

*Field verify all dimensions before framing.*
