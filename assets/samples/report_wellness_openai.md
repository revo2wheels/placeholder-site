📊 REPORT CONTEXT

META
- Framework: V5.1 Unified Reporting Framework (PI_v1.4)
- Version: v16.17
- Methodology: Unified Coaching Reference (Intervals + Seiler + Banister + Treff) — Deterministic endurance coaching (load modelling, physiological response, performance intelligence, adaptive decision logic)
- Generated at: 2026-04-01T12:51:40+02:00 (Europe/Zurich)
- Athlete: Demo Athlete (ID 1234567) — M, born 1975-01-01, Zurich, Switzerland
- Primary sport: Ride (ftp 300 W; lthr 157; max_hr 177)
- Report: Wellness & Recovery Status — period 2026-02-18 → 2026-04-01 (42-day window)
- Data sources: 42-day wellness records (Intervals native)
- Intended use: Monitoring readiness, recovery balance and non-training stress

Coaching (meta)
- Athlete identity and test baselines confirmed; use FTP/LTHR as existing session anchors.
- Keep timezone and platform sync in mind when scheduling sessions.

🫀 PHYSIOLOGY RESPONSE

WELLNESS — STATE
| Metric | Value |
|---|---:|
| HRV (42d mean / latest) | 52.6 / 55 ms |
| HRV Stability (14d) | 0.819 (amber) |
| Resting HR (latest) | 40–44 bpm (reported latest 40; rest_hr_delta 0.1) |
| Sleep score (14d avg) | 84.6 (green) |
| Load context (CTL / ATL / TSB) | 89.48 / 100.34 / −10.86 |
| Recovery state | Load Pressure — operational_state: recovery_priority |

WELLNESS — SIGNALS
| Signal | Value | Qualitative |
|---|---:|---:|
| HRV latest vs 42d mean | 55 / 52.6 ms | green |
| HRV Stability (14d) | 0.819 | amber |
| Autonomic ratio (42d) | 1.046 | green |
| Resting HR delta (7d vs 28d) | 0.1 | green |
| Sleep quality (14d avg) | 84.6 | green |
| Mean Decoupling (7d, HR–Power) | 9.05 % | red |
| Max Decoupling (7d) | 21.18 % | red |
| Max W′ Depletion (7d) | 0.7925 | red |
| High-intensity days (7d) | 3 days | amber |
| Nutrition classification | severely_underfuelled | red |
| RecoveryMarkers — StressTolerance / Monotony / Strain | 1.15 / 0.8 / 576.8 | amber / green / amber |

Interpretation (≤3 bullets)
- Autonomic signals are generally preserved: HRV latest is slightly above the 42-day mean and Autonomic ratio is >1.0, indicating maintained autonomic balance despite load. HRV stability is amber, showing increased variability.
- Load shows accumulated pressure (CTL 89.5; ATL 100.3; TSB −10.9) with durability signals (mean/max decoupling) and high W′ depletion suggesting neuromuscular / anaerobic strain.
- Nutrition is a clear limiting signal (severely_underfuelled): carbohydrate shortfall markedly increases recovery demand and likely contributes to durability/fatigue markers.

Coaching (wellness)
- Prioritise consistent sleep timing and carbohydrate intake tonight and tomorrow to support glycogen resynthesis (carbs_actual 85 g vs required ~437 g).
- Prefer low-intensity endurance or recovery sessions while HRV stability remains amber and decoupling is elevated.
- Monitor HRV nightly and sleep score; if HRV falls below the 42‑day mean or TSB drops further, extend recovery emphasis.

⚙️ TRAINING STRESS CONTEXT

PERFORMANCE_INTELLIGENCE — LOAD CONTEXT
| Metric | Value | Signal |
|---|---:|---:|
| Max W′ Depletion (7d) | 0.7925 | red |
| Mean Decoupling (HR–Power, 7d) | 9.05 % | red |
| High Drift Sessions (7d) | 5 | amber |

Coaching (performance_intelligence)
- These load markers indicate clustered supra‑threshold exposure and durability strain — avoid stacking additional high-intensity sessions in the next 72 hours.
- Use steady aerobic sessions to rebuild durability and allow W′ repletion without further decoupling stress.

PERFORMANCE_INTELLIGENCE.NUTRITION
| Field | Value |
|---|---:|
| Framework | Fuel Availability (IOC / ACSM Sports Nutrition) |
| Interpretation | Carbohydrate availability determines glycogen replenishment and endurance capacity |
| Classification | severely_underfuelled |
| Confidence | moderate |
| Context window | rolling_3d |
| Signals: carbs_actual_g | 85 g |
| Signals: protein_actual_g | 90 g |
| Signals: fat_actual_g | 44 g |
| Required carbs_g | 437 g |
| Required protein_g | 117 g |
| Required fat_g | 73 g |
| Deltas: carbs_delta_g | −352 g |
| Deltas: protein_delta_g | −27 g |
| Deltas: fat_delta_g | −29 g |

Coaching (nutrition)
- Immediate action: raise carbohydrate intake toward the ~3–10 g/kg guidance for current load (target ~437 g/day per recent demand) to support recovery and W′ repletion.
- Consider a carbohydrate-forward meal within 2 hours post-session and distribute intake across the day over the next 48 hours.

Adaptation Under Pressure. HRV is slightly above the 42‑day mean (latest 55 vs mean 52.6) but HRV stability is amber (0.819), indicating increased night-to-night variability. CTL (89.48), ATL (100.34) and TSB (−10.86) show accumulated load pressure consistent with the “load_pressure” state. Autonomic_ratio 1.046 with resting_hr_delta 0.1 and sleep_score 84.6 suggests preserved autonomic balance despite physiological strain flagged by performance_intelligence. In plain language: your system is coping but stressed — prioritise sleep consistency, carbohydrate restoration, and low-intensity sessions over the next 48–72 hours.

---
Closing Reflection
How well did you meet your carbohydrate and sleep targets in the last 24–48 hours given the current training load?
```
show full physiology_response
show full training stress
show me more wellness command questions
```