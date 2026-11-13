# Gemini Deep Research intake — Athlete-OS refresh (2026-11-13)

Use this packet so Deep Research recalibrates kcal, timeline, waist targets, and S&C off **measured** data — not the old 36" estimate.

## Already locked (paste into the prompt)

| Item | Value |
|------|--------|
| Age / sex / height | 32♂ · 5'5" (165.1 cm) · turns 33 Jan 20, 2027 |
| Ethnicity / genetics flags | Guatemalan descent; SLC16A11; LCT-13910 CC (lactose risk — phenotype OK so far); ABCA1 R230C risk |
| Sport | BJJ brown belt; coaches Flow; trains GB Northridge ≥2×/wk goal |
| Phase start | Mon Nov 9, 2026 · ~21-week recomp |
| Weight | Baseline 189.7 (Nov 6) · 188.3 (Nov 12) · **186.7** (Nov 13 Withings) |
| Withings Body+ | Muscle% 66.7 · Fat% **29.8** (BIA noisy — trend only) |
| Navel waist | **~40–41"** first physical tape (provisional; **no tape ≥1 yr**; old 36" retired) |
| Chest (nipple-line) | **41.6"** |
| Thigh | **R 22.3" / L 20.6"** (use right as primary) |
| Neck | **15.2"** |
| Calf | **15.0"** |
| Flexed arm | **R 13.5"** |
| Ankle | **L 9.1"** above malleolus |
| Wrist | **6.6"** (medium frame; McCallum waist ideal ~30") |
| Tape scale | Inches side = **8 ticks/inch (eighths)** — not tenths |
| Fat pattern | Android — belly + soft chest / “man boobs” |
| Current plan kcal | **2,250** · P **180–195** · C ~215 · F ~72 · fiber 45–50 |
| Failure mode | **Binge / overeating** (not under-protein); Gates front-load ≥100P by 5 PM |
| Training | Lift A Tue / Lift B Fri ≤48 min; GB hard 2×; teach Flow; Fri = Lift B only (no BJJ stack) |
| Rx / clinical | Sertraline 75 mg @ 3 PM; allergy med QHS; **diagnosed sleep apnea, no CPAP**; intermittent sciatica; GAD / panic; flight anxiety (Indonesia trip late Jan) |
| Sleep ops | Wife drop-off Tue–Sat ~7:40; biphasic second sleep most days; Wed straight to Flow 9 AM |
| Week-1 adherence | Often **400–700 kcal under** target while protein high — bean/carb top-up allowed |

## Highest-value gaps (measure / look up before research)

### A. Tape — finish the frame set (15 min, AM preferred)
Do **post-void, relaxed, inches only**, same session:

| Priority | Site | How |
|----------|------|-----|
| **P0** | **Navel waist** | Clean AM redo — becomes official SoT |
| **P0** | **Neck** | Narrowest below larynx (apnea + McCallum) |
| **P1** | **Hips** | Widest glute/hip |
| **P1** | **Flexed upper arm** | Peak biceps, both sides if asymmetric |
| **P1** | **Calf** | Widest |
| **P2** | **Shoulders** | Widest delts (stocky look) |
| **P2** | **Ankle** | Smallest above malleoli (frame check w/ wrist) |
| **P2** | **Forearm** | Peak flexed |
| **P2** | Which thigh / chest landmark | L vs R thigh; confirm nipple-line chest |

### B. Photos (huge for research quality)
Same light, same distance, morning, underwear/rashguard:
- Front / side / rear
- Optional: chest close-up (soft tissue vs firm sub-nipple button note)

### C. Strength history (myonuclear / load realism)
| Need | Example |
|------|---------|
| Layoff length | ~how many months off hard BJJ / lifting before Nov 9 |
| Best prior working sets | Trap-bar / DL, squat/goblet, incline or bench, row, OHP, pulldown — load × reps @ rough RPE |
| Current EOS loads | Whatever you used Lift A / orientation |
| Injuries beyond sciatica | Shoulders, knees, neck, fingers, prior surgeries |

### D. Cardio / mats
| Need | Why |
|------|-----|
| Typical hard-GB rounds × RPE | EAT estimate |
| Resting HR + hard-session peak (if Polar/watch ever used) | Conditioning baseline |
| Zone 2 comfort pace | Bike/walk HR 125–138 feasible? |

### E. Labs / medical (Kaiser portal if available — don’t invent)
Paste dates + values if you have them; else list “unknown”:
- **Lipids** (LDL/HDL/TG), **A1c / fasting glucose**, **CMP** (liver/kidney)
- **CBC**, **TSH**, **Vitamin D**, **B12/ferritin** if ever drawn
- **Total / free testosterone**, estradiol — only if already tested
- Sleep study: **AHI**, mild/mod/severe, date; any oral appliance trial
- BP (home or clinic)
- True gyno eval? firm button under nipple Y/N

### F. Nutrition behavior (for binge-aware macros)
| Need | Why |
|------|-----|
| 3–5 Lose It day exports (already have pattern) | Confirms chronic under-eating vs binge nights |
| Alcohol frequency | kcal + sleep |
| Late-night binge foods / triggers | Anxiety, phone, boredom |
| GI: beans/psyllium/whey tolerance | Fiber ceiling |
| Food allergies / religious / household constraints | Wife’s foods vs athlete |

### G. Schedule constraints (already mostly known — confirm)
- Exact teach hours per week (mat feet time)
- Travel: Indonesia (+ Philippines?) dates / weeks away from gym
- How many nights you can protect ≤12:00 AM lights-out

## Prompt framing for Gemini (suggested)

Ask it to produce a **grappler recomp plan** that:
1. Uses **navel waist + central adiposity** as primary progress metrics (not BMI → 150 lb).
2. Recalculates fat-loss runway from **~40–41" waist / ~30% BF direction**, not 36" / 26%.
3. Keeps **binge prevention** as the nutrition constraint (front-load protein; avoid aggressive deficits).
4. Respects **apnea without CPAP**, sertraline timing, sciatica lift substitutions, **2× lift MED**, GB ≥2×, teach load.
5. Separates **Tier A vs Tier B** outcomes for 21 weeks vs maintenance fill.
6. Does **not** prescribe Rx, surgery, or CPAP — flag Kaiser items only.
7. Outputs: revised kcal/protein bands, weekly rate of loss, waist milestones, S&C periodization check, and what to measure monthly.

## After research
Drop the Gemini report into `archive/research/` and tell the Athlete-OS agent to diff it against `athlete/profile.md` + `nutrition/phases.csv` + `strength/lifts.md` before changing Gates.
