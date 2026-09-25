# MM Scan Shadow Snapshot
Generated: 2026-09-25T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1064.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-25T11:07:18+0000 (#1266 CLUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-24T12:00:01Z → 2026-09-25T12:00:01Z)
- New signals: 13 (LONG 6 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1064.2h, restarts: 0
- Last closer: 2026-09-25T03:00:24Z
- Last backfill: 2026-09-25T11:30:03Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-09-18T12:00:01Z → 2026-09-25T12:00:01Z)
- New signals: 90 (~12.9/day)
- Closed: 72 (TP 38, SL 29, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 18
- TP rate 7d: 56.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1266
- Closed: 1248 (TP_clean 637, SL_clean 437, SL→reverse 0, Sideways 174, N/A 0)
- Ongoing (<24h): 18
- TP rate: 59.3% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 1266 | 25.09 | 14:07 | CLUSDT | SHORT | ongoing | осторожно 70% |
| 1265 | 25.09 | 10:32 | BIOUSDT | SHORT | ongoing | входить 86% |
| 1264 | 25.09 | 06:03 | SUIUSDT | LONG | ongoing | осторожно 63% |
| 1263 | 25.09 | 06:01 | PHAUSDT | SHORT | ongoing | осторожно 69% |
| 1262 | 25.09 | 01:02 | EIGENUSDT | SHORT | ongoing | осторожно 64% |
| 1261 | 24.09 | 23:31 | XAIUSDT | LONG | ongoing | осторожно 64% |
| 1260 | 24.09 | 22:32 | GRASSUSDT | LONG | ongoing | осторожно 63% |
| 1259 | 24.09 | 21:02 | COTIUSDT | LONG | ongoing | осторожно 71% |
| 1258 | 24.09 | 20:03 | METUSDT | LONG | ongoing | осторожно 62% |
| 1257 | 24.09 | 18:00 | 4USDT | SHORT | ongoing | осторожно 65% |
| 1256 | 24.09 | 16:32 | LITUSDT | LONG | ongoing | осторожно 72% |
| 1255 | 24.09 | 15:34 | GALAUSDT | SHORT | ongoing | осторожно 62% |
| 1254 | 24.09 | 15:05 | CHZUSDT | SHORT | ongoing | осторожно 68% |
| 1253 | 24.09 | 11:02 | BOMEUSDT | LONG | ongoing | осторожно 62% |
| 1252 | 24.09 | 10:05 | DOTUSDT | SHORT | ongoing | осторожно 62% |
| 1251 | 24.09 | 09:08 | MRVLUSDT | SHORT | ongoing | осторожно 62% |
| 1250 | 24.09 | 07:38 | MUBARAKUSDT | SHORT | ongoing | входить 81% |
| 1249 | 24.09 | 06:06 | MUUSDT | SHORT | ongoing | осторожно 79% |
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
| 1226 | 22.09 | 14:34 | AAOIUSDT | SHORT | TP_clean | осторожно 67% |
| 1225 | 22.09 | 13:05 | WIFUSDT | LONG | TP_clean | осторожно 60% |
| 1224 | 22.09 | 12:00 | SANDUSDT | LONG | SL_clean | осторожно 61% |
| 1223 | 22.09 | 11:06 | ASTERUSDT | SHORT | TP_clean | осторожно 65% |
| 1222 | 22.09 | 10:06 | AAOIUSDT | SHORT | TP_clean | осторожно 74% |
| 1221 | 22.09 | 10:05 | KERNELUSDT | LONG | TP_clean | осторожно 61% |
| 1220 | 22.09 | 02:35 | ASTERUSDT | SHORT | TP_clean | осторожно 70% |
| 1219 | 22.09 | 02:34 | KERNELUSDT | LONG | TP_clean | осторожно 61% |
| 1218 | 21.09 | 23:30 | PHAUSDT | LONG | SL_clean | осторожно 61% |
| 1217 | 21.09 | 23:09 | MYXUSDT | LONG | SL_clean | осторожно 68% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-26 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-25 12:30 UTC
- mmscan-snapshot: next run 2026-09-25 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
