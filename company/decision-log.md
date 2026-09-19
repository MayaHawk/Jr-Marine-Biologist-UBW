# Decision Log

**What this is:** the permanent record of every significant decision Maya has made. It exists so the team never re-litigates a settled question, and so that six months from now anyone can see *why* the business works the way it does.

**Editing rule:** only decisions Maya has **actually made** go here. A recommendation is not a decision. An agent's preference is not a decision.

**Last updated:** 2026-08-18

---

## Format

Each entry uses this shape:

```
### D-### — <short title>
- **Date:**
- **Decision:**
- **Made by:** Maya Hawk
- **Context:** what prompted it
- **Options considered:**
- **Why this option:**
- **Affects:** which files, agents, or plans change as a result
- **Revisit when:** the condition that should reopen this
```

---

### D-001 — Build the operating system before running any marketing
- **Date:** 2026-08-18
- **Decision:** Build the team structure, shared knowledge base, workflows, and approval rules first. Do not begin executing marketing campaigns yet.
- **Made by:** Maya Hawk
- **Context:** Setting up the AI operating team for Junior Marine Biologist.
- **Options considered:** (a) start producing marketing content immediately; (b) build the system first.
- **Why this option:** Content produced before the team shares one set of facts, one voice, and one set of approval rules creates contradictions that cost more to fix than to prevent.
- **Affects:** all agents; `tasks/master-task-list.md`
- **Revisit when:** the operating system is complete and Maya approves moving to execution.

### D-002 — Maya holds all external-action authority
- **Date:** 2026-08-18
- **Decision:** No agent may spend money, publish content, contact customers or leads, sign agreements, change pricing, place orders, move money, file taxes, or make any external commitment without Maya's explicit approval.
- **Made by:** Maya Hawk
- **Context:** Foundational operating rule for the team.
- **Options considered:** (a) allow agents limited autonomous action; (b) require approval for everything external.
- **Why this option:** The founder is the final decision maker; the reputational and financial cost of an unapproved external action is far higher than the cost of an extra approval step.
- **Affects:** every agent definition; `CLAUDE.md`; `company/team-operating-rules.md`
- **Revisit when:** Maya chooses to delegate a specific, narrow action.

### D-003 — The finance agent is not a CPA
- **Date:** 2026-08-18
- **Decision:** The Finance & Operations Manager is an internal bookkeeping and financial planning role only. It does not replace a licensed CPA, tax professional, or attorney, and must never present itself as one.
- **Made by:** Maya Hawk
- **Context:** Foundational operating rule.
- **Options considered:** none — a stated requirement.
- **Why this option:** Tax and legal advice from an unlicensed source creates real liability.
- **Affects:** `.claude/agents/finance-manager.md`; everything in `finance/`
- **Revisit when:** never, unless a licensed professional is formally engaged.

---

### D-004 — This repository is the single source of truth
- **Date:** 2026-09-19
- **Decision:** The `Jr-Marine-Biologist-UBW` repository is the one place business truth lives. Work done in the separate "Under Blue Waters" Claude Project will be brought across into these files, and the project will stop being a parallel record.
- **Made by:** Maya Hawk
- **Context:** Between 2026-08-25 and 2026-09-19 Maya worked in a separate Claude Project. That project cannot be seen from here — Claude Projects are isolated — so this repository fell a month behind while real work continued elsewhere. Two parallel systems had formed.
- **Options considered:** (a) consolidate into this repository; (b) make the Under Blue Waters project primary and copy the agents there; (c) keep both for different purposes.
- **Why this option:** This repository holds the eight agents, the risk register, the confirmed cost data, the templates, and a dated commit history. A chat project keeps conversation, not a structured, searchable, version-controlled record. Option (c) is what had accidentally happened, and it is precisely the "multiple conflicting versions" failure the operating rules exist to prevent.
- **Affects:** every file; how Maya works day to day
- **Revisit when:** never, unless Maya deliberately moves the system somewhere else.

---

### D-005 — Discontinue the subscription model
- **Date:** 2026-09-17
- **Decision:** Stop selling a recurring subscription. Sell one-off Adventure Kits and prepaid 12/24-kit bundles only. Nothing auto-renews. Subscription language removed site-wide.
- **Made by:** Maya Hawk
- **Why this option:** GoDaddy could not support recurring billing, forcing a workaround through a second brand. Prepaid bundles capture the same up-front cash without the billing machinery or the brand handoff at checkout.
- **Affects:** 🔴 **`company/goals-and-metrics.md` — the stated business goal was "increasing paid subscriptions," which no longer exists as a product.** Also all sales, social, and customer-experience work built around retention of subscribers.
- **Revisit when:** a platform that supports recurring billing under the Jr. Marine Biologist brand is chosen.

### D-006 — Prices set
- **Date:** 2026-09
- **Decision:** Adventure Kit $45.99 with free US shipping · 12-kit bundle $503.99 · 24-kit bundle $949.99 · Digital Lesson Pack $9.99 · Complete Digital Library $99.
- **Made by:** Maya Hawk
- **Affects:** all finance, sales and marketing work. **Note: set before COGS was known.**
- **Revisit when:** real cost per kit lands.

### D-007 — No refunds, credits or discounts without explicit permission
- **Date:** 2026-09-17
- **Decision:** No agent, and no email, may offer a customer a refund, credit or discount without Maya's explicit permission each time.
- **Context:** A customer email offered a full refund that Maya had not authorised; the customer accepted it in writing.
- **Affects:** every customer-facing template. ⚠️ **The live Terms of Service still says "we will refund any kits not yet sent" — this contradicts the new policy and is unresolved.**

### D-008 — Consolidate to jrmarinebiology@gmail.com
- **Date:** 2026-09-17
- **Decision:** Site-wide support email is jrmarinebiology@gmail.com. Info@underbluewaters.com removed from every page.
- **Made by:** Maya Hawk

### D-009 — Under Blue Waters is the heritage brand used to reach the warm list
- **Date:** 2026-09-18
- **Decision:** The campaign to past camp families introduces Jr. Marine Biologist as "the newest thing from Under Blue Waters," in a friendly founder voice, keeping the original subject line.
- **Made by:** Maya Hawk
- **Note:** This supersedes assumption A-007 in a third direction — Under Blue Waters is neither the product brand nor a separate experiences brand, but the **trust anchor** that gives Jr. Marine Biologist a warm audience.

---

### D-010 — New business goal: sell 2,000 kits
- **Date:** 2026-09-19
- **Decision:** The goal is to **sell 2,000 kits as quickly as possible for as much as possible.** This replaces the original subscription goal.
- **Made by:** Maya Hawk
- **Context:** The subscription was discontinued (D-005), voiding the previous goal. 3,000 printed boxes are already owned and paid for; 2,000 kits converts two-thirds of that asset into cash.
- **Options considered:** Maya set this directly.
- **Why this option:** It is a concrete number tied to an asset already on the shelf, rather than an abstraction.
- **Affects:** `company/goals-and-metrics.md`, every agent's definition of success, and the task list. Sales and Operations become the lead functions.
- **Team note for Maya:** "as quickly as possible" and "for as much as possible" conflict. The team will surface the trade-off each time rather than silently choosing. The arithmetic also shows the warm list alone reaches at most ~52% of the goal, so bulk buyers are required.
- **Revisit when:** 2,000 kits are sold, or Maya changes the target.

---

### D-011 — Sell outward from Delray Beach, delivering locally within one week
- **Date:** 2026-09-19
- **Decision:** Bulk outreach starts with buyers nearest Delray Beach and works outward. Local orders are **hand-delivered within one week — never same day.**
- **Made by:** Maya Hawk
- **Why this option:** Shipping is free to the customer, so Maya absorbs roughly $8.85–$12 per box. Delivering locally instead of shipping recovers that in full — about **$1,000 on a 100-kit order**, and up to **$20,000** across the 2,000-kit goal. It is also the one place where "as quickly as possible" and "for as much as possible" stop conflicting: a local buyer can be offered a better deal while Maya keeps more, because the postage never leaves her pocket. Maya's credibility is also strongest locally, having run ocean adventure camps out of Delray Beach since 2009.
- **Why one week and not same day:** Maya packs every kit herself and assembly time has never been measured. A same-day promise on a bulk order is capacity nobody has confirmed, and this business has already had one customer wait 50 days after being told a kit was coming. A week is honest, defensible, and still faster than any national competitor.
- **Affects:** `sales/partnerships/`, all outreach copy, `operations/sops/getting-orders-out-the-door.md`, delivery pricing
- **Revisit when:** assembly time is measured, or demand outgrows one person delivering.

---

### D-012 — The business does not offer refunds
- **Date:** 2026-09-19
- **Decision:** **Junior Marine Biologist does not offer refunds.** This is reaffirmed as standing policy, not a case-by-case judgement. On order **R916215991** specifically: no refund. The customer receives the **complete $99 Digital Library** instead.
- **Made by:** Maya Hawk
- **Context:** An email sent 2026-09-17 offered that customer a refund without authorisation, and she accepted it in writing. The Chief of Staff raised the resulting chargeback exposure on 2026-09-19; Maya reaffirmed the decision. It is recorded as made and is not to be reopened.
- **Affects:** every customer-facing template, all agent behaviour, the Terms of Service
- **What every agent must now do:**
  - Never offer, imply, hint at, or leave a blank that could be filled with a refund
  - Where a service template previously read `[MAYA: refund / replacement / credit — your call]`, refunds are removed from the options
  - A customer asking for a refund is escalated to Maya, never answered by an agent
- **⚠️ The one thing still outstanding:** the live Terms of Service say *"we will refund any kits not yet sent."* **A published Terms of Service is the stronger document in a dispute than an internal policy.** Fixing that line is now the only remaining exposure that is fully within Maya's control, and it is a five-minute edit. Tracked as risk R-11.
- **Revisit when:** Maya says otherwise.

---

### D-013 — Free local delivery starts at 50 kits
- **Date:** 2026-09-19
- **Decision:** The minimum order qualifying for **free local hand delivery is 50 kits.** Below that, an order ships.
- **Made by:** Maya Hawk
- **The economics:** 50 kits is a **$2,299.50** order at full price, and delivering rather than shipping recovers roughly **$440–$600** of postage that would otherwise come straight out of margin. A couple of hours of driving for ~$500 is a good trade. **40 buyers at 50 kits reaches the 2,000-kit goal.**
- **The consequence to be aware of:** a typical classroom is about 24 students, so **one teacher acting alone cannot reach 50.** They need a second class, a colleague, a grade level, or a co-op. This is a deliberate push toward larger orders — it suits the goal, but it changes who outreach targets: grade-level leads, curriculum coordinators, principals, co-op organisers, camp and after-school directors. Individual teachers are pointed at the $45.99 single kit or the $9.99 digital pack.
- **⚠️ Unresolved dependency:** the one-week local delivery promise (D-011) **cannot be safely quoted on a 50-kit order until assembly time is measured.** At 10 minutes a kit, 50 kits is 8 hours. At 50 minutes, it is 42 hours — more than a working week, before anything else gets done.
- **Affects:** `sales/partnerships/`, all bulk pricing tiers, outreach targeting
- **Revisit when:** assembly time is known, or demand shows the floor is set wrong.

---

### D-014 — Packing rate confirmed at 10 minutes per box, conditionally
- **Date:** 2026-09-19
- **Confirmed by:** Maya Hawk
- **The figure:** **10 minutes to pack one box** — *once everything is organised for shipping, and once a master material list exists.*
- **Why it matters:** this was the most-blocking unknown in the business. It unblocks five things at once:
  - **The one-week local delivery promise (D-011) is now honest.** A 50-kit order is 8.3 hours; a 100-kit order is ~2 working days.
  - **The 2,000-kit goal drops from a possible 42 weeks of packing to ~8.3 weeks** for one person.
  - **Christmas is comfortably feasible** — even 500 kits is about 2 weeks of packing inside a 12-week window.
  - **Labour becomes countable in margin for the first time:** ~$3.33/kit at $20/hr, about 7% of the $45.99 price.
  - **The hire-or-not question softens.** One person can do this; help would speed it, not rescue it.
- **⚠️ The two conditions are not decoration:**
  1. The **organising/staging step sits outside the 10 minutes** and is unmeasured. True cost per kit is 10 minutes plus an amortised share of staging.
  2. **The master material list does not exist.** Maya named it herself as the precondition. Until it does, the 10-minute rate is not reproducible at volume.
- **Affects:** `company/goals-and-metrics.md`, `sales/q4-christmas-window.md`, `sales/path-to-2000-kits.md`, `finance/cogs/`, every delivery promise
- **Revisit when:** staging time is measured, or the rate changes at volume.

---

### D-015 — Card design standard
- **Date:** 2026-09-19
- **Decision:** Every activity card, in all 24 topics, follows one standard.
  - **Front:** a **real marine photograph** (not illustration), **no title on the photo**, only the **topic name** and the card number worded **`Card [N] of 5`**.
  - **Back:** activity title **in bold**, then the steps, then materials — **kit materials in the main block, and everything the parent supplies at the bottom, italicised, under NOT INCLUDED.**
- **Made by:** Maya Hawk
- **Why this is more than a style rule:** it is the mechanism that makes the master materials list trustworthy. Maya's own flags sheet already records scissors marked "not included" on some cards but not others, and cotton balls listed both ways. **An inconsistently marked card creates a phantom item that gets costed, ordered and packed — or a parent who expects scissors in the box and finds none.** One marking rule ends that class of error.
- **Affects:** all 24 topics, `templates/card-design-standard.md`, every future materials list
- **Status of the range:** Fresh vs Salt Water and Navigating Our Oceans are card-complete. **Navigating Our Oceans is complete on both cards and materials, making it the reference build.**
- **Revisit when:** Maya changes the format.

---

*(New decisions are appended below, newest last.)*
