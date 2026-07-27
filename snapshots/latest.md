# MM Scan Shadow Snapshot
Generated: 2026-07-27T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 82.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-26T22:32:33+0000 (#593 ACEUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-26T06:00:01Z → 2026-07-27T06:00:01Z)
- New signals: 8 (LONG 6 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 82.1h, restarts: 12064
- Last closer: 2026-07-27T03:00:17Z
- Last backfill: 2026-07-27T05:30:02Z
- Anomalies: listener рестартов: 12064

## Health 7d (window: 2026-07-20T06:00:01Z → 2026-07-27T06:00:01Z)
- New signals: 75 (~10.7/day)
- Closed: 67 (TP 34, SL 15, SL→rev 0, Sideways 18, N/A 0)
- Ongoing: 8
- TP rate 7d: 69.4%
- Listener uptime 7d: 48.9% (continuous since unit start)

## Shadow Journal Live
- Total signals: 593
- Closed: 585 (TP_clean 297, SL_clean 197, SL→reverse 0, Sideways 91, N/A 0)
- Ongoing (<24h): 8
- TP rate: 60.1% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 593 | 27.07 | 01:32 | ACEUSDT | SHORT | ongoing | осторожно 67% |
| 592 | 27.07 | 01:32 | ESPUSDT | LONG | ongoing | осторожно 61% |
| 591 | 27.07 | 01:03 | EULUSDT | LONG | ongoing | осторожно 67% |
| 590 | 26.07 | 22:31 | CROSSUSDT | LONG | ongoing | осторожно 63% |
| 589 | 26.07 | 20:01 | ESPUSDT | LONG | ongoing | осторожно 61% |
| 588 | 26.07 | 19:30 | AKEUSDT | LONG | ongoing | осторожно 61% |
| 587 | 26.07 | 17:00 | CROSSUSDT | LONG | ongoing | осторожно 67% |
| 586 | 26.07 | 12:35 | VELVETUSDT | SHORT | ongoing | осторожно 61% |
| 585 | 26.07 | 03:01 | ERAUSDT | SHORT | TP_clean | осторожно 62% |
| 584 | 25.07 | 23:38 | WLDUSDT | SHORT | TP_clean | осторожно 70% |
| 583 | 25.07 | 21:05 | LAUSDT | SHORT | SL_clean | осторожно 70% |
| 582 | 25.07 | 17:04 | BZUSDT | SHORT | TP_clean | осторожно 67% |
| 581 | 25.07 | 17:03 | CLUSDT | SHORT | Sideways | осторожно 66% |
| 580 | 25.07 | 09:37 | CRVUSDT | SHORT | Sideways | осторожно 62% |
| 579 | 25.07 | 08:37 | SKHYNIXUSDT | SHORT | SL_clean | осторожно 62% |
| 578 | 25.07 | 07:01 | TNSRUSDT | LONG | TP_clean | осторожно 73% |
| 577 | 25.07 | 03:12 | AAVEUSDT | SHORT | Sideways | осторожно 81% |
| 576 | 25.07 | 01:05 | GWEIUSDT | LONG | TP_clean | осторожно 68% |
| 575 | 25.07 | 00:35 | B2USDT | SHORT | TP_clean | входить 81% |
| 574 | 25.07 | 00:32 | ZBTUSDT | LONG | TP_clean | осторожно 63% |
| 573 | 24.07 | 22:02 | ERAUSDT | LONG | SL_clean | осторожно 67% |
| 572 | 24.07 | 21:03 | LITUSDT | SHORT | TP_clean | осторожно 73% |
| 571 | 24.07 | 20:42 | SOLUSDT | SHORT | Sideways | осторожно 64% |
| 570 | 24.07 | 19:41 | 1000PEPEUSDT | SHORT | Sideways | осторожно 63% |
| 569 | 24.07 | 19:37 | ORCLUSDT | SHORT | TP_clean | осторожно 62% |
| 568 | 24.07 | 18:32 | ARXUSDT | SHORT | TP_clean | осторожно 67% |
| 567 | 24.07 | 16:05 | DOTUSDT | SHORT | Sideways | осторожно 88% |
| 566 | 24.07 | 16:05 | ETCUSDT | SHORT | Sideways | осторожно 77% |
| 565 | 24.07 | 15:06 | AVAXUSDT | SHORT | Sideways | осторожно 62% |
| 564 | 24.07 | 15:05 | WIFUSDT | SHORT | Sideways | осторожно 62% |
| 563 | 24.07 | 14:06 | EWYUSDT | LONG | SL_clean | осторожно 69% |
| 562 | 24.07 | 13:37 | ERAUSDT | SHORT | SL_clean | осторожно 60% |
| 561 | 24.07 | 13:31 | VANRYUSDT | LONG | TP_clean | осторожно 73% |
| 560 | 24.07 | 11:02 | EWYUSDT | SHORT | TP_clean | осторожно 66% |
| 559 | 24.07 | 10:31 | MUUUSDT | LONG | SL_clean | осторожно 65% |
| 558 | 24.07 | 09:37 | OPUSDT | LONG | Sideways | осторожно 60% |
| 557 | 24.07 | 08:11 | CBRSUSDT | LONG | SL_clean | осторожно 88% |
| 556 | 24.07 | 05:03 | HOMEUSDT | LONG | TP_clean | осторожно 61% |
| 555 | 24.07 | 01:41 | MUUSDT | LONG | SL_clean | осторожно 62% |
| 554 | 24.07 | 01:06 | COINUSDT | SHORT | TP_clean | осторожно 70% |
| 553 | 24.07 | 00:38 | HYPEUSDT | SHORT | Sideways | осторожно 61% |
| 552 | 24.07 | 00:31 | BANKUSDT | LONG | TP_clean | осторожно 65% |
| 551 | 23.07 | 23:33 | LITUSDT | SHORT | TP_clean | осторожно 62% |
| 550 | 23.07 | 23:31 | LAUSDT | LONG | SL_clean | осторожно 62% |
| 549 | 22.07 | 22:04 | SMCIUSDT | LONG | TP_clean | осторожно 74% |
| 548 | 23.07 | 03:08 | XMRUSDT | LONG | Sideways | осторожно 66% |
| 547 | 23.07 | 03:09 | MONUSDT | SHORT | TP_clean | осторожно 61% |
| 546 | 23.07 | 09:05 | MONUSDT | SHORT | TP_clean | осторожно 78% |
| 545 | 23.07 | 10:11 | MORPHOUSDT | SHORT | Sideways | осторожно 62% |
| 544 | 23.07 | 10:34 | VVVUSDT | SHORT | TP_clean | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-28 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-27 06:30 UTC
- mmscan-snapshot: next run 2026-07-27 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
