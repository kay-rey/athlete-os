# athlete-os

21-week BJJ body recomposition operating system for a 32yo brown belt (baseline Nov 6, 2026 → target Apr 2, 2027).

## Architecture

```
athlete-os/
├── .cursor/rules/recomp.mdc     # Permanent physiological, nutritional, and S&C rules
├── protocols/
│   ├── nutrition_phases.csv     # Phase 1–4 + Maintenance macros & deficits
│   ├── milestones.csv           # Anthropometric & strength benchmarks by week
│   ├── lifts_registry.md        # 2-day microcycle, tempos, RPE curve, autoregulation
│   └── schedule_master.md       # 7-day timetable, satiety gates, peri-sparring, groceries
├── data/
│   ├── weigh_ins.csv            # Daily scale, waist, gi overlap log
│   └── lifting_log.csv          # Session-level set log
├── reviews/
│   └── weekly_reviews.md        # Sunday 06:45 AM audit template
├── .gitignore
└── README.md
```

## Trajectory Snapshot

| | Week 0 (Nov 6, 2026) | Week 21 (Apr 2, 2027) |
|--|----------------------|------------------------|
| Weight | 189.7 lbs | 172.0 lbs (170–174) |
| BF% | 26.1–27.0% | 14.9% |
| LBM | 138.5–140.2 lbs | 146.4 lbs |
| Navel waist | 36.0" | 31.5" (31–32") |
| Pants / Gi | Size 34 tight; A1 gaps 1.5" | Size 31–32; A1 ≥5.5" overlap |

## Agent Usage

Before answering training or nutrition queries, read:

1. `data/weigh_ins.csv`
2. `data/lifting_log.csv`
3. `protocols/milestones.csv`
4. `protocols/nutrition_phases.csv`

Give exact gram, pound, RPE, and tempo directives. Never cut calories in Weeks 1–3 if navel waist is tightening (ICW buffer).
