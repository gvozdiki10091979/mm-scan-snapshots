# MM Scan Shadow Snapshot
Generated: 2026-09-18T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 896.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-18T08:04:11+0000 (#1176 AVAUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-17T12:00:01Z → 2026-09-18T12:00:01Z)
- New signals: 6 (LONG 4 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 896.2h, restarts: 0
- Last closer: 2026-09-18T03:00:32Z
- Last backfill: 2026-09-18T11:30:03Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-09-11T12:00:01Z → 2026-09-18T12:00:01Z)
- New signals: 82 (~11.7/day)
- Closed: 73 (TP 36, SL 27, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 9
- TP rate 7d: 57.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1176
- Closed: 1167 (TP_clean 592, SL_clean 406, SL→reverse 0, Sideways 169, N/A 0)
- Ongoing (<24h): 9
- TP rate: 59.3% decided (TP/(TP+SL)) · 50.7% pointwise (excl N/A)

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
| 1176 | 18.09 | 11:04 | AVAUSDT | LONG | ongoing | осторожно 61% |
| 1175 | 18.09 | 04:01 | AEROUSDT | LONG | ongoing | осторожно 64% |
| 1174 | 18.09 | 01:31 | DASHUSDT | LONG | ongoing | осторожно 63% |
| 1173 | 18.09 | 01:00 | TUTUSDT | LONG | ongoing | осторожно 60% |
| 1172 | 17.09 | 22:02 | POWERUSDT | SHORT | ongoing | осторожно 61% |
| 1171 | 17.09 | 17:37 | POWERUSDT | SHORT | ongoing | осторожно 77% |
| 1170 | 17.09 | 14:08 | COINUSDT | SHORT | ongoing | осторожно 66% |
| 1169 | 17.09 | 14:03 | KORUUSDT | LONG | ongoing | осторожно 62% |
| 1168 | 17.09 | 06:08 | KORUUSDT | SHORT | ongoing | осторожно 62% |
| 1167 | 17.09 | 04:02 | LAUSDT | LONG | SL_clean | осторожно 61% |
| 1166 | 17.09 | 04:00 | BRUSDT | LONG | TP_clean | осторожно 67% |
| 1165 | 17.09 | 01:31 | CRVUSDT | SHORT | SL_clean | осторожно 72% |
| 1164 | 17.09 | 01:04 | KORUUSDT | SHORT | SL_clean | осторожно 62% |
| 1163 | 16.09 | 21:36 | LITUSDT | SHORT | TP_clean | осторожно 74% |
| 1162 | 16.09 | 21:08 | CRCLUSDT | SHORT | TP_clean | осторожно 70% |
| 1161 | 16.09 | 20:41 | SOLUSDT | SHORT | SL_clean | осторожно 70% |
| 1160 | 16.09 | 20:40 | ORDIUSDT | SHORT | SL_clean | осторожно 63% |
| 1159 | 16.09 | 20:04 | ATOMUSDT | SHORT | SL_clean | осторожно 68% |
| 1158 | 16.09 | 16:37 | ONUSDT | SHORT | SL_clean | осторожно 89% |
| 1157 | 16.09 | 16:05 | XMRUSDT | SHORT | TP_clean | осторожно 61% |
| 1156 | 16.09 | 14:07 | SOLUSDT | SHORT | SL_clean | осторожно 69% |
| 1155 | 16.09 | 13:38 | KAITOUSDT | SHORT | SL_clean | осторожно 65% |
| 1154 | 16.09 | 12:06 | AKEUSDT | LONG | TP_clean | осторожно 66% |
| 1153 | 16.09 | 10:38 | 1000BONKUSDT | SHORT | TP_clean | осторожно 61% |
| 1152 | 16.09 | 08:06 | VETUSDT | SHORT | TP_clean | осторожно 60% |
| 1151 | 16.09 | 06:12 | BNCUSDT | SHORT | Sideways | осторожно 61% |
| 1150 | 16.09 | 05:04 | AXLUSDT | SHORT | TP_clean | осторожно 76% |
| 1149 | 16.09 | 03:34 | ETHFIUSDT | SHORT | TP_clean | осторожно 66% |
| 1148 | 16.09 | 00:37 | HYPEUSDT | SHORT | SL_clean | осторожно 62% |
| 1147 | 16.09 | 00:01 | MONUSDT | SHORT | SL_clean | осторожно 68% |
| 1146 | 15.09 | 22:03 | AXLUSDT | LONG | SL_clean | осторожно 65% |
| 1145 | 15.09 | 20:05 | RENDERUSDT | SHORT | TP_clean | осторожно 62% |
| 1144 | 15.09 | 18:02 | MINIMAXUSDT | SHORT | TP_clean | осторожно 71% |
| 1143 | 15.09 | 11:37 | MTLUSDT | LONG | SL_clean | осторожно 69% |
| 1142 | 15.09 | 11:07 | KORUUSDT | SHORT | TP_clean | осторожно 66% |
| 1141 | 15.09 | 11:00 | CAPUSDT | LONG | TP_clean | осторожно 61% |
| 1140 | 15.09 | 09:34 | CXMTUSDT | SHORT | Sideways | осторожно 84% |
| 1139 | 15.09 | 07:39 | FFUSDT | SHORT | SL_clean | осторожно 60% |
| 1138 | 15.09 | 06:13 | HYPEUSDT | SHORT | TP_clean | осторожно 73% |
| 1137 | 15.09 | 06:12 | SOXLUSDT | SHORT | TP_clean | осторожно 60% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-09-19 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-18 12:30 UTC
- mmscan-snapshot: next run 2026-09-18 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
