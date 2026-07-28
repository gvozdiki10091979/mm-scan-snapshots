# MM Scan Shadow Snapshot
Generated: 2026-07-28T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 106.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-28T04:07:38+0000 (#609 PYTHUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-27T06:00:01Z → 2026-07-28T06:00:01Z)
- New signals: 16 (LONG 7 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 16
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 106.1h, restarts: 12064
- Last closer: 2026-07-28T03:00:17Z
- Last backfill: 2026-07-28T05:30:02Z
- Anomalies: listener рестартов: 12064

## Health 7d (window: 2026-07-21T06:00:01Z → 2026-07-28T06:00:01Z)
- New signals: 88 (~12.6/day)
- Closed: 72 (TP 36, SL 18, SL→rev 0, Sideways 18, N/A 0)
- Ongoing: 16
- TP rate 7d: 66.7%
- Listener uptime 7d: 63.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 609
- Closed: 593 (TP_clean 302, SL_clean 200, SL→reverse 0, Sideways 91, N/A 0)
- Ongoing (<24h): 16
- TP rate: 60.2% decided (TP/(TP+SL)) · 50.9% pointwise (excl N/A)

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
| 609 | 28.07 | 07:07 | PYTHUSDT | SHORT | ongoing | осторожно 62% |
| 608 | 28.07 | 07:05 | PENDLEUSDT | SHORT | ongoing | осторожно 74% |
| 607 | 28.07 | 07:03 | TRUMPUSDT | SHORT | ongoing | осторожно 62% |
| 606 | 28.07 | 06:38 | SOXSUSDT | LONG | ongoing | осторожно 80% |
| 605 | 28.07 | 06:13 | DELLUSDT | SHORT | ongoing | осторожно 60% |
| 604 | 28.07 | 06:07 | INTCUSDT | SHORT | ongoing | осторожно 70% |
| 603 | 28.07 | 06:03 | TLMUSDT | LONG | ongoing | осторожно 79% |
| 602 | 28.07 | 03:01 | COTIUSDT | LONG | ongoing | осторожно 72% |
| 601 | 28.07 | 01:11 | XLMUSDT | SHORT | ongoing | осторожно 69% |
| 600 | 28.07 | 00:25 | BOMEUSDT | LONG | ongoing | осторожно 61% |
| 599 | 27.07 | 22:08 | XMRUSDT | SHORT | ongoing | осторожно 66% |
| 598 | 27.07 | 18:05 | OPUSDT | SHORT | ongoing | осторожно 60% |
| 597 | 27.07 | 16:04 | XMRUSDT | SHORT | ongoing | осторожно 72% |
| 596 | 27.07 | 12:07 | IRYSUSDT | LONG | ongoing | осторожно 85% |
| 595 | 27.07 | 12:01 | NILUSDT | LONG | ongoing | осторожно 69% |
| 594 | 27.07 | 10:31 | EULUSDT | LONG | ongoing | осторожно 72% |
| 593 | 27.07 | 01:32 | ACEUSDT | SHORT | TP_clean | осторожно 67% |
| 592 | 27.07 | 01:32 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 591 | 27.07 | 01:03 | EULUSDT | LONG | SL_clean | осторожно 67% |
| 590 | 26.07 | 22:31 | CROSSUSDT | LONG | TP_clean | осторожно 63% |
| 589 | 26.07 | 20:01 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 588 | 26.07 | 19:30 | AKEUSDT | LONG | TP_clean | осторожно 61% |
| 587 | 26.07 | 17:00 | CROSSUSDT | LONG | SL_clean | осторожно 67% |
| 586 | 26.07 | 12:35 | VELVETUSDT | SHORT | SL_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-07-29 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-28 06:30 UTC
- mmscan-snapshot: next run 2026-07-28 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
