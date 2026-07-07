---
title: "Inception-to-Seed Playbook"
show_in_nav: true
nav_label: "Playbook"
nav_order: 1
custom_css: |
  .playbook { position: relative; z-index: 1; max-width: 920px; margin: 0 auto; padding: 48px 24px 96px; }
  .playbook-hero { margin-bottom: 40px; }
  .playbook-kicker { font-family: 'Space Mono', monospace; font-size: 11px; letter-spacing: 0.14em; text-transform: uppercase; color: var(--green-deep); margin-bottom: 12px; }
  .playbook h1 { font-family: 'Cormorant Garamond', serif; font-weight: 400; font-size: 44px; line-height: 1.1; color: var(--text-dark); margin: 0 0 10px; }
  .playbook-sub { font-size: 15px; font-weight: 300; color: var(--text-mid); max-width: 620px; line-height: 1.7; }
  .playbook-toc { border: 1px solid var(--green-soft); background: rgba(255,255,255,0.55); border-radius: 6px; padding: 22px 26px; margin: 36px 0 56px; }
  .playbook-toc-label { font-family: 'Space Mono', monospace; font-size: 10px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-light); margin-bottom: 12px; }
  .playbook-toc ol { margin: 0; padding-left: 20px; }
  .playbook-toc li { font-size: 14px; line-height: 2; }
  .playbook-toc a { color: var(--text-dark); text-decoration: none; border-bottom: 1px solid var(--green-soft); }
  .playbook-toc a:hover { color: var(--green-deep); border-color: var(--green-deep); }
  .playbook-toc .toc-sub { font-size: 12.5px; color: var(--text-mid); }
  .playbook h2 { font-family: 'Cormorant Garamond', serif; font-weight: 500; font-size: 32px; color: var(--text-dark); margin: 72px 0 6px; padding-top: 18px; border-top: 2px solid var(--green-mid); }
  .playbook h3 { font-family: 'DM Sans', sans-serif; font-weight: 500; font-size: 17px; color: var(--green-deep); margin: 44px 0 12px; }
  .playbook h4 { font-family: 'Space Mono', monospace; font-size: 12px; letter-spacing: 0.08em; text-transform: uppercase; color: var(--text-mid); margin: 28px 0 8px; }
  .playbook p, .playbook li { font-size: 14.5px; font-weight: 300; line-height: 1.75; color: var(--text-dark); }
  .playbook strong { font-weight: 500; color: var(--green-deep); }
  .playbook ul, .playbook ol { padding-left: 22px; margin: 10px 0 18px; }
  .playbook table { display: block; overflow-x: auto; border-collapse: collapse; margin: 18px 0 28px; width: 100%; }
  .playbook th { font-family: 'Space Mono', monospace; font-size: 10.5px; letter-spacing: 0.06em; text-transform: uppercase; color: var(--green-deep); text-align: left; padding: 10px 14px; border-bottom: 2px solid var(--green-mid); background: rgba(160,195,130,0.08); white-space: nowrap; }
  .playbook td { font-size: 13px; font-weight: 300; line-height: 1.6; color: var(--text-dark); padding: 10px 14px; border-bottom: 1px solid var(--green-soft); vertical-align: top; min-width: 130px; }
  .playbook tr:hover td { background: rgba(160,195,130,0.06); }
  .playbook pre { background: rgba(255,255,255,0.7); border: 1px solid var(--green-soft); border-radius: 6px; padding: 20px; overflow-x: auto; margin: 18px 0 28px; }
  .playbook pre code { font-family: 'Space Mono', monospace; font-size: 11.5px; line-height: 1.7; color: var(--text-dark); }
  .playbook hr { border: none; border-top: 1px solid var(--green-soft); margin: 48px 0; }
  .playbook em { color: var(--text-mid); }
  .playbook .backtop { font-family: 'Space Mono', monospace; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; }
  .playbook .backtop a { color: var(--text-light); text-decoration: none; }
  .playbook .backtop a:hover { color: var(--green-deep); }
  @media (max-width: 640px) { .playbook h1 { font-size: 34px; } .playbook h2 { font-size: 26px; } }
---

<div class="playbook" markdown="1">

<div class="playbook-hero" markdown="0">
  <div class="playbook-kicker">Portfolio Resource</div>
  <h1 id="top">Inception-to-Seed GTM &amp; Capital Playbook</h1>
  <p class="playbook-sub">Tactical benchmarks and execution playbooks from ideation through seed — go-to-market, team building, and fundraising, cross-referenced across nine commercial motions. Calibrated to 2025–2026 US early-stage norms.</p>
</div>

<div class="playbook-toc" markdown="0">
  <div class="playbook-toc-label">Contents</div>
  <ol>
    <li><a href="#pillar-1">GTM Engine, ICPs &amp; Pricing Models</a><br>
      <span class="toc-sub"><a href="#m-enterprise">Enterprise B2B</a> · <a href="#m-plg">PLG</a> · <a href="#m-prosumer">Prosumer</a> · <a href="#m-deeptech">Deep Tech</a> · <a href="#m-defense">Defense &amp; GovTech</a> · <a href="#m-b2b2c">B2B2C</a> · <a href="#m-haas">HaaS</a> · <a href="#m-marketplace">Marketplace</a> · <a href="#m-fintech">Fintech</a></span></li>
    <li><a href="#pillar-2">Team Building, Co-Founder Matching &amp; Hiring</a><br>
      <span class="toc-sub"><a href="#talent-playbooks">Motion-specific talent</a> · <a href="#vetting">Vetting sequence</a> · <a href="#comp">Comp bands</a> · <a href="#counteroffers">Counter-offers</a> · <a href="#scorecard">30-60-90 scorecard</a></span></li>
    <li><a href="#pillar-3">Fundraising, Equity Structuring &amp; Capital</a><br>
      <span class="toc-sub"><a href="#countdown">8-week countdown</a> · <a href="#dataroom">Data room architecture</a> · <a href="#closing">Tactical closing</a></span></li>
  </ol>
</div>

## Pillar 1 — GTM Engine, ICPs & Pricing Models {#pillar-1}

### 1.0 Ideation-to-Seed GTM Matrix (All Motions) {#gtm-matrix}

| Layer | [1] Ideation | [2] Validation | [3] Pre-Seed | [4] Seed |
|---|---|---|---|---|
| **Core objective** | Find a hair-on-fire problem | Prove willingness-to-pay | Prove repeatability (n≥3 similar wins) | Prove a scalable channel |
| **Customer count target** | 20–40 problem interviews | 3–5 design partners | 5–15 paying customers | 20–50 customers or 1k+ activated users |
| **Revenue signal** | $0 — signed LOIs acceptable | First paid pilot ($5k–25k) | $50k–250k ARR (B2B) / $5–20k MRR (PLG) | $250k–$1M+ ARR; 3x YoY pace |
| **Founder time on GTM** | 30% (discovery) | 50% (founder-led sales) | 60–70% | 50% + first GTM hire |
| **Kill criteria** | <30% of interviews rank problem top-3 | No one pays after 10 pitches | CAC payback >24 mo, no pattern in wins | Pipeline coverage <3x, NRR <90% |
| **Key artifact** | Problem-ranking scorecard | Pilot agreement template | Repeatable sales narrative doc | Pipeline model + hiring plan |

**Universal validation loop (weeks 1–8):**

1. **Weeks 1–2:** 20 problem interviews. Script: "Walk me through the last time X happened. What did it cost you? What did you try?" Never pitch. Score each: severity (1–5), frequency, budget owner identified (Y/N).
2. **Weeks 3–4:** Mock-up or concierge MVP. Ask for money or a signed design-partner agreement — a "yes, when it's built" is a no.
3. **Weeks 5–8:** 3 design partners live. Weekly usage check-ins. Kill or double down based on retention, not enthusiasm.

### 1.1 Enterprise B2B (Top-Down, High ACV) {#m-enterprise}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | 1 vertical, 1 buyer title (e.g., "VP Supply Chain at $100M–$1B CPG"), 1 quantified pain (>$500k/yr cost). Companies: 200–2,000 FTEs — big enough for budget, small enough for founder access. |
| Seed | Same vertical, expand to 2 adjacent titles; add firmographic triggers (new exec hire, funding event, compliance deadline). Named-account list of 200. |

#### GTM execution loop — cold outbound blueprint

- List: 200 named accounts × 3 contacts = 600 prospects (Clay + Apollo, ~$300/mo tooling).
- Sequence: 5 touches over 14 days — Day 1 email (problem-specific, <90 words, one CTA), Day 3 LinkedIn connect, Day 5 bump, Day 9 new-angle email, Day 14 breakup.
- Benchmarks: 45–60% open, **3–7% reply, 1–3% meeting-booked** from cold. Founder-sent emails outperform SDR-sent by ~2x at this stage.
- Meeting→pilot conversion target: 20–30%. Pilot→annual conversion target: **60%+** (below 40% = ICP or product problem).

#### Pricing & business model

- Design-partner pilots: **$10k–$50k for 90 days**, credited against year-1 contract. Never free — free pilots convert at <20% vs 60%+ paid.
- Year-1 ACV targets: $25k–$75k at validation; $50k–$150k by seed. Price on value: charge 10–20% of quantified annual savings.
- Structure: annual prepaid (offer 10–15% discount for annual upfront — cash > optics). Add usage tier only after 3+ customers hit plan ceilings.
- Benchmarks to hit by seed: NRR ≥110%, gross margin ≥70%, sales cycle ≤90 days at this ACV band, logo churn <10%/yr.

### 1.2 Product-Led Growth (Bottom-Up, Self-Serve) {#m-plg}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | Individual end-user with a daily-frequency task (e.g., "backend engineer debugging prod incidents 3x/week"). Reachable in public communities. |
| Seed | Same user + the team lead who expenses the team plan. Define the "aha moment" quantitatively (e.g., "3 projects created in first 7 days"). |

#### GTM execution loop — viral / self-serve

1. Launch surface: HN / Product Hunt / target subreddit + 10 niche communities. Goal: 1,000 signups in month 1.
2. Instrument activation funnel day one: signup → aha-moment → habit (3+ sessions/wk). Benchmarks: **signup→activation 30–50%; activation→paid 5–15%**.
3. Build one viral loop into the workflow (share link, invite-to-collaborate, public artifact). Target viral coefficient K=0.3–0.6 (K>1 is rare; 0.5 compounds meaningfully).
4. Weekly cohort review: retention curve must flatten. D30 retention **>20% (good), >40% (exceptional)** for workflow tools.

#### Pricing & business model

- Free tier gated by value metric (seats, projects, volume) — not by time. Reverse trials (14-day full access, then downgrade) convert **1.5–2x** better than freemium alone.
- Price points: $10–$30/user/mo individual; $20–$50/user/mo team tier with admin/SSO. Annual discount 16–20% ("2 months free").
- Free→paid conversion benchmarks: **2–5% freemium, 8–15% reverse trial**. Self-serve NRR target 100–110%; layer sales-assist at seed for accounts >20 seats (this is where NRR moves to 120%+).

### 1.3 Prosumer (Individual Professional, High Volume) {#m-prosumer}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | One professional identity with income attached to the tool's output (creators, traders, therapists, realtors). Must self-identify in communities you can name. |
| Seed | Segment by revenue-seriousness: hobbyist (churns) vs professional (pays annual). Focus 100% on the professional segment even if smaller. |

#### GTM execution loop

- Content/audience-led: founder builds in public in the niche (YouTube/TikTok/newsletter). Benchmark: 1 high-intent piece/week; expect 6 months to meaningful inbound.
- Affiliate/creator program at pre-seed: 20–30% first-year rev share to niche creators — often the single highest-ROI prosumer channel.
- Paid ads only after LTV is known: keep **CAC < 1/3 LTV**; prosumer LTV = ARPU / monthly churn.

#### Pricing & business model

- $8–$30/mo; anchor with a $99–$299/yr annual plan (push annual hard — monthly prosumer churn runs **4–8%/mo**; annual cuts effective churn ~60%).
- Add a one-time "pro pack" or lifetime tier ($199–$499) at launch for cash, retire it by seed.
- Benchmarks: payback <3 months, annual-plan mix >40% of revenue by seed, refund rate <5%.

### 1.4 Deep Tech (Pre-Revenue Commercialization) {#m-deeptech}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | Corporate innovation/R&D lead at a strategic who owns a roadmap gap your science fills. Also: program managers at NSF/DOE/DARPA whose solicitations match. |
| Seed | Business-unit owner (not innovation lab) at 2–3 strategics with a production use case; procurement path mapped. |

#### GTM execution loop — milestone / JDA-driven

1. Non-dilutive first: NSF SBIR Phase I ($275k), DOE/NIH/DARPA equivalents. Submission windows are program-specific — build a 12-month grant calendar; expect 60–90 day review cycles, 10–15% award rates.
2. Joint Development Agreements (JDAs) with strategics: **$100k–$500k NRE**, 6–12 month term, milestone-gated payments (30/40/30 split typical), with pre-negotiated commercial terms (pricing, exclusivity limits ≤12 months and field-of-use only, IP: you own foreground IP, always).
3. Convert JDA → supply/license agreement before it ends; a JDA without a conversion clause is free R&D for the strategic.

#### Pricing & business model

- Stack: grants (40–60% of pre-seed capital) + JDAs + eventual licensing (3–8% royalty on net sales) or direct product sales.
- Never sell IP or grant broad exclusivity at this stage; field-of-use, time-boxed exclusivity priced at 2–3x standard fees if unavoidable.
- Benchmarks by seed: ≥$500k non-dilutive raised, 2 JDAs signed, 1 conversion to commercial term sheet, TRL 5–6.

### 1.5 DefenseTech & GovTech (Federal/State Procurement) {#m-defense}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | End-user + Program Executive Office (PEO) pair — the operator who wants it AND the office that can pay. One without the other = no deal. |
| Seed | Named programs of record you're targeting for insertion; 2–3 transition sponsors with FY budget line-items identified. |

#### GTM execution loop — SBIR / OTA / procurement pipeline

1. **Phase I SBIR/STTR:** AFWERX Open Topic (3 windows/yr, ~$75k, 8-week feasibility), Army xTech, NSF ($275k). Direct-to-Phase-II available if you have a prototype: **$750k–$1.9M**.
2. **Phase II → TACFI/STRATFI:** $375k–$15M matched extensions — requires customer memo + matching funds. Start hunting the transition sponsor during Phase I, not after.
3. **OTAs (Other Transaction Agreements):** via consortia (DIU, SOFWERX, C5, NSTXL) — 60–90 day awards vs 18-month FAR contracts. Membership fees $500–$5k/yr.
4. **Phase III:** sole-source contracts of any size, no recompete — this is the goal state. Document SBIR data rights obsessively (they're your moat).
5. Dual-use rule: keep a commercial revenue line ≥30% of plan by seed — pure-defense pre-revenue is fundable but discounts your valuation 20–30%.

#### Pricing & business model

- Government: firm-fixed-price preferred; load rates properly (wrap rate 2.2–2.8x on direct labor). Never cost-plus at this size.
- Program-of-record timeline honesty: 3–7 years. Bridge with SBIR stack + commercial. Benchmarks by seed: $1–3M in SBIR/OTA awards, 1 STRATFI/TACFI or equivalent transition vehicle in motion, ≥1 commercial pilot.

### 1.6 B2B2C / Channel-Led (Indirect via Platform Layer) {#m-b2b2c}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | The channel partner's product/partnership lead + evidence the *end consumer* wants it (test direct first, even if the model is indirect). |
| Seed | 2–3 signed channel partners of a repeatable archetype (e.g., "regional banks 500k–2M customers" or "HR platforms 1k–10k employer clients"). |

#### GTM execution loop

1. Validate end-user demand direct-to-consumer first (cheap landing-page tests, $2–5k ad spend) — channels amplify demand, they don't create it.
2. Land first partner with asymmetric terms: 60–90 day paid pilot, $15k–$50k, success metrics pre-agreed (activation %, attach rate).
3. Build the partner-facing integration + reporting layer before partner #2 — time-to-launch for partner #2 should be <30 days vs 4–6 months for #1.

#### Pricing & business model

- Rev share: partner keeps **15–35%**; or per-active-user fee ($0.50–$5/user/mo wholesale). Minimum commitments in every contract ($25k–$100k/yr floor) — pure rev-share with no floor lets partners shelf you.
- Watch concentration: no partner >40% of revenue by seed. Benchmarks: end-user attach rate 5–15% of partner base, partner payback <12 months, ≥2 partners live.

### 1.7 Hardware-as-a-Service (HaaS) {#m-haas}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | Operations owner with a measurable physical-world cost (downtime, labor hours, shrinkage) at mid-market sites (10–200 locations). |
| Seed | Multi-site operator archetype where one pilot site converts to fleet rollout; CFO-level buyer for the subscription framing. |

#### GTM execution loop

1. Pilot at 1–3 sites: **$5k–$25k paid pilot**, 60–90 days, single success metric (e.g., "reduce downtime 20%").
2. Instrument everything — the ROI report from pilot sites is your entire sales deck for the fleet deal.
3. Fleet expansion contract pre-negotiated in the pilot agreement ("upon hitting metric X, pricing for sites 4–50 is Y").

#### Pricing & business model

- Bundle: hardware amortized into subscription — **$200–$1,500/device/mo** depending on capability; 24–36 month terms with auto-renew.
- Unit economics gates: blended gross margin ≥50% (hardware COGS recovered in ≤12 months of subscription), logo churn <5%/yr (contracts help), installation either <$500/site or charged as one-time fee.
- Never sell hardware outright at a loss hoping for software attach — attach rates disappoint. Benchmarks by seed: 5–15 paying sites, ≥1 fleet expansion signed, NRR ≥120% (site expansion is the engine).

### 1.8 Marketplace & Network Effects {#m-marketplace}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | The constrained side first (usually supply). Define one geo/category wedge: "wedding photographers in Austin," not "creative services." |
| Seed | Both sides profiled with liquidity math: how much supply density does one demand cohort need for <X-hour fill time? |

#### GTM execution loop

1. Single-market wedge. Hand-recruit supply (50–200 units) via outbound; do-things-that-don't-scale matching (founder as the matching algorithm for the first 100 transactions).
2. Liquidity benchmarks before expanding geo/category: **fill rate >60%, time-to-fill declining month-over-month, ≥20% of transactions repeat**.
3. Disintermediation defense from day one: escrow/payments in-platform, reviews, insurance/guarantee — make going direct riskier than paying the take rate.

#### Pricing & business model

- Take rates by category: commoditized goods 5–15%; services 15–25%; high-trust/managed 25–35%. Start at the low end, raise after liquidity (raising take rate pre-liquidity kills supply).
- Charge the side that gets more value (usually demand); subsidize the constrained side.
- Benchmarks by seed: $1–5M annualized GMV in wedge market, take rate net revenue $150k–$750k, supplier M3 retention >50%, one market at demonstrable liquidity before market #2.

### 1.9 Fintech & Embedded Finance {#m-fintech}

#### ICP evolution

| Stage | ICP definition |
|---|---|
| Validation | A segment underserved by incumbents on a specific money flow (e.g., "landscaping SMBs waiting 45 days on invoices"). Quantify the flow: volume × frequency × pain. |
| Seed | Same segment + distribution wedge defined (community, vertical SaaS partner, or owned channel) — fintech CAC kills more seed companies than fraud does. |

#### GTM execution loop

1. Stack selection weeks 1–4: BaaS/sponsor bank (Lead Bank, Column, Stripe Treasury), card issuing (Lithic, Marqeta), KYC (Persona, Alloy). Budget **$10k–$30k/mo** infra + compliance floor — raise accordingly.
2. Wedge product live in 90 days; measure money-movement activation (funded account %, first-transaction rate) not signups. Funded-account benchmark: **>40%** of approved applications.
3. Compliance as GTM: a real compliance narrative closes partners and survives diligence — hire a fractional BSA/compliance officer ($4–8k/mo) pre-seed.

#### Pricing & business model

- Interchange: ~1.5–2.9% gross on credit, ~1.1% debit (Durbin-exempt via sponsor bank); your net after sponsor/processor: **50–110bps**. Interchange alone rarely supports a business — plan a second line (SaaS fee, float at 4–5% yield, lending margin).
- Payments take rate: 25–100bps net. Lending: know your loss budget (charge-offs <5% consumer, <3% SMB secured).
- Benchmarks by seed: $10–50M annualized TPV or $1–5M loan originations, unit-level contribution margin positive, compliance audit-ready.

<p class="backtop"><a href="#top">↑ Back to top</a></p>

## Pillar 2 — Team Building, Co-Founder Matching & High-Density Hiring {#pillar-2}

### 2.0 Ideation-to-Seed Talent Matrix {#talent-matrix}

| Layer | [1] Ideation | [2] Validation | [3] Pre-Seed | [4] Seed |
|---|---|---|---|---|
| **Team size** | 1–2 founders | 2–3 (founders + contractor) | 3–6 | 6–15 |
| **Key move** | Co-founder matching & trial project | First founding engineer | Founding GTM or design hire | First manager/exec; recruiting becomes a founder KPI |
| **Equity pool** | Founder split only | Create 10% option pool | Pool 10–12% | Refresh to 12–15% at round |
| **Vetting depth** | 2–4 week paid trial project | Work-sample + 2 backchannels | Full loop + 3 backchannels | Structured scorecards, panel debriefs |
| **Comp philosophy** | Sweat equity | Below-market cash, high equity | 60–75% market cash | 75–90% market cash |

**Co-founder matching protocol (ideation):**

1. Source: prior colleagues > school/research network > founder matching platforms (YC co-founder matching) > events. Prior-work relationships have ~2x survival rates.
2. **Mandatory trial: 2–4 weeks building something real together** before any equity conversation. Evaluate: velocity, conflict style, who does the unglamorous work.
3. The 50-questions conversation before incorporating: money expectations, 5-year commitment, firing each other, spouse/geo constraints, what "done" looks like.
4. Split: default near-equal (60/40 max spread) with **4-year vesting, 1-year cliff — no exceptions, including yourself**. Unequal splits based on "the idea" are a red flag; ideas are worth ~5%.

### 2.1 Motion-Specific Talent Playbooks {#talent-playbooks}

| Motion | First 3 hires after founders | Sourcing channel | Watch-out |
|---|---|---|---|
| Enterprise B2B | Founding eng ×2, then founding AE (only after founder closes 10 deals) | Ex-colleagues; AEs from adjacent-vertical startups at Series B (they know playbooks, still hungry) | Hiring sales before founder-led repeatability = burning $250k to learn nothing |
| PLG | Product eng, growth eng, data scientist (analytics) | Communities where your users live; ship-in-public engineers | Don't hire marketing before activation funnel is instrumented |
| Prosumer | Full-stack eng, content/creator lead, support-as-community | The niche itself — hire a power user | Creator-lead must be *of* the niche, not a generalist marketer |
| Deep Tech | Research scientist (often from founder's lab), systems eng, grants/BD hybrid | Academic networks, PhD program pipelines, defense primes' R&D alumni | Post-doc pay expectations vs equity literacy — spend an hour teaching equity math |
| Defense/GovTech | Cleared eng (or clearance-eligible), capture/BD lead (ex-program office or prime), mission-expert advisor | Veteran networks (ShieldTalent, Breakline), SkillBridge fellows (free 3–6 mo trial with military talent) | Clearance timeline is 6–18 months — hire clearance-eligible early; a capture lead with real PEO relationships is worth 1.5x market |
| B2B2C | Partnerships lead (ex-BD at a platform), integration eng, partner success | Alumni of your target partners' partnership teams | Partnerships people who "know everyone" but closed nothing — count signed deals |
| HaaS | Firmware/hardware eng, ops/field-deploy lead, supply-chain contractor | Hardware startup alumni (drone/robotics layoff cycles are hiring windows), ex-Apple/Tesla ops | Hardware hires expect higher cash, understand equity less — expect 80–90% cash weighting |
| Marketplace | City/category launcher (GM archetype), growth eng, ops generalist | Ex-Uber/DoorDash/Instacart launch alumni networks | GMs need P&L ownership from day 1 or the good ones leave |
| Fintech | Backend eng (payments experience), compliance officer (fractional→full-time), risk/data analyst | Fintech infra alumni (Stripe/Plaid/Unit/Marqeta), compliance from challenger banks | Never ship money movement without compliance sign-off; regulators don't accept "we're early" |

### 2.2 Technical Vetting Sequence {#vetting}

1. **Screen (30 min):** past-work deep-dive — "walk me through the hardest system you built; what would you change?" Depth of ownership > breadth of stack.
2. **Paid work sample (2–4 hrs, $200–$500 or a real scoped ticket):** representative task from your actual backlog, not leetcode. Grade on a written rubric: correctness, communication, tradeoff articulation, taste.
3. **Architecture/system session (60 min):** design something adjacent to your real system; probe with "what breaks at 10x?"
4. **Backchannel ×2–3 (mandatory, off-list):** former managers/peers. Two questions: "top 5% of people you've worked with — yes or no?" and "what will I have to manage?" Any hedge on question 1 is a no.
5. **Founder dinner/working session:** conflict simulation — debate a real product decision; watch for how they disagree.

**Time budget:** ≤10 days screen-to-offer. Offers lost to slowness cost more than any comp bump.

### 2.3 Compensation Bands (early-stage US, cash + equity) {#comp}

| Role | Validation / Pre-Seed | Seed |
|---|---|---|
| Founding engineer (#1–2) | $120–$160k + **1.0–2.5%** | $150–$190k + 0.5–1.5% |
| Engineer #3–5 | $130–$165k + 0.3–0.8% | $150–$185k + 0.2–0.6% |
| Founding designer | $120–$150k + 0.5–1.5% | $140–$175k + 0.3–0.8% |
| Founding AE / GTM #1 | $80–$110k base ($160–$220k OTE) + 0.3–1.0% | $100–$130k base (2x OTE) + 0.25–0.75% |
| Growth/data (PLG) | $130–$160k + 0.4–1.0% | $150–$185k + 0.25–0.6% |
| Capture/BD (Defense) | $130–$170k + 0.5–1.25% | $150–$200k + 0.4–1.0% |
| Fractional compliance (Fintech) | $4–8k/mo, 0–0.25% | Full-time $160–$210k + 0.3–0.75% |
| VP / Head-of (exec at seed) | — | $170–$220k + **0.8–2.0%** |

Rules: 4-year vest / 1-year cliff universally; refresh grants at each round for top performers; publish internal leveling by 10 FTEs to prevent negotiation-skill-based inequity.

### 2.4 Counter-Offer Defense {#counteroffers}

- **Pre-empt at offer stage:** "When you resign, your employer will counter with 20–30% and a title. Let's talk about that now" — inoculation cuts counter-acceptance dramatically.
- Never bid against the counter with cash alone; reframe: counters fix the symptom (comp) not the cause (ceiling, mission, ownership). ~50–80% of counter-accepters are gone within 12–18 months anyway — say this.
- Give a 48-hour decision window on your offer with a real (not fake) expiry. If they take the counter, part warmly and re-ping in 9 months.

### 2.5 30-60-90 Onboarding Scorecard {#scorecard}

```
HIRE: ____________  ROLE: ____________  MANAGER: ____________  START: ______

DAYS 1–30 — LEARN & FIRST SHIP
□ Ships first PR / closes first ticket by day 10 (eng) OR completes 10 customer
  calls (GTM) OR maps full partner/compliance landscape (BD/ops)
□ 1:1s completed with every teammate + 3 customers/users
□ Can articulate: our ICP, our #1 metric, our current biggest risk — unprompted
□ Written "fresh eyes" memo: 3 things that confused them, 3 things to change
SCORE /10: __   RED FLAGS: ______________________

DAYS 31–60 — OWN A LANE
□ Owns one metric or system end-to-end (named here: ____________)
□ Ships a meaningful improvement without hand-holding
□ (GTM) Sources ≥5 qualified opps solo  (Eng) On-call ready / owns a service
□ Communication: async updates land without chasing
SCORE /10: __   COURSE-CORRECT: ______________________

DAYS 61–90 — COMPOUND
□ Measurable impact on owned metric (target: ____________)
□ Raises the bar: improved a process/doc/tool others now use
□ Would we enthusiastically re-hire? (unanimous founder yes/no): ____
□ 90-day calibration conversation held; growth plan for next 2 quarters written
DECISION: ACCELERATE / COACH / EXIT — mediocre-at-90-days rarely becomes great.
```

<p class="backtop"><a href="#top">↑ Back to top</a></p>

## Pillar 3 — Tight-Process Fundraising, Equity Structuring & Capital Stratification {#pillar-3}

### 3.0 Ideation-to-Seed Capital Matrix {#capital-matrix}

| Layer | [1] Ideation | [2] Validation | [3] Pre-Seed | [4] Seed |
|---|---|---|---|---|
| **Instrument** | Personal + F&F SAFEs | Angel SAFEs | Post-money SAFEs (or small priced) | Priced equity round (or SAFE stack ≤25% dilution) |
| **Round size** | $25k–$250k | $250k–$750k | $500k–$2.5M | $2M–$6M |
| **Valuation/cap** | $3–6M post-money cap | $5–10M cap | $8–15M cap (AI/deep tech: $12–25M) | $15–35M post-money |
| **Dilution budget** | ≤5% | 5–10% | 10–20% | **15–20% max** |
| **Runway bought** | 6–9 mo | 9–12 mo | 12–18 mo | 18–24 mo |
| **Proof required** | Founders + insight | Design partners, early usage | Early revenue / signed pilots / grant awards | Repeatability: $250k–$1M ARR or motion-specific equivalents (Pillar 1) |
| **Lead profile** | None (party round fine) | Angels, operators | Pre-seed funds, solo GPs | Institutional seed lead writing 40–60% of round |

**SAFE hygiene:** post-money SAFEs only (YC standard); model the full stack dilution before each signature — founders routinely discover they've sold 35% via stacked SAFEs. F&F rule: only money they can lose; paper it properly (SAFE, not handshake); accredited-investor check.

**Cumulative dilution guardrail:** founders should hold **≥60% post-seed**, ≥50% post-A. Below that, later-stage investors start discounting founder motivation.

### 3.1 The 8-Week Countdown to Launch {#countdown}

| Week | Workstream | Deliverables & numbers |
|---|---|---|
| **-8** | Narrative & targets | Story memo (1-pager): why now, why us, why this wedge. Build target list: **60–80 firms**, tiered A/B/C by fit (stage, check size, sector thesis, existing portfolio conflicts). |
| **-7** | Materials v1 | Deck (12–15 slides), financial model (18–24 mo, driver-based), data room skeleton. Deck order: problem→insight→product→traction→market→team→ask. |
| **-6** | Data room build | Full architecture (below). Metrics audit — every number in the deck must reconcile to the data room. |
| **-5** | Warm-path mapping | For every A-tier firm, find the warm intro (portfolio founders > operators > other VCs). Cold is fine for B/C tier: partner-specific, 4-sentence email, deck attached. |
| **-4** | Practice circuit | 5–8 pitches to friendly VCs/founders NOT on target list. Rebuild deck from objections. Kill any slide that needs verbal explanation. |
| **-3** | Intro staging | Ask connectors to hold intros until launch week. Draft forwardable blurbs (3 sentences, one metric, the ask). |
| **-2** | Ops setup | CRM with stages: intro→meeting→partner mtg→IC→TS. Calendar blocked: **20–30 first meetings inside a 2-week window** — density creates FOMO; a trickle creates staleness. |
| **-1** | Final polish | Deck v3, 90-second verbal pitch tight, diligence FAQ doc (the 20 hardest questions, answered). Line up 2–3 "first yes" candidates (angels/insiders) to anchor momentum. |
| **0 — Launch** | Sprint | All intros fire Monday–Tuesday. Batch meetings weeks 1–2, partner meetings weeks 2–4, target first term sheet by week 3–4, close week 6–8. Process runs **6–8 weeks max**; anything longer reads as a struggling round. |

### 3.2 Data Room Architecture {#dataroom}

**Standard B2B SaaS / PLG / Prosumer / Marketplace / Fintech:**

```
/01_Corporate      — cert of inc, bylaws, cap table, board consents, prior SAFEs
/02_Financials     — P&L, burn, bank statements (3 mo), driver-based model
/03_Metrics        — ARR/MRR waterfall, cohort retention grids, CAC/payback, pipeline
                     (marketplace: GMV, take rate, liquidity by market)
                     (fintech: TPV, unit economics per flow, loss rates, compliance docs)
/04_Product        — roadmap, architecture 1-pager, security posture, demo video
/05_GTM            — ICP doc, pipeline snapshot, 3 customer contracts (redacted OK),
                     win/loss notes
/06_Team           — org chart, key-hire pipeline, founder bios, option pool status
/07_Legal          — IP assignments (EVERY contributor — #1 diligence killer),
                     key contracts, insurance
/08_References     — 5 customer references, prepped and pre-warned
```

**Deep Tech / DefenseTech deltas:**

- `/03_Metrics` → replaced by **/03_Technical_Validation**: TRL evidence, third-party test data, peer-reviewed publications, milestone history vs plan.
- `/07_Legal` expands: patent filings + FTO (freedom-to-operate) analysis, university IP license terms (exclusive? royalty stack? sublicensable?), **SBIR data-rights assertions**, ITAR/EAR classification memo, facility clearance status.
- Add **/09_Government**: award letters (Phase I/II), contract vehicles, transition-sponsor memos, pipeline of open solicitations with submission dates.
- **Tiered access:** Tier 1 (everyone post-first-meeting): deck, summary metrics/TRL. Tier 2 (post-partner-meeting): full financials, contracts. Tier 3 (post-term-sheet, under NDA): IP details, gov pipeline specifics, source-code review. Never expose core IP to Tier 1 — strategic-CVC leakage is real.

### 3.3 Tactical Closing {#closing}

#### FOMO management (ethical version — scarcity through genuine parallelism)

- Batch meetings so every partner knows others are moving. Line: *"We're running a tight process — first partner meetings are this week and next; we expect to make decisions by [date 3 weeks out]."*
- When a partner meeting goes well: *"Where does this sit for you? We're scheduling second meetings for early next week and I want to make sure you have what you need to move at that pace."*
- Never fabricate term sheets. If asked directly: *"We have strong interest and multiple second meetings scheduled; I'm not going to characterize other firms' positions."* Lying here follows you for a decade.

#### First term sheet play

- A term sheet starts a 7–10 day clock. Immediately notify every live process: *"We've received a term sheet. We're excited about it, but we committed to a process and want to finish conversations. Can you get to a decision by [date 5–7 days out]?"* Real interest accelerates; polite interest exits — both outcomes are wins.

#### Multi-term-sheet dynamics

- Decide on **lead quality, not headline price**: partner (not firm) track record, reserves for follow-on (want ≥1:1), reference checks with 3 of their founders *including one whose company failed*.
- Valuation spread ≤20%: take the better partner. Spread >30%: ask the preferred-but-lower firm to move — most close 50–70% of the gap for a company they want. Line: *"You're our first choice on partnership. The delta to my other offer is [X]. Help me close it."*
- Syndication: lead takes 40–60%; fill remainder with 1 value-add second check + angels/operators. Cap the party-round tail — >15 investors on the cap table = signature-chasing forever. Use a single SPV/roll-up vehicle for small checks.
- Round-size discipline: raise for 18–24 months of milestones, not for the biggest headline. Oversubscription: take **≤20% above target** only if dilution stays inside the 15–20% budget; otherwise cut checks, don't raise the raise.

#### Terms that matter more than valuation

1x non-participating liquidation preference (never participating) · board 2 founders / 1 investor at seed · option pool "shuffle" negotiated (pool created pre-money dilutes you — size it against your actual 18-month hiring plan, typically 10% not 15%) · pro-rata rights fine · MFN on side letters · no full-ratchet anti-dilution (broad-based weighted average only).

<p class="backtop"><a href="#top">↑ Back to top</a></p>

---

*Benchmarks reflect 2025–2026 US early-stage market norms and premier accelerator/fund published data. Ranges vary by geography and sector heat; treat as calibration points, not gospel.*

</div>
