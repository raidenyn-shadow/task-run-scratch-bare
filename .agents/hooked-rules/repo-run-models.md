---
pointer: "Run models, reviewer models and presets live only in this file; never substitute a model; read this file before any run phase or review."
skills:
  - "openspec-ff-change"
  - "opsx:ff"
  - "openspec-propose"
  - "opsx:propose"
  - "openspec-new-change"
  - "opsx:new"
  - "openspec-continue-change"
  - "opsx:continue"
  - "openspec-archive-change"
  - "opsx:archive"
commands:
  - "\\bopenspec\\s+new\\s+change\\b"
  - "\\bopenspec\\s+instructions\\s+(brainstorm|proposal|design|specs|tasks|plan)\\b"
---

# Run models

The model for each role of a task's run. This is the only workflow file that names a model.

| Role | Model | Effort |
| --- | --- | --- |
| plan | Opus-5.5 | medium |
| review | GPT-6.2-Sol | medium |
| implement | DeepSeek | medium |

A model cannot be started: stop and tell the user; never substitute another model.
