# athlete-os

21-week BJJ body recomposition operating system for a 32yo brown belt (**Phase 1 start Mon Nov 9, 2026** → Week 21 **Apr 4, 2027**; planned KBBQ weekend Nov 7–8 before launch).

Built from the Grappler Body Recomposition Playbook research, with clocks remapped to an **≈11:00 AM wake** chronotype (not the playbook’s 7:00 AM template).

## Architecture

```
athlete-os/
├── .cursor/rules/recomp.mdc          # Permanent physiological / S&C / chronotype rules
├── protocols/
│   ├── nutrition_phases.csv          # Phase 1–4 + Maintenance macros & deficits
│   ├── milestones.csv                # Anthropometric & strength benchmarks by week
│   ├── lifts_registry.md             # 2-day microcycle (midday Tue/Fri), tempos, RPE
│   ├── coaching_calendar.md          # Flow (coach) vs GB Northridge (athlete) map
│   ├── schedule_master.md            # Coach+athlete timetable + satiety gates
│   ├── supplementation_matrix.md     # Stack doses, forms, timing + Rx meds
│   ├── trajectory_realism.md         # Honest Tier A/B/C success framing
│   └── weekend_prestart.md           # KBBQ weekend rules + Mon Nov 9 launch
├── data/
│   ├── weigh_ins.csv                 # Daily scale, waist, gi overlap log
│   └── lifting_log.csv               # Session-level set log
├── reviews/
│   └── weekly_reviews.md             # Sunday wake audit template
├── research/
│   └── grappler_recomp_playbook.md   # Source research (ignore its early-AM clocks)
├── .gitignore
└── README.md
```

## Trajectory Snapshot

| | Week 0 (Nov 9, 2026) | Week 21 (Apr 4, 2027) |
|--|----------------------|------------------------|
| Weight | 189.7 lbs | 172.0 lbs (170–174) |
| BF% | 26.1–27.0% | 14.9% |
| LBM | 138.5–140.2 lbs | 146.4 lbs |
| Navel waist | 36.0" | 31.5" (31–32") |
| Pants / Gi | Size 34 tight; A1 gaps 1.5" | Size 31–32; A1 ≥5.5" overlap |

## Late-Wake Day Skeleton

| Clock | Block |
|-------|-------|
| ≈11:00 AM | Wake → void → scale → (collagen on lift days) |
| ≈11:15 AM | Gate 1 breakfast (45g protein + D3/K2 + Ω-3) |
| ≈11:45 AM–12:33 PM | Lift A/B *or* Zone 2 *or* mobility |
| ≈12:40 / 1:00 PM | Psyllium → Lunch + Kirkland multi (≥2 hrs before sertraline) |
| **3:00 PM** | **Sertraline 75 mg** |
| 4:30 PM | Gate 4 protein anchor (≥100g by 5:00 PM) |
| 5:00 PM | Peri-mat carbs on sparring evenings |
| Thu ≈12:00 PM | **GB Northridge Gulag** (home gym athlete session) |
| Mon–Thu 5:00–7:30 PM | **Flow** coach block (job; coach-mode) |
| **Friday PM** | **Free** (no Flow teach) after Lift B — default rest; GB only if Thu missed |
| Sat ≈7:30 wake | Flow Adults 9:00am teach → **mat cleanup** → GB usually skipped |
| 60 min pre-bed → bedtime | Magnesium stack → **allergy med** at lights-out |

## Agent Usage

Before answering training or nutrition queries, read:

1. `data/weigh_ins.csv`
2. `data/lifting_log.csv`
3. `protocols/milestones.csv`
4. `protocols/nutrition_phases.csv`
5. `protocols/coaching_calendar.md`
6. `protocols/schedule_master.md`
7. `protocols/supplementation_matrix.md`

Give exact gram, pound, RPE, and tempo directives on the late-wake clock. Never cut calories in Weeks 1–3 if navel waist is tightening (ICW buffer).

## Is the Week-21 “stocky” target realistic?

**Leaner / tighter gi / stronger in 21 weeks — yes.** Fat loss of ~1 lb/week and waist drop are coherent with the deficit model, especially returning from a lifting layoff.

**Finished stocky density by Week 21 — usually no.** Treat milestones as Tier B aims; full yoke/shelf fullness often needs **Weeks 22–30 at maintenance (2,500 kcal)**. See `protocols/trajectory_realism.md`.
