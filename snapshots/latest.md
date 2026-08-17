# MM Scan Shadow Snapshot
Generated: 2026-08-17T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 134.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-17T14:32:40+0000 (#822 RIVERUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-16T18:00:02Z → 2026-08-17T18:00:02Z)
- New signals: 5 (LONG 2 / SHORT 3)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 5
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 134.2h, restarts: 0
- Last closer: 2026-08-17T03:00:22Z
- Last backfill: 2026-08-17T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 4

## Health 7d (window: 2026-08-10T18:00:02Z → 2026-08-17T18:00:02Z)
- New signals: 64 (~9.1/day)
- Closed: 55 (TP 25, SL 19, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 9
- TP rate 7d: 56.8%
- Listener uptime 7d: 79.9% (continuous since unit start)

## Shadow Journal Live
- Total signals: 822
- Closed: 813 (TP_clean 419, SL_clean 273, SL→reverse 0, Sideways 121, N/A 0)
- Ongoing (<24h): 9
- TP rate: 60.5% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 822 | 17.08 | 17:32 | RIVERUSDT | SHORT | ongoing | осторожно 70% |
| 821 | 17.08 | 17:32 | HOMEUSDT | SHORT | ongoing | осторожно 60% |
| 820 | 17.08 | 04:06 | ENAUSDT | LONG | ongoing | осторожно 60% |
| 819 | 17.08 | 03:13 | SOPHUSDT | LONG | ongoing | осторожно 78% |
| 818 | 16.08 | 22:05 | ACEUSDT | SHORT | ongoing | входить 82% |
| 817 | 16.08 | 19:36 | ROBOUSDT | SHORT | ongoing | осторожно 63% |
| 816 | 16.08 | 17:00 | CHIPUSDT | LONG | ongoing | осторожно 74% |
| 815 | 16.08 | 09:31 | HOMEUSDT | SHORT | ongoing | осторожно 65% |
| 814 | 16.08 | 07:06 | FILUSDT | SHORT | ongoing | осторожно 60% |
| 813 | 16.08 | 04:34 | ENAUSDT | SHORT | TP_clean | осторожно 62% |
| 812 | 16.08 | 04:31 | KAITOUSDT | SHORT | TP_clean | осторожно 62% |
| 811 | 16.08 | 02:07 | USUSDT | SHORT | SL_clean | осторожно 67% |
| 810 | 15.08 | 17:01 | COWUSDT | LONG | TP_clean | осторожно 67% |
| 809 | 15.08 | 15:05 | DOSUSDT | LONG | SL_clean | осторожно 63% |
| 808 | 15.08 | 12:39 | BMTUSDT | SHORT | TP_clean | осторожно 74% |
| 807 | 15.08 | 11:02 | ONGUSDT | LONG | SL_clean | осторожно 80% |
| 806 | 15.08 | 11:01 | BTWUSDT | LONG | SL_clean | осторожно 69% |
| 805 | 15.08 | 10:01 | 1000BONKUSDT | SHORT | Sideways | осторожно 62% |
| 804 | 15.08 | 09:31 | ALICEUSDT | LONG | SL_clean | осторожно 65% |
| 803 | 15.08 | 08:33 | AVAXUSDT | LONG | SL_clean | осторожно 60% |
| 802 | 15.08 | 08:08 | CBRSUSDT | SHORT | Sideways | осторожно 60% |
| 801 | 15.08 | 01:34 | STORJUSDT | LONG | Sideways | осторожно 61% |
| 800 | 14.08 | 22:05 | ENAUSDT | SHORT | Sideways | осторожно 72% |
| 799 | 14.08 | 19:34 | HOMEUSDT | LONG | TP_clean | осторожно 70% |
| 798 | 14.08 | 19:05 | CRCLUSDT | SHORT | Sideways | осторожно 67% |
| 797 | 14.08 | 10:35 | BSPUSDT | SHORT | SL_clean | осторожно 73% |
| 796 | 14.08 | 06:33 | MRVLUSDT | LONG | SL_clean | осторожно 69% |
| 795 | 14.08 | 06:11 | NBISUSDT | LONG | TP_clean | осторожно 60% |
| 794 | 14.08 | 01:37 | ESPUSDT | SHORT | TP_clean | осторожно 62% |
| 793 | 14.08 | 01:36 | SMCIUSDT | LONG | TP_clean | осторожно 70% |
| 792 | 14.08 | 01:34 | NBISUSDT | LONG | TP_clean | осторожно 66% |
| 791 | 13.08 | 19:02 | DOSUSDT | SHORT | SL_clean | входить 86% |
| 790 | 13.08 | 17:36 | BICOUSDT | SHORT | TP_clean | осторожно 68% |
| 789 | 13.08 | 14:38 | ENAUSDT | SHORT | Sideways | осторожно 62% |
| 788 | 13.08 | 14:35 | SPCXUSDT | LONG | SL_clean | осторожно 61% |
| 787 | 13.08 | 14:09 | BRUSDT | LONG | TP_clean | осторожно 71% |
| 786 | 13.08 | 12:01 | MINIMAXUSDT | LONG | TP_clean | осторожно 61% |
| 785 | 13.08 | 10:34 | ROBOUSDT | LONG | TP_clean | осторожно 64% |
| 784 | 13.08 | 08:30 | IDUSDT | LONG | TP_clean | осторожно 71% |
| 783 | 13.08 | 05:34 | SAMSUNGUSDT | LONG | TP_clean | осторожно 62% |
| 782 | 13.08 | 03:39 | 1000LUNCUSDT | SHORT | Sideways | осторожно 76% |
| 781 | 13.08 | 03:36 | VIRTUALUSDT | LONG | SL_clean | осторожно 65% |
| 780 | 13.08 | 03:33 | HOMEUSDT | LONG | TP_clean | осторожно 70% |
| 779 | 13.08 | 02:30 | APRUSDT | LONG | TP_clean | осторожно 74% |
| 778 | 13.08 | 01:06 | UNIUSDT | SHORT | Sideways | осторожно 62% |
| 777 | 13.08 | 00:34 | KAITOUSDT | SHORT | TP_clean | осторожно 61% |
| 776 | 13.08 | 00:31 | EULUSDT | SHORT | TP_clean | осторожно 65% |
| 775 | 13.08 | 00:05 | ICPUSDT | SHORT | Sideways | осторожно 73% |
| 774 | 12.08 | 22:36 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 773 | 12.08 | 19:01 | LSKUSDT | LONG | TP_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-18 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-17 18:30 UTC
- mmscan-snapshot: next run 2026-08-18 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
