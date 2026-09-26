# MM Scan Shadow Snapshot
Generated: 2026-09-26T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1094.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-26T15:03:00+0000 (#1276 QUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-25T18:00:01Z → 2026-09-26T18:00:01Z)
- New signals: 6 (LONG 4 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1094.2h, restarts: 0
- Last closer: 2026-09-26T03:00:45Z
- Last backfill: 2026-09-26T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 8

## Health 7d (window: 2026-09-19T18:00:01Z → 2026-09-26T18:00:01Z)
- New signals: 89 (~12.7/day)
- Closed: 75 (TP 38, SL 31, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 14
- TP rate 7d: 55.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1276
- Closed: 1262 (TP_clean 643, SL_clean 443, SL→reverse 0, Sideways 176, N/A 0)
- Ongoing (<24h): 14
- TP rate: 59.2% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 1276 | 26.09 | 18:03 | QUSDT | LONG | ongoing | осторожно 64% |
| 1275 | 26.09 | 13:36 | CLUSDT | LONG | ongoing | осторожно 65% |
| 1274 | 26.09 | 11:01 | 2ZUSDT | LONG | ongoing | осторожно 61% |
| 1273 | 25.09 | 22:34 | CLUSDT | SHORT | ongoing | осторожно 62% |
| 1272 | 25.09 | 22:02 | XPLUSDT | LONG | ongoing | осторожно 68% |
| 1271 | 25.09 | 21:08 | PENDLEUSDT | SHORT | ongoing | осторожно 61% |
| 1270 | 25.09 | 20:04 | UNIUSDT | LONG | ongoing | осторожно 62% |
| 1269 | 25.09 | 18:32 | INJUSDT | LONG | ongoing | осторожно 60% |
| 1268 | 25.09 | 18:31 | PHAUSDT | LONG | ongoing | осторожно 61% |
| 1267 | 25.09 | 17:34 | VETUSDT | LONG | ongoing | осторожно 90% |
| 1266 | 25.09 | 14:07 | CLUSDT | SHORT | ongoing | осторожно 70% |
| 1265 | 25.09 | 10:32 | BIOUSDT | SHORT | ongoing | входить 86% |
| 1264 | 25.09 | 06:03 | SUIUSDT | LONG | ongoing | осторожно 63% |
| 1263 | 25.09 | 06:01 | PHAUSDT | SHORT | ongoing | осторожно 69% |
| 1262 | 25.09 | 01:02 | EIGENUSDT | SHORT | TP_clean | осторожно 64% |
| 1261 | 24.09 | 23:31 | XAIUSDT | LONG | TP_clean | осторожно 64% |
| 1260 | 24.09 | 22:32 | GRASSUSDT | LONG | TP_clean | осторожно 63% |
| 1259 | 24.09 | 21:02 | COTIUSDT | LONG | TP_clean | осторожно 71% |
| 1258 | 24.09 | 20:03 | METUSDT | LONG | SL_clean | осторожно 62% |
| 1257 | 24.09 | 18:00 | 4USDT | SHORT | TP_clean | осторожно 65% |
| 1256 | 24.09 | 16:32 | LITUSDT | LONG | TP_clean | осторожно 72% |
| 1255 | 24.09 | 15:34 | GALAUSDT | SHORT | SL_clean | осторожно 62% |
| 1254 | 24.09 | 15:05 | CHZUSDT | SHORT | SL_clean | осторожно 68% |
| 1253 | 24.09 | 11:02 | BOMEUSDT | LONG | SL_clean | осторожно 62% |
| 1252 | 24.09 | 10:05 | DOTUSDT | SHORT | SL_clean | осторожно 62% |
| 1251 | 24.09 | 09:08 | MRVLUSDT | SHORT | Sideways | осторожно 62% |
| 1250 | 24.09 | 07:38 | MUBARAKUSDT | SHORT | SL_clean | входить 81% |
| 1249 | 24.09 | 06:06 | MUUSDT | SHORT | Sideways | осторожно 79% |
| 1248 | 24.09 | 03:06 | API3USDT | SHORT | TP_clean | осторожно 61% |
| 1247 | 23.09 | 22:09 | BIOUSDT | SHORT | SL_clean | осторожно 66% |
| 1246 | 23.09 | 21:36 | SKYUSDT | SHORT | TP_clean | осторожно 62% |
| 1245 | 23.09 | 19:38 | SKHYUSDT | SHORT | TP_clean | осторожно 62% |
| 1244 | 23.09 | 19:09 | DELLUSDT | SHORT | TP_clean | осторожно 63% |
| 1243 | 23.09 | 17:33 | SAMSUNGUSDT | SHORT | Sideways | осторожно 73% |
| 1242 | 23.09 | 13:06 | PEOPLEUSDT | SHORT | TP_clean | осторожно 61% |
| 1241 | 23.09 | 09:32 | ARBUSDT | LONG | SL_clean | осторожно 60% |
| 1240 | 23.09 | 08:07 | CYSUSDT | LONG | SL_clean | осторожно 60% |
| 1239 | 23.09 | 07:36 | LITEUSDT | LONG | Sideways | осторожно 67% |
| 1238 | 23.09 | 06:40 | DELLUSDT | SHORT | SL_clean | осторожно 78% |
| 1237 | 23.09 | 01:34 | 1000PEPEUSDT | LONG | SL_clean | осторожно 64% |
| 1236 | 22.09 | 23:38 | CHIPUSDT | LONG | TP_clean | осторожно 62% |
| 1235 | 22.09 | 21:09 | UNIUSDT | LONG | TP_clean | осторожно 60% |
| 1234 | 22.09 | 20:34 | ALLOUSDT | LONG | TP_clean | осторожно 65% |
| 1233 | 22.09 | 20:07 | BABAUSDT | SHORT | TP_clean | осторожно 86% |
| 1232 | 22.09 | 19:40 | ENSUSDT | LONG | TP_clean | осторожно 64% |
| 1231 | 22.09 | 19:30 | WIFUSDT | LONG | SL_clean | осторожно 70% |
| 1230 | 22.09 | 19:10 | SOXSUSDT | SHORT | TP_clean | осторожно 62% |
| 1229 | 22.09 | 19:06 | PENDLEUSDT | SHORT | SL_clean | осторожно 60% |
| 1228 | 22.09 | 16:36 | KORUUSDT | LONG | TP_clean | осторожно 69% |
| 1227 | 22.09 | 15:14 | BNBUSDT | SHORT | Sideways | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-27 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-26 18:30 UTC
- mmscan-snapshot: next run 2026-09-27 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
