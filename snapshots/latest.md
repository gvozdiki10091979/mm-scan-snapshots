# MM Scan Shadow Snapshot
Generated: 2026-08-22T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 242.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-22T05:34:37+0000 (#872 BMNRUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-21T06:00:01Z → 2026-08-22T06:00:01Z)
- New signals: 8 (LONG 2 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 242.2h, restarts: 0
- Last closer: 2026-08-22T03:00:25Z
- Last backfill: 2026-08-22T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 2

## Health 7d (window: 2026-08-15T06:00:01Z → 2026-08-22T06:00:01Z)
- New signals: 69 (~9.9/day)
- Closed: 59 (TP 28, SL 26, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 10
- TP rate 7d: 51.9%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 872
- Closed: 862 (TP_clean 443, SL_clean 294, SL→reverse 0, Sideways 125, N/A 0)
- Ongoing (<24h): 10
- TP rate: 60.1% decided (TP/(TP+SL)) · 51.4% pointwise (excl N/A)

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
| 872 | 22.08 | 08:34 | BMNRUSDT | LONG | ongoing | осторожно 61% |
| 871 | 22.08 | 03:37 | SKHYNIXUSDT | SHORT | ongoing | осторожно 73% |
| 870 | 22.08 | 01:09 | RKLBUSDT | SHORT | ongoing | осторожно 60% |
| 869 | 21.08 | 17:38 | GRVTUSDT | SHORT | ongoing | осторожно 65% |
| 868 | 21.08 | 16:08 | SCRTUSDT | SHORT | ongoing | осторожно 72% |
| 867 | 21.08 | 15:11 | LITUSDT | SHORT | ongoing | осторожно 60% |
| 866 | 21.08 | 11:00 | CXMTUSDT | SHORT | ongoing | входить 81% |
| 865 | 21.08 | 10:00 | ACEUSDT | LONG | ongoing | входить 88% |
| 864 | 21.08 | 08:31 | UNITREEUSDT | SHORT | ongoing | осторожно 73% |
| 863 | 21.08 | 07:04 | ZECUSDT | LONG | ongoing | осторожно 66% |
| 862 | 21.08 | 05:31 | CXMTUSDT | LONG | Sideways | осторожно 61% |
| 861 | 21.08 | 03:08 | CBRSUSDT | SHORT | TP_clean | осторожно 62% |
| 860 | 21.08 | 02:34 | BBUSDT | SHORT | SL_clean | осторожно 60% |
| 859 | 21.08 | 01:31 | HEIUSDT | SHORT | TP_clean | входить 90% |
| 858 | 21.08 | 00:33 | ZROUSDT | LONG | TP_clean | осторожно 65% |
| 857 | 21.08 | 00:14 | ZECUSDT | LONG | TP_clean | осторожно 65% |
| 856 | 20.08 | 23:01 | WLDUSDT | LONG | TP_clean | осторожно 60% |
| 855 | 20.08 | 22:31 | ONGUSDT | LONG | TP_clean | осторожно 61% |
| 854 | 20.08 | 18:13 | SNXXUSDT | SHORT | TP_clean | осторожно 63% |
| 853 | 20.08 | 14:13 | MORPHOUSDT | SHORT | SL_clean | осторожно 65% |
| 852 | 20.08 | 14:10 | WDCUSDT | SHORT | TP_clean | осторожно 61% |
| 851 | 20.08 | 12:37 | PRLUSDT | SHORT | SL_clean | осторожно 77% |
| 850 | 20.08 | 12:05 | COTIUSDT | LONG | TP_clean | осторожно 62% |
| 849 | 20.08 | 12:03 | BICOUSDT | SHORT | SL_clean | осторожно 73% |
| 848 | 20.08 | 06:11 | MINIMAXUSDT | SHORT | TP_clean | осторожно 77% |
| 847 | 20.08 | 02:09 | CYSUSDT | LONG | TP_clean | осторожно 70% |
| 846 | 19.08 | 23:57 | APRUSDT | LONG | SL_clean | осторожно 61% |
| 845 | 19.08 | 22:09 | JCTUSDT | SHORT | SL_clean | осторожно 62% |
| 844 | 19.08 | 19:07 | KORUUSDT | SHORT | SL_clean | осторожно 67% |
| 843 | 19.08 | 17:33 | SAMSUNGUSDT | SHORT | SL_clean | осторожно 62% |
| 842 | 19.08 | 15:36 | MUUUSDT | SHORT | TP_clean | осторожно 75% |
| 841 | 19.08 | 15:31 | SNDKUSDT | SHORT | TP_clean | осторожно 79% |
| 840 | 19.08 | 13:04 | ZHIPUUSDT | SHORT | SL_clean | осторожно 62% |
| 839 | 19.08 | 12:31 | DOSUSDT | LONG | TP_clean | осторожно 71% |
| 838 | 19.08 | 09:31 | VELVETUSDT | SHORT | SL_clean | осторожно 61% |
| 837 | 19.08 | 07:06 | EWYUSDT | SHORT | SL_clean | осторожно 65% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-22 06:30 UTC
- mmscan-snapshot: next run 2026-08-22 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
