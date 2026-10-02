# Project rules

Readable restatement of [`project-rules.json`](project-rules.json). CI validates that JSON against [`../schema/constraints.schema.json`](../schema/constraints.schema.json).

Rules for anyone who writes or revises this bible. World facts live in `bible/`.

## Job

A versioned world frame for one independently orbiting cell in the Kepler-62 Stapledon swarm. Habitat-kit reads it. Time-slice maps three epochs onto it. Blend-ci cooks stills of it. None of that work happens here.

## Out of scope

Habitat-kit code: generators, graphs, apply scripts.

Blend-ci: cooks, hashes, image CI. Calc tests in this repo are in scope.

Swarm integrator. Game engine. Other Plygonality toolchain repos.

Story seed for [Hard-SciFi-idea-generator](https://github.com/Plygonality/Hard-SciFi-idea-generator).

Second Unit-canon. Scale: https://github.com/Plygonality/Unit-canon

Named protagonists invented to fill space. Named people, factions, or religions on a still, graph, or Habitat Cut. Generation-ship endings.

## Tone

Numbers. Failure modes. Marked unknowns. No mythic diction. Skip "ancient builders", "fallen empire", "last ship".

Social history is allowed when tagged. It does not replace physics.

## Payload class

Hop hardware: 1–10 g probe body, sail system as extra mass, dormant WBE and ASI states, picobot seeds, digital archives. Living crews on a multi-millennium clock are out. A gram-class body does not run a civilisation.

## Sol vs Kepler

Sol is origin. Kepler-62 is one distant branch of a late-21st-century expansion programme. G2 lighting on a Kepler cell is wrong. Earth-flux panels on a 0.020 S☉ / 27.3 W/m² orbit are not operational. Label the split if a still could be misread. Sol launch stills may show Earth. Do not caption them as Kepler-62.

## Speed and launch

0.2c is the peak and the coast of the original Kepler hop after a laser-driven lightsail boost. It is not automatically the trip-average speed. 982 yr is light-travel.

Do not restore constant 0.001 g bang-coast-bang as the default. Do not write 7191–7201 A.D. as the current arrival window. Do not call the interstellar burn a solar-wind sail.

## Time

Reader dates are Gregorian A.D. in a Sol-barycentric frame. Hardware proper time and experienced time are separate logs. No shared "now" across Sol and Kepler. Passage dates are not capture dates.

## Mass table

1 mm of plate covering 1% of a 3.6 AU sphere ≈ 0.012 M⊕. 12 M⊕ is a 1 m plate at 1%. Those are plate-only examples, not total swarm mass. The 12 M⊕ @ 1 mm figure is a unit error. Do not restore it.

## Light and temperature

≈ 27.3 W/m² at 3.6 AU is dim, not a black void. ~120 K is a specified passive-exterior work figure. Active computers and radiators are separate.

## Key-art body

The large body in the key-art stills is not Kepler-62b, c, d, e, or f. Do not move the silhouette onto those planets. Do not name the body to close the question.

## Featured relic

Empty former habitation, protected unawakened archives, mixed repairs, a restoration or preservation request. One cell. Not the swarm's death. Physical failure sequence stays OPEN unless a later revision logs it.

## OPEN items

Do not fill them in a still brief, a graph comment, or a README aside. Promote only with a CHANGELOG line. Do not silently resolve braking or survival.

## Artwork

Key-art: [`../stills/`](../stills/). Two families, tracked with Git LFS: Kepler system (`01`–`03`) and Sol launch (`04`–`07`). Do not add stills to close an OPEN item. Do not label the irregular silhouette as Kepler-62b–f. Do not caption launch stills as Kepler-62. Launch diamonds are not cell silhouettes. Habitat Cuts are generated from Habitat-kit and stay unshot here. Do not dump Habitat-kit production notes into `bible/`.

## Nullseed

Later terminal-class megastructure. Detail: [`../bible/nullseed.md`](../bible/nullseed.md). Not the Habitat-kit cell, not the 3.6 AU swarm, not a rigid shell, not the large key-art body. No Gregorian construction date. Topology-preserving vacuum bifurcation is fictional setting physics, not a work figure and not a 2085 probe capability.

## Tags

Keep CANON / INFERENCE / OPEN / PROPOSED. PROPOSED is staging only and does not close an OPEN item. Definitions: [`../schema/status-tags.md`](../schema/status-tags.md). Machine contract: [`../schema/constraints.schema.json`](../schema/constraints.schema.json).
