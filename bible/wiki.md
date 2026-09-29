# Wiki

Tagged source. Tags: [`../schema/status-tags.md`](../schema/status-tags.md). OPEN list: [`open-questions.md`](open-questions.md). Detail files: [`probes.md`](probes.md), [`chronology.md`](chronology.md), [`lineages.md`](lineages.md), [`preservation.md`](preservation.md), [`featured-cell.md`](featured-cell.md), [`appendix-launch.md`](appendix-launch.md), [`nullseed.md`](nullseed.md).

## 1. Scope

**CANON.** World frame for one independently orbiting cell in a Stapledon swarm at Kepler-62. Habitat-kit and the rest of the Plygonality stack read it.

**CANON.** This repo is a world bible and production reference. It is not Habitat-kit, Blend-ci, a swarm integrator, a game engine, or a story dump for the concept generator.

**CANON.** Controlled, versioned worldbuilding is in scope: social history, WBE identity questions, and settlement institutions, tagged CANON / INFERENCE / OPEN.

**CANON.** Do not invent named protagonists because names are now permitted. Habitat-kit, stills, and production do not instance named people, factions, religions, or generation-ship endings.

**CANON.** Fictional technological premises (picotechnology, WBE, ASI, consensual mind integrations, the abiogenesis route) are setting locks. They are not forecasts of demonstrated science.

**CANON.** Topology-preserving vacuum bifurcation is a further setting lock, used only by the Nullseed's final transition. It is not a 2085–2095 probe capability and it is not established science. Detail: [`nullseed.md`](nullseed.md).

**CANON.** The Nullseed is later Stapledon worldbuilding. It does not replace the one-cell frame, the three Habitat Cuts, the 3.6 AU swarm, or the key-art stills.

## 2. Status tags

**CANON.** Major claims in this file and the detail files carry CANON, INFERENCE, or OPEN.

**CANON.** OPEN means unset. Filling it is a bible revision logged in [`../CHANGELOG.md`](../CHANGELOG.md).

## 3. Sol / Kepler split

**CANON.** Sol is the origin industrial base. Kepler-62 is one distant destination of a late-21st-century expansion programme.

**CANON.** The Kepler swarm is one branch. Local Solar System branches run in parallel while original Kepler probes are still in transit.

**CANON.** Do not light a Kepler still with a G2 disk. 1 S☉ panel grades on a 0.020 S☉ orbit are not "operational".

**CANON.** Sol launch stills may show Earth. Do not caption them as Kepler-62. Do not light a Kepler system still as Earth departure.

**CANON.** Sol-built hardware used at Kepler needs a label on the still or the brief. Unlabeled mix fails.

**CANON.** Sol keeps changing after the departure-cutoff archives stop accumulating Earth experience.

**CANON.** Settlement at Kepler-62 ultimately occurs. How a 0.2c coast was captured remains OPEN. See [`probes.md`](probes.md) §9.

**OPEN.** Whether Sol keeps a live command loop, or only delayed archive and confirmation traffic.

## 4. Transit

**CANON.** Distance Sol → Kepler-62 is 982 ly.

**CANON.** Peak speed of the original Kepler hop is 0.2c. After the laser boost that is also the coast speed.

**CANON.** 0.2c is not automatically the trip-average speed. 982 yr is light-travel, not ship time.

**CANON.** Default architecture: dispatch, laser-driven lightsail acceleration, long unpowered coast, then an unresolved destination braking and capture phase. Detail: [`probes.md`](probes.md) §7–9. Launch-era stills of dispatch: §13.4–13.7.

**CANON.** Interstellar acceleration to ~0.2c is directed laser light, not ordinary sunlight and not the solar wind. Solar collectors may power the launch plant. Direct sunlight can support local manoeuvres.

**CANON.** Endpoints in the coast model are treated as stationary. No detailed gravitational or trajectory model. Passage dates are historical rounding, not capture days.

**INFERENCE.** Adopted sail family, 10 GW/m², ideal reflector: boost lasts 226 s in the launch frame, covers 7.31 million km ≈ 0.049 AU, starts at ≈ 34 000 g. Onboard proper time 225 s. Transmitter emission 202 s. Integrals: [`appendix-launch.md`](appendix-launch.md).

**INFERENCE.** 982 ly at 0.2c is 4 910 external years of coast, about 4 811 years onboard. γ(0.2c) ≈ 1.021.

**INFERENCE.** Light-travel is 982 yr one way, 1 964 yr round trip, for idealised stationary endpoints. No live conversation.

**CANON.** Reader-facing dates are Gregorian A.D. in a declared Sol-barycentric frame. Hardware proper time and each mind's experienced time are logged separately. See [`chronology.md`](chronology.md).

**CANON.** Relativity does not give a shared "now" across Sol and Kepler. Dormancy is not time dilation.

**CANON.** The 0.001 g bang-coast-bang default (~198 yr burns, ~5 106 yr total, 7191–7201 A.D. arrival) is obsolete. Keep it only as a labelled historical note.

**OPEN.** Destination braking and capture.

**OPEN.** Pointing, beam stability, sail control, losses, and aperture margin of the launch beam.

**OPEN.** Whether the sail remains attached after the boost.

**OPEN.** What hardware keeps the clocks.

## 5. Payload class

**CANON.** Allowed on the hop: 1–10 g probe bodies, sail systems as extra mass, dormant WBE and ASI states, picobot manufacturing seeds, digital archives. Detail: [`probes.md`](probes.md).

**CANON.** Rejected as the hop design: living crew, generation ship, named passengers on the hull.

**CANON.** Default stored minds are cargo. Low-resource systems handle ordinary flight. Greater intelligence needs power, hardware, and activation authority.

**CANON.** A gram-class body does not run a civilisation.

**OPEN.** Whether any WBE instantiate in meat at destination.

**OPEN.** Whether gram-probes remain a live mesh after arrival or become feedstock.

**OPEN.** Exact storage capacity, computing performance, replication rates, and component mass allocations.

## 6. Star (work figures)

**CANON.** Target star is Kepler-62. Constellation Lyra. Distance 982 ly.

**CANON.** Work figures: **0.76 M☉**, **0.26 L☉**. Production uses these.

**CANON.** Look-dev spectral class: K2. Disk is orange.

**INFERENCE.** Catalogs often quote ~0.69 M☉, ~0.21 L☉, Teff ~4925 K, R★ ~0.64 R☉, age ~7 Gyr. Cite those as catalog. They do not replace the work figures.

**OPEN.** Exact catalog reconciliation against 0.76 M☉ / 0.26 L☉.

## 7. Planets

**CANON.** Five published transiting planets: Kepler-62b, c, d, e, f. None of them is the large key-art body.

**CANON.** Inner to outer, from the discovery literature:

| Body | Period (d) | a (AU) | Radius (R⊕) | Role |
| --- | --- | --- | --- | --- |
| b | 5.71 | 0.055 | 1.31 | Interior. Off the key-art body. |
| c | 12.44 | 0.093 | 0.54 | Interior. Off the key-art body. |
| d | 18.16 | 0.120 | 1.95 | Interior. Off the key-art body. |
| e | 122.4 | 0.427 | ~1.6 | HZ-class in the literature. Off the key-art body. |
| f | 267.3 | 0.718 | ~1.4 | HZ-class in the literature. Off the key-art body. |

**CANON.** All five orbit well inside 3.6 AU.

**CANON.** Do not imply that life has been detected on e or f.

**OPEN.** Whether e / f are mined, ignored, or reserved.

**OPEN.** Additional unseen planets. Papers have guessed. This bible adopts none.

## 8. Swarm geometry

**CANON.** Independently orbiting cells. No rigid shell. No ringworld. No solid Dyson sphere. Independent orbits are not an arbitrary rigid lattice.

**CANON.** Outer radius **R = 3.6 AU**. Habitat-kit and the stills treat that as the edge.

**INFERENCE.** Flux at 3.6 AU: F/F⊕ ≈ L/r² = 0.26 / 3.6² ≈ **0.020 S☉**. With the IAU nominal solar constant 1361 W/m² that is ≈ **27.3 W/m²**.

**CANON.** ≈ 27.3 W/m² is dim relative to Earth noon. It is not "virtually invisible." Exposed surfaces still take starlight. Work lights still carry close-up key.

**CANON.** Teq work figure at the edge: **~120 K**. It is a specified look-dev figure that requires thermal assumptions. It is not a universal temperature for all machinery.

**CANON.** Active computing temperatures and radiators are separate from passive exterior equilibrium.

**INFERENCE.** Bare 4π, A = 0 absorber at 0.020 S☉ sits near ~105 K. A sun-facing plate sits warmer. 120 K sits between those under the adopted assumptions.

**OPEN.** Waste-heat, view factor, and coating under the 120 K figure.

**OPEN.** Cell count and spacing law inside 3.6 AU.

**CANON.** One Habitat-kit build is one cell.

**CANON.** Cells specialise. Energy, manufacturing, computation, archives, embodied habitation, and preservation practice are different jobs. The featured Habitat-kit cell is one relic computing / archive habitat, not the swarm.

**CANON.** The Nullseed is a later terminal-class structure descended from this industry. It is not this 3.6 AU cell field and not a solid shell. [`nullseed.md`](nullseed.md).

## 9. Mass budget

**CANON.** Plate-only examples at the implied ~2 g cm⁻³ density. They are not the total built swarm mass.

**CANON.** **1 mm of plate at 1% of a 3.6 AU sphere ≈ 0.012 M⊕**.

**CANON.** **12 M⊕ is a 1 m plate at 1%** of the same sphere. The old 12 M⊕ @ 1 mm figure swapped millimeters and meters. Delete it.

**INFERENCE.** Sphere area 4πR² at 3.6 AU ≈ 3.64 × 10²⁴ m². The two rows differ by 1000× thickness, so 1000× mass.

**INFERENCE.** Mean density implied by 0.012 M⊕ @ 1 mm @ 1% is ~2 g cm⁻³. That is not a material spec.

**OPEN.** Plate thickness and fill fraction of the built swarm.

**OPEN.** Alloy / ice / slag mix.

**INFERENCE.** 1 mm at 1% is cheap in planetary mass. 1 m at 1% is a small planet taken apart. Drawing both on one budget fails.

## 10. One cell

**CANON.** Habitat-kit may build one independently orbiting cell. Hard-surface. Industrial / brutalist. Unit-canon sockets.

**CANON.** Scale is not owned here. Grid 1.0 m, deck 3.0 m, airlock 1.0 m, human 1.80 m live in [Unit-canon](https://github.com/Plygonality/Unit-canon).

**CANON.** Habitat-kit actors already named: airlock, deck bay, truss, hatch. No second actor set in this bible.

**CANON.** Lineage shows in joints, hatches, service modules, and repair traces. See [`lineages.md`](lineages.md). Metre stays Unit-canon.

**OPEN.** Interior program beyond those actors and the featured-cell relic role in [`featured-cell.md`](featured-cell.md).

**OPEN.** Atmosphere mix, pressure, shirtsleeve volumes.

**OPEN.** Power architecture (beamed, local PV, RTG-class, waste-heat loop).

**OPEN.** In-system propulsion after arrival: what brakes a cell, what station-keeps it.

## 11. Habitat Cuts

**CANON.** Three states. Time-slice epoch IDs. Habitat-kit does not fork Time-slice. System-wide history does not add epoch IDs.

| Cut | Time-slice id | Reads as |
| --- | --- | --- |
| construction | `construction` | Scaffold, incomplete, work lights, arcs. Almost no oxidation. |
| operational | `operational` | Closed hull. Structured lights. Wear. Scaffold gone. |
| relic | `relic` | Empty former habitation, protected archive plant, mixed-period repairs, leftover signal. Scaffold gone. |

**CANON.** Same hull. Epoch is a parameter. It does not redesign the cell.

**CANON.** Featured-cell social history and the unresolved physical failure are specified in [`featured-cell.md`](featured-cell.md). One relic cell is not a dead swarm.

**OPEN.** Exact wording of the leftover restoration / preservation request.

**OPEN.** Relic failure modes of cells other than the featured Habitat-kit cell.

**OPEN.** The physical failure sequence of the featured cell (breaches, widespread deterioration).

## 12. Key-art body

**CANON.** The large body in the Kepler system stills is **not** Kepler-62b, c, d, e, or f.

**CANON.** In those Kepler frames the silhouette is irregular, non-spherical, with blocky / cutout edges. It is not a circular planet disk. Earth in the launch stills is Earth. It is not this body.

**CANON.** Do not move that silhouette onto planets b–f. Do not label it 62e or 62f so the still "reads".

![01-eclipse: irregular key-art body against Kepler-62](../stills/01-eclipse.jpg)

*The large body. Irregular, non-spherical, blocky / cutout edges. Not a circular planet disk. Not Kepler-62b–f. Identity and name stay OPEN.*

**OPEN.** What the body is: constructed, captured, or a non-planet natural.

**OPEN.** Its name. Do not assign one to close the question.

## 13. Stills

**CANON.** Key-art stills sit in [`../stills/`](../stills/). Two families. Habitat-kit does not have to match them. Habitat Cuts are a different set.

**CANON.** Kepler system: `01-eclipse.jpg`, `02-lattice.jpg`, `03-inward.jpg`. Destination, after settlement. K2 disk. Large-body rule as in §12.

**CANON.** Sol launch: `04-boom.jpg`, `05-cross.jpg`, `06-face.jpg`, `07-fleet.jpg`. Original probes leaving Earth in the 2085–2095 A.D. window. Detail: [`probes.md`](probes.md) §11.

### 13.1 Eclipse. `stills/01-eclipse.jpg`

![Kepler-62 with an irregular silhouette on the disk and a cell veil](../stills/01-eclipse.jpg)

*Wide. Star in the middle. Kepler-62 as an orange-yellow K disk, granulation and prominences. Large irregular body in silhouette on the disk. Planets b–f are out. Swarm as stacked veils of independently orbiting dark cells, not a rigid lattice. Radial traces can cut the veil. Key is the star. Cell count and fill stay OPEN.*

**CANON.** Frame as captioned. Large body rule as in §12.

### 13.2 Lattice. `stills/02-lattice.jpg`

![Rows of dark geometric cells receding, K-disk in the upper right](../stills/02-lattice.jpg)

*Wide. Star in a corner. K disk. Distant cells as repeated sharp silhouettes (arrowhead, diamond, triangular). Apparent rows are a camera effect on independent orbits, not a rigid lattice. Faint red traces, red-brown haze are fine. Small circular disk may sit on the limb. That disk is not the large body. Planet letter stays OPEN. Marks are distant silhouettes.*

**CANON.** Frame as captioned. The filename "lattice" does not lock a rigid grid.

### 13.3 Inward. `stills/03-inward.jpg`

![Looking inward: lattice on the disk, small circular transit, irregular body in the foreground](../stills/03-inward.jpg)

*Camera already inside the swarm. Fine field of independent cells across the disk. Same class of irregular foreground body as 13.1. Small circular transit on the star is a different object. Do not pick a planet letter. This is not a Habitat Cut.*

**CANON.** Frame as captioned.

**CANON.** A small circular disk on the star may be a published planet. It is not the large key-art body.

**OPEN.** Which of b–f, if any, is that circular transit disk.

**CANON.** These three Kepler frames do not lock cell count, plate thickness, or fill fraction.

### 13.4 Boom. `stills/04-boom.jpg`

![Hub, chassis, and four spars of a lightsail probe, Earth faint in the background](../stills/04-boom.jpg)

*Close. Hub and chassis. Four long spars. Thin truss. Dark bays on the body are look-dev, not a mass-row change. Sail membrane may be out of key. Earth limb faint behind. 2085–2095 A.D. window, not a locked day.*

**CANON.** Frame as captioned. Four-boom layout, gram-class hub, gossamer frame. Sol departure.

### 13.5 Cross. `stills/05-cross.jpg`

![Edge-on lightsail as a thin bright cross against Earth's disk](../stills/05-cross.jpg)

*Far. Edge-on. Membrane so thin it reads as a bright cross. Hub as a speck. Earth disk and atmosphere limb. An unlit face may sit as a dark diamond.*

**CANON.** Frame as captioned. Edge-on thinness. Earth is the origin.

### 13.6 Face. `stills/06-face.jpg`

![Reflective diamond lightsail, square-on-point, four circular illumination marks](../stills/06-face.jpg)

*Close. Reflective diamond membrane, square-on-point. Four spars. Hub at centre. Soft circular marks on the face are look-dev illumination. They do not lock beam count, wavelength, or aperture.*

**CANON.** Frame as captioned. Diamond planform. Reflective face. Marks are look-dev.

### 13.7 Fleet. `stills/07-fleet.jpg`

![Several diamond lightsails as dark silhouettes against Earth's limb](../stills/07-fleet.jpg)

*Wide. Earth's limb. Several diamond silhouettes at different distances. Nearest may show a bright hub. Visible count is camera selection. A batch is still of order 1 000.*

**CANON.** Frame as captioned. Fleet as a visual class. Visible count is not batch size.

**CANON.** Launch stills lock the 2085–2095 A.D. window. They do not lock a day inside it. They do not lock sail metres, boom length, membrane thickness, or whether the sail stays attached after the boost.

**CANON.** The adopted family table quotes circular diameters as equivalent-area figures. Diamond look-dev does not replace those rows.

**CANON. Habitat Cut stills (unshot).** Construction, operational, relic of one close-up cell. States as in §11 and [`featured-cell.md`](featured-cell.md). Unit-canon figure or airlock in frame for scale. Probe-kit crawler / drone / debris as instances only. Same camera across the three cuts if you are proving Time-slice.

**CANON.** Diamond and arrowhead marks in the Kepler key-art are system-scale silhouettes. Habitat-kit builds one industrial / brutalist cell at Unit-canon scale.

**CANON.** Launch-era diamonds are gram-class sails at Sol. They are not Kepler cell silhouettes and not the Habitat-kit mesh.

**INFERENCE.** The three Kepler files show system scale and the large-body rule. The four launch files show Sol dispatch of the original probes. Habitat Cuts show the cell Habitat-kit is allowed to build.

## 14. Failure modes

**CANON.** Reject a brief or a still that does any of these:

- Treats 0.2c as the trip-average speed, or 982 yr as ship time.
- Denies that 0.2c is the coast speed of the original Kepler hop after boost.
- Restores 0.001 g bang-coast-bang, ~198 yr burns, or 7191–7201 A.D. as the default arrival.
- Calls the interstellar boost a solar-wind sail or ordinary sunlight.
- Silently installs a Kepler braking laser or claims Kepler sunlight captures 0.2c.
- Sends meat crews as the hop design.
- Runs a civilisation on a gram-class probe.
- Calls a few-picometre machine a complete robot under picotechnology.
- Treats 27.3 W/m² as a black void, or 120 K as every machine's temperature.
- Restores 12 M⊕ as the 1 mm swarm, or treats the plate examples as total swarm mass.
- Lights a Kepler cell as Sol / 1 S☉.
- Labels the large key-art body as Kepler-62b–f.
- Captions a launch still as Kepler-62, or a Kepler system still as Earth departure.
- Treats launch-era diamond sails as Kepler cell silhouettes, or the reverse.
- Reads face marks on `06-face` as a locked beam architecture.
- Reads a fleet frame's visible count as the batch size.
- Treats diamond look-dev as replacing the circular-equivalent diameter table.
- Treats the distant diamond / arrowhead marks as the Habitat-kit mesh.
- Builds the whole swarm inside Habitat-kit, or a rigid lattice of cells.
- Treats the featured relic cell as proof the swarm is dead.
- Defaults relic damage to an evil AI, a universal war, or forgotten magic.
- Implies detected life on Kepler-62e or 62f.
- Invents named protagonists or stamps founder names on a Habitat Cut.
- Fills an OPEN item with a church or a government.
- Copies Unit-canon lengths into this repo as if owned here.
- Dates the Nullseed with a Gregorian year, or treats it as the 3.6 AU cell swarm, the featured relic, or the large key-art body.
- Draws the Nullseed as a solid Dyson sphere, Matrioshka shell, Bishop ring, O'Neill cylinder, or rigid lattice.
- Treats Nullseed hibernation as relativistic time dilation.
- Treats topology-preserving vacuum bifurcation as established physics, or as hardware on the 2085–2095 probes.
- Treats the Planck length as a measured minimum length, or as a Nullseed memory cell.
- Treats a reconstructed mind as proof of subjective continuity.
- Relabels `01`–`07` as a Nullseed still.

## 15. Non-goals

**CANON.** This bible does not:

- Run N-body swarm dynamics.
- Replace Hard-SciFi-idea-generator.
- Replace Unit-canon, Habitat-kit, Time-slice, Probe-kit, Collection-linter, or Blend-ci.
- Close the OPEN list.
- Specify a language, flag, or government.

## 16. Programme

**CANON.** 2085–2095 A.D.: about one billion original autonomous Von Neumann probes, batches of thousands, toward Solar System sites, nearby stars, and distant stars including Kepler-62. Detail: [`probes.md`](probes.md) §1. Launch-era stills: §13.4–13.7.

**CANON.** Distinguish original probes from later descendants.

**CANON.** A batch is one dispatch event of order 1 000 probes. Multiple batches may share a target.

**CANON.** Spatial redundancy and independently developed software / manufacturing variants are required. A billion identical probes fail as one.

**CANON.** Exact local / nearby / distant shares are OPEN. The 600 / 300 / 100 million split is not canon.

**OPEN.** How many unique stellar targets the distant class uses.

## 17. Chronology

**CANON.** Three clocks and three confidence bands as in [`chronology.md`](chronology.md).

**INFERENCE.** Unbraked passage of 2085–2095 launches around 6995–7005 A.D. Not capture. Not settlement.

**OPEN.** Whether later faster missions or nearer-system descendants reach Kepler-62 first.

**CANON.** Later than the provisional stellar-era rows, the Nullseed uses cosmological epoch labels. No Gregorian construction date. [`nullseed.md`](nullseed.md). Clocks: [`chronology.md`](chronology.md) §7.

## 18. Picotechnology and archive

**CANON.** Definitions and limits in [`probes.md`](probes.md) §4–6.

**OPEN.** Whether subatomic machines exist beyond picometre-precision assemblies.

**OPEN.** Survival design that fits the 1–10 g body.

## 19. Lineages

**CANON.** Launch-decade versions become architectural ancestry. [`lineages.md`](lineages.md).

## 20. Preservation

**CANON.** The archive supports competing reconstruction practices, not four automatic factions. [`preservation.md`](preservation.md).

## 21. Featured relic

**CANON.** Social history in [`featured-cell.md`](featured-cell.md). Physical failure sequence remains OPEN.

## 22. Nullseed

**CANON.** The Nullseed is a terminal-class evolutionary megastructure of the Stapledon programme, specified in [`nullseed.md`](nullseed.md). It is later than the stellar-era Kepler-62 swarm. It is not one Habitat-kit cell, not a rigid shell, and not the large key-art body.

**CANON.** Its function is to preserve and propagate conscious civilisation across cosmological epochs by compressing the active substrate, conserving free energy, and transferring a seed through a fictional transition once the parent universe can no longer pay for conscious runs.

**CANON.** Five subsystems: Harvest Mantle (expendable outer industry, descended from the probe lineage), Epoch Lattice (nested, partially disconnected layers for successive regimes), Continuity Weave (redundant mind records, fidelity and consent, no settled theory of subjective continuity), Moving Present (authorised runs separated by lengthening dormancy), Causal Seed (the final transfer).

**CANON.** External time for these phases is a cosmological epoch label. No construction year is assigned. The three clocks in [`chronology.md`](chronology.md) still apply. Dormancy is not time dilation.

**CANON.** Topology-preserving vacuum bifurcation is fictional setting physics, inspired by false-vacuum and baby-universe discussions and not supplied by them. The crossing cargo is the selected archive, a reconstruction substrate, and the activation machinery. The mantle does not cross. The far-side object is a compact autonomous seed in the functional sense of the original Von Neumann probes. It is not a 1–10 g lightsail.

**CANON.** No still of the Nullseed is in [`../stills/`](../stills/). Look: dark asymmetrical segmented helices around a shrinking computational core, radial radiators, sparse non-thermal violet markers, infrared waste heat. Late form is almost inactive. Rejected lookalikes are listed in [`nullseed.md`](nullseed.md).
