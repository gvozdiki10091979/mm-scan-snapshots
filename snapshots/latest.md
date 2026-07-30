# MM Scan Shadow Snapshot
Generated: 2026-07-30T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 160.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-30T08:35:32+0000 (#656 HYPEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-29T12:00:01Z → 2026-07-30T12:00:01Z)
- New signals: 11 (LONG 5 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 160.1h, restarts: 12064
- Last closer: 2026-07-30T03:00:52Z
- Last backfill: 2026-07-30T11:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 10

## Health 7d (window: 2026-07-23T12:00:01Z → 2026-07-30T12:00:01Z)
- New signals: 114 (~16.3/day)
- Closed: 93 (TP 53, SL 25, SL→rev 0, Sideways 15, N/A 0)
- Ongoing: 21
- TP rate 7d: 67.9%
- Listener uptime 7d: 95.3% (continuous since unit start)

## Shadow Journal Live
- Total signals: 656
- Closed: 635 (TP_clean 331, SL_clean 210, SL→reverse 0, Sideways 94, N/A 0)
- Ongoing (<24h): 21
- TP rate: 61.2% decided (TP/(TP+SL)) · 52.1% pointwise (excl N/A)

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
| 656 | 30.07 | 11:35 | HYPEUSDT | LONG | ongoing | осторожно 66% |
| 655 | 30.07 | 08:41 | SOONUSDT | SHORT | ongoing | осторожно 64% |
| 654 | 30.07 | 08:35 | BCHUSDT | LONG | ongoing | осторожно 63% |
| 653 | 30.07 | 07:06 | LITUSDT | LONG | ongoing | осторожно 65% |
| 652 | 30.07 | 05:30 | VANRYUSDT | SHORT | ongoing | осторожно 71% |
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
| 635 | 29.07 | 04:35 | DIAUSDT | SHORT | TP_clean | осторожно 62% |
| 634 | 29.07 | 04:35 | DEXEUSDT | SHORT | TP_clean | входить 88% |
| 633 | 29.07 | 02:38 | BTWUSDT | SHORT | SL_clean | осторожно 65% |
| 632 | 29.07 | 01:36 | LITUSDT | SHORT | TP_clean | осторожно 64% |
| 631 | 28.07 | 22:32 | REUSDT | SHORT | TP_clean | осторожно 63% |
| 630 | 28.07 | 21:35 | CRCLUSDT | LONG | Sideways | осторожно 68% |
| 629 | 28.07 | 21:34 | VANRYUSDT | LONG | TP_clean | осторожно 74% |
| 628 | 28.07 | 21:08 | PENDLEUSDT | SHORT | TP_clean | осторожно 65% |
| 627 | 28.07 | 19:07 | INTCUSDT | SHORT | TP_clean | осторожно 66% |
| 626 | 28.07 | 19:05 | SKHYUSDT | SHORT | TP_clean | осторожно 64% |
| 625 | 28.07 | 17:37 | KORUUSDT | SHORT | SL_clean | осторожно 70% |
| 624 | 28.07 | 16:41 | DEXEUSDT | SHORT | TP_clean | осторожно 63% |
| 623 | 28.07 | 16:06 | SEIUSDT | SHORT | Sideways | осторожно 68% |
| 622 | 28.07 | 16:04 | LAUSDT | SHORT | SL_clean | осторожно 66% |
| 621 | 28.07 | 15:03 | KITEUSDT | SHORT | TP_clean | осторожно 62% |
| 620 | 28.07 | 14:04 | 1000BONKUSDT | SHORT | SL_clean | осторожно 60% |
| 619 | 28.07 | 14:03 | INTCUSDT | SHORT | TP_clean | осторожно 65% |
| 618 | 28.07 | 13:09 | INJUSDT | SHORT | TP_clean | осторожно 67% |
| 617 | 28.07 | 13:03 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 60% |
| 616 | 28.07 | 13:03 | ETHFIUSDT | SHORT | SL_clean | осторожно 70% |
| 615 | 28.07 | 12:03 | ONDOUSDT | SHORT | SL_clean | осторожно 65% |
| 614 | 28.07 | 12:03 | RENDERUSDT | SHORT | Sideways | осторожно 74% |
| 613 | 28.07 | 11:01 | ACHUSDT | LONG | SL_clean | осторожно 83% |
| 612 | 28.07 | 10:01 | REZUSDT | LONG | TP_clean | осторожно 79% |
| 611 | 28.07 | 09:37 | EULUSDT | SHORT | TP_clean | осторожно 66% |
| 610 | 28.07 | 09:03 | GWEIUSDT | SHORT | SL_clean | осторожно 66% |
| 609 | 28.07 | 07:07 | PYTHUSDT | SHORT | TP_clean | осторожно 62% |
| 608 | 28.07 | 07:05 | PENDLEUSDT | SHORT | TP_clean | осторожно 74% |
| 607 | 28.07 | 07:03 | TRUMPUSDT | SHORT | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-31 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-30 12:30 UTC
- mmscan-snapshot: next run 2026-07-30 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
