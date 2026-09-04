# MM Scan Shadow Snapshot
Generated: 2026-09-04T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 554.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-04T02:33:07+0000 (#1014 LAUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-03T06:00:02Z → 2026-09-04T06:00:02Z)
- New signals: 4 (LONG 4 / SHORT 0)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 4
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 554.2h, restarts: 0
- Last closer: 2026-09-04T03:00:52Z
- Last backfill: 2026-09-04T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 1

## Health 7d (window: 2026-08-28T06:00:02Z → 2026-09-04T06:00:02Z)
- New signals: 70 (~10.0/day)
- Closed: 65 (TP 26, SL 29, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 5
- TP rate 7d: 47.3%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1014
- Closed: 1009 (TP_clean 509, SL_clean 350, SL→reverse 0, Sideways 150, N/A 0)
- Ongoing (<24h): 5
- TP rate: 59.3% decided (TP/(TP+SL)) · 50.4% pointwise (excl N/A)

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
| 1014 | 04.09 | 05:33 | LAUSDT | LONG | ongoing | осторожно 62% |
| 1013 | 03.09 | 13:31 | ZKCUSDT | LONG | ongoing | осторожно 67% |
| 1012 | 03.09 | 13:30 | FLOCKUSDT | LONG | ongoing | осторожно 71% |
| 1011 | 03.09 | 10:05 | PYTHUSDT | LONG | ongoing | осторожно 61% |
| 1010 | 03.09 | 08:35 | FLOCKUSDT | SHORT | ongoing | осторожно 76% |
| 1009 | 03.09 | 03:00 | FLOCKUSDT | LONG | SL_clean | осторожно 75% |
| 1008 | 03.09 | 02:32 | SKRUSDT | SHORT | SL_clean | осторожно 69% |
| 1007 | 03.09 | 01:02 | TUTUSDT | SHORT | SL_clean | осторожно 60% |
| 1006 | 02.09 | 23:38 | ACEUSDT | LONG | TP_clean | осторожно 69% |
| 1005 | 02.09 | 23:08 | MORPHOUSDT | SHORT | TP_clean | осторожно 75% |
| 1004 | 02.09 | 23:05 | HOMEUSDT | LONG | TP_clean | осторожно 64% |
| 1003 | 02.09 | 21:10 | ZROUSDT | LONG | TP_clean | осторожно 64% |
| 1002 | 02.09 | 20:32 | FLOCKUSDT | SHORT | TP_clean | осторожно 64% |
| 1001 | 02.09 | 20:03 | TRUMPUSDT | SHORT | SL_clean | осторожно 63% |
| 1000 | 02.09 | 17:32 | CLUSDT | LONG | TP_clean | осторожно 65% |
| 999 | 02.09 | 16:34 | DASHUSDT | SHORT | Sideways | осторожно 76% |
| 998 | 02.09 | 15:05 | ZECUSDT | SHORT | SL_clean | осторожно 67% |
| 997 | 02.09 | 11:02 | KORUUSDT | SHORT | TP_clean | осторожно 61% |
| 996 | 02.09 | 10:04 | CRVUSDT | LONG | SL_clean | осторожно 61% |
| 995 | 02.09 | 08:07 | AAOIUSDT | SHORT | Sideways | осторожно 65% |
| 994 | 02.09 | 07:08 | UNITREEUSDT | SHORT | Sideways | осторожно 60% |
| 993 | 02.09 | 06:11 | SNDKUSDT | LONG | TP_clean | осторожно 60% |
| 992 | 02.09 | 06:05 | DEXEUSDT | SHORT | Sideways | осторожно 61% |
| 991 | 02.09 | 03:40 | KORUUSDT | SHORT | TP_clean | осторожно 60% |
| 990 | 02.09 | 03:30 | ACEUSDT | LONG | SL_clean | входить 84% |
| 989 | 02.09 | 01:08 | BICOUSDT | LONG | TP_clean | осторожно 61% |
| 988 | 02.09 | 00:37 | AAOIUSDT | SHORT | Sideways | осторожно 84% |
| 987 | 02.09 | 00:07 | HYPEUSDT | SHORT | Sideways | осторожно 68% |
| 986 | 01.09 | 21:33 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 85% |
| 985 | 01.09 | 20:02 | ACEUSDT | LONG | TP_clean | осторожно 64% |
| 984 | 01.09 | 19:37 | HYPEUSDT | SHORT | Sideways | осторожно 75% |
| 983 | 01.09 | 19:10 | COINUSDT | SHORT | TP_clean | осторожно 60% |
| 982 | 01.09 | 14:37 | CBRSUSDT | SHORT | TP_clean | осторожно 62% |
| 981 | 01.09 | 14:04 | BMNRUSDT | SHORT | TP_clean | осторожно 65% |
| 980 | 01.09 | 13:33 | ENSOUSDT | LONG | SL_clean | осторожно 65% |
| 979 | 01.09 | 07:01 | BTRUSDT | SHORT | SL_clean | осторожно 65% |
| 978 | 01.09 | 03:38 | CYSUSDT | SHORT | TP_clean | осторожно 66% |
| 977 | 01.09 | 01:03 | MAGMAUSDT | SHORT | SL_clean | осторожно 66% |
| 976 | 31.08 | 22:36 | ACEUSDT | SHORT | TP_clean | осторожно 60% |
| 975 | 31.08 | 22:10 | CXMTUSDT | SHORT | TP_clean | осторожно 71% |
| 974 | 31.08 | 19:30 | SNXXUSDT | LONG | SL_clean | осторожно 61% |
| 973 | 31.08 | 17:38 | MAGMAUSDT | SHORT | SL_clean | входить 87% |
| 972 | 31.08 | 17:35 | ZKCUSDT | LONG | SL_clean | осторожно 60% |
| 971 | 31.08 | 15:07 | DOTUSDT | SHORT | SL_clean | осторожно 61% |
| 970 | 31.08 | 15:03 | AXLUSDT | LONG | SL_clean | осторожно 67% |
| 969 | 31.08 | 14:43 | HOODUSDT | LONG | SL_clean | осторожно 61% |
| 968 | 31.08 | 11:02 | MIRAUSDT | LONG | SL_clean | осторожно 62% |
| 967 | 31.08 | 09:04 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 73% |
| 966 | 31.08 | 07:39 | ROBOUSDT | SHORT | TP_clean | осторожно 67% |
| 965 | 31.08 | 05:13 | ICPUSDT | SHORT | Sideways | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-05 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-04 06:30 UTC
- mmscan-snapshot: next run 2026-09-04 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
