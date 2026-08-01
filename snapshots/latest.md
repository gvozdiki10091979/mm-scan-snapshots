# MM Scan Shadow Snapshot
Generated: 2026-08-01T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 196.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-31T22:35:40+0000 (#669 ESPUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-31T00:00:01Z → 2026-08-01T00:00:01Z)
- New signals: 8 (LONG 4 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 196.1h, restarts: 12064
- Last closer: 2026-07-31T03:00:29Z
- Last backfill: 2026-07-31T23:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 9

## Health 7d (window: 2026-07-25T00:00:01Z → 2026-08-01T00:00:01Z)
- New signals: 93 (~13.3/day)
- Closed: 76 (TP 48, SL 21, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 17
- TP rate 7d: 69.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 669
- Closed: 652 (TP_clean 341, SL_clean 216, SL→reverse 0, Sideways 95, N/A 0)
- Ongoing (<24h): 17
- TP rate: 61.2% decided (TP/(TP+SL)) · 52.3% pointwise (excl N/A)

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
| 669 | 01.08 | 01:35 | ESPUSDT | LONG | ongoing | осторожно 60% |
| 668 | 01.08 | 01:08 | CRCLUSDT | SHORT | ongoing | осторожно 73% |
| 667 | 31.07 | 23:02 | DEXEUSDT | LONG | ongoing | осторожно 60% |
| 666 | 31.07 | 22:33 | LITUSDT | SHORT | ongoing | осторожно 89% |
| 665 | 31.07 | 15:41 | UAIUSDT | SHORT | ongoing | осторожно 65% |
| 664 | 31.07 | 11:01 | CFXUSDT | LONG | ongoing | осторожно 61% |
| 663 | 31.07 | 08:36 | BEATUSDT | LONG | ongoing | осторожно 68% |
| 662 | 31.07 | 08:09 | ONDOUSDT | SHORT | ongoing | осторожно 62% |
| 661 | 30.07 | 23:05 | ALLOUSDT | SHORT | ongoing | осторожно 75% |
| 660 | 30.07 | 21:37 | ESPUSDT | LONG | ongoing | осторожно 67% |
| 659 | 30.07 | 19:04 | EULUSDT | SHORT | ongoing | осторожно 67% |
| 658 | 30.07 | 17:00 | ESPUSDT | LONG | ongoing | входить 86% |
| 657 | 30.07 | 15:31 | SENTUSDT | LONG | ongoing | осторожно 64% |
| 656 | 30.07 | 11:35 | HYPEUSDT | LONG | ongoing | осторожно 66% |
| 655 | 30.07 | 08:41 | SOONUSDT | SHORT | ongoing | осторожно 64% |
| 654 | 30.07 | 08:35 | BCHUSDT | LONG | ongoing | осторожно 63% |
| 653 | 30.07 | 07:06 | LITUSDT | LONG | ongoing | осторожно 65% |
| 652 | 30.07 | 05:30 | VANRYUSDT | SHORT | TP_clean | осторожно 71% |
| 651 | 30.07 | 01:31 | ACHUSDT | LONG | TP_clean | осторожно 62% |
| 650 | 29.07 | 23:05 | APTUSDT | SHORT | SL_clean | осторожно 63% |
| 649 | 29.07 | 21:31 | ZAMAUSDT | LONG | SL_clean | осторожно 64% |
| 648 | 29.07 | 21:03 | 1000BONKUSDT | SHORT | TP_clean | осторожно 62% |
| 647 | 29.07 | 16:31 | PEOPLEUSDT | SHORT | TP_clean | осторожно 63% |
| 646 | 29.07 | 15:10 | LDOUSDT | SHORT | TP_clean | осторожно 61% |
| 645 | 29.07 | 14:04 | AVAXUSDT | SHORT | Sideways | осторожно 72% |
| 644 | 29.07 | 13:38 | BEATUSDT | SHORT | SL_clean | осторожно 65% |
| 643 | 29.07 | 12:37 | MVLLUSDT | SHORT | TP_clean | осторожно 60% |
| 642 | 29.07 | 12:03 | KAITOUSDT | SHORT | SL_clean | осторожно 73% |
| 641 | 29.07 | 12:01 | EULUSDT | SHORT | TP_clean | осторожно 60% |
| 640 | 29.07 | 11:42 | SOONUSDT | LONG | SL_clean | осторожно 68% |
| 639 | 29.07 | 09:31 | PEOPLEUSDT | SHORT | TP_clean | осторожно 62% |
| 638 | 29.07 | 09:14 | TAOUSDT | SHORT | TP_clean | осторожно 63% |
| 637 | 29.07 | 06:37 | DASHUSDT | SHORT | TP_clean | осторожно 74% |
| 636 | 29.07 | 06:10 | LITUSDT | SHORT | SL_clean | осторожно 66% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-01 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-01 00:30 UTC
- mmscan-snapshot: next run 2026-08-01 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
