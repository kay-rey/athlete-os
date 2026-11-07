# Apple Health import (derived)

Parsed from local export (not committed — ~2.5 GB):

`/Users/kayrey/Downloads/apple_health_export/export.xml`

**Do not** commit `export.xml` / `export_cda.xml` / workout-routes into this repo.

Phase-relevant write-up → [`journal/entries/2026-11-06-apple-health-briefing.md`](../../entries/2026-11-06-apple-health-briefing.md).

## Preference rules
- **Weight / body fat:** prefer **Withings** when present that day; else first available source (Lose It!, Connect, etc.)
- Daily row = earliest preferred reading that day; `day_mean_*` averages all preferred readings that day

## Files
| File | Contents |
|------|----------|
| `bodymass_daily.csv` | Daily weight (lbs), 2019 → export date |
| `bodyfat_daily.csv` | Daily body fat % |
| `waist.csv` | Sparse waist entries from Health |
| `nutrition_daily_2024plus.csv` | Daily macro rollups from Health dietary records (mostly Lose It!) |
| `workouts_2024plus.csv` | Workouts from 2024+ |
| `steps_daily_2024plus.csv` | Daily step totals 2024+ |

## Snapshot (this export)
- Weight climb: yearly means ~**162 (2024)** → **178 (2025)** → **187 (2026)**; Apr 2026 peak ~**196 lb**
- Last **Withings** scale: **2026-06-04** ≈ **183.7 lb**, BF ≈ **28.0%** (2026 BF mean ≈ **29%** vs ~20% in 2022–23)
- Last weight in Health overall: **2026-07-24** ≈ **188.7 lb** (Lose It!)
- Phase baseline in `journal/anthro.csv`: **2026-11-06** **189.7 lb** / **36.0"** (manual — not in this export as Withings)
- **NEAT collapse:** steps/day mean **~7,865 (2024)** → **~3,180 (2025)** → **~2,733 (2026)** — below profile’s 8.5–10k assumption
- Workouts in Health: heavy 2024 martial_arts; trickle to May 2025; **no 2026** workout objects (BJJ/coaching not logged here)
- Nutrition: only **13** Health dietary days in 2026 (high protein when present) — not a full diary
- Waist in Health last **33"** (Oct 2022) vs current tape **36"**
- Gap: Jun–Nov 2026 mostly missing Withings sync in Health

## Re-import
Re-run a stream parse of a fresh Health export into this folder; keep `journal/anthro.csv` as the Phase SoT (append new manual/Withings days there going forward).
