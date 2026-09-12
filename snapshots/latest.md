# MM Scan Shadow Snapshot
Generated: 2026-09-12T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 746.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-12T03:17:14+0000 (#1105 BTCUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-11T06:00:02Z → 2026-09-12T06:00:02Z)
- New signals: 15 (LONG 7 / SHORT 8)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 746.2h, restarts: 0
- Last closer: 2026-09-12T03:00:53Z
- Last backfill: 2026-09-12T05:30:03Z
- Anomalies: none

## Health 7d (window: 2026-09-05T06:00:02Z → 2026-09-12T06:00:02Z)
- New signals: 82 (~11.7/day)
- Closed: 67 (TP 40, SL 23, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 15
- TP rate 7d: 63.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1105
- Closed: 1090 (TP_clean 554, SL_clean 379, SL→reverse 0, Sideways 157, N/A 0)
- Ongoing (<24h): 15
- TP rate: 59.4% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1105 | 12.09 | 06:17 | BTCUSDT | LONG | ongoing | осторожно 63% |
| 1104 | 12.09 | 05:45 | ACEUSDT | SHORT | ongoing | осторожно 64% |
| 1103 | 12.09 | 05:38 | BTWUSDT | LONG | ongoing | осторожно 62% |
| 1102 | 12.09 | 04:42 | LDOUSDT | LONG | ongoing | осторожно 67% |
| 1101 | 12.09 | 04:32 | TREEUSDT | SHORT | ongoing | осторожно 64% |
| 1100 | 12.09 | 02:32 | SAGAUSDT | LONG | ongoing | осторожно 63% |
| 1099 | 12.09 | 02:10 | MARSCOINUSDT | LONG | ongoing | осторожно 63% |
| 1098 | 12.09 | 00:13 | XRPUSDT | LONG | ongoing | осторожно 67% |
| 1097 | 11.09 | 21:09 | OPUSDT | SHORT | ongoing | осторожно 78% |
| 1096 | 11.09 | 18:00 | LABUSDT | SHORT | ongoing | осторожно 62% |
| 1095 | 11.09 | 17:04 | CRCLUSDT | SHORT | ongoing | осторожно 63% |
| 1094 | 11.09 | 14:01 | ZHONGJIUSDT | SHORT | ongoing | осторожно 60% |
| 1093 | 11.09 | 13:31 | RVNUSDT | SHORT | ongoing | осторожно 70% |
| 1092 | 11.09 | 11:01 | LSKUSDT | LONG | ongoing | осторожно 61% |
| 1091 | 11.09 | 10:35 | TAOUSDT | SHORT | ongoing | осторожно 66% |
| 1090 | 11.09 | 05:31 | ACEUSDT | SHORT | SL_clean | осторожно 75% |
| 1089 | 11.09 | 05:10 | POLUSDT | SHORT | SL_clean | осторожно 61% |
| 1088 | 11.09 | 05:02 | WLDUSDT | SHORT | TP_clean | осторожно 68% |
| 1087 | 11.09 | 03:03 | INTCUSDT | SHORT | SL_clean | осторожно 61% |
| 1086 | 11.09 | 02:07 | PENGUUSDT | SHORT | TP_clean | осторожно 71% |
| 1085 | 11.09 | 01:39 | WDCUSDT | SHORT | TP_clean | осторожно 62% |
| 1084 | 11.09 | 01:02 | XRPUSDT | SHORT | SL_clean | осторожно 68% |
| 1083 | 11.09 | 01:02 | XLMUSDT | SHORT | SL_clean | осторожно 74% |
| 1082 | 11.09 | 00:31 | SOPHUSDT | SHORT | TP_clean | осторожно 80% |
| 1081 | 10.09 | 23:04 | VVVUSDT | LONG | SL_clean | осторожно 65% |
| 1080 | 10.09 | 23:03 | 1000BONKUSDT | SHORT | SL_clean | осторожно 62% |
| 1079 | 10.09 | 22:33 | BOMEUSDT | SHORT | TP_clean | осторожно 61% |
| 1078 | 10.09 | 22:09 | TQQQUSDT | SHORT | Sideways | осторожно 62% |
| 1077 | 10.09 | 22:05 | REUSDT | SHORT | TP_clean | осторожно 66% |
| 1076 | 10.09 | 22:01 | USELESSUSDT | SHORT | TP_clean | осторожно 70% |
| 1075 | 10.09 | 21:11 | TRUMPUSDT | SHORT | TP_clean | осторожно 61% |
| 1074 | 10.09 | 21:02 | CRWVUSDT | SHORT | TP_clean | осторожно 64% |
| 1073 | 10.09 | 20:10 | PONSUSDT | SHORT | TP_clean | осторожно 67% |
| 1072 | 10.09 | 20:03 | VETUSDT | LONG | SL_clean | осторожно 73% |
| 1071 | 10.09 | 17:32 | KATUSDT | LONG | SL_clean | осторожно 63% |
| 1070 | 10.09 | 15:37 | USELESSUSDT | SHORT | TP_clean | входить 90% |
| 1069 | 10.09 | 13:05 | 1000BONKUSDT | SHORT | TP_clean | осторожно 62% |
| 1068 | 10.09 | 11:01 | ARKUSDT | LONG | SL_clean | осторожно 73% |
| 1067 | 10.09 | 11:01 | ANIMEUSDT | LONG | SL_clean | осторожно 79% |
| 1066 | 10.09 | 10:34 | SUIUSDT | SHORT | TP_clean | осторожно 74% |
| 1065 | 10.09 | 10:33 | PENDLEUSDT | SHORT | TP_clean | осторожно 64% |
| 1064 | 10.09 | 07:40 | SOXLUSDT | LONG | SL_clean | осторожно 66% |
| 1063 | 10.09 | 06:39 | POLUSDT | LONG | SL_clean | осторожно 63% |
| 1062 | 10.09 | 04:32 | DEXEUSDT | SHORT | SL_clean | осторожно 69% |
| 1061 | 10.09 | 04:04 | SNXXUSDT | SHORT | TP_clean | осторожно 60% |
| 1060 | 10.09 | 02:34 | SKHYUSDT | LONG | SL_clean | осторожно 63% |
| 1059 | 10.09 | 01:37 | DELLUSDT | SHORT | TP_clean | осторожно 65% |
| 1058 | 09.09 | 20:32 | CRDOUSDT | SHORT | TP_clean | осторожно 61% |
| 1057 | 09.09 | 19:06 | AVGOUSDT | SHORT | Sideways | осторожно 60% |
| 1056 | 09.09 | 15:00 | KATUSDT | LONG | TP_clean | осторожно 83% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-13 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-12 06:30 UTC
- mmscan-snapshot: next run 2026-09-12 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
