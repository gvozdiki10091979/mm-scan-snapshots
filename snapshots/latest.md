# MM Scan Shadow Snapshot
Generated: 2026-07-24T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 16.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-24T11:06:59+0000 (#563 EWYUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-23T12:00:01Z → 2026-07-24T12:00:01Z)
- New signals: 21 (LONG 12 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 21
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 16.1h, restarts: 12064
- Last closer: 2026-07-24T03:00:08Z
- Last backfill: 2026-07-24T11:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 5

## Health 7d (window: 2026-07-17T12:00:01Z → 2026-07-24T12:00:01Z)
- New signals: 69 (~9.9/day)
- Closed: 43 (TP 25, SL 6, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 26
- TP rate 7d: 80.6%
- Listener uptime 7d: 9.6% (continuous since unit start)

## Shadow Journal Live
- Total signals: 563
- Closed: 537 (TP_clean 275, SL_clean 184, SL→reverse 0, Sideways 78, N/A 0)
- Ongoing (<24h): 26
- TP rate: 59.9% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 563 | 24.07 | 14:06 | EWYUSDT | LONG | ongoing | осторожно 69% |
| 562 | 24.07 | 13:37 | ERAUSDT | SHORT | ongoing | осторожно 60% |
| 561 | 24.07 | 13:31 | VANRYUSDT | LONG | ongoing | осторожно 73% |
| 560 | 24.07 | 11:02 | EWYUSDT | SHORT | ongoing | осторожно 66% |
| 559 | 24.07 | 10:31 | MUUUSDT | LONG | ongoing | осторожно 65% |
| 558 | 24.07 | 09:37 | OPUSDT | LONG | ongoing | осторожно 60% |
| 557 | 24.07 | 08:11 | CBRSUSDT | LONG | ongoing | осторожно 88% |
| 556 | 24.07 | 05:03 | HOMEUSDT | LONG | ongoing | осторожно 61% |
| 555 | 24.07 | 01:41 | MUUSDT | LONG | ongoing | осторожно 62% |
| 554 | 24.07 | 01:06 | COINUSDT | SHORT | ongoing | осторожно 70% |
| 553 | 24.07 | 00:38 | HYPEUSDT | SHORT | ongoing | осторожно 61% |
| 552 | 24.07 | 00:31 | BANKUSDT | LONG | ongoing | осторожно 65% |
| 551 | 23.07 | 23:33 | LITUSDT | SHORT | ongoing | осторожно 62% |
| 550 | 23.07 | 23:31 | LAUSDT | LONG | ongoing | осторожно 62% |
| 549 | 22.07 | 22:04 | SMCIUSDT | LONG | TP_clean | осторожно 74% |
| 548 | 23.07 | 03:08 | XMRUSDT | LONG | Sideways | осторожно 66% |
| 547 | 23.07 | 03:09 | MONUSDT | SHORT | TP_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-07-25 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-24 12:30 UTC
- mmscan-snapshot: next run 2026-07-24 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
