# MM Scan Shadow Snapshot
Generated: 2026-09-14T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 788.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-13T22:05:40+0000 (#1121 STEEMUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-13T00:00:01Z → 2026-09-14T00:00:01Z)
- New signals: 9 (LONG 7 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 788.2h, restarts: 0
- Last closer: 2026-09-13T03:00:38Z
- Last backfill: 2026-09-13T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 8

## Health 7d (window: 2026-09-07T00:00:01Z → 2026-09-14T00:00:01Z)
- New signals: 85 (~12.1/day)
- Closed: 68 (TP 40, SL 20, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 17
- TP rate 7d: 66.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1121
- Closed: 1104 (TP_clean 562, SL_clean 380, SL→reverse 0, Sideways 162, N/A 0)
- Ongoing (<24h): 17
- TP rate: 59.7% decided (TP/(TP+SL)) · 50.9% pointwise (excl N/A)

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
| 1121 | 14.09 | 01:05 | STEEMUSDT | LONG | ongoing | осторожно 76% |
| 1120 | 13.09 | 21:37 | FLOCKUSDT | LONG | ongoing | осторожно 66% |
| 1119 | 13.09 | 19:00 | CVCUSDT | LONG | ongoing | осторожно 61% |
| 1118 | 13.09 | 15:31 | POLYXUSDT | LONG | ongoing | осторожно 61% |
| 1117 | 13.09 | 11:31 | CVCUSDT | LONG | ongoing | осторожно 67% |
| 1116 | 13.09 | 11:01 | STEEMUSDT | LONG | ongoing | осторожно 61% |
| 1115 | 13.09 | 09:06 | LITUSDT | SHORT | ongoing | осторожно 76% |
| 1114 | 13.09 | 03:31 | IOSTUSDT | SHORT | ongoing | осторожно 68% |
| 1113 | 13.09 | 03:06 | PUNDIXUSDT | LONG | ongoing | осторожно 67% |
| 1112 | 12.09 | 20:32 | LSKUSDT | LONG | ongoing | осторожно 62% |
| 1111 | 12.09 | 20:00 | PUNDIXUSDT | LONG | ongoing | осторожно 86% |
| 1110 | 12.09 | 16:00 | LSKUSDT | LONG | ongoing | входить 86% |
| 1109 | 12.09 | 13:06 | BCHUSDT | LONG | ongoing | осторожно 62% |
| 1108 | 12.09 | 10:25 | ADAUSDT | LONG | ongoing | осторожно 63% |
| 1107 | 12.09 | 10:05 | INJUSDT | LONG | ongoing | осторожно 60% |
| 1106 | 12.09 | 09:19 | EDGEUSDT | SHORT | ongoing | осторожно 75% |
| 1105 | 12.09 | 06:17 | BTCUSDT | LONG | ongoing | осторожно 63% |
| 1104 | 12.09 | 05:45 | ACEUSDT | SHORT | TP_clean | осторожно 64% |
| 1103 | 12.09 | 05:38 | BTWUSDT | LONG | TP_clean | осторожно 62% |
| 1102 | 12.09 | 04:42 | LDOUSDT | LONG | Sideways | осторожно 67% |
| 1101 | 12.09 | 04:32 | TREEUSDT | SHORT | TP_clean | осторожно 64% |
| 1100 | 12.09 | 02:32 | SAGAUSDT | LONG | TP_clean | осторожно 63% |
| 1099 | 12.09 | 02:10 | MARSCOINUSDT | LONG | TP_clean | осторожно 63% |
| 1098 | 12.09 | 00:13 | XRPUSDT | LONG | Sideways | осторожно 67% |
| 1097 | 11.09 | 21:09 | OPUSDT | SHORT | Sideways | осторожно 78% |
| 1096 | 11.09 | 18:00 | LABUSDT | SHORT | SL_clean | осторожно 62% |
| 1095 | 11.09 | 17:04 | CRCLUSDT | SHORT | TP_clean | осторожно 63% |
| 1094 | 11.09 | 14:01 | ZHONGJIUSDT | SHORT | Sideways | осторожно 60% |
| 1093 | 11.09 | 13:31 | RVNUSDT | SHORT | Sideways | осторожно 70% |
| 1092 | 11.09 | 11:01 | LSKUSDT | LONG | TP_clean | осторожно 61% |
| 1091 | 11.09 | 10:35 | TAOUSDT | SHORT | TP_clean | осторожно 66% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-09-14 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-14 00:30 UTC
- mmscan-snapshot: next run 2026-09-14 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
