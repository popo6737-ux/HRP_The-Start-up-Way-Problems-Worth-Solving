# FoamFit — Business Plan

**A wet-wipe-free smart toilet paper solution**

> Version 1.0 | Date: 2026-05-09 (translated for coursework, 2026-07-25)

---

## 1. Idea Overview

**Product name (working title):** FoamFit — Foam-Dispensing Module

**One-line definition:**
FoamFit is a modular add-on device that attaches to the jumbo-roll toilet paper dispensers already installed in public restrooms. The physical force of pulling toilet paper drives a small mechanical pump that automatically sprays a metered dose of foam cleanser onto the paper — delivering a wet-wipe-level clean without any electricity.

---

## 2. Problem Definition (Pain Point)

After a bowel movement, dry toilet paper alone often leaves users feeling insufficiently clean in public restrooms. Yet:

- **Toilet clogging:** Wet wipes don't dissolve in water, clogging pipes and generating hundreds of thousands of KRW in repair costs.
- **Trash overflow:** Discarded wet wipes fill restroom trash bins, increasing the cleaning burden.
- **Bidets aren't scalable:** Installation cost, space, and plumbing requirements make bidets impractical for most public restrooms.

→ A real **friction point**: wanting to feel clean, but unable or unwilling to use a wet wipe.

---

## 3. Market Validation

### Blind app survey (n=18, 2026)

| Response | Share | Count |
|---|---|---|
| Would use a wet-wipe alternative if available in every restroom **(= potential customer)** | **50.0%** | 9 |
| Dry toilet paper is good enough | 33.3% | 6 |
| Even wet wipes are too much hassle | 16.7% | 3 |

**Key insight:** Half of respondents are willing to use a more comfortable alternative if one exists.

> ⚠️ **Honest assessment of validation level:** This survey confirms **problem awareness** — that people want a wet-wipe alternative — but it does not validate reactions to FoamFit as a **specific solution**. Price, installation experience, and actual in-use performance remain untested. See `lean-startup-analysis.md` for a fuller breakdown.

See `competitive-analysis.md` for the competitive landscape — most notably **CWS Hygiene**, a European B2B washroom-services company that already supplies foam dispensers as part of a rental/subscription service, and **Tushé**, a touchless electric foam dispenser sold in the US for home use.

---

## 4. Solution Design

### 4-1. Hardware Architecture

```
[ Existing jumbo-roll dispenser ]  ───  kept exactly as-is
        ↓
[ FoamFit attachment module ]
  ├─ Mechanical pump: linked to the paper-pull lever → dispenses a small dose of foam
  ├─ Foam cartridge: replaceable (OEM foam initially → proprietary formula later)
  ├─ Spray nozzle: positioned where the paper is dispensed
  └─ User lock switch: any user who doesn't want the feature can turn it off
```

**Core principle:** The physical force of pulling paper → compresses the mechanical pump → dispenses foam. **No electricity or batteries required, at any point.**

### 4-2. Key Design Decisions

| Item | Decision | Rationale |
|---|---|---|
| Spray substance | Foam cleanser (not liquid) | Prevents paper tearing + stronger cleaning performance |
| Product form | Modular (attaches to existing dispenser) | Minimizes B2B adoption barrier, enables easy PoC |
| Trigger mechanism | Mechanical, linked to the paper-pull lever | No power source needed, fits naturally into existing user behavior |
| Power | None (purely mechanical) | Zero install/maintenance cost, no electrical work required |
| Lock control | User-operated on/off | Preserves individual choice for users who don't want it |
| Foam supply strategy | Start with OEM foam → develop proprietary formula | Fast time-to-market + long-term technical differentiation |
| Partnership strategy | Prioritize co-development with dispenser manufacturers | Solves compatibility, leverages existing distribution networks |

### 4-3. User Flow

```
① User reaches for the lever
      ↓
② The mechanical pump compresses (no electricity involved)
      ↓
③ The nozzle dispenses a small dose of foam cleanser
      ↓
④ User wipes with the foam-coated paper, similar to a wet wipe

※ When the lock switch is ON: no foam is dispensed; the paper works as ordinary toilet paper
```

---

## 5. B2B Strategy

### 5-1. Target Customers

| Target | Rationale |
|---|---|
| Highway rest areas | Highest foot traffic, fastest path to usage data |
| Public institutions (government/municipal buildings) | Public-hygiene rationale supports large-scale contracts |
| Large shopping malls / mixed-use facilities | A differentiator for visitor satisfaction |
| Corporate office buildings | Fast decision-making by facilities teams, higher-quality feedback |

### 5-2. Objection Handling

| Anticipated objection | Response |
|---|---|
| "Won't paper consumption go up and increase costs?" | The savings from avoiding wet-wipe-related clog repairs are far larger. |
| "Isn't replacing equipment expensive?" | No replacement needed — the module simply attaches to the existing dispenser (5-minute install). |
| "Won't this be a maintenance headache?" | A single recurring cartridge subscription consolidates all maintenance. |
| "Does this require electrical work?" | It's purely mechanical — no power source is required at any point. |
| "Won't users find this off-putting?" | The lock switch preserves individual choice for anyone who doesn't want it. |
| "Isn't there already a similar product (e.g., Tushé)?" | Tushé is a touchless, battery-powered device built for home use. FoamFit is purely mechanical, so it can be deployed across hundreds of stalls in a public facility with zero battery-management burden — a design built specifically for B2B infrastructure, not the home. |
| "Doesn't CWS in Europe already offer foam dispensers to commercial washrooms as a rental service?" | Yes — CWS is the most direct and serious competitor we've identified. However, their dispenser is sensor-driven (electric), not purely mechanical, and still requires power and maintenance. CWS has not yet entered the Korean market, which may leave more room for entry where incumbent vendor contracts are less established. (This is an untested assumption that needs field validation.) |

---

## 6. Business Model & Roadmap

### Revenue Structure

| Revenue stream | Mechanism | Notes |
|---|---|---|
| Module sales | Upfront hardware sale | Priced near cost to drive adoption |
| Foam cartridge subscription | Monthly flat fee or usage-based | **Core revenue driver** |
| Partnership revenue | Licensing or revenue share | Primary revenue source in Phase 1 |

### Three-Phase Roadmap

```
Phase 1 (0–12 months): Co-development partnership with dispenser manufacturers
  ├─ Enter the market through partners' existing distribution networks
  ├─ Secure an OEM foam-cleanser supply agreement
  ├─ Run PoC pilot installations (e.g., highway rest areas)
  └─ Complete a working mechanical-pump prototype

Phase 2 (12–24 months): Establish the cartridge subscription model
  ├─ Launch B2B subscriptions (monthly or auto-ship)
  ├─ Collect and optimize based on usage data
  └─ Build a base of reference customers

Phase 3 (24+ months): Expand as an independent brand
  ├─ Develop a proprietary foam formula and file patents
  ├─ Launch FoamFit as a standalone brand
  └─ Scale direct B2B sales
```

---

## 7. Next Action Items

- [ ] Identify dispenser manufacturers and initiate partnership outreach
- [ ] Build a working mechanical-pump prototype
- [ ] Source OEM foam-cleanser suppliers (spray-bidet foam manufacturers)
- [ ] Conduct prior-art / patent research (mechanical pump + dispenser-integration mechanism)
- [ ] Review regulatory/certification requirements (cleanser regulations, e.g., Korea MFDS)
- [ ] Secure a site for an MVP PoC pilot (highway rest area preferred)
- [ ] Run an expanded survey (larger sample, n=100+)
