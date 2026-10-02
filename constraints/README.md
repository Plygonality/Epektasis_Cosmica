# Constraints

Enforceable world-frame checks. Every `*.json` file here must validate against [`../schema/constraints.schema.json`](../schema/constraints.schema.json). Calc tests run that check.

| File | Job |
| --- | --- |
| [`physics.json`](physics.json) | Binding figures, Unit-canon scale keys, rejects. |
| [`project-rules.json`](project-rules.json) | Project rules tagged CANON / INFERENCE / OPEN / PROPOSED. PROPOSED is staging only. |
| [`physics-checklist.md`](physics-checklist.md) | Human restatement of `physics.json`. |
| [`project-rules.md`](project-rules.md) | Human restatement of `project-rules.json`. |

Markdown is for reading. JSON is what CI enforces. If they fight, fix the JSON, then the markdown.

Habitat-kit owns generator notes. Do not dump dump-scripts, graph recipes, or cook runbooks into this folder.
