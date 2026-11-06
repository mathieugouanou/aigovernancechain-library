# The AI Risk Taxonomy, machine-readable edition

Thirty named AI risks in six MECE categories, as data you can load into your own tooling. This is the machine-readable edition of the free reference map published by AI GOVERNANCE CHAIN™.

Files:

- ai_risk_taxonomy.json : the full taxonomy as JSON
- ai_risk_taxonomy.yaml : the same taxonomy as YAML

What you can do with it:

- Seed your risk register: load the 30 risks as the starting rows of your own register or GRC tool.
- Tag your systems: map each AI use case in your inventory to the risk ids it is exposed to.
- Build checks: wire the category and risk slugs into review gates, CI checks, or intake forms.
- Keep the ids stable: the numeric ids and slugs are the canonical reference. Cite them as taxonomy risk 12 (sycophancy-truthfulness-failure).

Quick start (Python):

    import json
    tax = json.load(open("ai_risk_taxonomy.json", encoding="utf-8"))
    for cat in tax["categories"]:
        for risk in cat["risks"]:
            print(risk["id"], risk["name"])

Where the free version stops: this data names the risks. Scoring your exposure, treatment planning, risk appetite, and monitoring are the AI Risk Management Kit (paid). The human-readable edition, with the how-to-use guidance, is in the Free Library.

License: CC BY-NC-ND 4.0. Attribution required. No commercial use without a written license: contact@aigovernancechain.com

AI GOVERNANCE CHAIN™
(c) 2026 Mathieu K. Gouanou. All rights reserved.
A member of the Harvard Business Review Advisory Council, an opt-in research community of business professionals.
Document standard: human-first AI governance.
