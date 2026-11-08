# Apple Health briefing — Phase 1 context

Source: derived CSVs in `journal/imports/apple_health/` from `/Users/kayrey/Downloads/apple_health_export` (export through ~2026-11-06).  
**Phase SoT scale/tape:** `journal/anthro.csv` → **2026-11-06 = 189.7 lb / 36.0" waist** (not in Health as Withings).

## Executive verdict

You are starting Phase 1 **heavier and softer than your 2022–24 baseline**, after a 2025–26 climb that peaked near **196 lb** in April 2026. Last synced Withings (Jun 4) was ~**183.7 lb / ~28% BF**; by Nov 6 you are back near **190**.

Historical risk flag: Apple Health showed steps falling ~**7.9k/day (2024)** → ~**2.7k/day (2026)**, while the old TDEE model assumed ~8.5–10k. **You are not counting steps going forward** — do not chase a step quota. If Phase waist stalls with solid Gates + GB 2× + lifts + Sunday Zone 2, revisit kcal — not a pedometer.

Health is **history** (scale/BF when synced). It is **not** your BJJ log, food diary, or something you must monitor daily.

## Weight (daily preferred; Withings when available)

| Year | Days | Min | Max | Mean | Year-end-ish last |
|------|------|-----|-----|------|-------------------|
| 2019 | 41 | 159.5 | 172.0 | 163.7 | 159.7 |
| 2020 | 175 | 148.2 | 174.5 | 160.1 | 163.2 |
| 2021 | 70 | 157.1 | 170.1 | 163.7 | 163.4 |
| 2022 | 157 | 142.2 | 170.0 | 158.0 | 144.8 |
| 2023 | 72 | 144.9 | 169.9 | 158.5 | 169.8 |
| 2024 | 86 | 149.8 | 178.0 | 161.7 | 168.3 |
| 2025 | 27 | 174.5 | 183.1 | 178.1 | 176.5 |
| 2026 | 32 | 176.5 | 196.0 | 187.4 | 188.7 |

- Lifetime low in this series: **~142 lb** (Nov 2022 Withings).
- Lifetime high in this series: **~196 lb** (Apr 2026 Lose It! / Withings cluster).

### 2026 month strip

| Month | n | Mean lb | Range |
|-------|---|--------|-------|
| Jan | 1 | 176.5 | 176.5 |
| Apr | 4 | 194.3 | 191.6–196.0 |
| May | 24 | 186.9 | 183.2–191.4 |
| Jun | 2 | 184.3 | 183.7–185.0 |
| Jul | 1 | 188.7 | 188.7 (Lose It!) |
| Nov 6 | — | **189.7** | Phase baseline (`anthro.csv`) |

Path: Apr peak → May–Jun cut toward ~184 → summer drift → Nov baseline ~190.

## Body fat %

| Year | Mean (excl ~0 junk) | Notes |
|------|---------------------|-------|
| 2022–23 | ~19.6% | Leaner era |
| 2024 | ~20.4% | Drift up |
| 2025 | ~25.9% | Clear soft-tissue gain |
| 2026 | ~29.3% | Last Withings **~28.0%** (2026-06-04) |

Profile Phase target **~14.9%** is a long walk from current Health BF — score Tier A (waist/adherence) first.

## Waist

Health only has sparse manual entries; last Health waist **33"** (2022-10-04). Current tape **36.0"** (2026-11-06). Prefer `journal/anthro.csv` going forward.

## Steps / NEAT (critical)

From `steps_daily_2024plus.csv`:

| Year | Days | Mean steps/day |
|------|------|----------------|
| 2024 | 366 | **~7,865** |
| 2025 | 365 | **~3,180** |
| 2026 | 310 | **~2,733** |

Context only (not a live target). Phase levers without counting: Sunday Zone 2, Mon errands, on-feet teaching — judge by waist, not steps.

## Training log gap

- `workouts_2024plus.csv`: **285** workouts in 2024 (incl. **110** martial_arts), only **14** in 2025, **0** in 2026.
- Last Garmin martial_arts in Health: **2025-02-21**. Strength/walks trickle to **2025-05-09**, then silence.
- Flow coaching + GB sessions are **not** visible here for 2026. Use `calendar/academies.md` + Sunday review / chat for mat truth — not Apple Health workouts.

## Nutrition (Health dietary records)

- **13** logged days in 2026 (Lose It! → Health); not continuous coverage.
- On those days: mean ≈ **2,374 kcal · 222P · 244C · 69F**; **10/13** days ≥180g protein.
- Useful as proof you *can* hit high protein; **useless** as Phase compliance SoT. Log meals to `journal/meals.csv` (chat) from Day 1.

## Cardio markers (sparse recent)

- Resting HR 2024 mean ~**46** bpm (athletic); last RHR day in export ~2025-05-19.
- BP sample thin (2024): ~**122/59**.
- SleepAnalysis record volume collapses after 2024 — do not trust this export for 2025–26 sleep quality.

## What to trust going forward

| Need | Trust |
|------|--------|
| Phase weight / waist / A1 | `journal/anthro.csv` (append) |
| Food / macros | Chat → `journal/meals.csv` |
| Lifts | `journal/lifting.csv` |
| Historical scale/BF/steps | `journal/imports/apple_health/*` |
| Mat frequency | Calendar + weekly review, not Health workouts |
| Next Health refresh | Re-export → re-parse imports; never commit raw `export.xml` |

## Phase 1 implications (no macro change this pass)

1. Baseline **189.7 / 36"** is credible vs summer drift after a spring peak.
2. Prioritize **GB ≥2×**, lifts, Gates, and Sunday Zone 2 — **no step counting**.
3. Expect ICW scale noise Weeks 1–3; waist > scale.
4. Revisit TDEE/kcal only if waist stalls after Weeks 1–3 with solid adherence (not because of a step number).
