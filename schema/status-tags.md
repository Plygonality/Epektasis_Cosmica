# Status tags

Every major claim in the vault gets one tag. Keep the tag when you quote. Constraint JSON uses this enum. The schema is [`constraints.schema.json`](constraints.schema.json).

| Tag | Meaning | Who may change it | In a still or kit |
| --- | --- | --- | --- |
| **CANON** | Locked for this version. Set here, or a published number adopted as a work figure. | A tagged bible revision. Look-dev does not move it. | Use it. Do not "improve" it. |
| **INFERENCE** | Follows from CANON by arithmetic, geometry, or a stated model. Names that parent model. Wrong if the model is wrong. | A tagged revision that shows the derivation. | Use it. If it fights the parent CANON, keep the CANON. |
| **OPEN** | Deliberately unset. Unanswered. | A later revision that promotes it, with a CHANGELOG line and a reason. | Leave blank. No fill. No name. |
| **PROPOSED** | Operator-supplied candidate. Staging only. Not canon. Does not close an OPEN item. | A later revision that promotes it to CANON, or that withdraws it. | Do not instance it as fact. |

## Rules

1. A vault sentence that states a world claim and carries no tag is a defect. Tag it or delete it.
2. `production.md` maps facts. It does not add them. Habitat-kit owns generator notes.
3. OPEN to CANON needs a CHANGELOG line and a reason (measurement, a lock, or a derivation you can show).
4. CANON down to OPEN is breaking. Bump the minor version.
5. PROPOSED is not a soft OPEN and not a quiet CANON. Do not retag an existing OPEN item as PROPOSED so the new tag has an example. Do not promote PROPOSED to CANON in the same pass that adds the tag.
6. Promoting PROPOSED to CANON needs a CHANGELOG line and a reason. Withdrawing a proposal needs a CHANGELOG line. Neither action answers a different OPEN item.
7. Catalog numbers and work figures can disagree. Production uses the work figure. Catalog stays in a note.
8. One fact, one home. The detail file named for that topic holds the full table, derivation, or narrative. `bible/wiki.md` keeps one compact tagged index line and a link. A repeated number elsewhere is index-only and names its owner.

## Claim format

```
CANON. Peak speed of the original Kepler hop is 0.2c. After the laser boost that is also the coast speed.
INFERENCE. 982 ly at 0.2c is ~4,910 yr external coast. Unbraked passage for 2085–2095 launches is 6995–7005 A.D. Parent model: idealised coast at 0.2c.
OPEN. Destination braking and capture.
```

No claim in this revision is tagged PROPOSED.

Skip "maybe", "perhaps", "in the lore". Use the tag. Do not use `can`, `could`, `might`, `may`, or `would` to avoid assigning a tag.
