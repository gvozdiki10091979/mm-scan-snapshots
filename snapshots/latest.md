# MM Scan Shadow Snapshot
Generated: 2026-08-25T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 308.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-24T22:01:12+0000 (#895 COTIUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-24T00:00:01Z → 2026-08-25T00:00:01Z)
- New signals: 6 (LONG 3 / SHORT 3)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 308.2h, restarts: 0
- Last closer: 2026-08-24T03:00:19Z
- Last backfill: 2026-08-24T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 7

## Health 7d (window: 2026-08-18T00:00:01Z → 2026-08-25T00:00:01Z)
- New signals: 70 (~10.0/day)
- Closed: 57 (TP 25, SL 25, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 13
- TP rate 7d: 50.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 895
- Closed: 882 (TP_clean 450, SL_clean 302, SL→reverse 0, Sideways 130, N/A 0)
- Ongoing (<24h): 13
- TP rate: 59.8% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 895 | 25.08 | 01:01 | COTIUSDT | LONG | ongoing | осторожно 61% |
| 894 | 24.08 | 19:01 | SUPERUSDT | LONG | ongoing | входить 82% |
| 893 | 24.08 | 13:03 | HEMIUSDT | SHORT | ongoing | осторожно 64% |
| 892 | 24.08 | 09:37 | GRAMUSDT | SHORT | ongoing | осторожно 61% |
| 891 | 24.08 | 03:40 | SKHYNIXUSDT | SHORT | ongoing | осторожно 64% |
| 890 | 24.08 | 03:31 | ONTUSDT | LONG | ongoing | осторожно 66% |
| 889 | 24.08 | 02:30 | SPKUSDT | LONG | ongoing | осторожно 74% |
| 888 | 24.08 | 00:12 | TACUSDT | SHORT | ongoing | осторожно 78% |
| 887 | 23.08 | 23:32 | 1000RATSUSDT | SHORT | ongoing | входить 80% |
| 886 | 23.08 | 23:01 | COTIUSDT | LONG | ongoing | осторожно 61% |
| 885 | 23.08 | 16:08 | ZECUSDT | LONG | ongoing | осторожно 70% |
| 884 | 23.08 | 13:07 | DOGEUSDT | LONG | ongoing | осторожно 67% |
| 883 | 23.08 | 09:03 | PYTHUSDT | LONG | ongoing | осторожно 77% |
| 882 | 23.08 | 05:32 | BICOUSDT | LONG | SL_clean | осторожно 63% |
| 881 | 23.08 | 04:04 | POWRUSDT | LONG | SL_clean | осторожно 71% |
| 880 | 23.08 | 04:01 | GASUSDT | LONG | SL_clean | осторожно 63% |
| 879 | 23.08 | 00:03 | PRLUSDT | SHORT | TP_clean | осторожно 73% |
| 878 | 22.08 | 23:07 | HYPEUSDT | LONG | Sideways | осторожно 64% |
| 877 | 22.08 | 22:42 | AAVEUSDT | LONG | SL_clean | осторожно 62% |
| 876 | 22.08 | 19:30 | USELESSUSDT | LONG | SL_clean | осторожно 65% |
| 875 | 22.08 | 18:04 | LITUSDT | LONG | TP_clean | осторожно 63% |
| 874 | 22.08 | 17:09 | AXTIUSDT | SHORT | Sideways | осторожно 63% |
| 873 | 22.08 | 16:31 | HEIUSDT | SHORT | TP_clean | осторожно 61% |
| 872 | 22.08 | 08:34 | BMNRUSDT | LONG | Sideways | осторожно 61% |
| 871 | 22.08 | 03:37 | SKHYNIXUSDT | SHORT | Sideways | осторожно 73% |
| 870 | 22.08 | 01:09 | RKLBUSDT | SHORT | TP_clean | осторожно 60% |
| 869 | 21.08 | 17:38 | GRVTUSDT | SHORT | SL_clean | осторожно 65% |
| 868 | 21.08 | 16:08 | SCRTUSDT | SHORT | SL_clean | осторожно 72% |
| 867 | 21.08 | 15:11 | LITUSDT | SHORT | SL_clean | осторожно 60% |
| 866 | 21.08 | 11:00 | CXMTUSDT | SHORT | Sideways | входить 81% |
| 865 | 21.08 | 10:00 | ACEUSDT | LONG | TP_clean | входить 88% |
| 864 | 21.08 | 08:31 | UNITREEUSDT | SHORT | TP_clean | осторожно 73% |
| 863 | 21.08 | 07:04 | ZECUSDT | LONG | TP_clean | осторожно 66% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-25 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-25 00:30 UTC
- mmscan-snapshot: next run 2026-08-25 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
