# MM Scan Shadow Snapshot
Generated: 2026-08-20T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 206.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-20T15:13:49+0000 (#854 SNXXUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-19T18:00:01Z → 2026-08-20T18:00:01Z)
- New signals: 10 (LONG 3 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 206.2h, restarts: 0
- Last closer: 2026-08-20T03:00:23Z
- Last backfill: 2026-08-20T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 8

## Health 7d (window: 2026-08-13T18:00:01Z → 2026-08-20T18:00:01Z)
- New signals: 63 (~9.0/day)
- Closed: 45 (TP 19, SL 18, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 18
- TP rate 7d: 51.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 854
- Closed: 836 (TP_clean 429, SL_clean 283, SL→reverse 0, Sideways 124, N/A 0)
- Ongoing (<24h): 18
- TP rate: 60.3% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 854 | 20.08 | 18:13 | SNXXUSDT | SHORT | ongoing | осторожно 63% |
| 853 | 20.08 | 14:13 | MORPHOUSDT | SHORT | ongoing | осторожно 65% |
| 852 | 20.08 | 14:10 | WDCUSDT | SHORT | ongoing | осторожно 61% |
| 851 | 20.08 | 12:37 | PRLUSDT | SHORT | ongoing | осторожно 77% |
| 850 | 20.08 | 12:05 | COTIUSDT | LONG | ongoing | осторожно 62% |
| 849 | 20.08 | 12:03 | BICOUSDT | SHORT | ongoing | осторожно 73% |
| 848 | 20.08 | 06:11 | MINIMAXUSDT | SHORT | ongoing | осторожно 77% |
| 847 | 20.08 | 02:09 | CYSUSDT | LONG | ongoing | осторожно 70% |
| 846 | 19.08 | 23:57 | APRUSDT | LONG | ongoing | осторожно 61% |
| 845 | 19.08 | 22:09 | JCTUSDT | SHORT | ongoing | осторожно 62% |
| 844 | 19.08 | 19:07 | KORUUSDT | SHORT | ongoing | осторожно 67% |
| 843 | 19.08 | 17:33 | SAMSUNGUSDT | SHORT | ongoing | осторожно 62% |
| 842 | 19.08 | 15:36 | MUUUSDT | SHORT | ongoing | осторожно 75% |
| 841 | 19.08 | 15:31 | SNDKUSDT | SHORT | ongoing | осторожно 79% |
| 840 | 19.08 | 13:04 | ZHIPUUSDT | SHORT | ongoing | осторожно 62% |
| 839 | 19.08 | 12:31 | DOSUSDT | LONG | ongoing | осторожно 71% |
| 838 | 19.08 | 09:31 | VELVETUSDT | SHORT | ongoing | осторожно 61% |
| 837 | 19.08 | 07:06 | EWYUSDT | SHORT | ongoing | осторожно 65% |
| 836 | 19.08 | 05:05 | WLDUSDT | SHORT | SL_clean | осторожно 61% |
| 835 | 19.08 | 03:35 | KORUUSDT | SHORT | SL_clean | осторожно 60% |
| 834 | 19.08 | 01:01 | ACEUSDT | LONG | TP_clean | осторожно 67% |
| 833 | 18.08 | 21:31 | BTWUSDT | SHORT | SL_clean | осторожно 67% |
| 832 | 18.08 | 21:12 | EWYUSDT | SHORT | SL_clean | осторожно 65% |
| 831 | 18.08 | 16:01 | COTIUSDT | LONG | SL_clean | осторожно 61% |
| 830 | 18.08 | 14:02 | COHRUSDT | SHORT | TP_clean | осторожно 69% |
| 829 | 18.08 | 12:35 | BMNRUSDT | SHORT | Sideways | осторожно 74% |
| 828 | 18.08 | 09:11 | INTCUSDT | SHORT | TP_clean | осторожно 62% |
| 827 | 18.08 | 07:37 | XPINUSDT | SHORT | SL_clean | осторожно 63% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-20 18:30 UTC
- mmscan-snapshot: next run 2026-08-21 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
