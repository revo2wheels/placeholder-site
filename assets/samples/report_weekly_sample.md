Load Pressure — recovery_priority

📊 REPORT CONTEXT
- framework: V5.1 Unified Reporting Framework
- version: v16.17
- generated_at (local): 2026-04-01T12:48:13+02:00
- timezone: Europe/Zurich
- athlete.id: 1234567
- athlete.name: Demo Athlete
- athlete.sex / dob / location: M / 1975-01-01 / Zurich, Switzerland
- primary_sport: ride
- ftp: 300 W | lthr: 157 bpm | max_hr: 177 bpm
- report_type: weekly
- window_days: 7
- period: 2026-03-25 → 2026-03-31
- report_header.title: Weekly Training Report
- report_header.scope: Detailed analysis of the last 7 days of training activity
- report_header.data_sources: 7-day full activities, 42-day wellness, 90 day light activities
- intended_use: Day-to-day coaching decisions, intensity balance, short-term fatigue and recovery management

Coaching
- State banner: Training is in "Load Pressure" with operational state = recovery_priority. Prioritise stabilising load and recovery before reloading.

🧭 TRAINING LOAD

Training volume
- Hours | TSS | Distance: 12.97 h | 721 TSS | 326.6 km

Key weekly metrics (condensed)
| Metric | Value |
|---|---:|
| ACWR | 0.97 |
| Strain | 576.8 |
| FatigueTrend (%) | 31.9 |
| ZQI (%) | 7.5 |
| Polarisation (power) | 1.076 |
| PolarisationIndex | 2.188 |
| Monotony | 0.8 |
| FOxI (%) | 63.4 |
| CUR (%) | 36.6 |
| GR | 1.69 |
| MES | 22.5 |
| StressTolerance | 1.15 |

Coaching (≤5)
- ACWR ≈ 0.97 → productive weekly load but not excessive; monitor FatigueTrend.
- FatigueTrend = 31.9% indicates accumulating fatigue — favour recovery/stabilisation.
- PolarisationIndex and ZQI are within green → maintain contrast (low + targeted high intensity).
- Metabolic scores (FOxI, MES) support continued aerobic emphasis.

Daily load (fixed-width timeline)
```
Date       │ █ timeline ── blocks ── │ TSS
2026-03-25 │ ▂▂▂▂▂▂▂▂▂▂           │  75
2026-03-26 │ (no data)             │   0
2026-03-27 │ ▂▂▂▂▂▂▂▂▂▂▂         │  79
2026-03-28 │ ▂▂▂▂▂▂▂▂▂▂▂▂▂      │  92
2026-03-29 │ ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇│ 385
2026-03-30 │ ▂▂                 │  26
2026-03-31 │ ▂▂▂▂▂▂▂▂         │  64
Fatigue    │ ↑  (sign(ATL−CTL) positive → accumulating acute load)
```
(Coaching) The big spike on 2026-03-29 drove most weekly fatigue; plan for low-load recovery before reintroducing intensity.

Events
| Date | Activity | Duration (min) | Distance (km) | TSS | IF | NP | HRR60 |
|---|---|---:|---:|---:|---:|---:|---:|
| 2026-03-31 | ⚡🔁❤️ [Indoor Ride] | 61 | 39.6 | 61 4️⃣🙂 | 0.78 | 233 | 28 |
| 2026-03-31 | ⚡ [Indoor Ride] | 10.0 | 5.4 | 3 | 0.44 | 133 |  |
| 2026-03-30 | ⚡🧘 [recovery 45m] | 47 | 28.3 | 26 | 0.58 | 174 |  |
| 2026-03-29 | 🔁 [Dog walk] | 67 | 5.8 | 44 | 0.62 |  |  |
| 2026-03-29 | ⚡ [Basecamp 5365m] | 370 | 131.1 | 341 6️⃣🙂 | 0.74 | 223 |  |
| 2026-03-28 | ⚡🔁 [Snow Ride] | 99 | 45.2 | 92 6️⃣🙂 | 0.74 | 223 |  |
| 2026-03-27 | ⚡ [Indoor Ride] | 63 | 40.9 | 79 6️⃣😐 | 0.87 | 261 | 20 |
| 2026-03-25 | ⚡ [Indoor Ride - VO2 Max 5x3min] | 61 | 30.2 | 75 6️⃣😐 | 0.86 | 258 | 28 |

Legend: ⚡ Efficient | 🟢 Aerobic | 💥 Anaerobic | 🔁 Repeated | 📈 Progressive | 🧘 Recovery | ❤️ HRR60

Coaching
- Events show clustered high-load rides (notably 29 Mar Basecamp) → explains weekly fatigue accumulation.
- Keep 1–2 low-intensity days after heavy long rides for recovery.

🫀 PHYSIOLOGY RESPONSE

Wellness (summary)
| Metric | Value |
|---|---:|
| HRV ratio | 1.05 |
| Resting HR | 42 bpm (wellness.rest_hr 42) |
| HRV mean / latest | 52.6 / 55 |
| HRV trend 7d | +1.7 |
| CTL / ATL / TSB | 89.48 / 100.34 / -10.86 |

Subjective (aggregated): fatigue 2.1 (avg) | stress 1.9 | soreness 2.0 | mood 2.7 | motivation 2.9

Coaching
- HRV stable-to-up slightly (+1.7 over 7d) despite negative TSB; autonomic signals permit conservative training but prioritise recovery.
- Subjective scores are near average — align objective recovery with perceived recovery (keep easy sessions).

Insight view (summary)
- Positive: fat_oxidation_index — classification: green (continue low-intensity work to enhance fat metabolism).

⚙️ PERFORMANCE INTELLIGENCE

SYSTEM STATE
| Operational state | State label | ATL | CTL | TSB |
|---|---|---:|---:|---:|
| recovery_priority | Load Pressure | 100.33614 | 89.47856 | -10.85758 |

Coaching
- Operational state = recovery_priority; stabilise load and prioritise recovery sessions next.

LOAD SIGNATURE — WDRM (anaerobic)
| Metric | Value |
|---|---:|
| Max W′ Depletion (7d) | 0.7925035126869989 (high) |
| Mean W′ Depletion (7d) | 0.25881123587545607 (moderate) |
| Moderate depletion sessions (7d) | 2 |
| High depletion sessions (7d) | 2 |
| Total work above FTP (7d, J) | 112009 |

LOAD SIGNATURE — ISDM (durability)
| Metric | Value |
|---|---:|
| Mean decoupling (HR–Power %) | 9.051464414285714 (high) |
| Max decoupling (%) | 21.18352 (high) |
| High drift sessions (7d) | 5 |
| Long endurance sessions (7d) | 1 |

LOAD SIGNATURE — NDLI (neural density)
| Metric | Value |
|---|---:|
| Rolling work above FTP (7d, J) | 112009 |
| High-intensity days (7d) | 3 (amber) |
| Mean IF (7d) | 0.70499 |
| Mean efficiency factor (7d) | 1.81539 |
| Mean variability index (7d) | 1.09381 |

Nutrition (flag)
- classification: severely_underfuelled (rolling_3d). Signals: carbs_actual 85 g vs required 437 g → carbs_delta -352 g.

Coaching
- High Max W′ depletion + high drift sessions → neuromuscular + metabolic overlap (note: high_dep_sessions>0 AND high_drift_sessions>0).
- Severe carbohydrate shortfall likely limiting recovery and adaptation — immediate fuelling focus required.

wbal_summary
- mean_wbal_depletion_pct: 0.276
- mean_anaerobic_contrib_pct: 0.717
- sessions_with_wbal_data: 7
- window: weekly
- temporal pattern: 2026-03-25 ▇ · 2026-03-27 ▇ · 2026-03-28 ▃ · 2026-03-29 ▂ · 2026-03-30 ▂ · 2026-03-31 ▃  → (▂=low ▃=moderate ▇=high)
- dominant_pattern: distributed

Coaching
- Weekly W′ pattern is distributed with some deep depletion events early in the window — schedule easy aerobic consolidation sessions to recover W′ stores.

📈 ADAPTATION

Energy system progression — Ride (condensed)
Power anchors (best in last 85d)
- 5s: [826 W]
- 1m: [466 W]
- 5m: [333 W]
- 20m: [307 W]
- 60m: [288 W]

System status (key systems)
| System | Status |
|---|---|
| Aerobic durability | strong_gain |
| Threshold | moderate_gain |
| VO2 | decline |
| Anaerobic | decline |
| Adaptation state | aerobic_consolidation |

Derived indicators (selection)
| Metric | Value |
|---|---:|
| glycolytic_bias_ratio | 1.52 |
| aerobic_durability_ratio | 0.86 |
| durability_gradient | 0.94 |
| system_balance_score | 0.84 |
| vo2_reserve_ratio | 1.133 |

Coaching
- Energy model: aerobic and threshold building while VO2 and anaerobic capacity show short-term drift — reintroduce controlled VO2 stimulus after recovery.
- Use power anchors to guide targeted VO2 efforts (5m & 20m zones) once W′ and fuelling are stabilised.

Physiology — Lactate calibration (compact)
| Field | Value |
|---|---:|
| lactate.samples | 38 |
| lactate.mean_mmol | 1.92 |
| lactate.latest_mmol | 1.8 |
| power_spread_w | [170, 195] |
| personalized_z2 (W) | start 210 — end 225 |
| LT1 (inferred) | 210 W |
| LT2 (inferred) | 300 W |
| confidence_r | 0.977 |

Coaching
- LT1 ≈ 210 W (Z2 start) — use 210–225 W for steady aerobic consolidation rides.

Phases (summary — recent, max 4 rows)
| Phase | Duration | Trend |
|---|---:|---|
| Deload (2026-03-16 → 2026-03-22) | 7 d | controlled reduction in load |
| Build (2026-03-23 → 2026-03-29) | 7 d | progressive overload active |
| Taper (2026-03-30 → 2026-04-05) | 7 d (projected) | reduce ATL ~30–50% while maintaining intensity |
| (prior) Build (2026-02-16 → 2026-03-15) | 28 d | progressive overload block |

Coaching
- Phase alignment indicates a Build → Taper transition; given current load_pressure, respect taper/delayed reloading and ensure fuelling during taper.

🎯 ADAPTIVE DECISIONS

STATE SNAPSHOT
| ADE directive | State | Resolution | Load trend |
|---|---|---|---:|
| Stabilise load and prioritise recovery | Load Pressure | honoured | declining |

ADAPTATION RESPONSE
| adaptation_focus | key_constraint | next_action | dominant_signal |
|---|---|---|---|
| aerobic_consolidation | severely_underfuelled (carbs deficit) | Endurance or recovery session | load_pressure / recovery_priority |

OPERATIONS
| week_delta | planned_load (current → next) | 14d forecast (CTL / TSB / fatigue_class) |
|---:|---:|---:|
| 396 (delta_to_target projected) | completed_tss 90 → projected_total_tss 420 | CTL 87.67 / TSB -2.12 / neutral |

TRAINING GUIDANCE
| Directive |
|---|
| Stabilise load and prioritise recovery |

PHASE ALIGNMENT
| Required Phase | Recent Load Alignment | Past Pattern | Phase Streak |
|---|---|---|---:|
| recovery | aligned | fatigue_streak | 6 |

FUTURE ACTIONS
| Priority | Action | Reason |
|---|---|---|
| normal | Neutral load (2026-04-01 → 2026-04-15) | Training stimulus and recovery are balanced. |

Coaching (adaptive)
- Primary directive: stabilise load and prioritise recovery; plan easy endurance or recovery sessions next.
- Address fuelling gap immediately (carbs) to permit W′ and VO2 restitution and to support aerobic consolidation.

Closing note
High Strain — Weekly load was productive by ACWR (0.97) but produced notable accumulation of fatigue (FatigueTrend 31.9%) and durability stress (mean decoupling 9.05%, max 21.18%). NDLI shows moderate neural clustering (3 high‑intensity days) while energy_system_progression indicates aerobic consolidation with VO2/anaerobic drift. Actions: stabilise load, prioritise recovery, and urgently close the carbohydrate fuelling gap to support adaptation.

---
Closing Reflection
Is the current recovery and fuelling plan sufficient to reverse the HR–power decoupling (durability decline) observed this week?

Suggested follow-up commands (copy/paste)
```
show full physiology_response
show full performance_intelligence
show full adaptation
show full adaptive_decisions
load planned events
show power curves
load athlete profiles
load last activity and analyse
show me more command questions
```