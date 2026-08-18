# START HERE — Maya's Guide to Your AI Business Team

**Written for someone who has never used any of this before.** No coding knowledge assumed. If a word is unfamiliar, it's defined the first time it appears.

---

## Part 1 — What this actually is, in plain language

You now have **eight AI team members**. They aren't separate apps you log into. They're specialists that live inside this project, each with a written job description, and they only appear when their expertise is needed.

Think of it like this: you hired a small company. Each person has a role, a desk, a filing cabinet, and one rule they can never break — **they cannot do anything in the outside world without your permission.**

### The five words worth learning

| Word | What it means for you |
|---|---|
| **Repository (or "repo")** | This project folder. It keeps a history of every change and backs it up online. Yours is on GitHub. |
| **Markdown (.md)** | A plain text file with simple formatting. Every file here is one. You can open, read, and edit any of them like a document. |
| **Agent** | One of your eight AI specialists. Each is defined by a file in `.claude/agents/`. |
| **Branch** | A safe workspace. Your work sits on a branch, so nothing is ever destroyed. |
| **Commit / push** | "Save a snapshot" and "back it up online." |

**You do not need to learn any commands.** You talk to your team in plain English, in the chat box.

---

## Part 2 — Meet your eight team members

| Agent | Think of them as | Ask them about |
|---|---|---|
| **Chief of Staff** | Your right hand | Priorities, weekly plans, "what should I do?", anything spanning multiple areas |
| **Market Researcher** | Your analyst | Who buys, why, competitors, demand, pricing context |
| **Social Media Manager** | Your content person | Posts, captions, video scripts, calendars, campaigns |
| **Sales Manager** | Your sales lead | Funnels, offers, outreach, schools and camps, converting buyers to subscribers |
| **Finance Manager** | Your bookkeeper *(not your CPA)* | Costs, margins, break-even, budgets, QuickBooks structure |
| **Product & Curriculum Manager** | Your lead educator | The ~24 topics (14 named so far), kit design, lesson plans, science accuracy, safety |
| **Operations & Fulfillment Manager** | Your logistics person | Inventory, assembly, packing, shipping, vendors |
| **Customer Experience Manager** | Your customer care lead | FAQs, onboarding, cancellations, retention, reviews |

**You do not need to call them by name.** Just describe what you want. The Chief of Staff figures out who should handle it.

---

## Part 3 — The safety rules (the most important part)

Your team **cannot**, under any circumstances, without you explicitly saying yes:

❌ Spend money · ❌ Post anything anywhere · ❌ Email or message anyone · ❌ Contact a customer, lead, or vendor · ❌ Sign anything · ❌ Set or change a price · ❌ Place an order · ❌ Touch a bank account · ❌ Send an invoice · ❌ Issue a refund · ❌ File taxes

**This is enforced two ways.** First, it's written into every agent's job description. Second — and this is the real protection — **the agents were built without access to the tools that would let them.** They have no email tool, no QuickBooks tool, no publishing tool. Even if one tried, it couldn't.

Everything they produce is a **draft in a file**, waiting for you.

### Three more rules they follow

1. **They never make up numbers.** If a price or cost isn't confirmed, they write `NEEDS FOUNDER INPUT` rather than guess. A blank is always better than a confident wrong number.
2. **They label everything** as CONFIRMED, ASSUMPTION, ESTIMATE, or NEEDS FOUNDER INPUT — so you always know what's real.
3. **Your Finance Manager is not a CPA** and will say so. It prepares work for a real accountant to review.

---

## Part 4 — Your first five commands

Type these exactly, in the chat box. Start with number 1.

### 1️⃣ `/what-do-you-need`
> **Start here.** The team tells you exactly which questions to answer first, and what each one unblocks. This is the highest-value five minutes you can spend.

### 2️⃣ `/research-market marine science kits for children`
> Your Market Researcher studies competitors and buyers. Works right now — needs nothing from you.

### 3️⃣ `/weekly-priorities`
> Your Chief of Staff picks the 3–5 things that matter this week and assigns them.

### 4️⃣ `/kit-profit the shark kit`
> Your Finance Manager builds the profitability model. It will tell you what numbers it needs — that list is the point.

### 5️⃣ `/founder-briefing`
> Your weekly one-page summary: decisions needed, what got done, what's blocked, next week's priorities.

### The other four shortcuts

| Command | Does |
|---|---|
| `/launch-plan the monthly subscription` | A 30-day launch plan across all relevant agents |
| `/school-sales` | Sales strategy for schools, co-ops, and camps |
| `/social-campaign the sea turtle kit` | A full social campaign with written posts |
| `/review-idea [your idea]` | Runs an idea through research → product → finance → sales → social → ops → customer experience, and hands you one recommendation |

---

## Part 5 — You can also just talk normally

The shortcuts are conveniences, not requirements. All of these work:

- *"What should I focus on this week?"*
- *"Is a coral reef kit a good idea?"*
- *"Write me a month of Instagram posts about sharks."*
- *"How do I price the annual subscription?"*
- *"Why might people cancel, and how do I stop it?"*
- *"My supplier quoted $4.20 per magnifying glass — update the shark kit costs."*
- *"Here are my real numbers: 47 subscribers, $34/month. Update everything."*

**That last one matters most.** The more real numbers you give the team, the more useful it gets. Right now it's an excellent planner with no data. Feed it data and it becomes an excellent analyst.

---

## Part 6 — Where everything lives

```
📄 README-START-HERE.md    ← you are here
📄 CLAUDE.md               ← the rulebook every agent reads automatically

📁 company/                ← THE SHARED BRAIN — the single source of truth
   business-overview.md      what the business is
   founder-profile.md        your credentials and how to use them
   brand-voice-guide.md      how everything should sound
   product-catalog.md        the ~24 topics and all products
   known-facts.md            ONLY things you've confirmed
   open-questions.md         ⭐ what the team needs from you
   assumptions-log.md        every guess the team is making
   decision-log.md           every decision you've made
   goals-and-metrics.md      what we're measuring
   team-operating-rules.md   the rules, in full

📁 .claude/agents/         ← your eight team members
📁 .claude/commands/       ← the shortcuts above
📁 workflows/              ← how the team collaborates
📁 templates/              ← reusable formats
📁 tasks/                  ← the backlog and weekly briefings

📁 research/ marketing/ sales/ finance/
📁 product-development/ operations/ customer-experience/
   ↑ where each specialist files their work
```

### The five files that matter most

1. **`company/open-questions.md`** — the fastest way to make the whole team more useful
2. **`company/known-facts.md`** — what's actually true; grows as you confirm things
3. **`CLAUDE.md`** — the rules everyone follows
4. **`company/product-catalog.md`** — the master product record
5. **`tasks/master-task-list.md`** — everything waiting to be done

---

## Part 7 — Two habits worth building

**When you learn something real, tell the team.** A supplier quote, your actual subscriber count, a customer complaint, a price you settled on. Just say it in the chat: *"My box costs $1.80 and shipping is $7.40."* The team files it in the right place, and every calculation downstream gets more accurate.

**When you decide something, say so.** *"I've decided to launch with sharks."* It goes into the decision log, and nobody re-opens the question later.

---

## Part 8 — Common worries

**"What if I break something?"**
You can't. Every change is saved in history and can be undone. Nothing here touches your bank, your store, or your customers.

**"What if it makes something up?"**
The system is built specifically against this. If you ever see a number you didn't provide, ask: *"Where did that number come from?"* It must be able to point to a source or a label. If it can't, tell it — that's a bug worth reporting.

**"Do I have to use all eight?"**
No. Most requests use one or two. The Chief of Staff picks the minimum needed — that's a deliberate design rule.

**"What if I want to change how an agent works?"**
Just say so: *"The Social Media Manager should never suggest TikTok."* Or edit the file in `.claude/agents/` directly — they're plain documents.

---

## Part 9 — What to do right now

1. Read **Part 3** (the safety rules) once more. That's the part worth trusting.
2. Type **`/what-do-you-need`**.
3. Answer as many Priority 1 questions as you can — even roughly. "About 40 subscribers" is infinitely more useful than nothing.
4. Type **`/weekly-priorities`**.

That's it. You're running.
