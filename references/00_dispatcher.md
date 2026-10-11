# Text-First Conversion Rate Optimization (CRO) & Hero Architecture

Operational framework for engineering high-converting, low-friction landing page hero sections by establishing typography as the visual carrier, eliminating decorative graphics, demolishing objections above the fold, and choreographing the visitor scan path. **Scope note:** §1–§10 govern the hero viewport; §11–§15 extend to adjacent conversion surfaces (post-description conversion hardware, the SERP/title-tag CTR surface, the off-site review surface, the DOM-native lead-magnet document, and the paid-traffic advertorial presell page).

---

## 1. The Time-to-Convince Cost Model & The Amplification Test

### 1.1 The Fundamental CRO Law
> **"Every unvetted or decorative visual added to a hero section increases the time required to convince a prospect to convert."**

Humans communicate and transact through language. Text is the primary carrier of value, intent, capability, and proof. 
* When an unvetted or decorative visual is inserted into the above-the-fold viewport, it forces the human visual cortex to parse layout, iconography, colors, and spatial geometry before or during the reading process.
* This split-second cognitive detour raises cognitive friction, dilutes attention, and increases the bounce rate ("pogo-sticking").
* **The Capability Exception:** Authentic proof assets that directly substantiate physical competence (such as in-situ trade photography defined in Section 7.1) are the structured exception, functioning as instant capability verification rather than decorative fluff.

### 1.2 The Amplification vs. Decoration Test
Every element placed in the hero section must pass this binary test:

| Classification | Definition | Conversion Impact | Action |
|---|---|---|---|
| **Amplification** | An asset that directly clarifies, substantiates, or speeds up comprehension of the core proposition (e.g., authentic in-situ work photo for a local service, or deliberate typographic contrast). | Accelerates conversion; lowers doubt. | **Retain & Stage** |
| **Decoration (Vanity)** | An asset added because a designer or stakeholder felt text-only was "too minimal" or "boring", or generic AI-generated illustrations, stock photos, or abstract 3D shapes. | Increases time-to-convince; depresses conversion. | **Eliminate Immediately** |

### 1.3 The "Too Boring / Too Minimal" Fallacy
When a team complains that a text-first page looks "boring", the defect is never the absence of a graphic. The failure lies in:
1. **Weak Typographic Hierarchy:** Flat font scales, inadequate line-height, or lack of typographic presence.
2. **Ambiguous Messaging:** Vague slogans instead of clear problem-solution framing.
3. **Absence of Staging:** Failure to direct the eye through deliberate contrast, whitespace, and optical positioning.

### 1.4 The Local Trust Paradox (Utilitarian vs. Corporate Agency Templates)
* **The Empirical Observation:** Local homeowners with urgent problems (e.g., 11 p.m. pest emergency, burst pipe) are actively repelled by generic, over-designed corporate templates that signal out-of-town lead brokers or AI-generated sites.
* **The Counter-Intuitive Finding:** A clean, functional, utilitarian website that looks 10-15 years established with a real local phone number and authentic work photos frequently converts at a higher rate than a modern "polished" design.
* **The Distinction:** This is NOT permission for ugly or broken sites. The key differentiator is visual authenticity, operational presence, and zero corporate varnish.
*(Source: Caleb Ulku, "How To Stop Being Invisible On Google". September 2026.)*

---

## 2. Text as the Visual Carrier

In a text-first architecture, typography does not merely convey information—**the typography is the visual**.

```
┌──────────────────────────────────────────────────────────────────┐
│                                                                  │
│   [Eyebrow / Context Anchor]                                     │
│                                                                  │
│   YOUR ACCOUNTS.                                                 │
│   AUTOMATICALLY BALANCED.                                        │
│   ── High-contrast, scaled display type (visual centerpiece)     │
│                                                                  │
│   Subhead demolishing primary objection (time/complexity)        │
│                                                                  │
│   [Benefit-Carrying CTA Button]   [Universal Category Anchors]   │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

### 2.1 Glossomorphic & Overlapping Type
To elevate text into the primary aesthetic hook:
* Utilize subtle gradient fills, precise letter-spacing, or delicate overlapping letterforms (e.g., subtle glossomorphic depth where descenders and ascenders interact).
* This provides visual sophistication and artistic polish without introducing distracting illustration assets.

### 2.2 The Optical Raise
* **The Rule:** Do **not** vertically center hero copy within the viewport.
* **Execution:** Offset the entire hero block slightly upward (approximately 35–40% from the viewport ceiling). 
* **Mechanism:** The human eye scans downward. An optical raise creates generous lower breathing room, establishing immediate dominance for the headline before pulling the eye down toward secondary anchors.

### 2.3 The Line-Taper Silhouette Rule
When formatting a multi-line display headline:
* **The Rule:** Line 2 must be visually shorter than Line 1 (an inverted pyramid / tapered silhouette).
* **Failure Mode:** A bottom line that extends wider than the top line creates an awkward visual shelf that breaks forward reading momentum.
* **Verification:** Ensure line breaks guide the eye smoothly into the subhead.

### 2.4 Partial-Contrast Headlines (Tech-Fatigue Defense)
When addressing modern markets suffering from tech jargon overload (e.g., "AI fatigue"):
* **Mechanism:** Apply high contrast (100% opacity, bold weight) to the **core outcome or benefit**, while dimming the mechanism or technical enabler (e.g., secondary weight or subdued tint).
* **Accessibility Floor:** Even dimmed clauses must maintain at least the WCAG 2.1 AA contrast floor (minimum 4.5:1 for body, 3:1 for large display type ≥ 18pt/24px) against the background canvas per [Accessible Contrast](../../kirby-accessible-contrast/SKILL.md). Never drop opacity to illegible levels.
* **Result:** Prospects parse the emotional relief or business payoff first, registering the technical mechanism only as secondary confirmation.

---

## 3. Reading-Order Choreography & Contrast-Tier Staging

### 3.1 The Three-Tier Contrast Architecture
Control the visitor's scan path through disciplined luminance and contrast tiers:

1. **Tier 1: The Core Value Proposition (`<h1>`)**
   - Maximum visual weight, highest contrast ratio against the background canvas (minimum 4.5:1 for AA, 7:1 for AAA per [Accessible Contrast](../../kirby-accessible-contrast/SKILL.md) — held to a stricter standard than the baseline 3:1 large-text floor to maximize visual dominance).
   - Captured within the first 500ms of arrival.
2. **Tier 2: The Credibility Anchor or Secondary Curiosity Driver**
   - Company name, trust badge, or counter-intuitive brand pairing.
   - Positioned deliberately to provoke the "Why?" inquiry (e.g., a mortgage company instructing "Quit your job").
3. **Tier 3: The Directional Action / Low-Contrast Navigational Cue**
   - Subhead objection remover, directional arrow, or subtle CTA.
   - Intentionally subdued so it is discovered *after* the premise has been absorbed.

### 3.2 Whitespace as an Active Structural Force
* Surrounding text with radical whitespace isolates the message from noise.
* Adding a visual asset (such as an AI illustration of a person at a desk) shatters this choreography, pulling the eye away from the copy and destroying the curiosity sequence.

---

## 4. Above-the-Fold Immediate Objection Demolition

### 4.1 The First-Doubt Interception
Every product or service introduces a primary operational doubt in the prospect's mind within 2 seconds of reading the value proposition. The hero subhead must destroy this doubt immediately:

| Product Category | Primary Customer Doubt / Objection | Immediate Demolition Subhead |
|---|---|---|
| **Tracking / Analytics** | "I will have to spend hours manually tagging, sorting, and categorizing." | *"It all happens automatically across every transaction in real time."* |
| **Complex Software / AI** | "I'll have to configure complex settings or manage broken agent loops." | *"Human experts work alongside autonomous agents to handle the work for you."* |
| **Consulting / Services** | "This is going to lock me into a costly long-term contract." | *"First month is completely free. No commitment, cancel with one click."* |
| **Financial / High Ticket** | "I'll be subjected to aggressive sales phone calls." | *"Instant transparent quote online. Zero spam, zero phone calls."* |

For full 17-step objection sequences deeper on the page, see [Direct Response Copywriting](../../kirby-direct-response-copywriting/SKILL.md).

### 4.2 Universal Category-Applicability Framing
When displaying supporting chips, tags, or use-case badges beneath the hero:
* **The Rule:** At least **two** categories must be universally applicable to 100% of your target audience (e.g., *Groceries* and *Home Utilities* for consumer finance; *Authentication* and *Database* for developer tooling).
* **Risk:** Showing only niche or specialized edge cases (e.g., *Weddings* or *Yacht Charters*) causes non-matching prospects to self-select out and bounce.

---

## 5. The "You"-First Reframing Audit

### 5.1 The Vanity vs. Outcome Matrix
Prospects do not care about the company, the founder, or how clever the software is. They care about their problems, their time, and their money.

```
❌ VENDOR-CENTRIC (BANNED):
"The Best Automated Bookkeeping Software for Modern Teams"
(Vague, superlative, talks about 'The Software')

✅ USER-CENTRIC (MANDATED):
"Your Accounts. Automatically Reconciled Every Evening."
(Direct, talks about 'Your Accounts', proves concrete outcome)
```

### 5.2 Reframing Protocol
1. **Purge Superlatives:** Strip all instances of "Best", "Leading", "Premier", "All-in-One", or "#1".
2. **Subject Inversion:** Replace sentences opening with "We deliver", "Our platform provides", or "Built for" with sentences opening with "Your", "You get", or direct active verbs.
3. **Connect to Subhead:** Ensure the opening pronoun of the subhead binds directly to the prospect's daily workflow.

---

## 6. Benefit-Carrying CTAs vs. Deliberate Exclusivity Withholding

### 6.1 Banned Vague CTA Verbs
The following CTA button labels are banned across all hero sections:
* ❌ `"Get Started"` (Banal, communicates zero value, signals upcoming onboarding friction)
* ❌ `"Learn More"` (Signals homework, reading, and deferred utility)
* ❌ `"Submit"` (Bureaucratic, cold, transactional)
* ❌ `"Click Here"` (Clueless, amateurish)

### 6.2 The Benefit-Carrying Replacement Standard
Every CTA button must finish the mental sentence: *"I want to..."*
* ✅ `"Reconcile My Accounts"`
* ✅ `"Claim My Free Audit"`
* ✅ `"Automate My Workflow"`
* ✅ `"Get Instant Pricing"`

### 6.3 Deliberate CTA Withholding (Exclusivity & Ego Architecture)
In premium, closed-ecosystem, or high-status offerings (e.g., venture accelerators, private masterminds, elite technical guilds):
* **The Principle:** Placing an aggressive, neon-colored CTA button above the fold signals desperation and commoditization.
* **The Execution:**
  - Withhold the primary CTA button from the central hero stage.
  - Utilize intellectual markers: serif italic emphasis on target identity (e.g., *formidable founders*), academic-style footnote cues (`[1]`), or quotes from respected domain authorities.
  - Position an understated, low-contrast action link in the top navigation or allow the visitor to self-navigate down the page.
  - **Psychological Trigger:** Signals an exclusive club that screens visitors, compelling high-status prospects to lean in and qualify themselves.

### 6.4 The In-Content Internal Link Friction Rule (Attention Leakage Guardrail)
* **The Cognitive Friction Trap**: Internal links within conversion landing pages are attention leaks. Placing links to secondary blog posts, category archives, or unrelated services directly above or adjacent to the primary conversion area distracts prospects from the conversion goal.
* **The Mandate (Ep. 1173)**: Keep in-content internal links on BOFU conversion pages **strictly near-zero** (`../../kirby-aiseo-skill/SKILL.md` §10.11F). A visitor who lands on a commercial conversion page is there to resolve a buying, calling, or booking decision. Never bleed conversion attention to boost another page's internal link equity.

---

## 7. The SaaS Dashboard Trap & Two-Branch Decision Rule

To reconcile visual assets with [SEO Telemetry & Attribution Tracking](../../kirby-seo-telemetry/SKILL.md), audit all hero sections against this deterministic two-branch protocol:

```
                      ┌────────────────────────────┐
                      │ What is the business type? │
                      └─────────────┬──────────────┘
                                    │
            ┌───────────────────────┴───────────────────────┐
            ▼                                               ▼
   [Local Trade / Physical]                        [Software / SaaS / Knowledge]
            │                                               │
   AUTHENTIC IN-SITU PHOTO                         TEXT-FIRST HERO MANDATE
   • Real technician at work                       • Zero dashboard screenshots
   • High contrast, static                         • Bold typography is the visual
   • Proves capability instantly                   • Immediate objection demolition
```

### 7.1 Branch 1: Local Trades & Real-World Services
* **Asset:** Authentic in-situ photography of the technician or specialist actively executing the work (e.g., roofer installing flashing, technician in server rack).
* **Rationale:** A customer seeking emergency plumbing or physical infrastructure needs instant proof that the provider is real, local, equipped, and competent.

### 7.2 Branch 2: Software, SaaS, & Digital Products (The Dashboard Trap)
* **The Anti-Pattern:** Pasting an application UI dashboard screenshot, metrics graph, or table layout into the hero section.
* **Why It Destroys Conversion:**
  - To a new prospect, a dashboard is visual clutter consisting of 50 unfamiliar buttons, columns, and data points.
  - It visually screams: *"Look at how much complex software you will need to learn before getting value."*
* **The Mandate:** Use the **Text-First Hero**. Banish product screenshots below the fold, where they can be introduced alongside structured walkthrough steps.

### 7.3 The Rotating Hero Carousel Anti-Pattern
* **The Anti-Pattern:** Agency split-tests consistently prove changing/rotating hero image sliders actively hurt conversion rates on local service landing pages.
* **The Mechanism:** Each image transition resets the visitor's visual processing, fragmenting attention and delaying the time-to-convince.
* **The Mandate:** Mandate static, high-contrast hero layouts with an immediate value proposition, prominent phone number, and zero visual distraction. This complements Branch 1 (§7.1) where authentic in-situ photos should be static, not cycling.
*(Source: Caleb Ulku, "How To Stop Being Invisible On Google". September 2026.)*

---

## 8. Audience Reading-Tolerance Calibration

Calibrate copy length and density in the hero section to the prospect's cognitive mode:

| Prospect Archetype | Context / State | Reading Tolerance | Hero Section Architecture |
|---|---|---|---|
| **Distressed / Urgent** (Emergency plumber, incident response) | High anxiety, zero patience | **Near Zero** | Massive phone CTA + 5-word headline + in-situ photo + £0 call-out badge. |
| **B2B Decision Maker** (CFO, VP Ops) | Evaluating operational risk | **Moderate** | Outcome-driven display type + quantitative proof ("Save 14 hrs/mo") + objection killer. |
| **Technical Specialist / Founder** (Engineers, Architects) | Seeking deep capability, wary of hype | **High** | Dense, highly specific text-first copy + structural footnotes + technical clarity without visual fluff. |

---

## 9. The Annotation Teardown Deliverable System

When providing client-facing CRO advisory or teardown audits, package findings into a structured **Annotation Deliverable**:

1. **The Hero Screenshot / Optical Map:**
   - Overlay numbered bounding boxes highlighting: (1) Headline, (2) Subhead, (3) Primary Action, (4) Distracting Visual Fluff.
2. **The 4-Point Teardown Ledger:**
   - **Point A (Visual Tax):** Identify decorative assets that inflate the time-to-convince cost.
   - **Point B (The "You" Score):** Ratio of user-centric terms ("you", "your") vs. vendor-centric terms ("we", "our", "the best").
   - **Point C (Objection Demolition Speed):** Measure the word distance between the `<h1>` and the dismantling of the primary operational doubt.
   - **Point D (CTA Intent Score):** Audit of CTA verbs against the banned list.
3. **The Text-First Refactored Wireframe:**
   - Deliver the revised copy, contrast tiers, and optical raise coordinates in clean markdown.

---

## 10. Pre-Flight Gate & 11-Point Scoring Checklist

Every hero section must score at least **10/11** before going live. **Gate scope:** items 1–10 grade the *hero viewport*; item 11 grades the page-level BOFU link budget (§6.4). The §11–§15 conversion surfaces carry their own gates — provider licensing and mobile caps (§11), per-template price tests (§12), the FTC guardrail (§13), the per-page 10/11 export gate (§14), and the §15 disclosure/CTA-friction gate — and are not hero-gated.

- [ ] **1. Amplification Test Passed:** Zero purely decorative or vanity graphics in the hero.
- [ ] **2. Anti-Dashboard Verification:** If software/SaaS, hero contains zero UI dashboards or complex table screenshots.
- [ ] **3. Text-as-Visual Standard:** Typography possesses distinct scale, weight, and hierarchy to anchor the canvas.
- [ ] **4. Optical Raise Applied:** Hero block positioned 35–40% from the ceiling, leaving breathing room below.
- [ ] **5. Line-Taper Enforced:** Multi-line headline features a shorter bottom line than top line.
- [ ] **6. Partial-Contrast Implemented:** Secondary jargon or technical qualifiers are visually dimmed against the core outcome, and dimmed clauses still meet the §2.4 floor (≥4.5:1 body / ≥3:1 large display).
- [ ] **7. Immediate Objection Demolished:** Primary operational doubt (time/effort/friction) killed in the subhead.
- [ ] **8. "You"-First Headline Verified:** Zero platitudes or "Best X" claims; headline focuses on user outcomes.
- [ ] **9. Universal Category Anchors Present:** Supporting tags include at least two universally applicable categories.
- [ ] **10. Benefit-Carrying CTA Verified:** Button uses active, benefit-carrying phrasing (no "Get Started" or "Learn More"), OR explicit deliberate CTA withholding is documented for premium/elite club positioning per Section 6.3.
- [ ] **11. BOFU Link-Minimalism Verified:** In-content internal links on conversion landing pages conform to near-zero budgets (`../../kirby-aiseo-skill/SKILL.md` §10.11F); zero internal links competing with or distracting from the primary CTA above the fold.

---

## 11. Brand Icon CTA Blocks Below Product Descriptions

*Source: 9,249 validated case-study meta-analysis (Edward Sturm Ep. 1191). Single split test — directional, not a law. Application scope: digital funnels where authentication or payment friction is the conversion barrier (Branch 2 / §7.2 contexts and e-commerce checkout); the source's tested vertical and provider set are unstated — a "Continue with Google" button is meaningless on a local plumber's landing page.*

* **The Placement:** Positioning brand icon CTA blocks **beneath product descriptions** produced an **+80% conversion lift** in the source test. The mechanism: by the description's end the prospect has absorbed the value case — the icon block converts accumulated comprehension into a zero-friction action step.
* **Label-law exemption:** Icon blocks are provider-branded buttons (authentication or payment friction reducers), not copy CTAs — §6.1's banned-verb list and §6.2's "I want to…" standard govern *text* CTAs and do not apply to them. The tested provider set and vertical are unstated in the source; treat the +80% as a directional signal for authentication/payment blocks specifically.
* **Interaction with §1.2 (Amplification Test) and §10 (Hero Gate):** Icons placed after the value case are *amplification* assets (they substantiate capability and reduce action friction), not decoration — but the anti-decoration law protects the hero viewport, and the §10 checklist grades hero content and the page link budget only; these blocks live outside both by design.
* **Cautions:**
  - One split test; validate in your own funnel before treating +80% as expected.
  - Icon blocks clutter mobile layouts quickly — cap at 2–3 providers, single row, on mobile breakpoints.
  - Platform icon usage is license-bound (brand guidelines per provider); unauthorized or stale logo use creates trademark exposure.

---

## 12. Price Gating & CTR Protection

*Source: 9,249 validated case-study meta-analysis (Edward Sturm Ep. 1191).*

* **Layer 1 — Title tags (universal):** Displaying exact product prices in `<title>` tags reduced organic traffic by **15%** (7% on rental listing pages in a related test). Never put exact prices in title tags: the title carries the value proposition; the price reveal is the click-through event.
* **Layer 2 — Hero/above-the-fold (B2B & high-ticket):** Gate exact prices behind a §6.2-compliant benefit-carrying CTA (the §4.1 "Instant transparent quote online" pattern; "Get Instant Pricing" style). Quantitative non-price proof in the hero ("Save 14 hrs/mo", §8) remains compatible — the penalty is attached to *price*, not numbers.
* **Layer 3 — Product detail pages (B2C commodity):** Buyers comparison-shop on price; hiding it on a PDP frustrates high-intent visitors and raises bounce/abandonment. A PDP price is expected; a SERP-title price is a click-killer. Gate the snippet, not the shelf.
* **Discipline:** The −15% is a title-tag measurement, not an above-the-fold copy measurement — test per template before extending it.

---

## 13. Review N-gram Optimization via Honest-Specificity Prompting (Compliance-Restricted)

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026).*

> **⚠️ FTC guardrail — ship and obey:** Steered or incentivized review text risks violations of the FTC's Rule on the Use of Consumer Reviews and Testimonials (16 CFR Part 465, civil penalties) and platform removal; *any* incentive — even unconditional — triggers material-connection disclosure under the FTC Endorsement Guides (16 CFR Part 255). Engineered "authenticity" is detectable, and exposure is reputationally destructive. The sanctioned form below is **prompting for honest reviews that naturally use concrete, specific language** — never scripting text, never paying for review content, never conditioning anything on star level.

* **The Doctrine:** Retrieval and ranking systems weight review text n-grams; reviews containing the specific phrases customers actually search ("crispy fries", "tasty burger", "fixed the leak same day") carry more retrieval value than generic praise ("great service!").
* **Sanctioned Execution (honest-specificity prompting — issued unconditionally to every customer):**
  1. Physical collateral (table tents, window decals, receipts) and staff apparel invite reviews with *questions*, not scripts: *"Tell us about the fries."*
  2. NFC/QR review stands at the payment or exit point route to the platform's organic review flow. A *conditional* pre-survey (filtering who reaches the public flow) is banned — an **unconditional** internal quality survey sent to all customers is the compatible policy-safe pattern (`kirby-local-seo` Module 3 §3.16), provided public solicitation goes to everyone equally.
  3. Post-service follow-ups ask about the *specific job performed* ("How did the emergency call-out go?") — specificity comes from the question, not from dictated phrasing.
* **Prohibited:** providing review text for customers to copy; discounts/payment conditional on review content or star level; undisclosed incentives of any kind; any mechanism that suppresses unhappy customers' path to review. **Staffing note:** `kirby-local-seo` Module 3 §3.16's review-performance staffing metric must never be applied as solicitation pressure — the prompt goes to every customer regardless of expected sentiment.


---

## 14. DOM-Native Lead-Magnet Layouts (Bridge to kirby-ai-design-system)

*Rendering surface: the multi-page PDF guide pipeline in `../../kirby-ai-design-system/SKILL.md` Module 4. This section defines how the CRO doctrine above maps onto DOM-native page architecture — copy leads, layout follows.*

* **Copy-first invariant preserved in canvas form:** Module 4's production SOP drafts page copy into DOM text slots BEFORE styling. The §1.2 Amplification Test applies to every asset slot: a Higgsfield-generated image earns a slot only as an *authentic proof asset* (§7.1's in-situ standard) — decorative AI illustration in a lead magnet is the same vanity classification as in a hero.
* **Objection-demolition hierarchy → page sequence:** the guide's page order follows §4: the first interior page after the cover demolishes the primary operational doubt (the §4.1 table supplies the subhead patterns); each later page exists to demolish the next objection or deliver a proof point — no filler pages.
* **Contrast-tier staging → layer classes:** §3's three-tier architecture (Tier 1 `<h1>`-equivalent / Tier 2 credibility anchor / Tier 3 directional cue) maps to the canvas master-frame zones; per-page styling assigns tiers from the Brand Guidelines tokens only, and type-on-background pairs pass `../../kirby-accessible-contrast/SKILL.md` before render (≥4.5:1 body, ≥3:1 large display).
* **CTA and pricing doctrine carry over verbatim:** closing/CTA pages use §6.2 benefit-carrying button copy (§6.1 banned verbs apply), §6.3 withholding applies to premium positioning, and §12's price-gating layers apply to the guide's offer-reveal page — price never appears on the cover or in the email subject delivering the document (the title-tag equivalents).
* **"You"-first audit on every page:** §5's reframing protocol runs page-by-page; the §10 checklist grades each page archetype — a lead-magnet page is a hero viewport at document scale, so score 10/11 per page before export.

---

## 15. Native Advertorial Bridge & Presell Pages (Paid-Traffic Surface)

*Source: Sabri Suby / King Kong, "How to Go From $0 to $100k/day with Meta Ads". October 2026. Funnel topology and media-buying doctrine live in `../../kirby-paid-acquisition/SKILL.md` Module 4 — this section owns the page-level formatting rules.*

* **The surface:** an editorial presell page (listicle, case-study article, advertorial) sitting between the paid click and the offer page. Cold paid traffic must never be direct-linked to a sales page, and paid traffic must never land on a generic homepage — the presell is the bridge (paid-acquisition Module 1 §1.5, Module 4 §4.3).
* **Native editorial camouflage:** the page reads as content, not as an ad — the click was earned by a native-pattern ad (paid-acquisition Module 2 §2.2), and the page must honor that contract. Headline formats follow editorial conventions; body copy follows article architecture; the §5.2 banned-vocabulary and platitude rules apply unchanged.
* **Interaction with §1.2 (Amplification Test):** presell pages are content surfaces, so authentic proof imagery (screenshots, data, candid in-situ photos per §7.1's standard) is substantiation and earns its slot — but decorative graphics remain banned by the same anti-vanity law.
* **Interaction with §4 (objection demolition):** the presell's core job is discharging the offer page's objections *before the reader ever reaches the offer*. Sequence the article so that by the click-through moment, most of the §4.1 objection table for the offer is already demolished — the offer page then only has to convert, not re-persuade.
* **Interaction with §6 (CTA doctrine) — deliberate friction-class inversion:** the presell CTA is low-friction "Learn More"-class **by design** for the 97% not-ready-to-buy market (paid-acquisition Module 2 §2.3). This is a scoped exemption from §6.1's banned-verb list, valid only on the presell page for cold top-of-funnel traffic; the offer page the presell feeds must use §6.2 benefit-carrying CTA copy in full. Documenting the funnel stage is what licenses the exemption.
* **Carry-overs:** §3 contrast-tier staging choreographs the article's reading order; §12 price gating applies with extra force — exact prices never appear on the presell (the reveal belongs to the offer page); the retargeting pixel fires here (paid-acquisition Module 2 §2.4 Stage 4).
* **§15 gate (own gate, not hero-gated):** (1) advertorial/paid placement is disclosed per the guardrail in `../../kirby-off-page-seo/SKILL.md` Module 12 §12.7 — native camouflage is a format, never a deception license; (2) CTA friction class matches funnel stage (Learn More-class on the presell, §6.2 on the offer); (3) the page passes the §5 "you"-first audit as an article.
