# MM Scan Shadow Snapshot
Generated: 2026-07-24T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 4.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-23T22:41:17+0000 (#555 MUUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-23T00:00:01Z → 2026-07-24T00:00:01Z)
- New signals: 20 (LONG 9 / SHORT 11)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 20
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 4.1h, restarts: 12064
- Last closer: 2026-07-23T03:00:13Z
- Last backfill: 2026-07-23T23:30:02Z
- Anomalies: listener рестартов: 12064

## Health 7d (window: 2026-07-17T00:00:01Z → 2026-07-24T00:00:01Z)
- New signals: 72 (~10.3/day)
- Closed: 52 (TP 31, SL 8, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 20
- TP rate 7d: 79.5%
- Listener uptime 7d: 2.4% (continuous since unit start)

## Shadow Journal Live
- Total signals: 555
- Closed: 535 (TP_clean 274, SL_clean 184, SL→reverse 0, Sideways 77, N/A 0)
- Ongoing (<24h): 20
- TP rate: 59.8% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 555 | 24.07 | 01:41 | MUUSDT | LONG | ongoing | осторожно 62% |
| 554 | 24.07 | 01:06 | COINUSDT | SHORT | ongoing | осторожно 70% |
| 553 | 24.07 | 00:38 | HYPEUSDT | SHORT | ongoing | осторожно 61% |
| 552 | 24.07 | 00:31 | BANKUSDT | LONG | ongoing | осторожно 65% |
| 551 | 23.07 | 23:33 | LITUSDT | SHORT | ongoing | осторожно 62% |
| 550 | 23.07 | 23:31 | LAUSDT | LONG | ongoing | осторожно 62% |
| 549 | 22.07 | 22:04 | SMCIUSDT | LONG | TP_clean | осторожно 74% |
| 548 | 23.07 | 03:08 | XMRUSDT | LONG | ongoing | осторожно 66% |
| 547 | 23.07 | 03:09 | MONUSDT | SHORT | ongoing | осторожно 61% |
| 546 | 23.07 | 09:05 | MONUSDT | SHORT | ongoing | осторожно 78% |
| 545 | 23.07 | 10:11 | MORPHOUSDT | SHORT | ongoing | осторожно 62% |
| 544 | 23.07 | 10:34 | VVVUSDT | SHORT | ongoing | осторожно 73% |
| 543 | 23.07 | 11:30 | ZKCUSDT | LONG | ongoing | осторожно 61% |
| 542 | 23.07 | 14:07 | BARDUSDT | LONG | ongoing | осторожно 65% |
| 541 | 23.07 | 16:06 | TLMUSDT | SHORT | ongoing | осторожно 65% |
| 540 | 23.07 | 18:11 | PENDLEUSDT | SHORT | ongoing | осторожно 79% |
| 539 | 23.07 | 19:11 | SPCXUSDT | SHORT | ongoing | осторожно 60% |
| 538 | 23.07 | 20:11 | COINUSDT | SHORT | ongoing | осторожно 60% |
| 537 | 23.07 | 20:38 | SNDKUSDT | LONG | ongoing | осторожно 66% |
| 536 | 23.07 | 21:07 | MUUUSDT | LONG | ongoing | осторожно 65% |
| 535 | 23.07 | 21:32 | KAITOUSDT | LONG | ongoing | осторожно 73% |
| 534 | 22.07 | 16:36 | MUUUSDT | LONG | TP_clean | осторожно 64% |
| 533 | 22.07 | 16:34 | LITEUSDT | LONG | TP_clean | осторожно 90% |
| 532 | 22.07 | 13:32 | SOXSUSDT | SHORT | SL_clean | осторожно 62% |
| 531 | 22.07 | 13:31 | TLMUSDT | SHORT | TP_clean | осторожно 66% |
| 530 | 22.07 | 12:07 | OPUSDT | SHORT | Sideways | осторожно 68% |
| 529 | 22.07 | 09:31 | SLXUSDT | LONG | TP_clean | осторожно 61% |
| 528 | 22.07 | 09:04 | MIRAUSDT | LONG | TP_clean | осторожно 72% |
| 527 | 22.07 | 08:09 | NIGHTUSDT | SHORT | TP_clean | осторожно 65% |
| 526 | 22.07 | 00:33 | XPLUSDT | LONG | Sideways | осторожно 67% |
| 525 | 21.07 | 21:35 | SNDKUSDT | LONG | TP_clean | осторожно 69% |
| 524 | 21.07 | 19:08 | KERNELUSDT | LONG | Sideways | осторожно 79% |
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
| 507 | 21.07 | 06:34 | SKHYUSDT | LONG | TP_clean | осторожно 74% |
| 506 | 21.07 | 09:04 | 1000BONKUSDT | LONG | SL_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-24 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-24 00:30 UTC
- mmscan-snapshot: next run 2026-07-24 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
