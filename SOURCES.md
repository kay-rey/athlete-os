# Source-of-truth map (DRY)

Edit **only** the owning file. Everywhere else links here — do not copy tables.

## Doctrine (what you should do)

| Concern | Own here |
|---------|----------|
| Identity, Rx, chronotype, anthro targets, energetics, phase dates | `athlete/profile.md` |
| Tier A/B/C realism | `athlete/trajectory.md` |
| Strength/anthro benchmarks | `athlete/milestones.csv` |
| Flow grid, GB hours, GB 2× priority, Muay Thai rules | `calendar/academies.md` |
| Day-by-day ops, Gates 1–7, grocery quantities | `day/schedule.md` |
| Sleep modes, wife drop-off, Reyes/MasterBJJ focus, phone rails | `life/lifestyle.md` |
| Costco Via Princessa chooser (Best / Also OK / Skip) | `day/costco_tonight.md` |
| Pre-start KBBQ / Day-1 flag | `day/weekend_prestart.md` |
| Taste likes/dislikes + gate flavor examples | `nutrition/preferences.md` |
| Staple meal deep-dives / batch recipes | `nutrition/recipes/*` |
| Lose It app setup | `nutrition/loseit_setup.md` |
| Phase kcal/macros | `nutrition/phases.csv` |
| Lift programming / RPE / tempos | `strength/lifts.md` |
| Bottle inventory, quality audit, doses | `stack/supplements.md` |
| Agent hard rules + journal + food deep-dive | `.cursor/rules/recomp.mdc` |

## Journal (what you actually did — append-only)

| Concern | Own here |
|---------|----------|
| Scale + tape measurements | `journal/anthro.csv` |
| Food intake logs | `journal/meals.csv` |
| Lift session logs | `journal/lifting.csv` |
| Mat / BJJ / Flow / MT session logs | `journal/mats.csv` |
| Freeform day notes | `journal/entries/` |
| Sunday audits | `journal/weekly_reviews.md` |
| Photos / labels | `journal/reference/` |
| Logging conventions | `journal/README.md` |
| Apple Health / device history (derived) | `journal/imports/apple_health/` (not raw export.xml) |

## Archive (not live SoT)

| Concern | Own here |
|---------|----------|
| Upstream Gemini playbook (clocks outdated) | `archive/research/*` |
