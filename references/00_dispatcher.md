# Text-First Conversion Rate Optimization (CRO) & Hero Architecture

Operational framework for engineering high-converting, low-friction landing page hero sections by establishing typography as the visual carrier, eliminating decorative graphics, demolishing objections above the fold, and choreographing the visitor scan path.

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

## 10. Pre-Flight Gate & 10-Point Scoring Checklist

Every hero section must score at least **9/10** before going live:

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
