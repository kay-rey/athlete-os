# Garmin Connect import (derived)

Parsed from local GDPR export (not committed — ~169 MB unzipped):

`/Users/kayrey/Downloads/725c71ea-bb56-4fd2-a2fb-9daf38fd927b_1`

**Parse scope:** `DI_CONNECT/` only. **Do not** commit the raw export, FIT zips, or email-bearing source filenames.

Phase-relevant write-up → [`journal/entries/2026-11-13-garmin-briefing.md`](../../entries/2026-11-13-garmin-briefing.md).  
Cross-check with Apple Health → `journal/imports/apple_health/`.

## Files
| File | Contents |
|------|----------|
| `activities.csv` | 588 summarized activities (2022-11-17 → 2025-05-25): type, name, duration, HR, calories, training load/TE |
| `activities_yearly.csv` | Counts + total minutes/calories by year × activity_type |
| `uds_daily.csv` | Daily User Daily Summary (2022-10-07 → 2025-12-13): steps, RHR, body battery, stress, intensity, kcal |
| `sleep_daily.csv` | Sleep stages / stress when present (rich nights ~2023-03 → 2025-05) |
| `weight_history.csv` | Garmin biometrics weights (mostly MFP/manual; grams→lbs) |
| `benchmarks.csv` | Strength app benchmarks (Apr 2023) |

## Snapshot (this export)
- **MMA / BJJ-class logging:** 163 `mixed_martial_arts` sessions ≈ **15,299 min** (2023: 45 / 2024: **110 ≈ 10,678 min** / 2025: 8) — 2024 matches Apple Health martial_arts minute-for-minute
- **Strength:** 89 sessions; benchmarks (2023-04): back squat ~180×10, DL ~165×8, bench ~135×3, OHP ~60×10, row ~80×10 lb
- **Cycling-heavy era:** 241 road_biking + virtual rides in the activity set
- **Activities end 2025-05-25** (same cliff as Health Connect); UDS continues thinner into **2025-12-13**
- **RHR** (UDS days with data): ~47 (2023) → ~46 (2024) → ~50 (2025)
- **Sleep stages** mean ~**7.5 h** total sleep on measured nights; coverage fades after May 2025
- **Garmin weight** mostly MyFitnessPal — **not** preferred vs Withings in Health; last Garmin weight **2025-08-23 ≈ 176.5 lb** (MFP)

## Preference rules
- **Phase weight SoT:** `journal/anthro.csv` / Withings — not Garmin MFP weights
- **2026 mats:** `journal/mats.csv` — not Garmin (no 2026 activities)
- **Steps:** archival only — athlete is **not** counting steps
- Email / profile PKs scrubbed from committed filenames; activity IDs kept for dedupe

## Re-import
Drop a fresh Garmin export beside the Downloads path above; re-run the local parse into this folder; keep raw export out of git.
