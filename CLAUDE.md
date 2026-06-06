# i2P House — Claude Command Center

This file auto-loads at the start of every Claude Code session. It is the operational briefing for Claude (and any AI agent working in this repo). Read it before doing anything else.

---

## Who You Are Working With

**CEO:** KaTerrell Kennedy (KT)
**Company:** i2P LLC
**Mission:** Build AI-driven sports intelligence, haptic accessibility tech, and performance technology.
**Primary repo:** i2phouse.com (GitHub Pages website + AI operations hub)

## AI Operations Model

KT runs business operations with Claude (code, strategy, research, patent prep) and Perplexity (research, search, competitive intelligence). Both AI systems must stay aligned to this briefing. When starting a session, read this file first.

---

## Operating Principle

i2P runs as one company with clear lanes, not as one folder of mixed experiments. Each venture gets a home, each legal or funding claim has a source of truth, and sensitive files stay outside normal operations.

---

## Venture Map

### Technology and IP

| Venture | Folder | Status | Notes |
|---|---|---|---|
| AEGIS | `03_AEGIS` | Patent-pending, active R&D | Acoustic AI / accessibility tech for BLV fans |
| Battito / i2P Haptic Designs | `04_I2P_HAPTIC_DESIGNS` | Pre-filing, confidential | Patent application NOT filed |
| BRIA | `12_BRIA` | Concept stage, confidential | Do not disclose technical protocol externally |
| All patent filings | `01_PATENTS` | Ongoing | Filings, notices, receipts, invention records, attorney materials |

### Commerce and Products

| Venture | Folder | Status | Notes |
|---|---|---|---|
| VOID Fashion (Apparel + RIDER + Slickers) | `05_VOID` | Pre-launch | Campaign shot; tech packs complete; all fashion is VOID branded — no other name |
| GLOWSEOUL | `05_VOID` or dedicated folder | Pre-launch | K-beauty; formulas and suppliers are trade secrets |
| FIFA Agent Prep Platform | `11_EDUCATION` | Shippable — not launched | SaaS / sports agent tools; Stripe checkout blocker unresolved |
| Ctrl Club Futbol | `06_WEBSITES` | Sprint 2 active | Content / e-commerce brand; BVS rubric is trade secret |

### Services and Operating Businesses

| Venture | Folder | Status | Notes |
|---|---|---|---|
| Sacred Spaces | `13_SACRED_SPACES` | Launched | Premium cleaning service business |
| Total Spectrum Autism Services LLC | Separate entity | Operating | Confirm county, active status, revenue |
| Athletic Corridor Foundation | On hiatus | Officially paused May 30, 2026 | athleticcorridor.com reassigned to FIFA Agent Prep |

### Funding, Partnerships, and Operations

| Area | Folder |
|---|---|
| Grants (NSF SBIR, Vogt, FIFA Innovation) | `02_GRANTS` |
| Partnerships (NDI, KSTC, Jan Rogers) | `07_PARTNERSHIPS` |
| Investor / financial / diligence | `08_FINANCIAL` |
| Meeting notes and follow-ups | `09_MEETINGS` |
| Automations and internal tools | `10_OPERATIONS` |
| Websites and public digital assets | `06_WEBSITES` |

### Holding and Legal

| Entity | Notes |
|---|---|
| i2P LLC | Primary operating company — `00_CORPORATE` |
| Total Spectrum Autism Services LLC | Separate entity — confirm current filing status |
| Sacred Spaces | Confirm legal entity and filing status |

---

## AEGIS — Lead Patent Asset

**What it is:** Real-time acoustic anticipation engine. Listens to live crowd sound, detects building crowd swell before a peak match moment, delivers haptic alert to blind/low-vision (BLV) sports fans BEFORE the moment happens. Audio-only — no cameras, no player tracking, no official data feeds required.

**Full name:** Acoustic Momentum Detection Engine (formerly "Quantum-Classical Hybrid Intelligence Engine" — retired framing, do not use).

**Patent status:** Patent-pending. U.S. provisional application 64/006,872. Filed March 16, 2026.

**USPTO surcharge:** Missing Parts fee PAID June 2, 2026 (surcharge $13, code 3052 + Micro Entity cert PTO/SB/15A). ✅

**Critical deadline:** Non-provisional filing due **March 16, 2027**. Maintain 90/60/30-day reminders.

**NSF SBIR Phase I pitch:** Targeting NSF 26-510 or NSF 26-511. Up to $305,000. **Next due date: July 27, 2026.** KT is solo PI. KSTC contact: Ellie Derbyshire. NDI contact: Alexis Jones, MSW. Portal was closed due to legislative changes — confirm current status before submitting.

**Production system:** Live on Azure Container Apps. API endpoint active. RF model (trained on 1,400+ crowd events). `AEGIS_LOCAL/` has NO git repo — all production code is local-only. **Back up before factory reset.**

**What AEGIS may be called publicly:** Patent-pending. Accessibility technology. Acoustic anticipation engine.

**What AEGIS must NOT be called:** Related to betting, gambling, wagering, picks, props, or sportsbook products. Not a performance analytics tool. Not a Quantum-Classical Hybrid Intelligence Engine.

**Deprecated:** The `picks` automation pipeline (`generate_picks.py`, `run_full_picks_pipeline.sh`) fed the retired CTRL-Bet venture (killed June 5, 2026). The AEGIS engine itself is unaffected — use alert outputs, not picks log.

---

## i2P Haptic Designs — Battito™

**Status:** Pre-revenue, hardware development. Patent application in preparation.

**Brand:** Battito™ (Italian: "heartbeat") — formally named April 23, 2026.

**Patent status:** NOT YET FILED. USPTO #227004 = Customer/Correspondence Number ONLY — NOT a patent number. Target: ~March 2027.

**Attorney:** TBD — pro bono program. Ibrahim Farag is no longer on the Battito team.

**Safe language:** "Patent application in preparation" — never "patent pending," "provisional," or "USPTO #227004 filed."

**Active SKUs (both under i2P House / VOID brand):**
- SKU-02: Void Frames
- SKU-03: Void Ear Tunnel
- ~~SKU-01~~ DELETED (internal name: "Shower Choker" / "i2P Resonance") — do NOT reference publicly.

**LinkedIn scrub (until filed + counsel clears):** Remove product names and technical specs from public profiles. Safe: "wearable technology venture" only.

---

## VOID — i2P House Fashion Brand

**Brand rule:** ALL fashion under i2P House is **VOID** branded. There is no "KORR" brand. There is no other fashion name. Everything is VOID.

**Three lines:**
- **VOID Apparel** — Travel Edition + Heritage Collection. Campaign (14 hero images) complete and ready to launch.
- **VOID RIDER** — "Iblis Black Box." 275 numbered limited-run luxury leather moto jackets. Sourcing brief complete (Portugal/Turkey). Manufacturer outreach pending.
- **VOID Thermochromic Slickers** — Champions League Ultras collection. Tech packs + CSV complete. Ready for manufacturer submission. Jim Madison Screenprint × Rowdy Glow Thermochromic collab. 6 core silhouettes + 23-club UCL Winners Ultras line.

---

## GLOWSEOUL — K-Beauty Skincare

**Status:** Pre-launch. Formulations complete. Scientific brief ready.

**Why it's priority:** Fastest to market (no patent delays, no hardware). Highest margins in portfolio. Underserved market (K-Beauty for melanated/deeper skin tones).

**5 SKUs:** Brightening Serum · Dark Spot Cream · Vitamin C Serum · Retinal Booster · PDRN Recovery Serum

**Trade secrets:** Formulas, suppliers, and margins are confidential — do not share publicly.

---

## FIFA Agent Prep Platform

**Status:** Shippable product — complete, NOT yet launched.

**What it is:** Multi-agent AI system for aspiring FIFA-licensed football agents. 320-question quiz bank, 10 case studies, automated contract generator, 7 specialized AI agents.

**Critical blocker:** Stripe client-only checkout integration NOT enabled. ENROLL NOW buttons do not work. Fix: Stripe Dashboard → Settings → Checkout settings → enable client-only integration.

**Security:** Memberstack TEST API Secret Key was exposed in a Claude session (June 1, 2026) — roll it immediately in Dev Tools → Reset Secret Key.

**Domain:** athleticcorridor.com now hosts FIFA Agent Prep (Athletic Corridor Foundation on hiatus). athleticcorridor.org is locked in AWS Route 53 for when foundation reactivates.

**OpenClaw clarification:** OpenClaw is NOT an i2P asset. It is an external tool used during development. i2P owns the FIFA Agent Prep Platform — not OpenClaw.

---

## Ctrl Club Futbol

**Status:** Active — Sprint 2 content production in progress.

**Type:** E-commerce soccer brand under i2P LLC.

**Sprint status:** Sprint 1 complete (100% BVS approval). Sprint 2 in progress.

**BVS (Brand Voice Score):** 5-dimension content quality rubric. All content measured before publication. Sprint 1 sets the benchmark. BVS rubric is a trade secret.

**Endrick Live Player Intelligence Agent:** Architecture defined, build pending. 5-layer automated content system (data ingestion → contextual AI → content production → automation → deliverables) focused on Endrick (Real Madrid/Brazil).

---

## IP Rules — Follow These Every Session

1. **AEGIS:** Patent-pending. Always frame as accessibility technology for BLV fans. Never use betting/gambling language. Never call it Quantum-Classical Hybrid or a performance analytics tool.
2. **Battito / i2P Haptic Designs:** NOT filed. Do NOT say patent-pending. Say "patent application in preparation." Keep technical details confidential. Ibrahim Farag is NOT the attorney for this — TBD.
3. **BRIA:** Confidential. Do NOT disclose technical or protocol details externally. No manufacturing or partner outreach before filing decision.
4. **OpenClaw:** External tool. Not an i2P asset.
5. **KORR:** This brand name does not exist. Everything is VOID.
6. **Trade secrets — never commit to Git, never paste into public tools:**
   - AEGIS: training data, scoring architecture, feature weighting, validation methodology, model files
   - Battito: haptic efficacy data, materials, manufacturing process
   - BRIA: protocol logic and signaling maps
   - GLOWSEOUL: formulas, suppliers, margins
   - FIFA Agent Prep: curriculum database, contract generator logic
   - Ctrl Club: BVS rubric and content pipeline
7. **Git rule:** Never commit patent drafts, trade-secret documents, credentials, or attorney-client materials to this repo.

---

## Security — Credentials Requiring Action

| Credential | Status | Action |
|---|---|---|
| Memberstack TEST API Secret Key | Exposed June 1, 2026 | Roll immediately — Dev Tools → Reset Secret Key |
| NVIDIA_API_KEY | Exposed in Claude session May 24, 2026 | Rotate at build.nvidia.com |
| FOOTBALL_DATA_API_TOKEN | Rotated May 18, 2026 — now env var | ✅ Done |
| Supabase keys | In build-i2p-systems/.env | Do not commit |
| AEGIS_LOCAL/ `.env` | ORIGINQ_API_KEY | Do not commit |

---

## Critical Backup Gaps (Before Factory Reset)

| Asset | Location | Risk |
|---|---|---|
| AEGIS production code | `~/AEGIS_LOCAL/` — NO git repo | Total loss if Mac wiped |
| Match MP4s (3.0GB) | Local only | Total loss |
| WAV chunks (3.3GB) | Local only | Total loss |
| labeled_data.db (411 samples) | Local only | Total loss — retraining corpus |
| VOID campaign images (14 hero shots) | `~/Desktop/i2P_Command_Center/05_VOID/` | Total loss |

**Recommended:** `git init ~/AEGIS_LOCAL && git remote add origin [new private repo]` + Google Drive/iCloud backup of MP4s before wiping.

---

## Company Lanes

| Lane | Home | Purpose |
|---|---|---|
| Executive command | `00_COMMAND_CENTER` | Priorities, business map, cadence, handoffs, decision logs |
| Legal, IP, compliance | `00_CORPORATE`, `01_PATENTS`, `99_SECURITY_REVIEW` | Entity truth, patent truth, trade-secret handling, credential safety |
| AEGIS and accessibility | `03_AEGIS` | Prototype, validation, datasets, acoustic signal processing, haptics, grants |
| Haptics and apparel IP | `04_I2P_HAPTIC_DESIGNS`, `12_BRIA` | Battito hardware, SKUs, prototype notes, patent-prep |
| i2P House commerce | `05_VOID` | VOID fashion, rider, thermochromic, GLOWSEOUL, manufacturing, ecommerce |
| Education and products | `11_EDUCATION` | FIFA Agent Prep, courses, curriculum, sales, payment |
| Services | `13_SACRED_SPACES` | Service menu, pricing, client ops, SOPs, bookings |
| Funding and partnerships | `02_GRANTS`, `07_PARTNERSHIPS`, `08_FINANCIAL` | Grants, investors, diligence, partners, timelines |

---

## Weekly Operating Cadence

**Every Monday:**
1. Choose one primary revenue objective.
2. Choose one funding or IP objective.
3. Choose one cleanup/compliance objective.
4. Update the active project dashboard.

**Every Friday:**
1. Archive completed outputs.
2. Update `PERPLEXITY_BUSINESS_HANDOFF.md` if facts changed.
3. Check `99_SECURITY_REVIEW`.
4. Run `git status --short` before any commit.

---

## Immediate Priorities (Updated June 2026)

### This Week
- [ ] **BACKUP AEGIS_LOCAL before factory reset** — git init + push to private repo; back up 3GB MP4s and WAV chunks
- [ ] Roll Memberstack TEST API Secret Key (exposed June 1, 2026)
- [ ] Rotate NVIDIA_API_KEY (exposed May 24, 2026)
- [ ] Fix Stripe client-only checkout — FIFA Agent Prep ENROLL NOW buttons broken
- [ ] AEGIS attorney packet — send provisional, NP draft claims, multi-sport expansion to counsel
- [ ] Create formal trade-secret register — encrypted local storage, outside Git and iCloud
- [ ] Confirm Battito public materials say "patent application in preparation" only
- [ ] Create BRIA confidential invention disclosure (attorney-only version)
- [ ] NSF pitch: confirm solicitation target (26-510 vs 26-511), budget, testing partners, NDI/Alexis Jones permission to name

### Next 30 Days
- [ ] Prior-art searches for AEGIS multi-sport claims, Battito/Void Ear Tunnel, BRIA
- [ ] Battito provisional filing decision + find pro bono patent attorney
- [ ] BRIA filing decision before any manufacturing/partner outreach
- [ ] Trademark clearance: Battito, VOID, GLOWSEOUL, Ctrl Club, Sacred Spaces, i2P House
- [ ] Confirm Total Spectrum Autism Services LLC — entity status, county, active status, revenue
- [ ] Confirm Sacred Spaces legal entity and filing status
- [ ] GLOWSEOUL launch prep — Shopify/ecommerce setup
- [ ] FIFA Agent Prep soft launch (after Stripe fix)

### Next 90 Days
- [ ] Finalize AEGIS non-provisional claim strategy with counsel
- [ ] Design patent candidates for hardware/apparel embodiments
- [ ] Convert investor/grant decks to public-safe versions
- [ ] Launch fastest monetizable assets: GLOWSEOUL → FIFA Agent Prep → VOID Apparel

---

## Key Contacts

| Name | Role | Context |
|---|---|---|
| Ellie Derbyshire | KSTC | Active NSF pitch-development partner |
| Alexis Jones, MSW | NDI | Warm BLV recruitment/validation channel for AEGIS — confirm permission to name |
| Ibrahim Farag | Legal / Patent | AEGIS NP filing only — no longer on Battito team |
| Jan Rogers | Partnerships / ACF | Strategic partner; ACF grants files at `SHARED/Jan_Rogers_ACF/` |

---

## Custom Skills Available

- `/patentability-claims-search-agent` — Run structured patentability search, claim charting, mock office actions, prosecution prep for AEGIS and other IP assets.

---

## Repo Structure

```
i2phouse.com/
├── index.html              # i2P House website (GitHub Pages)
├── CNAME                   # i2phouse.com domain
├── CLAUDE.md               # This file — auto-loads business context
├── .claude/
│   └── commands/
│       └── patentability-claims-search-agent.md
└── .gitignore              # Blocks sensitive docs from Git
```

## What Does NOT Belong in This Repo

- Patent application drafts or claims
- Trade-secret documents of any kind
- Attorney-client communications
- Financial models or investor diligence materials
- AEGIS training data, model weights, or validation corpus
- Battito or BRIA technical specifications
- API keys, credentials, or .env files
- Any file from `01_PATENTS/`, `03_AEGIS/patent/`, `99_SECURITY_REVIEW/`

These live in encrypted local storage on KT's machine only.
