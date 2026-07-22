# MM Scan Shadow Snapshot
Generated: 2026-07-22T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3459619
- Uptime: 23.7h (active since Tue 2026-07-21 12:17:35 UTC)
- Last signal: 2026-07-22T10:32:53+0000 (#532 SOXSUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 9135

## Health 24h (window: 2026-07-21T12:00:01Z → 2026-07-22T12:00:01Z)
- New signals: 9 (LONG 5 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 23.7h, restarts: 9135
- Last closer: 2026-07-22T03:00:07Z
- Last backfill: 2026-07-22T11:30:02Z
- Anomalies: listener рестартов: 9135; ongoing >24h без закрытия: 3

## Health 7d (window: 2026-07-15T12:00:01Z → 2026-07-22T12:00:01Z)
- New signals: 67 (~9.6/day)
- Closed: 55 (TP 36, SL 10, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 12
- TP rate 7d: 78.3%
- Listener uptime 7d: 14.1% (continuous since unit start)

## Shadow Journal Live
- Total signals: 532
- Closed: 520 (TP_clean 265, SL_clean 182, SL→reverse 0, Sideways 73, N/A 0)
- Ongoing (<24h): 12
- TP rate: 59.3% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

## Shadow Journal FULL (historical 12.05–12.06)
- Total: 761
- Closed: 755 (ongoing 6, N/A 14)
- TP rate: 54.1% pointwise (excl N/A) · 58.8% decided (TP/(TP+SL))
- Segment A (pre-v4, <19.05): n=410, decided TP rate 55.4%
- Segment B (v4, ≥19.05): n=351, decided TP rate 62.5%

## Pre-reg вердикты (frozen, manually maintained, last 2026-06-12; validated 99.2% shadow)
- H016a: 🟢 ПОДТВЕРЖДЕНА (N=20, точечная 83%)
- H016b: 🔴 ОПРОВЕРГНУТА (N=20, 33%)
- H016c: 🟡 НЕОПРЕДЕЛЁННО + 🔴 АРХИТЕКТУРНО (N=14, 50%)
- milestone_N300: 🟡 ПОГРАНИЧНЫЙ (60.2% v17_13)

## Active H016a context (architect, frozen)
- TRUE кейсов: 14/15
- Точечная SL_clean rate: 42.9%

## Last 50 signals (live)
| # | Date | Time | Ticker | Side | Финал | Conf |
|---|------|------|--------|------|-------|------|
| 532 | 22.07 | 13:32 | SOXSUSDT | SHORT | ongoing | осторожно 62% |
| 531 | 22.07 | 13:31 | TLMUSDT | SHORT | ongoing | осторожно 66% |
| 530 | 22.07 | 12:07 | OPUSDT | SHORT | ongoing | осторожно 68% |
| 529 | 22.07 | 09:31 | SLXUSDT | LONG | ongoing | осторожно 61% |
| 528 | 22.07 | 09:04 | MIRAUSDT | LONG | ongoing | осторожно 72% |
| 527 | 22.07 | 08:09 | NIGHTUSDT | SHORT | ongoing | осторожно 65% |
| 526 | 22.07 | 00:33 | XPLUSDT | LONG | ongoing | осторожно 67% |
| 525 | 21.07 | 21:35 | SNDKUSDT | LONG | ongoing | осторожно 69% |
| 524 | 21.07 | 19:08 | KERNELUSDT | LONG | ongoing | осторожно 79% |
| 523 | 18.07 | 10:05 | LITUSDT | SHORT | TP_clean | осторожно 83% |
| 522 | 18.07 | 18:07 | SAMSUNGUSDT | SHORT | Sideways | осторожно 62% |
| 521 | 18.07 | 18:34 | ENAUSDT | SHORT | Sideways | осторожно 63% |
| 520 | 18.07 | 19:05 | DEXEUSDT | LONG | SL_clean | осторожно 64% |
| 519 | 19.07 | 02:03 | XPLUSDT | SHORT | TP_clean | осторожно 62% |
| 518 | 19.07 | 11:03 | QTUMUSDT | LONG | TP_clean | осторожно 71% |
| 517 | 19.07 | 13:33 | FWDIUSDT | LONG | TP_clean | осторожно 65% |
| 516 | 19.07 | 18:02 | LUMIAUSDT | SHORT | SL_clean | осторожно 63% |
| 515 | 19.07 | 19:03 | KORUUSDT | SHORT | SL_clean | осторожно 75% |
| 514 | 19.07 | 23:38 | ORDIUSDT | SHORT | TP_clean | осторожно 65% |
| 513 | 20.07 | 00:35 | ATHUSDT | LONG | TP_clean | осторожно 60% |
| 512 | 20.07 | 02:01 | VANRYUSDT | SHORT | TP_clean | осторожно 60% |
| 511 | 20.07 | 06:01 | SNXXUSDT | LONG | TP_clean | осторожно 62% |
| 510 | 20.07 | 06:04 | ACEUSDT | LONG | SL_clean | осторожно 61% |
| 509 | 20.07 | 13:35 | SAMSUNGUSDT | LONG | TP_clean | осторожно 60% |
| 508 | 20.07 | 21:39 | BILLUSDT | SHORT | TP_clean | осторожно 73% |
| 507 | 21.07 | 06:34 | SKHYUSDT | LONG | ongoing | осторожно 74% |
| 506 | 21.07 | 09:04 | 1000BONKUSDT | LONG | ongoing | осторожно 64% |
| 505 | 21.07 | 11:02 | KERNELUSDT | LONG | ongoing | осторожно 73% |
| 504 | 18.07 | 07:08 | KITEUSDT | SHORT | TP_clean | осторожно 60% |
| 503 | 18.07 | 07:04 | MVLLUSDT | SHORT | Sideways | осторожно 62% |
| 502 | 18.07 | 06:40 | METAUSDT | SHORT | Sideways | осторожно 62% |
| 501 | 18.07 | 06:34 | KORUUSDT | SHORT | TP_clean | осторожно 63% |
| 500 | 18.07 | 06:02 | CHZUSDT | SHORT | Sideways | осторожно 68% |
| 499 | 18.07 | 02:38 | TUSDT | LONG | TP_clean | осторожно 61% |
| 498 | 18.07 | 01:06 | MVLLUSDT | SHORT | Sideways | осторожно 66% |
| 497 | 17.07 | 22:33 | REUSDT | SHORT | TP_clean | осторожно 66% |
| 496 | 17.07 | 22:32 | KORUUSDT | SHORT | TP_clean | осторожно 77% |
| 495 | 17.07 | 22:04 | MUUSDT | LONG | Sideways | осторожно 60% |
| 494 | 17.07 | 14:08 | AAVEUSDT | SHORT | TP_clean | осторожно 74% |
| 493 | 17.07 | 14:07 | CBRSUSDT | SHORT | TP_clean | осторожно 66% |
| 492 | 17.07 | 13:38 | SKLUSDT | SHORT | TP_clean | осторожно 72% |
| 491 | 17.07 | 12:32 | SENTUSDT | LONG | TP_clean | осторожно 60% |
| 490 | 17.07 | 11:37 | XRPUSDT | SHORT | Sideways | осторожно 74% |
| 489 | 17.07 | 11:10 | ZECUSDT | SHORT | SL_clean | осторожно 69% |
| 488 | 17.07 | 11:09 | UNIUSDT | SHORT | Sideways | осторожно 61% |
| 487 | 17.07 | 07:31 | VELVETUSDT | LONG | TP_clean | осторожно 69% |
| 486 | 17.07 | 06:38 | KATUSDT | SHORT | TP_clean | осторожно 62% |
| 485 | 17.07 | 06:32 | AGLDUSDT | SHORT | SL_clean | осторожно 61% |
| 484 | 17.07 | 06:10 | ARMUSDT | SHORT | TP_clean | осторожно 69% |
| 483 | 17.07 | 01:07 | ARMUSDT | SHORT | TP_clean | осторожно 77% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-22 12:30 UTC
- mmscan-snapshot: next run 2026-07-22 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
