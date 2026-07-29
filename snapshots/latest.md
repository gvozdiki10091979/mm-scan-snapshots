# MM Scan Shadow Snapshot
Generated: 2026-07-29T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 130.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-29T03:37:15+0000 (#637 DASHUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-28T06:00:01Z → 2026-07-29T06:00:01Z)
- New signals: 28 (LONG 4 / SHORT 24)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 28
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 130.1h, restarts: 12064
- Last closer: 2026-07-29T03:00:19Z
- Last backfill: 2026-07-29T05:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 7

## Health 7d (window: 2026-07-22T06:00:01Z → 2026-07-29T06:00:01Z)
- New signals: 110 (~15.7/day)
- Closed: 75 (TP 41, SL 19, SL→rev 0, Sideways 15, N/A 0)
- Ongoing: 35
- TP rate 7d: 68.3%
- Listener uptime 7d: 77.4% (continuous since unit start)

## Shadow Journal Live
- Total signals: 637
- Closed: 602 (TP_clean 309, SL_clean 202, SL→reverse 0, Sideways 91, N/A 0)
- Ongoing (<24h): 35
- TP rate: 60.5% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 637 | 29.07 | 06:37 | DASHUSDT | SHORT | ongoing | осторожно 74% |
| 636 | 29.07 | 06:10 | LITUSDT | SHORT | ongoing | осторожно 66% |
| 635 | 29.07 | 04:35 | DIAUSDT | SHORT | ongoing | осторожно 62% |
| 634 | 29.07 | 04:35 | DEXEUSDT | SHORT | ongoing | входить 88% |
| 633 | 29.07 | 02:38 | BTWUSDT | SHORT | ongoing | осторожно 65% |
| 632 | 29.07 | 01:36 | LITUSDT | SHORT | ongoing | осторожно 64% |
| 631 | 28.07 | 22:32 | REUSDT | SHORT | ongoing | осторожно 63% |
| 630 | 28.07 | 21:35 | CRCLUSDT | LONG | ongoing | осторожно 68% |
| 629 | 28.07 | 21:34 | VANRYUSDT | LONG | ongoing | осторожно 74% |
| 628 | 28.07 | 21:08 | PENDLEUSDT | SHORT | ongoing | осторожно 65% |
| 627 | 28.07 | 19:07 | INTCUSDT | SHORT | ongoing | осторожно 66% |
| 626 | 28.07 | 19:05 | SKHYUSDT | SHORT | ongoing | осторожно 64% |
| 625 | 28.07 | 17:37 | KORUUSDT | SHORT | ongoing | осторожно 70% |
| 624 | 28.07 | 16:41 | DEXEUSDT | SHORT | ongoing | осторожно 63% |
| 623 | 28.07 | 16:06 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 622 | 28.07 | 16:04 | LAUSDT | SHORT | ongoing | осторожно 66% |
| 621 | 28.07 | 15:03 | KITEUSDT | SHORT | ongoing | осторожно 62% |
| 620 | 28.07 | 14:04 | 1000BONKUSDT | SHORT | ongoing | осторожно 60% |
| 619 | 28.07 | 14:03 | INTCUSDT | SHORT | ongoing | осторожно 65% |
| 618 | 28.07 | 13:09 | INJUSDT | SHORT | ongoing | осторожно 67% |
| 617 | 28.07 | 13:03 | 1000PEPEUSDT | SHORT | ongoing | осторожно 60% |
| 616 | 28.07 | 13:03 | ETHFIUSDT | SHORT | ongoing | осторожно 70% |
| 615 | 28.07 | 12:03 | ONDOUSDT | SHORT | ongoing | осторожно 65% |
| 614 | 28.07 | 12:03 | RENDERUSDT | SHORT | ongoing | осторожно 74% |
| 613 | 28.07 | 11:01 | ACHUSDT | LONG | ongoing | осторожно 83% |
| 612 | 28.07 | 10:01 | REZUSDT | LONG | ongoing | осторожно 79% |
| 611 | 28.07 | 09:37 | EULUSDT | SHORT | ongoing | осторожно 66% |
| 610 | 28.07 | 09:03 | GWEIUSDT | SHORT | ongoing | осторожно 66% |
| 609 | 28.07 | 07:07 | PYTHUSDT | SHORT | ongoing | осторожно 62% |
| 608 | 28.07 | 07:05 | PENDLEUSDT | SHORT | ongoing | осторожно 74% |
| 607 | 28.07 | 07:03 | TRUMPUSDT | SHORT | ongoing | осторожно 62% |
| 606 | 28.07 | 06:38 | SOXSUSDT | LONG | ongoing | осторожно 80% |
| 605 | 28.07 | 06:13 | DELLUSDT | SHORT | ongoing | осторожно 60% |
| 604 | 28.07 | 06:07 | INTCUSDT | SHORT | ongoing | осторожно 70% |
| 603 | 28.07 | 06:03 | TLMUSDT | LONG | ongoing | осторожно 79% |
| 602 | 28.07 | 03:01 | COTIUSDT | LONG | TP_clean | осторожно 72% |
| 601 | 28.07 | 01:11 | XLMUSDT | SHORT | TP_clean | осторожно 69% |
| 600 | 28.07 | 00:25 | BOMEUSDT | LONG | SL_clean | осторожно 61% |
| 599 | 27.07 | 22:08 | XMRUSDT | SHORT | TP_clean | осторожно 66% |
| 598 | 27.07 | 18:05 | OPUSDT | SHORT | TP_clean | осторожно 60% |
| 597 | 27.07 | 16:04 | XMRUSDT | SHORT | TP_clean | осторожно 72% |
| 596 | 27.07 | 12:07 | IRYSUSDT | LONG | TP_clean | осторожно 85% |
| 595 | 27.07 | 12:01 | NILUSDT | LONG | TP_clean | осторожно 69% |
| 594 | 27.07 | 10:31 | EULUSDT | LONG | SL_clean | осторожно 72% |
| 593 | 27.07 | 01:32 | ACEUSDT | SHORT | TP_clean | осторожно 67% |
| 592 | 27.07 | 01:32 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 591 | 27.07 | 01:03 | EULUSDT | LONG | SL_clean | осторожно 67% |
| 590 | 26.07 | 22:31 | CROSSUSDT | LONG | TP_clean | осторожно 63% |
| 589 | 26.07 | 20:01 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 588 | 26.07 | 19:30 | AKEUSDT | LONG | TP_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-30 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-29 06:30 UTC
- mmscan-snapshot: next run 2026-07-29 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
