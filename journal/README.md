# Health journal

Append-only log of what you **actually** ate, weighed, measured, lifted, and trained on the mats. Doctrine (what you *should* do) lives outside this folder — see root `SOURCES.md`.

## Files
| File | Use |
|------|-----|
| `anthro.csv` | Scale + tape (weight, waist, A1, optional chest/hips/thigh/arm) |
| `meals.csv` | Every food/drink report from chat |
| `lifting.csv` | Lift A/B sets |
| `mats.csv` | BJJ / Flow / MT sessions (academy, role, RPE, GB credit, notes) |
| `entries/YYYY-MM-DD.md` | Freeform day notes when needed (travel, KBBQ, “felt flat”) |
| `weekly_reviews.md` | Sunday audits |
| `reference/` | Photos (bottles, labels, scale) |
| `imports/apple_health/` | Derived CSVs from Apple Health export (history); see folder README |
| `imports/garmin/` | Derived CSVs from Garmin Connect GDPR export (history); see folder README |

### Mat logging (how)
**Default:** after class, tell the agent (or paste a Notes line) → append `mats.csv`.  
**Phone capture (optional):** one Apple Notes / Shortcuts line per session, then dump here — don’t need a separate BJJ app.  
**Apple Health “Martial Arts”:** duration only if you want a workout ring; it is **not** the technique/GB-credit log.  
**Flow vs GB:** Flow rows get `gb_credit=N`. Hard GB / OM that counts toward ≥2× gets `gb_credit=Y`.

## Conventions
- Timezone: **America/Los_Angeles** dates
- Morning scale: post-void, pre-food when possible
- Agent **appends** rows — never rewrite history; correct with a new row + note if needed
- Food shares → deep-dive then `meals.csv` row(s); staple changes also patch `nutrition/` or `stack/`
- Weekly review pulls from these CSVs + `calendar/academies.md` / `day/schedule.md`
