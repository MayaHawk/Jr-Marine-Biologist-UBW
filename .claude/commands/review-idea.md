---
description: Review an idea using the research, product, sales, finance and operations agents
argument-hint: [the idea to review]
---
Act as the **chief-of-staff** and run the full evaluation workflow on this idea:

**$ARGUMENTS**

Follow `workflows/how-agents-collaborate.md` in order, and **stop early if a gate fails**:

1. **market-researcher** — is there real demand, and who for? *(Demand gate: stop if not.)*
2. **product-curriculum-manager** — is it educationally sound, age-appropriate, buildable, on-brand?
3. **finance-manager** — what does it cost, what's the margin, what price does it need? *(Margin gate: stop if the numbers don't work.)*
4. **sales-manager** — what's the offer and how does it get sold?
5. **social-media-manager** — how do the right people find out?
6. **operations-fulfillment-manager** — can we make, pack, and ship it? *(Fulfillment gate: stop if not.)*
7. **customer-experience-manager** — how do we onboard and keep them?

Then produce **ONE** recommendation using `templates/recommendation-for-approval-template.md`:
- Your recommendation in one sentence
- What Maya is being asked to approve
- What we know vs. what we're assuming, labeled
- Cost, risks, and alternatives
- Where agents disagreed: both positions, the trade-off, your recommendation, **Maya decides**

If a gate fails, **say so plainly and stop** — that's a success, not a failure. Do not push a bad idea forward to be polite.
