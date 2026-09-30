# Changelog

## 0.7.1, 2026-09-30

Project renamed *Epektasis Cosmica*. Scope now reads as the Stapledon programme's civilisations, megastructures, minds, and cosmology, not only the Sol and Kepler-62 swarms.

- README title and intro, bible README, and wiki §1 carry the new name.
- "Stapledon swarm" still names the stellar-era cell swarms. The Nullseed is still a Stapledon-programme class.
- Repository slug, `stapledon-swarm-calc` package name, and `stapledon-swarm.constraints/1` schema id unchanged, so downstream repos and CI keep resolving.
- No world fact changed. No OPEN item filled. No binding number changed.
- Calc package version set to 0.7.1 so it matches this bible revision.

## 0.7.0, 2026-09-29

Nullseed. Terminal-class descendant megastructure. No Gregorian construction date.

- New detail file `bible/nullseed.md`. Five subsystems: Harvest Mantle, Epoch Lattice, Continuity Weave, Moving Present, Causal Seed.
- Wiki §22, chronology §7, README indexes, featured-cell disambiguation, production reject, project-rule boundary.
- Evolutionary order is cosmological epoch labels after the provisional stellar-era rows, including the featured relic. The relic's failure sequence stays OPEN. Mantle recycling is not that failure.
- Topology-preserving vacuum bifurcation is a late setting lock only. It is not established physics and not a 2085–2095 probe capability.
- Subjective continuity of a reconstructed mind stays unresolved, consistent with the 2045–2058 WBE lock.
- No still added. `01`–`07` are not Nullseed frames. No OPEN item filled. No binding number changed.
- Calc package version set to 0.7.0 so it matches this bible revision.

## 0.6.0, 2026-09-24

Launch-era stills. Original probes leaving Earth, 2085–2095 A.D.

- Four Sol-departure stills in `stills/`: `04-boom.jpg`, `05-cross.jpg`, `06-face.jpg`, `07-fleet.jpg`. Embedded with captions in README, `stills/README.md`, wiki §13.4–13.7, and `probes.md` §11.
- Look-dev planform locked: diamond (square-on-point) membrane, four spars, gram-class hub. Edge-on reads as a thin cross.
- Adopted family table still quotes circular diameters as equivalent-area figures. Diffraction note stays on the circular 1 g row.
- Launch diamonds are not Kepler cell silhouettes. Earth in these frames is Earth.
- Face marks are look-dev illumination. They do not lock beam count or aperture (OPEN item 3 stands).
- Fleet visible count is camera selection. Batch size stays of order 1 000.
- Stills do not lock sail metres, boom length, membrane thickness, chassis bay count, retention after boost, or a day inside 2085–2095.
- Production map, project rules, and physics rejects updated for the Sol-launch / Kepler-system split.
- No OPEN item filled.

## 0.5.0, 2026-09-15

Split what is context from what CI can fail.

- README responsibilities: `bible/` is human + AI context; `calc/` and `schema/` are enforceable; `stills/` are caches.
- Constraint JSON Schema: `schema/constraints.schema.json`. Every `constraints/*.json` file validates in calc tests.
- `calc/` imports Unit-canon for meters / deck / airlock / figure. `lightsail.py` keeps SI/IAU physics constants as a documented local override.
- CI: `.github/workflows/calc.yml` runs pytest only. No Blend-ci, no Blender, no PNG hash, no LFS stills fetch.
- Key-art JPEGs tracked with Git LFS. Habitat Cuts stay generated from Habitat-kit.
- `bible/production.md` stays a thin map. Habitat-kit owns generator notes.

## 0.4.1, 2026-09-12

Reader-facing era label is Gregorian A.D., not CE. Every README (`README.md`, `bible/README.md`, `calc/README.md`, `stills/README.md`) states that.

## 0.4.0, 2026-09-12

Laser-driven lightsail replaces constant 0.001 g as the default hop. Controlled worldbuilding replaces the blanket ban on social history. Named founder table withdrawn.

- Launch architecture: dispatch, laser-driven lightsail, unpowered coast, unresolved capture. Interstellar 0.2c is directed laser light. Solar collectors may power the plant. Not a solar-wind sail.
- Adopted sail family (1–10 g body, sail mass = body, 0.1 g/m², 10 GW/m²) recalculated. Boost: 226 s, 7.31 million km ≈ 0.049 AU, ≈ 34 000 g. Script: `calc/lightsail.py`.
- Obsolete 0.001 g model (~198 yr burns, ~5 106 yr total, 7191–7201 A.D. arrival) removed from authoritative tables. Historical note only.
- Unbraked coast 4 910 yr external / 4 811 yr proper. 2085–2095 launches pass the target around 6995–7005 A.D. Passage is not capture. Settlement occurs; braking stays OPEN.
- Probe body 1–10 g. Sail extra. Archive is comprehensive acquired record plus gaps, not unrecorded history.
- 600 / 300 / 100 million target split withdrawn from canon. Shares stay OPEN.
- Later-faster arrival before original Kepler probes moved from CANON to OPEN.
- Named founder table (Rao, Venn, Aster, Saye, Okonkwo, Witness) withdrawn. Rationale: this revision allows institutions and WBE identity questions without inventing protagonists.
- Featured relic: active population migrated; damaged or unresolved archives never met fidelity and consent tests; leftover signal asks for restoration or continued preservation. Physical failure sequence stays OPEN.
- Lineages: launch-decade versions become architectural ancestry (joints, hatches, service modules, repair traces). Not factions.
- Preservation: competing reconstruction practices, not four named factions. No detected life on Kepler-62e / f.
- Flux stated as ≈ 27.3 W/m². Dim, not a black void. 120 K is a passive-exterior work figure, not every machine's temperature. Plate-mass rows marked plate-only. Independent orbits are not a rigid lattice. Oxidation needs an environment.
- New detail files: `bible/probes.md`, `chronology.md`, `lineages.md`, `preservation.md`, `featured-cell.md`, `appendix-launch.md`.
- OPEN list rebuilt 1:1 from the wiki (29 items). Braking, survival, beam control, and sail retention added.

## 0.3.0, 2026-09-12

Programme history locked. Cruise wording corrected. Featured relic given a job.

- Founding launch window 2085–2095 A.D. About one billion original probes in batches of thousands. 3000 A.D. withdrawn as a founding date.
- 0.2c is peak and coast of the original Kepler hop. It is not the trip-average speed. The old line "cruise at 0.2c is wrong" is deleted.
- Transit table replaced with the special-relativistic 0.001 g result: 5,105.7 yr external, 5,007.9 yr proper, 97.9 yr clock difference. A 2090 departure arrives around 7196.
- Reader dates are Gregorian A.D. in a Sol-barycentric frame. Onboard proper time and experienced time are separate logs. Clock hardware stays OPEN.
- Three ages for stored minds: calendar, hardware elapsed, experienced. Dormancy is not time dilation.
- Nearby hops under the same model: 4.24 ly around 2218 at ~0.066c; 100 ly around 2786.
- Later descendants of the same programme can reach Kepler-62 before the original probes. A 0.5c / 3000 A.D. / 5483 A.D. row is representative INFERENCE, not a second founding launch.
- Picotechnology locked as picometre precision on atomic and molecular machines. Four limits recorded. Subatomic robots stay OPEN.
- Archive locked as the complete acquired Earth archive at cutoff, including gaps. 2085 freezes one cutoff. Later batches may revise.
- Founder group locked in the wiki. Habitat-kit and stills still do not instance names.
- Featured Habitat-kit relic cell preserves a departure-era computing environment. Leftover signal requests a 2085 commitment. Exact wording OPEN. Other cells’ relic modes OPEN.
- Payload class adds dormant ASI states and selective authorised activation. A gram-probe does not run a civilisation.
- OPEN list pulled 1:1 from the wiki again. Items 1, 2, 13 revised. Featured-cell relic role locked; other cells’ relic modes remain OPEN. Items 22–26 added (probe mass, unique targets, subatomic machines, archive capacity, later-descendant launch years).

## 0.2.0, 2026-09-07

Flattened the bible.

- Wiki is `bible/wiki.md`. Production map is `bible/production.md`.
- README §3 is how to read the wiki.
- Project rules live in `constraints/project-rules.md`.

## 0.1.2, 2026-09-06

Prose pass. Same numbers. Same tags. Same stills.

- Cut em-dashes, stacked "not this / but that" lines, and even sentence rhythm.
- Captions rewritten the same way. OPEN list unchanged.

## 0.1.1, 2026-09-06

Key-art stills added. No OPEN item filled.

- Three system stills in `stills/`: `01-eclipse.jpg`, `02-lattice.jpg`, `03-inward.jpg`. Embedded with captions in README, `stills/README.md`, and wiki §12–13.
- Large body locked as an irregular, non-spherical silhouette. Still not Kepler-62b–f. Identity and name remain OPEN.
- Distant cells in key-art read as repeating sharp geometric silhouettes. That is system-scale, not the Habitat-kit mesh.
- A small circular transit disk may appear. It is not the large body. Which of b–f stays unset.
- Habitat Cuts stay unshot. README gallery added. "No binaries" rule narrowed to "no binaries except `stills/`."

## 0.1.0, 2026-09-05

Initial public bible.

- Wiki, production map, and OPEN list.
- OPEN list extracted 1:1 from the wiki into `bible/open-questions.md`. No OPEN item filled.
- Binding numbers locked: 982 ly, 0.2c peak, ~5000–5100 yr bang-coast-bang at ~0.001 g, Kepler-62 work figures 0.76 M☉ / 0.26 L☉, swarm R = 3.6 AU, flux ≈ 0.020 S☉, Teq work figure ~120 K.
- Mass-table correction recorded: 1 mm @ 1% of a 3.6 AU sphere ≈ 0.012 M⊕; 12 M⊕ is a 1 m plate @ 1%.
- Sol / Kepler split, gram-probe / dormant WBE / digital-archive payload class, and the key-art rule (large body ≠ Kepler-62b–f) recorded as CANON.
- Scale pointed at [Unit-canon](https://github.com/Plygonality/Unit-canon). This repo does not own grid / deck / airlock / figure numbers.
- Habitat Cuts mapped to Time-slice `construction` / `operational` / `relic`.
- Four stills described in text only. No artwork binaries.
- MIT.
