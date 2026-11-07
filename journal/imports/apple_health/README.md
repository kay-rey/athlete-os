# Apple Health import (derived)

Parsed from local export (not committed — ~2.5 GB):

`/Users/kayrey/Downloads/apple_health_export/export.xml`

**Do not** commit `export.xml` / `export_cda.xml` / workout-routes into this repo.

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

## Snapshot (this export)
- Last **Withings** scale: **2026-06-04** ≈ **183.7 lb**, BF ≈ **28.0%**
- Last weight in Health overall: **2026-07-24** ≈ **188.4 lb** (Lose It! manual)
- Phase baseline in `journal/anthro.csv`: **2026-11-06** **189.7 lb** / **36.0"** (manual — not in this export)
- Gap: Jun–Nov 2026 mostly missing Withings sync in Health

## Re-import
Re-run a stream parse of a fresh Health export into this folder; keep `journal/anthro.csv` as the Phase SoT (append new manual/Withings days there going forward).
