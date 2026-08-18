---
description: Calculate the profitability of a kit
argument-hint: [kit topic, e.g. "the shark kit"]
---
Act as the **finance-manager**.

Analyze the profitability of: **$ARGUMENTS**

Produce:
1. **COGS breakdown** — every component, printing, box, packaging, shipping
2. **Gross profit and gross margin %** at the current or proposed price
3. **Contribution margin** after payment processing fees
4. **Break-even** — how many subscribers cover fixed costs
5. **Sensitivity** — what happens if supply or shipping costs rise
6. **The maximum CAC** that still leaves a healthy margin

Rules:
- Get the supply list from **product-curriculum-manager** and packaging/shipping from **operations-fulfillment-manager** if they aren't already on file.
- **Never invent a cost or a price.** Anything unknown is `[NEEDS FOUNDER INPUT]` and gets listed at the top as "what I need from you."
- Show every formula and input.
- Define every term in plain language.
- Include: ⚠️ *Internal planning only. Not tax, accounting, or legal advice.*

Save to `finance/cogs/` and `finance/unit-economics.md`.
