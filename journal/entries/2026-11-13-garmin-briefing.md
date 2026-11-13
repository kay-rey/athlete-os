# Garmin Connect briefing — Phase research context (2026-11-13)

Source: derived CSVs in `journal/imports/garmin/` from local GDPR export  
`/Users/kayrey/Downloads/725c71ea-bb56-4fd2-a2fb-9daf38fd927b_1` (`DI_CONNECT/` only).  
Cross-check: `journal/imports/apple_health/` + `journal/entries/2026-11-06-apple-health-briefing.md`.  
**Phase SoT** remains `journal/anthro.csv` (weight/waist) and `journal/mats.csv` (2026 mats).

## Executive verdict

Garmin confirms a **high-volume 2023–2024 combat + strength + cycling base**, then a **hard logging/wearable cliff by mid-2025**. That supports myonuclear rebound expectations and explains why Apple Health shows **no 2026 workouts**. Use Garmin for **historical EAT, RHR, sleep, and prior lift benchmarks** — not for current Phase compliance.

## Training (summarized activities)

| Metric | Value |
|--------|--------|
| Activities | **588** unique (`activityId` deduped) |
| Date range | **2022-11-17 → 2025-05-25** |
| `mixed_martial_arts` | **163** sessions ≈ **15,299 min** |
| MMA by year | 2023: 45 / **3,824 min** · **2024: 110 / 10,678 min** · 2025: 8 / 797 min |
| Named “Jiujitsu” | 12 (subset of MMA-class logging) |
| Strength | **89** sessions |
| Road + virtual cycling | **~251** (road_biking 241 + virtual_ride 10) |

**2024 martial volume matches Apple Health exactly:** Health `martial_arts` 2024 = **110 sessions / 10,678 min** = Garmin MMA 2024. Devices agree; the gap is **post–May 2025 / all of 2026**.

### Strength benchmarks (Garmin Strength app, 2023-04)

| Lift | Logged | Est. 1RM |
|------|--------|----------|
| Barbell back squat | 180 lb × 10 | ~240 lb |
| Barbell deadlift | 165 lb × 8 | ~205 lb |
| Barbell bench | 135 lb × 3 | ~143 lb |
| Overhead press | 60 lb × 10 | ~80 lb |
| Barbell row | 80 lb × 10 | ~107 lb |

These are **~2.5 years old** and conventional-bar context — useful as a prior-strength floor for research, not current EOS working loads.

## Daily wellness (UDS)

| Metric | Coverage | Notes |
|--------|----------|-------|
| Days | **1025** · **2022-10-07 → 2025-12-13** | Continues after activity cliff |
| Steps (mean, days with data) | 2023 ≈ **4,083** · 2024 ≈ **5,151** · 2025 ≈ **3,541** | Lower than Apple Health phone/watch totals (see crosswalk) |
| Resting HR | 2023 ≈ **47** · 2024 ≈ **46** · 2025 ≈ **50** | Athletic RHR; slight rise in 2025 |
| Body battery (daily high) | 2023 ≈ **83** · 2024 ≈ **89** · 2025 ≈ **88** | When worn |
| Avg all-day stress | 2023 ≈ **25** · 2024 ≈ **27** · 2025 ≈ **21** | Garmin 0–100 scale |

## Sleep

- **768** nights with stage minutes · **2023-03-04 → 2025-05-10**
- Mean total sleep (deep+light+REM) ≈ **449 min (~7.5 h)**
- After **2025-05-11**, sleep files are thin — do not infer 2026 sleep quality from Garmin

## Weight in Garmin biometrics

- **170** weight rows · mostly **MFP** (151), some MANUAL
- Last entry **2025-08-23 ≈ 176.5 lb** (MFP)
- **Not preferred** vs Withings / `anthro.csv`. Treat as secondary diary noise (same class as Lose It! scale entries in Health)

## Crosswalk vs Apple Health

| Topic | Garmin | Apple Health | Use for research |
|-------|--------|--------------|------------------|
| 2024 hard mats | MMA 110 / 10,678 min | martial_arts 110 / 10,678 min | **Identical — high confidence EAT history** |
| 2025–26 mats | Activities end **2025-05-25** | Workouts end **2025-05-09**; **0 in 2026** | Layoff / logging cliff; Phase mats → `mats.csv` |
| Steps 2024 | UDS mean ~**5.2k** | Health mean ~**7.9k** | Different sensors/sources; **archival only, no step goals** |
| Steps 2025–26 | ~3.5k (partial 2025) | ~3.2k / ~2.7k | Both show NEAT collapse vs 2024 |
| RHR | ~46–50 Garmin UDS | Health ~46 (2024 athletic era) | Consistent “trained” RHR when worn |
| Sleep 2025–26 | Good through **May 2025**, then thin | Collapses after 2024 in export | Garmin better for 2023–early 2025 sleep |
| Weight | MFP-heavy → ~176.5 (Aug 2025) | Withings preferred; Phase **189.7 → 186.7** | **Withings/anthro win**; Garmin MFP understates recent mass |
| BF% / waist | Not in this parse | BF climb ~20%→29%; live waist **41.0"** | Health + tape SoT |

## Implications for Gemini / Athlete-OS

1. Prior plan TDEE that assumed high 2024-like training + NEAT is **optimistic for 2026** unless GB 2× + teaching restore EAT.
2. Concurrent recomp / strength return is plausible given **2023–24** lift + MMA density and stored benchmarks.
3. Do **not** invent 2026 wearable load from Garmin — export has a real silence.
4. Keep binge-aware Gates; device history does not replace Lose It / meals journal for Phase adherence.

## What not to feed Gemini raw
- Full UDS/sleep JSON shards, FIT zips, email-bearing filenames, aviation/empty GDPR folders
