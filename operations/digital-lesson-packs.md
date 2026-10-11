# Digital Lesson Packs — Upload Status & Procedure

**Owner:** `operations-fulfillment-manager`
**Last updated:** 2026-10-11
**Source:** Maya's session report *"Under Blue Waters: Digital Course Upload"*, 2026-10-10 to 2026-10-11, done with Maya present in her main chat window. Everything marked CONFIRMED below comes from that report.

> **What this file is for:** the one place that tracks the 24 $9.99 Digital Lesson Packs on underbluewaters.com: what each pack contains, which topics are done, and the open items. The step-by-step upload procedure lives in Maya's saved Claude skill **`ubw-digital-pack-upload`**. This file summarizes it so the team can see it too.

---

## 1. What a Digital Lesson Pack contains — CONFIRMED (D-016)

**Price:** $9.99 per topic (CONFIRMED, D-006). One WooCommerce product per topic. Each pack has **seven separate downloads:**

| # | Download | Notes |
|---|---|---|
| 1 | START HERE – Parent Guide & How to Print | Coral Reefs version exists (from 2026-10-04). **The other 23 topics need one made.** |
| 2 | [Topic] – Ages 4-6 | |
| 3 | [Topic] – Ages 7-9 | |
| 4 | [Topic] – Ages 10+ | |
| 5 | [Topic] – Extra Resources | ID cards, grids, kit sheets, poster |
| 6 | [Topic] – Certificate of Completion | Typeable PDF: parents click a box and type the child's name |
| 7 | 10% Off Coupon – Code KIT10 | The existing Canva coupon page. **It is a 10% code, not 40%.** |

The three age files match the store's three age groups, 4-6 / 7-9 / 10+ (CONFIRMED in `company/known-facts.md`, 2026-09-19).

### The certificate — CONFIRMED rules
- It is a **typeable PDF** that works in any browser, Adobe Reader or Mac Preview. **No Canva account is needed.**
- 🔴 **Never deliver a Canva link taken from the full course file.** Anyone holding it could see the whole course for free.
- Wording: **"MARINE BIOLOGY FOR KIDS / PROUDLY AWARDS THIS"**, not "Under Blue Waters".

### Entire Course / $99 Digital Library — ⏸️ ON HOLD (D-016)
Planned format: **one file per topic, with all age groups for that topic in that one file.** Maya put it on hold so the individual packs get done first.
> ⚠️ **This affects other files.** Several sales files plan to offer the $99 library free with bulk quotes, and order **R916215991** was promised the library instead of a refund (D-012). See open question **DP-6**.

---

## 2. Status by topic

| Topic | Product ID | SKU | Store status | Files | Next step |
|---|---|---|---|---|---|
| **Coral Reefs** (pilot) | 2206 | JMB-DLP-13 | 🟨 **DRAFT, hidden from customers** | All 7 attached | Test order (DP-1), then Maya decides whether to publish (DP-4) |
| Other 23 topics | in Digital Products category (ID 35) | JMB-DLP-NN | DRAFT | **1 file each.** Each needs the full set, including a Parent Guide | Maya exports the ALL [Topic] file and attaches it |

**CONFIRMED (store admin, 2026-10-10/11):** the Digital Products category (ID 35) holds **24 lesson packs, all drafts**. In that category, **only the $9.99 Certificates product (ID 2474) is live.**

> ⚠️ **Does not match `company/product-catalog.md` §A0 (September 2026).** That section says Navigating Our Oceans is "live and visible" and 17 products carry the wrong (Navigating) PDF. `product-development/topics/sharks-canva-file-inventory.md` puts those 17 in the **GoDaddy store**. These may be two different stores, or Navigating may have been unpublished since then. **Not resolved. See open question DP-7.**

---

## 3. Coral Reefs — the pilot record

### Canva master
Design **"UBW Marine Biology for Kids Coral Reef"**, now **40 pages**. Sharing: **"Only you can access"**, no public view link, 0 visitors.

**Page map of the final export:**

| Section | Pages |
|---|---|
| Ages 4-6 (5 cards + certificate + blank) | 1–12 |
| Ages 7-9 | 13–24 |
| Extra Resources: Coral ID Card, Reef Mapping Grid, Reef Formations sheet | 25–27 |
| Ages 10+ | 28–39 |
| Extra Resources: Corals & Reef Builders poster | 40 |

**Fixes made in Canva:**
- All 3 certificates changed to the "Marine Biology for Kids" wording.
- **Ages 10+ fronts:**
  - Removed the old title text.
  - Added the round logo and a **"No. X of 5"** caption on a dark see-through strip.
  - Fixed the card order: Card 1 Symbiosis, Card 2 Darwin.
  - Swapped the Card 3 and Card 5 photos so each front matches its back.
- **Card 5 fronts:**
  - Ages 4-6 now has an atoll photo and Ages 7-9 a barrier reef photo, so they no longer repeat.
  - The "Coral Reefs Formation" infographic became an extra resource page.
- **Units:** "10 cm / 1 cm / centimetre" became "4 inches / less than half an inch".
- **Ages 4-6 grid step** now says "print two Reef Mapping Grids or draw two 4 × 4 grids", which matches the printed grid.
- **Step formatting:** on every back, only "Step N. Title:" is bold and the instruction is plain.
- **Ages 7-9 headers** made smaller so "No. X of 5" no longer wraps (pages 15, 16, 19, 23).
- **Overlaps:**
  - Fixed the Term line overlapping the Materials text (pages 23, 31).
  - "Terms:" changed to "Term:".

> ⚠️ **Card-number wording conflict, not resolved.** The Coral Reefs fronts say **"No. X of 5"**. Decision D-015 and `templates/card-design-standard.md` set the wording as **`Card [N] of 5`**. The Sharks fronts also say "No. 1 of 5". **See open question DP-8.**

**Known minor issue:** on Ages 7-9 Card 5 (page 23), all the Reef Facts bullets are bold.

### Store product: "Coral Reefs: Digital Lesson Pack"
- Product ID **2206** · SKU **JMB-DLP-13** · **$9.99** · slug `printable-coral-reef-activities-for-kids`
- **Status: DRAFT (hidden)**
- Files are in the protected downloads folder (`woocommerce_uploads/2026/10`).
  - Each file was checked byte-for-byte against the original.
  - Each was compressed for faster download while staying sharp for printing.

| Download | Size |
|---|---|
| START HERE – Parent Guide & How to Print | (from 2026-10-04, kept) |
| Coral Reefs – Ages 4-6 | 7.1 MB |
| Coral Reefs – Ages 7-9 | 5.1 MB |
| Coral Reefs – Ages 10+ | 6.0 MB |
| Coral Reefs – Extra Resources (ID Card, Mapping Grid, Reef Formations, Reef Poster) | 3.4 MB |
| Coral Reefs – Certificate of Completion (type your child's name) | 0.8 MB |
| 10% Off Coupon – Code KIT10 | (existing file, kept) |

The old 2026-10-04 Coral Reefs files are **still in the media library. Nothing was deleted.**

---

## 4. The procedure for each next topic (summary of skill `ubw-digital-pack-upload`)

1. **Maya** exports **ALL [Topic]** from Canva as **PDF Print, all pages**, and attaches it in chat. *(The Canva connector can't open her ALL designs: permission denied.)*
2. **QA** against the card standards in §6.
3. **Canva fixes** if needed, then a fresh export. Never delete Maya's Canva pages; park extras at the end and list them.
4. **Split** the export by age group plus extra resources.
5. **Upload** to the hidden pack and check each file byte-for-byte.
6. **Build the typeable certificate.**
7. **Run the final checks.** The product stays a draft until Maya says otherwise.

Each topic also needs its own **Parent Guide**. Coral Reefs is the template.

---

## 5. Store facts — CONFIRMED 2026-10-10/11

| Fact | Detail |
|---|---|
| Platform | underbluewaters.com runs **WordPress + WooCommerce** |
| Login | Through **GoDaddy**. **Maya signs in. Claude never types passwords.** |
| Max upload size | 1 GB |
| Download setting | **"Force downloads"**, with random codes added to file names |
| Digital Products category | ID 35. 24 lesson packs as drafts, SKU JMB-DLP-NN. Only Certificates (ID 2474) is live. |
| Coupon **KIT10** | 10% off the **Jr. Marine Biology Kits** category (ID 34). One use per customer. Can't be combined with other coupons. Never expires. |
| Bundles product | ID 1874, $503.99 / $949.99. **It sits in the Kits category (ID 34)** |

---

## 6. Card standards Maya applies (CONFIRMED)
These come on top of `templates/card-design-standard.md`:
- **US units and US spelling only.** No centimetres.
- Say **"field notebook"**, never "paper".
- **No face-in-water or breath-holding activities** (already a safety rule, 2026-09-16).
- **No repeated front photos between age groups.**

---

## 7. Open items, in order

| # | Item | Needs |
|---|---|---|
| DP-1 | **Test order on Coral Reefs.** Create a one-time 100%-off test coupon, place a $0 order, then check the download email, all 7 links, and that each file opens and prints. | Maya's approval (it creates a coupon and an order) |
| DP-2 | **KIT10 loophole.** Bundles sit in the Kits category, so KIT10 takes **$50–$95** off a bundle. Proposed fix: exclude Bundles from KIT10. | Maya's yes/no: it changes a price and a coupon |
| DP-3 | **Protected folder.** GoDaddy's server doesn't block direct links to the downloads folder, so anyone holding an exact file link can open the file. Risk is low because names are random and customers never see the real addresses. Real fix: GoDaddy support adds a rule blocking that folder. | Maya's yes/no to **draft** the message. Contacting GoDaddy needs separate approval. |
| DP-4 | **Publish Coral Reefs** once the test passes | Maya's call |
| DP-5 | **Next topic**, using the §4 procedure | Maya attaches the export |
| — | Parent Guides for the other 23 topics | Coral Reefs is the template |
| — | Later: load the $99 Digital Library | On hold (D-016) |
| — | Later: clean up the old 2026-10-04 files | **Only with Maya's OK** |
| — | Minor: Reef Facts bullets all bold, page 23 | Canva edit |

---

## Needs Maya's Approval
**Ask Maya before any of these:**
- publishing
- test orders
- creating or changing coupons
- deleting anything
- contacting GoDaddy
- changing Canva sharing

**Never** offer a customer a refund or discount without her OK (D-007, D-012).
