# MM Scan Shadow Snapshot
Generated: 2026-08-03T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 256.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-08-03T10:00:41+0000 (#685 VANRYUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-08-02T12:00:01Z → 2026-08-03T12:00:01Z)
- New signals: 5 (LONG 1 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 5
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 256.1h, restarts: 12064
- Last closer: 2026-08-03T03:00:18Z
- Last backfill: 2026-08-03T11:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 2

## Health 7d (window: 2026-07-27T12:00:01Z → 2026-08-03T12:00:01Z)
- New signals: 89 (~12.7/day)
- Closed: 82 (TP 48, SL 27, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 7
- TP rate 7d: 64.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 685
- Closed: 678 (TP_clean 352, SL_clean 228, SL→reverse 0, Sideways 98, N/A 0)
- Ongoing (<24h): 7
- TP rate: 60.7% decided (TP/(TP+SL)) · 51.9% pointwise (excl N/A)

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
| 685 | 03.08 | 13:00 | VANRYUSDT | SHORT | ongoing | осторожно 74% |
| 684 | 03.08 | 12:07 | ACEUSDT | LONG | ongoing | осторожно 65% |
| 683 | 03.08 | 09:38 | BEATUSDT | SHORT | ongoing | осторожно 67% |
| 682 | 02.08 | 18:06 | CAPUSDT | SHORT | ongoing | осторожно 78% |
| 681 | 02.08 | 15:38 | BTWUSDT | SHORT | ongoing | осторожно 76% |
| 680 | 02.08 | 11:30 | TLMUSDT | LONG | ongoing | осторожно 67% |
| 679 | 02.08 | 07:33 | CFXUSDT | LONG | ongoing | осторожно 65% |
| 678 | 02.08 | 05:37 | CAPUSDT | SHORT | SL_clean | осторожно 77% |
| 677 | 02.08 | 01:01 | CFXUSDT | LONG | Sideways | осторожно 61% |
| 676 | 02.08 | 00:12 | AAVEUSDT | SHORT | SL_clean | осторожно 62% |
| 675 | 01.08 | 20:31 | AEVOUSDT | LONG | SL_clean | осторожно 67% |
| 674 | 01.08 | 14:05 | HYPEUSDT | SHORT | Sideways | осторожно 62% |
| 673 | 01.08 | 12:08 | LDOUSDT | SHORT | TP_clean | осторожно 75% |
| 672 | 01.08 | 11:02 | TLMUSDT | LONG | SL_clean | осторожно 62% |
| 671 | 01.08 | 06:02 | VANRYUSDT | SHORT | SL_clean | осторожно 68% |
| 670 | 01.08 | 04:02 | XPLUSDT | SHORT | SL_clean | осторожно 60% |
| 669 | 01.08 | 01:35 | ESPUSDT | LONG | TP_clean | осторожно 60% |
| 668 | 01.08 | 01:08 | CRCLUSDT | SHORT | TP_clean | осторожно 73% |
| 667 | 31.07 | 23:02 | DEXEUSDT | LONG | TP_clean | осторожно 60% |
| 666 | 31.07 | 22:33 | LITUSDT | SHORT | TP_clean | осторожно 89% |
| 665 | 31.07 | 15:41 | UAIUSDT | SHORT | TP_clean | осторожно 65% |
| 664 | 31.07 | 11:01 | CFXUSDT | LONG | SL_clean | осторожно 61% |
| 663 | 31.07 | 08:36 | BEATUSDT | LONG | TP_clean | осторожно 68% |
| 662 | 31.07 | 08:09 | ONDOUSDT | SHORT | TP_clean | осторожно 62% |
| 661 | 30.07 | 23:05 | ALLOUSDT | SHORT | TP_clean | осторожно 75% |
| 660 | 30.07 | 21:37 | ESPUSDT | LONG | SL_clean | осторожно 67% |
| 659 | 30.07 | 19:04 | EULUSDT | SHORT | SL_clean | осторожно 67% |
| 658 | 30.07 | 17:00 | ESPUSDT | LONG | SL_clean | входить 86% |
| 657 | 30.07 | 15:31 | SENTUSDT | LONG | SL_clean | осторожно 64% |
| 656 | 30.07 | 11:35 | HYPEUSDT | LONG | TP_clean | осторожно 66% |
| 655 | 30.07 | 08:41 | SOONUSDT | SHORT | SL_clean | осторожно 64% |
| 654 | 30.07 | 08:35 | BCHUSDT | LONG | TP_clean | осторожно 63% |
| 653 | 30.07 | 07:06 | LITUSDT | LONG | Sideways | осторожно 65% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-04 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-03 12:30 UTC
- mmscan-snapshot: next run 2026-08-03 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
