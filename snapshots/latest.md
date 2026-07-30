# MM Scan Shadow Snapshot
Generated: 2026-07-30T00:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 148.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-29T22:31:11+0000 (#651 ACHUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-29T00:00:02Z → 2026-07-30T00:00:02Z)
- New signals: 18 (LONG 3 / SHORT 15)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 18
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 148.1h, restarts: 12064
- Last closer: 2026-07-29T03:00:19Z
- Last backfill: 2026-07-29T23:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 31

## Health 7d (window: 2026-07-23T00:00:02Z → 2026-07-30T00:00:02Z)
- New signals: 116 (~16.6/day)
- Closed: 67 (TP 35, SL 18, SL→rev 0, Sideways 14, N/A 0)
- Ongoing: 49
- TP rate 7d: 66.0%
- Listener uptime 7d: 88.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 651
- Closed: 602 (TP_clean 309, SL_clean 202, SL→reverse 0, Sideways 91, N/A 0)
- Ongoing (<24h): 49
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
| 651 | 30.07 | 01:31 | ACHUSDT | LONG | ongoing | осторожно 62% |
| 650 | 29.07 | 23:05 | APTUSDT | SHORT | ongoing | осторожно 63% |
| 649 | 29.07 | 21:31 | ZAMAUSDT | LONG | ongoing | осторожно 64% |
| 648 | 29.07 | 21:03 | 1000BONKUSDT | SHORT | ongoing | осторожно 62% |
| 647 | 29.07 | 16:31 | PEOPLEUSDT | SHORT | ongoing | осторожно 63% |
| 646 | 29.07 | 15:10 | LDOUSDT | SHORT | ongoing | осторожно 61% |
| 645 | 29.07 | 14:04 | AVAXUSDT | SHORT | ongoing | осторожно 72% |
| 644 | 29.07 | 13:38 | BEATUSDT | SHORT | ongoing | осторожно 65% |
| 643 | 29.07 | 12:37 | MVLLUSDT | SHORT | ongoing | осторожно 60% |
| 642 | 29.07 | 12:03 | KAITOUSDT | SHORT | ongoing | осторожно 73% |
| 641 | 29.07 | 12:01 | EULUSDT | SHORT | ongoing | осторожно 60% |
| 640 | 29.07 | 11:42 | SOONUSDT | LONG | ongoing | осторожно 68% |
| 639 | 29.07 | 09:31 | PEOPLEUSDT | SHORT | ongoing | осторожно 62% |
| 638 | 29.07 | 09:14 | TAOUSDT | SHORT | ongoing | осторожно 63% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-07-30 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-30 00:30 UTC
- mmscan-snapshot: next run 2026-07-30 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
