# MM Scan Shadow Snapshot
Generated: 2026-09-16T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 842.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-16T05:06:34+0000 (#1152 VETUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-15T06:00:01Z → 2026-09-16T06:00:01Z)
- New signals: 13 (LONG 3 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 842.2h, restarts: 0
- Last closer: 2026-09-16T03:00:26Z
- Last backfill: 2026-09-16T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-09-09T06:00:01Z → 2026-09-16T06:00:01Z)
- New signals: 100 (~14.3/day)
- Closed: 84 (TP 43, SL 29, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 16
- TP rate 7d: 59.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1152
- Closed: 1136 (TP_clean 577, SL_clean 392, SL→reverse 0, Sideways 167, N/A 0)
- Ongoing (<24h): 16
- TP rate: 59.5% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1152 | 16.09 | 08:06 | VETUSDT | SHORT | ongoing | осторожно 60% |
| 1151 | 16.09 | 06:12 | BNCUSDT | SHORT | ongoing | осторожно 61% |
| 1150 | 16.09 | 05:04 | AXLUSDT | SHORT | ongoing | осторожно 76% |
| 1149 | 16.09 | 03:34 | ETHFIUSDT | SHORT | ongoing | осторожно 66% |
| 1148 | 16.09 | 00:37 | HYPEUSDT | SHORT | ongoing | осторожно 62% |
| 1147 | 16.09 | 00:01 | MONUSDT | SHORT | ongoing | осторожно 68% |
| 1146 | 15.09 | 22:03 | AXLUSDT | LONG | ongoing | осторожно 65% |
| 1145 | 15.09 | 20:05 | RENDERUSDT | SHORT | ongoing | осторожно 62% |
| 1144 | 15.09 | 18:02 | MINIMAXUSDT | SHORT | ongoing | осторожно 71% |
| 1143 | 15.09 | 11:37 | MTLUSDT | LONG | ongoing | осторожно 69% |
| 1142 | 15.09 | 11:07 | KORUUSDT | SHORT | ongoing | осторожно 66% |
| 1141 | 15.09 | 11:00 | CAPUSDT | LONG | ongoing | осторожно 61% |
| 1140 | 15.09 | 09:34 | CXMTUSDT | SHORT | ongoing | осторожно 84% |
| 1139 | 15.09 | 07:39 | FFUSDT | SHORT | ongoing | осторожно 60% |
| 1138 | 15.09 | 06:13 | HYPEUSDT | SHORT | ongoing | осторожно 73% |
| 1137 | 15.09 | 06:12 | SOXLUSDT | SHORT | ongoing | осторожно 60% |
| 1136 | 15.09 | 05:34 | UNITREEUSDT | LONG | Sideways | осторожно 71% |
| 1135 | 15.09 | 05:03 | LABUSDT | SHORT | TP_clean | осторожно 74% |
| 1134 | 15.09 | 03:33 | ARKUSDT | LONG | SL_clean | осторожно 61% |
| 1133 | 15.09 | 03:12 | SPCXUSDT | LONG | SL_clean | осторожно 66% |
| 1132 | 15.09 | 01:10 | SOPHUSDT | SHORT | SL_clean | осторожно 61% |
| 1131 | 14.09 | 23:08 | ICPUSDT | LONG | SL_clean | осторожно 61% |
| 1130 | 14.09 | 21:02 | CVCUSDT | LONG | SL_clean | входить 90% |
| 1129 | 14.09 | 20:08 | MINAUSDT | SHORT | TP_clean | осторожно 63% |
| 1128 | 14.09 | 19:05 | ORCLUSDT | SHORT | Sideways | осторожно 68% |
| 1127 | 14.09 | 16:03 | MTLUSDT | LONG | TP_clean | осторожно 61% |
| 1126 | 14.09 | 14:38 | ALGOUSDT | SHORT | Sideways | осторожно 73% |
| 1125 | 14.09 | 14:32 | TUSDT | LONG | TP_clean | осторожно 61% |
| 1124 | 14.09 | 08:38 | ICPUSDT | LONG | SL_clean | осторожно 63% |
| 1123 | 14.09 | 06:07 | DELLUSDT | LONG | SL_clean | осторожно 79% |
| 1122 | 14.09 | 06:06 | BLURUSDT | LONG | SL_clean | осторожно 60% |
| 1121 | 14.09 | 01:05 | STEEMUSDT | LONG | SL_clean | осторожно 76% |
| 1120 | 13.09 | 21:37 | FLOCKUSDT | LONG | TP_clean | осторожно 66% |
| 1119 | 13.09 | 19:00 | CVCUSDT | LONG | SL_clean | осторожно 61% |
| 1118 | 13.09 | 15:31 | POLYXUSDT | LONG | TP_clean | осторожно 61% |
| 1117 | 13.09 | 11:31 | CVCUSDT | LONG | TP_clean | осторожно 67% |
| 1116 | 13.09 | 11:01 | STEEMUSDT | LONG | TP_clean | осторожно 61% |
| 1115 | 13.09 | 09:06 | LITUSDT | SHORT | TP_clean | осторожно 76% |
| 1114 | 13.09 | 03:31 | IOSTUSDT | SHORT | TP_clean | осторожно 68% |
| 1113 | 13.09 | 03:06 | PUNDIXUSDT | LONG | TP_clean | осторожно 67% |
| 1112 | 12.09 | 20:32 | LSKUSDT | LONG | TP_clean | осторожно 62% |
| 1111 | 12.09 | 20:00 | PUNDIXUSDT | LONG | TP_clean | осторожно 86% |
| 1110 | 12.09 | 16:00 | LSKUSDT | LONG | TP_clean | входить 86% |
| 1109 | 12.09 | 13:06 | BCHUSDT | LONG | SL_clean | осторожно 62% |
| 1108 | 12.09 | 10:25 | ADAUSDT | LONG | Sideways | осторожно 63% |
| 1107 | 12.09 | 10:05 | INJUSDT | LONG | TP_clean | осторожно 60% |
| 1106 | 12.09 | 09:19 | EDGEUSDT | SHORT | SL_clean | осторожно 75% |
| 1105 | 12.09 | 06:17 | BTCUSDT | LONG | Sideways | осторожно 63% |
| 1104 | 12.09 | 05:45 | ACEUSDT | SHORT | TP_clean | осторожно 64% |
| 1103 | 12.09 | 05:38 | BTWUSDT | LONG | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-17 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-16 06:30 UTC
- mmscan-snapshot: next run 2026-09-16 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
