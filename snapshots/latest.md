# MM Scan Shadow Snapshot
Generated: 2026-09-06T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 602.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-06T04:36:50+0000 (#1029 PENDLEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-05T06:00:01Z → 2026-09-06T06:00:01Z)
- New signals: 6 (LONG 4 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 602.2h, restarts: 0
- Last closer: 2026-09-06T03:00:23Z
- Last backfill: 2026-09-06T05:30:02Z
- Anomalies: none

## Health 7d (window: 2026-08-30T06:00:01Z → 2026-09-06T06:00:01Z)
- New signals: 73 (~10.4/day)
- Closed: 67 (TP 25, SL 31, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 6
- TP rate 7d: 44.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1029
- Closed: 1023 (TP_clean 514, SL_clean 356, SL→reverse 0, Sideways 153, N/A 0)
- Ongoing (<24h): 6
- TP rate: 59.1% decided (TP/(TP+SL)) · 50.2% pointwise (excl N/A)

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
| 1029 | 06.09 | 07:36 | PENDLEUSDT | LONG | ongoing | осторожно 69% |
| 1028 | 05.09 | 23:36 | VELVETUSDT | SHORT | ongoing | осторожно 63% |
| 1027 | 05.09 | 23:35 | 1000PEPEUSDT | LONG | ongoing | осторожно 60% |
| 1026 | 05.09 | 18:04 | SPXUSDT | SHORT | ongoing | осторожно 61% |
| 1025 | 05.09 | 14:01 | FLOCKUSDT | LONG | ongoing | входить 81% |
| 1024 | 05.09 | 12:32 | COTIUSDT | LONG | ongoing | осторожно 60% |
| 1023 | 05.09 | 03:36 | XRPUSDT | SHORT | Sideways | осторожно 62% |
| 1022 | 05.09 | 03:08 | ETHUSDT | SHORT | Sideways | осторожно 61% |
| 1021 | 05.09 | 01:37 | RENDERUSDT | SHORT | SL_clean | осторожно 71% |
| 1020 | 04.09 | 21:09 | WLFIUSDT | SHORT | Sideways | осторожно 60% |
| 1019 | 04.09 | 20:05 | DOTUSDT | SHORT | SL_clean | осторожно 60% |
| 1018 | 04.09 | 19:04 | COTIUSDT | LONG | TP_clean | осторожно 76% |
| 1017 | 04.09 | 15:32 | ASTERUSDT | SHORT | SL_clean | осторожно 70% |
| 1016 | 04.09 | 13:01 | BICOUSDT | LONG | TP_clean | осторожно 71% |
| 1015 | 04.09 | 12:38 | UAIUSDT | SHORT | SL_clean | осторожно 73% |
| 1014 | 04.09 | 05:33 | LAUSDT | LONG | TP_clean | осторожно 62% |
| 1013 | 03.09 | 13:31 | ZKCUSDT | LONG | TP_clean | осторожно 67% |
| 1012 | 03.09 | 13:30 | FLOCKUSDT | LONG | TP_clean | осторожно 71% |
| 1011 | 03.09 | 10:05 | PYTHUSDT | LONG | SL_clean | осторожно 61% |
| 1010 | 03.09 | 08:35 | FLOCKUSDT | SHORT | SL_clean | осторожно 76% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-09-07 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-06 06:30 UTC
- mmscan-snapshot: next run 2026-09-06 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
