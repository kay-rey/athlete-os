# Health journal

Append-only log of what you **actually** ate, weighed, measured, and lifted. Doctrine (what you *should* do) lives outside this folder — see root `SOURCES.md`.

## Files
| File | Use |
|------|-----|
| `anthro.csv` | Scale + tape (weight, waist, A1, optional chest/hips/thigh/arm) |
| `meals.csv` | Every food/drink report from chat |
| `lifting.csv` | Lift A/B sets |
| `entries/YYYY-MM-DD.md` | Freeform day notes when needed (travel, KBBQ, “felt flat”) |
| `weekly_reviews.md` | Sunday audits |
| `reference/` | Photos (bottles, labels, scale) |

## Conventions
- Timezone: **America/Los_Angeles** dates
- Morning scale: post-void, pre-food when possible
- Agent **appends** rows — never rewrite history; correct with a new row + note if needed
- Food shares → deep-dive then `meals.csv` row(s); staple changes also patch `nutrition/` or `stack/`
- Weekly review pulls from these CSVs + `calendar/academies.md` / `day/schedule.md`
