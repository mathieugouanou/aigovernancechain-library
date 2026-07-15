# The Technical Layer

Machine-readable and runnable editions of the AI GOVERNANCE CHAIN™ instruments, for engineers who
want to import the frameworks into their own tooling instead of reading them.

No prior context is assumed. Every file is standalone, carries its license and
citation inside the data, and mirrors a canonical human-readable instrument in
the free library.

## The files

| File | What it is | Use it to |
|---|---|---|
| ai_risk_taxonomy.json / .yaml | The 30 named AI risks across six categories, as structured data with stable ids and slugs | Seed a risk register, tag an AI inventory, cite risks by stable id (e.g. risk 12, sycophancy) |
| sycophancy_test_battery.json | Ten paired-prompt tests with per-test scoring rubrics, 30 points | Red-team any AI system for flattery, capitulation, and manufactured agreement |
| score_battery.py | The runnable scorer for the battery | Score a battery run, get the band and the weakest patterns |
| governance_health_score_schema.json | The AI Governance Health Score™: 16 questions, 4 axes, 64 points, bands | Embed the quarterly health score in your own pipeline or dashboard |
| decision_trace_log_template.yaml | The Decision-Trace Log, one entry per AI-influenced decision | Drop into your repo; entries are the evidence an auditor accepts |
| ai_use_case_intake_template.yaml | The AI Use-Case Intake Form, one file per system | Make "register it first" the default before anything ships |

## Quick start

```python
import json
with open("ai_risk_taxonomy.json") as f:
    taxonomy = json.load(f)
for risk in taxonomy["risks"]:
    print(risk["id"], risk["slug"], "-", risk["name"])
```

Run the battery scorer:

```bash
python score_battery.py            # after filling SCORES in the file
python score_battery.py results.json
```

## Canonical ids

Ids and slugs in these files are canonical and stable. Cite them
("taxonomy risk 12", "battery test T03", "health question HS06") and they will
not change meaning across versions.

## The boundary

These free files carry the WHAT and the WHY. The HOW, the WITH-YOU, and the
DONE-FOR-YOU (the full kits, the operating system, the audit) live in the paid
catalog: see the storefront. Where free ends, a pointer inside each file tells
you exactly which paid instrument continues.

---
License: Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0). Free to use and share with attribution. Commercial use requires a written license: contact@aigovernancechain.com

AI GOVERNANCE CHAIN™
AI Governance Framework
(c) 2026 Mathieu K. Gouanou. All rights reserved.
Member, Harvard Business Review Advisory Council.
Document standard: human-first AI governance.
