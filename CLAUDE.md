# i2P House — Claude Command Center

This file auto-loads at the start of every Claude Code session. It is the operational briefing for Claude (and any AI agent working in this repo). Read it before doing anything else.

## Who You Are Working With

**CEO:** KaTerrell Kennedy (KT)
**Company:** i2P LLC
**Mission:** Build AI-driven sports intelligence, haptic accessibility tech, and performance technology.
**Primary repo:** i2phouse.com (GitHub Pages website + AI operations hub)

## AI Operations Model

KT runs business operations with Claude (code, strategy, research, patent prep) and Perplexity (research, search, competitive intelligence). Both AI systems must stay aligned to this briefing. When starting a session, read this file first.

## Active Ventures — Priority Order

| Venture | Status | Type |
|---|---|---|
| AEGIS | Patent-pending, active R&D | Acoustic AI / accessibility tech |
| Battito / i2P Haptic Designs | Pre-filing, confidential | Haptic wearable hardware |
| BRIA | Concept stage, strategy TBD | Adaptive safety apparel |
| VOID (thermochromic slickers) | Tech packs complete | Fashion / safety apparel |
| FIFA Agent Prep Platform | Shippable product | SaaS / sports agent tools |
| Ctrl Club Futbol | Active | Content / agent intelligence |
| GLOWSEOUL | Pre-launch | Beauty / skincare brand |
| Sacred Spaces | Launched | Service business |
| Total Spectrum Autism Services | Operating | Care services business |
| Athletic Corridor Foundation | On hiatus | Nonprofit |
| i2P House | Active | Website / AI ops hub |

## AEGIS — Lead Patent Asset

**What it is:** Real-time acoustic anticipation engine. Listens to live crowd sound, detects building crowd swell before a peak match moment, delivers haptic alert to blind/low-vision sports fans BEFORE the moment happens. Audio-only — no cameras, no player tracking, no official data feeds required.

**Patent status:** Patent-pending. U.S. provisional application 64/006,872. Filed March 16, 2026.

**Critical deadline:** Non-provisional filing due **March 16, 2027**. Calendar 90/60/30-day reminders.

**NSF SBIR Phase I pitch:** Targeting NSF 26-510 or NSF 26-511. Up to $305,000. **Next due date: July 27, 2026.** KT is solo PI. KSTC contact: Ellie Derbyshire. NDI contact: Alexis Jones, MSW.

**What AEGIS may be called publicly:** Patent-pending. Accessibility technology. Acoustic anticipation engine.

**What AEGIS must NOT be called:** Related to betting, gambling, wagering, picks, props, or sportsbook products.

## IP Rules — Follow These Every Session

1. **Battito / i2P Haptic Designs:** NOT filed. Do NOT say patent-pending. Say "patent application in preparation." Keep all technical details confidential.
2. **BRIA:** Confidential. Do NOT disclose technical or protocol details externally.
3. **Trade secrets (never commit to Git, never paste into public tools):** AEGIS training data, scoring architecture, feature weighting, validation methodology; Battito haptic efficacy data, materials, manufacturing process; BRIA protocol logic; GLOWSEOUL formulas and suppliers; FIFA Agent Prep curriculum; Ctrl Club BVS rubric.
4. **Git rule:** Never commit patent application drafts, trade-secret documents, or attorney-client materials to this repo.

## Immediate Priorities (Updated June 2026)

### This Week
- [ ] AEGIS attorney packet — send provisional, NP draft claims, multi-sport claim expansion, patent status file to counsel
- [ ] Create formal trade-secret register — encrypted local storage, outside Git and iCloud
- [ ] Scrub all public AEGIS docs for betting/gambling language
- [ ] Confirm Battito public materials say "patent application in preparation" only
- [ ] Create BRIA confidential invention disclosure (attorney-only version)
- [ ] NSF pitch: confirm solicitation target (26-510 vs 26-511), budget, testing partners, NDI permission

### Next 30 Days
- [ ] Prior-art searches for AEGIS multi-sport claims, Battito/Void Ear Tunnel, BRIA
- [ ] Battito provisional filing decision
- [ ] BRIA filing decision before any manufacturing/partner outreach
- [ ] Trademark clearance: Battito, VOID, GLOWSEOUL, Ctrl Club, Sacred Spaces, i2P House

### Next 90 Days
- [ ] Finalize AEGIS non-provisional claim strategy with counsel
- [ ] Design patent candidates for hardware/apparel embodiments
- [ ] Convert investor/grant decks to public-safe versions

## Key Contacts

| Name | Role | Context |
|---|---|---|
| Ellie Derbyshire | KSTC | Active NSF pitch-development partner |
| Alexis Jones, MSW | NDI | Warm BLV recruitment/validation channel for AEGIS |
| Ibrahim Farag | Legal / Patent | Patent counsel contact |

## Custom Skills Available

- `/patentability-claims-search-agent` — Run structured patentability search, claim charting, mock office actions, prosecution prep for AEGIS and other IP assets.

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
- Any file from `01_PATENTS/`, `03_AEGIS/patent/`, `99_SECURITY_REVIEW/`

These live in encrypted local storage on KT's machine only.
