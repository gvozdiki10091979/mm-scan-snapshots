# MM Scan Shadow Snapshot
Generated: 2026-08-19T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 170.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-19T04:06:57+0000 (#837 EWYUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-18T06:00:01Z → 2026-08-19T06:00:01Z)
- New signals: 10 (LONG 2 / SHORT 8)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 170.2h, restarts: 0
- Last closer: 2026-08-19T03:00:14Z
- Last backfill: 2026-08-19T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 1

## Health 7d (window: 2026-08-12T06:00:01Z → 2026-08-19T06:00:01Z)
- New signals: 70 (~10.0/day)
- Closed: 59 (TP 29, SL 18, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 11
- TP rate 7d: 61.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 837
- Closed: 826 (TP_clean 426, SL_clean 277, SL→reverse 0, Sideways 123, N/A 0)
- Ongoing (<24h): 11
- TP rate: 60.6% decided (TP/(TP+SL)) · 51.6% pointwise (excl N/A)

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
| 837 | 19.08 | 07:06 | EWYUSDT | SHORT | ongoing | осторожно 65% |
| 836 | 19.08 | 05:05 | WLDUSDT | SHORT | ongoing | осторожно 61% |
| 835 | 19.08 | 03:35 | KORUUSDT | SHORT | ongoing | осторожно 60% |
| 834 | 19.08 | 01:01 | ACEUSDT | LONG | ongoing | осторожно 67% |
| 833 | 18.08 | 21:31 | BTWUSDT | SHORT | ongoing | осторожно 67% |
| 832 | 18.08 | 21:12 | EWYUSDT | SHORT | ongoing | осторожно 65% |
| 831 | 18.08 | 16:01 | COTIUSDT | LONG | ongoing | осторожно 61% |
| 830 | 18.08 | 14:02 | COHRUSDT | SHORT | ongoing | осторожно 69% |
| 829 | 18.08 | 12:35 | BMNRUSDT | SHORT | ongoing | осторожно 74% |
| 828 | 18.08 | 09:11 | INTCUSDT | SHORT | ongoing | осторожно 62% |
| 827 | 18.08 | 07:37 | XPINUSDT | SHORT | ongoing | осторожно 63% |
| 826 | 18.08 | 03:01 | GPSUSDT | LONG | TP_clean | осторожно 75% |
| 825 | 18.08 | 01:10 | AAOIUSDT | LONG | SL_clean | осторожно 73% |
| 824 | 18.08 | 01:01 | KORUUSDT | LONG | SL_clean | осторожно 75% |
| 823 | 17.08 | 22:33 | SKHYNIXUSDT | LONG | TP_clean | осторожно 63% |
| 822 | 17.08 | 17:32 | RIVERUSDT | SHORT | TP_clean | осторожно 70% |
| 821 | 17.08 | 17:32 | HOMEUSDT | SHORT | TP_clean | осторожно 60% |
| 820 | 17.08 | 04:06 | ENAUSDT | LONG | Sideways | осторожно 60% |
| 819 | 17.08 | 03:13 | SOPHUSDT | LONG | SL_clean | осторожно 78% |
| 818 | 16.08 | 22:05 | ACEUSDT | SHORT | TP_clean | входить 82% |
| 817 | 16.08 | 19:36 | ROBOUSDT | SHORT | TP_clean | осторожно 63% |
| 816 | 16.08 | 17:00 | CHIPUSDT | LONG | TP_clean | осторожно 74% |
| 815 | 16.08 | 09:31 | HOMEUSDT | SHORT | SL_clean | осторожно 65% |
| 814 | 16.08 | 07:06 | FILUSDT | SHORT | Sideways | осторожно 60% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-20 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-19 06:30 UTC
- mmscan-snapshot: next run 2026-08-19 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
