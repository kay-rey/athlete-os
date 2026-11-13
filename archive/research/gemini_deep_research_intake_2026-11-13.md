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
| Navel waist | **41.0" Phase SoT baseline** (locked 2026-11-13; no prior tape ≥1 yr; old 36" retired) |
| Chest (nipple-line) | chat 41.6 → **41 6/8" (41.75")** |
| Thigh | R chat 22.3 → **22 3/8"** · L 20.6 → **20 6/8"** (right primary) |
| Neck | chat 15.2 → **15 2/8" (15.25")** |
| Calf | **15"** |
| Flexed arm | R chat 13.5 → **13 5/8"** |
| Ankle | L chat 9.1 → **9 1/8"** above malleolus |
| Hips | chat 40.1 → **40 1/8"** horizontal fullest glute (ideal ~37.3") |
| Waistband | chat 38.4 → **38 4/8"** (pants fit only — not SoT) |
| Wrist | chat 6.6 → **6 6/8" (6.75")** medium; McCallum waist ideal **~30.7"** |
| Tape scale | Inches = **8 ticks/inch**; chat `N.k` means **k eighths**, not tenths |
| Fat pattern | Android — belly + soft chest / “man boobs” |
| Current plan kcal | **2,250** · P **180–195** · C ~215 · F ~72 · fiber 45–50 |
| Failure mode | **Binge / overeating** (not under-protein); Gates front-load ≥100P by 5 PM |
| Training | Lift A Tue / Lift B Fri ≤48 min; GB hard 2×; teach Flow; Fri = Lift B only (no BJJ stack) |
| Rx / clinical | Sertraline 75 mg @ 3 PM; allergy med QHS; **diagnosed sleep apnea, no CPAP**; intermittent sciatica; GAD / panic; flight anxiety (Indonesia trip late Jan) |
| Sleep ops | Wife drop-off Tue–Sat ~7:40; biphasic second sleep most days; Wed straight to Flow 9 AM |
| Week-1 adherence | Often **400–700 kcal under** target while protein high — bean/carb top-up allowed |

## Apple Health export — what to feed Gemini (analyzed 2026-11-13 local)

Source: `/Users/kayrey/Downloads/apple_health_export/export.xml` + derived `journal/imports/apple_health/*` + briefing `journal/entries/2026-11-06-apple-health-briefing.md`. **Do not upload the raw 2.5 GB export to Gemini.**

### USE in the research prompt (high signal)
| Fact | Why it matters |
|------|----------------|
| Weight path: yearly means ~**162 (2024) → 178 (2025) → 187 (2026)**; lifetime low **~142 lb (Nov 2022)**; peak **~196 lb (Apr 2026)**; last Withings sync **183.7 lb / ~28% BF (2026-06-04)**; then drift to Phase **189.7 → 186.7** | Proves long recomp history + recent soft regain; timeline realism |
| BF% era shift: **~20% (2022–24) → ~26% (2025) → ~29% (2026)**; live Withings **29.8% (Nov 13)** | Aligns with **41" navel**, not old 26%/36" model |
| Health waist last **33" (Oct 2022)** vs live **41.0"** | Old Health waist is stale; ignore for SoT |
| Steps/NEAT collapse: **~7.9k/day (2024) → ~3.2k (2025) → ~2.7k (2026)** | Old TDEE assumed high NEAT — **uncertain**; judge by waist, **no step goals** |
| Training history in Health: **2024** heavy (**110** martial_arts ≈ **10.7k min**, plus cycling/strength); **2025** trickle; **2026 workouts = 0** in Health | Layoff / logging gap — myonuclear rebound plausible; mat SoT is `mats.csv` not Health |
| Last Garmin martial_arts in Health: **2025-02-21**; strength/walks to **2025-05-09** | Garmin archive still useful for HR/sleep after that |
| 2026 Lose It→Health nutrition: only **13 days**; mean ~**2374 kcal / 222P**; **10/13 ≥180P**; range **900–3297 kcal** | Can hit protein; also binge/under-eat extremes — supports Gate architecture |
| Sources present: **Withings, Connect (Garmin), Apple Watch, WHOOP, Lose It!** | Multi-device history; WHOOP/Connect HR may exist in raw XML even if not in derived CSVs yet |
| Sparse vitals: RHR ~**46** bpm mean in 2024 athletic era; BP sample ~**122/59** (2024); sleep records collapse after 2024 | Directional only — don’t overfit sleep from this export |

### DO NOT treat as Phase SoT / ignore for macros
- Daily steps as a target  
- Health workout calendar for 2026 BJJ/teach  
- Sparse Health dietary days as compliance  
- Old Health waist **33"** or estimated **36"**  
- Raw HeartRate (1.1M+ samples) dumped into Gemini — summarize only if needed  
- Committing/uploading `export.xml`

## Garmin Connect export — what to feed Gemini (parsed 2026-11-13 local)

Source: `/Users/kayrey/Downloads/725c71ea-bb56-4fd2-a2fb-9daf38fd927b_1` → derived `journal/imports/garmin/*` + `journal/entries/2026-11-13-garmin-briefing.md`. **Do not upload the raw GDPR dump.**

### USE in the research prompt (high signal)
| Fact | Why it matters |
|------|----------------|
| **588** activities **2022-11-17 → 2025-05-25**; MMA **163 / ~15.3k min**; **2024 = 110 / 10,678 min = Health martial_arts** | Confirmed high EAT year; identical dual-device proof |
| Strength **89** sessions; Apr 2023 benchmarks (squat 180×10, DL 165×8, bench 135×3, OHP 60×10, row 80×10) | Prior strength floor for recomp realism |
| Heavy cycling era (241 road_biking) | Extra EAT in 2023–24 beyond mats |
| Activity cliff May 2025; **no 2026 Garmin activities** | Layoff/logging gap into Phase |
| UDS RHR ~47→46→50; BB high ~83–89; stress ~25–27 | Conditioning / recovery history when worn |
| Sleep stages ~7.5 h mean through **~2025-05**; then thin | Fills Health sleep gap for 2023–early 2025 |
| Garmin weights mostly MFP; last ~176.5 lb (Aug 2025) | **Do not override** Withings / anthro |

### Still better from athlete dump (not in devices)
Current EOS loads, apnea AHI, Indonesia dates, binge foods, photos.

## Highest-value gaps (measure / look up before research)

### A. Tape — finish the frame set (15 min, AM preferred)
Do **post-void, relaxed, inches only**, same session:

| Priority | Site | How |
|----------|------|-----|
| Done | **Navel waist** | **41.0" locked** — future tapes for trend |
| Done | **Neck / hips / arm / calf / ankle / thighs** | Logged 2026-11-13 (see table above) |
| **P2** | **Shoulders / forearm** | Optional |
| **P2** | Chest landmark | Confirm nipple-line |

### B. Photos (huge for research quality)
Same light, same distance, morning, underwear/rashguard:
- Front / side / rear
- Optional: chest close-up (soft tissue vs firm sub-nipple button note)

### C. Strength history (myonuclear / load realism)
| Need | Example |
|------|---------|
| Layoff length | Devices silent after May 2025 — confirm months off hard BJJ before Nov 9 |
| Prior working sets | **Garmin 2023 benchmarks logged** — still want trap-bar / incline / current EOS |
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
