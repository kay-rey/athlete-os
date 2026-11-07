# athlete-os

Solo **21-week BJJ recomp OS + health journal** (Flow coach + GB Northridge athlete).

**Start:** Phase 1 Mon Nov 9, 2026 → Week 21 ≈ Apr 4, 2027.  
**Edit map:** [`SOURCES.md`](SOURCES.md) (DRY — one owner per fact).

Tell the agent what you ate, weighed, or measured — it appends `journal/` and only patches doctrine when a staple/rule changes.

## Layout

```
SOURCES.md                   # what owns what
athlete/                     # profile, trajectory, milestones
calendar/academies.md        # Flow + GB + Muay Thai rules
day/                         # schedule (Gates) + weekend prestart
nutrition/                   # phases, preferences, recipes/
strength/lifts.md            # Lift A/B
stack/supplements.md         # bottles + doses
journal/                     # HEALTH JOURNAL (append-only)
  anthro.csv · meals.csv · lifting.csv
  entries/ · weekly_reviews.md · reference/
archive/research/            # playbook source (NOT live SoT)
.cursor/rules/recomp.mdc     # agent constraints
```

## Agent
Follow `.cursor/rules/recomp.mdc`. Deep-dive every food/supplement share. Journal every intake/anthro/lift report. Commit on `main` only.
