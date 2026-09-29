# Production map

No new world facts. Thin map of the wiki onto Habitat-kit, Time-slice, Probe-kit, Unit-canon, Collection-linter, and Blend-ci. Habitat-kit owns graphs, cooks, and dump runbooks. Do not grow this file into a Habitat-kit playbook. If a sentence is not a mapping, delete it.

## 1. Who builds what

| Repo | May instance | May not |
| --- | --- | --- |
| **This bible** | Tagged facts, OPEN list, key-art caches in `stills/`, calc reprint + tests | Graphs, cooks, Habitat Cuts, a simulator, Habitat-kit playbooks |
| **[Habitat-kit](https://github.com/Plygonality/Habitat-kit)** | One cell. Actors: airlock, deck bay, truss, hatch. Three Habitat Cuts. Lineage joints / hatches / service modules as mesh vocabulary. | The swarm. The large key-art body. The Nullseed. A second generator. Extra epoch IDs. |
| **[Time-slice](https://github.com/Plygonality/Time-slice)** | Epoch IDs `construction` / `operational` / `relic` on that cell. Decay-pass + signal-field. | A new identity per epoch. Extra epochs for plot. |
| **[Probe-kit](https://github.com/Plygonality/Probe-kit)** | Crawler, drone, debris as instances on the cell. Gram-class probe body and sail remnant as props. | A second habitat generator. Named crew. |
| **[Unit-canon](https://github.com/Plygonality/Unit-canon)** | Grid 1.0 m, deck 3.0 m, airlock 1.0 m, figure 1.80 m. | Numbers copied into graphs in this repo. Lineage does not fork units. |
| **[Collection-linter](https://github.com/Plygonality/Collection-linter)** | Roles `human_figure`, `airlock`, `deck`, `grid` against Unit-canon. | World-fact checks. Linter does not know Kepler-62. |
| **[Blend-ci](https://github.com/Plygonality/Blend-ci)** | Headless cook of a Habitat-kit / gn-as-code dump. Viewport or workbench PNG. Hash / lint drift. | Writing the bible. Building the cell. |

## 2. Habitat Cuts → Time-slice

Same hull. Epoch is a socket pack. Habitat-kit does not fork Time-slice. System history does not add IDs.

| Habitat Cut | Time-slice `epoch` | Decay-pass | Signal-field |
| --- | --- | --- | --- |
| construction | `construction` | High scaffold, high incomplete, near-zero oxidation | Work lights, arcs, messy |
| operational | `operational` | Wear, hull closed, no scaffold | Lanes, running lights |
| relic | `relic` | Empty former habitation; protected archive plant; mixed-period repairs; scaffold gone | Sparse leftovers. Request for restoration or continued preservation. |

Emitter sites stay seed-locked. Epoch only weights which sites are live.

Do not add a fourth cut. Arrival, founding, and war are plot. They are not epochs. Nullseed cosmological labels in [`nullseed.md`](nullseed.md) are not Time-slice IDs.

Relic maps [`featured-cell.md`](featured-cell.md). Do not stamp names. Do not caption the swarm as dead. Do not default to evil AI, universal war, or magic.

Oxidation in the decay-pass needs a brief that supplies a credible environment or exposure history. Otherwise use impact, radiation, thermal fatigue, joint failure, or deposits.

## 3. What a cell graph is allowed to show

Habitat-kit owns the graph. World-frame rejects also live in [`../constraints/physics.json`](../constraints/physics.json). Do not paste dump scripts here.

Allowed:

- One hard-surface cell. Industrial / brutalist.
- Unit-canon sockets for every length.
- Habitat-kit actors already in that kit: airlock, deck bay, truss, hatch.
- Lineage expressed as recurring joints, hatch designs, service modules, and repair traces.
- Related shells with different quarantine / soil / environmental kit when mapping [`preservation.md`](preservation.md).
- Probe-kit instances: crawler, drone, debris. Optional `origin=sol` gram-class body or sail remnant.
- Work lights that read against 27.3 W/m² starlight.
- The three states in the table above.

Rejected:

- The full 3.6 AU swarm as a Habitat-kit object.
- The Nullseed, its helices, or its Causal Seed.
- A rigid lattice of cells.
- A solid Dyson sphere, Matrioshka shell, Bishop ring, or O'Neill cylinder standing in for the swarm or the Nullseed.
- A planet-scale body labeled Kepler-62b–f.
- Sol-white key on a Kepler cell.
- Named signage, chapels, flags, crew, invented protagonists.
- Magic lengths or a second unit system for a lineage.
- A generation-ship interior.
- A civilisation running inside a gram-probe prop.
- A destination braking laser implied in the background.
- Detected-life captions on e / f.

## 4. Still mapping

`stills/` is a cache of key-art, two families (Git LFS). Blend-ci does not cook them. Habitat-kit does not rebuild them. Habitat Cuts are generated from Habitat-kit. Captions: [`wiki.md`](wiki.md) §13.

| Still | File | Owner | Camera |
| --- | --- | --- | --- |
| Eclipse | [`stills/01-eclipse.jpg`](../stills/01-eclipse.jpg) | This repo | Kepler system. Large irregular body ≠ b–f. Independent cells, not a rigid lattice. |
| Lattice | [`stills/02-lattice.jpg`](../stills/02-lattice.jpg) | This repo | Kepler system. Receding geometric cells. Filename does not lock a grid. |
| Inward | [`stills/03-inward.jpg`](../stills/03-inward.jpg) | This repo | Kepler system. Independent cells on the disk. Small circular transit is a different object. |
| Boom | [`stills/04-boom.jpg`](../stills/04-boom.jpg) | This repo | Sol launch. Hub, chassis, four spars. Earth faint. |
| Cross | [`stills/05-cross.jpg`](../stills/05-cross.jpg) | This repo | Sol launch. Edge-on cross on Earth's disk. |
| Face | [`stills/06-face.jpg`](../stills/06-face.jpg) | This repo | Sol launch. Reflective diamond face. Marks are look-dev. |
| Fleet | [`stills/07-fleet.jpg`](../stills/07-fleet.jpg) | This repo | Sol launch. Several diamonds on Earth's limb. Visible count is not batch size. |
| Construction cell | Habitat-kit `screenshots/construction/` | Habitat-kit + Time-slice + Blend-ci | Cell. Generated from Habitat-kit. Unshot here. |
| Operational cell | Habitat-kit `screenshots/operational/` | Habitat-kit + Time-slice + Blend-ci | Cell. Generated from Habitat-kit. Unshot here. |
| Relic cell | Habitat-kit `screenshots/relic/` | Habitat-kit + Time-slice + Blend-ci | Cell. Generated from Habitat-kit. Empty habitation + protected archive plant. Unshot here. |

Distant Kepler cells in `01`–`03` read as sharp dark polygons. System-scale silhouette. Habitat-kit instances one airlock / deck-bay / truss / hatch cell.

Launch diamonds in `04`–`07` are gram-class sails at Sol. Do not map them as Kepler cells. Do not apply 27.3 W/m² Kepler fill to those frames. Earth / G2 is correct there.

If look-dev is chasing these frames:

| Cue | Keep | Drop |
| --- | --- | --- |
| Star | Orange-yellow K disk, prominences fine | Sol-white, tiny G2 |
| Swarm | Many independent dark cells; veil / field | Solid shell, single ringworld, rigid lattice |
| Large body | Irregular, blocky, unlabeled | Caption 62b–f |
| Small circular disk | Optional transit; unnamed | Call it the large body |
| Haze / traces | Faint red orbital traces | Default Earth-blue space; welded grid |
| Exterior light | 27.3 W/m² is dim, not a black void | "Virtually invisible" exteriors |
| Launch stills | Earth limb, diamond sail, four spars, gram hub | Caption as Kepler-62; treat as cell silhouettes; lock beam count from face marks |

## 5. Lighting map

| Quantity | Work figure | Where it lands |
| --- | --- | --- |
| Star | K2, 0.26 L☉ | HDRI / sun lamp color. |
| Flux at cell | ≈ 0.020 S☉ ≈ 27.3 W/m² | Exterior fill. Dim. Visible. |
| Teq | ~120 K work figure for passive exterior under stated assumptions | Not shirtsleeve exteriors. Not every interior rack. |
| Active plant | Separate from Teq | Computers and radiators have their own temperatures. |
| Key | Work lights | Construction: arcs, temporary. Operational: structured. Relic: sparse leftovers. |

Earth-noon viewport on a Kepler cell means the cook is wrong. Mesh can still be right. Sol launch stills `04`–`07` may show Earth. That is the other family.

## 6. Scale map

Read from Unit-canon. Do not copy the JSON into this repo.

| Socket / role | Unit-canon key | Habitat-kit use |
| --- | --- | --- |
| Grid | `meters_per_grid` | Snap, array pitch |
| Deck | `deck_height` | Deck bay span |
| Airlock | `airlock_diameter` | Tube, hatch clear |
| Figure | `human_figure.standing_height` | Scale mannequin |

Collection-linter reports length faults. This bible does not. Lineage changes joints, not metres.

## 7. Sol hardware vs Kepler hardware

Sol-built prop (gram-class probe body, archive canister, sail remnant): tag `origin=sol` on the object or the brief. Assembled at Kepler-62: `origin=kepler`. Unlabeled mix fails.

Launch stills `04`–`07` are the look-dev for the dispatched Sol stack (body + sail). A later `origin=sol` remnant on a Kepler cell is a different state. Do not dress the remnant as a full diamond sail unless a brief says the sail stayed attached (OPEN).

Sail remnant mass is extra to the 1–10 g body. Do not caption a 2 g stack as "1 g including sail."

Habitat-kit v1 can skip Sol props. It still cannot light the cell as Sol.

## 8. World-frame gates

Bible rejects, not a Habitat-kit dump script. Run Habitat-kit's own tests in that repo. Fail a row here = the kit dump is off-bible.

1. **One cell.** Independently orbiting cell. Not the swarm. Not a planet. Not a rigid lattice.
2. **Unit-canon only.** Lengths from Unit-canon. No magic numbers in graphs. Lineage does not fork units.
3. **Three cuts, same hull.** `construction` / `operational` / `relic`. Epoch is a parameter. Relic is not a redesign. No fourth epoch.
4. **Flux.** Exterior fill ≈ 27.3 W/m² (0.020 S☉). Dim, not a void. Work lights carry the close-up key. Star is K2.
5. **Temperature.** Teq work figure ~120 K for passive exterior under stated assumptions. Active plant is separate. No shirtsleeve balcony. No Earth-noon grade.
6. **Payload class.** No living crew as the design. 1–10 g body, sail extra, dormant WBE / ASI / archive as hardware only. No civilisation-on-a-probe caption.
7. **Sol / Kepler.** Unlabeled Sol lighting or Sol hardware on a Kepler cell fails. Launch stills `04`–`07` are Sol; caption them as Earth departure. Do not caption Kepler `01`–`03` as Sol departure.
8. **Key-art body.** Kepler system still: large body is irregular and not Kepler-62b–f. Match `stills/01-eclipse.jpg` / `stills/03-inward.jpg`. No label. No detected-life caption on e / f. Launch diamonds are sails, not that body and not cells.
9. **Mass.** Do not caption a foil swarm as 12 M⊕. 1 mm @ 1% ≈ 0.012 M⊕. 12 M⊕ is 1 m @ 1%. Plate examples are not total swarm mass.
10. **0.2c is peak and coast.** No caption that the hop averaged 0.2c, or ran 982 yr at 0.2c. No 0.001 g two-century burn. No 7191–7201 default arrival. No silent Kepler brake laser.
11. **OPEN.** No new factions, religions, invented protagonists, or an identity for the large body.
12. **Relic.** Time-slice epoch. Empty habitation, protected unawakened archives, mixed repairs, restoration / preservation request. Not a dead swarm. Not a sermon. Oxidation needs an environment.

Actors, graphs, cooks, and Collection-linter live in Habitat-kit / Blend-ci. `calc/lightsail.py` reprints launch numbers. It is not a simulator.
