# MM Scan Shadow Snapshot
Generated: 2026-09-28T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1124.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-27T22:08:12+0000 (#1289 KITEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-27T00:00:01Z → 2026-09-28T00:00:01Z)
- New signals: 11 (LONG 9 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1124.2h, restarts: 0
- Last closer: 2026-09-27T03:00:24Z
- Last backfill: 2026-09-27T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-09-21T00:00:01Z → 2026-09-28T00:00:01Z)
- New signals: 84 (~12.0/day)
- Closed: 68 (TP 34, SL 27, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 16
- TP rate 7d: 55.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1289
- Closed: 1273 (TP_clean 646, SL_clean 450, SL→reverse 0, Sideways 177, N/A 0)
- Ongoing (<24h): 16
- TP rate: 58.9% decided (TP/(TP+SL)) · 50.7% pointwise (excl N/A)

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
| 1289 | 28.09 | 01:08 | KITEUSDT | LONG | ongoing | осторожно 63% |
| 1288 | 28.09 | 00:03 | XAIUSDT | LONG | ongoing | осторожно 62% |
| 1287 | 27.09 | 22:36 | TUSDT | LONG | ongoing | осторожно 65% |
| 1286 | 27.09 | 21:37 | ZECUSDT | LONG | ongoing | осторожно 64% |
| 1285 | 27.09 | 20:02 | BTWUSDT | SHORT | ongoing | осторожно 73% |
| 1284 | 27.09 | 13:31 | WUSDT | LONG | ongoing | осторожно 61% |
| 1283 | 27.09 | 08:30 | RAREUSDT | LONG | ongoing | осторожно 79% |
| 1282 | 27.09 | 07:01 | QNTUSDT | LONG | ongoing | входить 81% |
| 1281 | 27.09 | 06:11 | VETUSDT | SHORT | ongoing | осторожно 68% |
| 1280 | 27.09 | 04:31 | ESPUSDT | LONG | ongoing | осторожно 65% |
| 1279 | 27.09 | 03:01 | SUIUSDT | LONG | ongoing | осторожно 69% |
| 1278 | 26.09 | 22:00 | RAREUSDT | LONG | ongoing | осторожно 61% |
| 1277 | 26.09 | 21:32 | DOTUSDT | LONG | ongoing | осторожно 60% |
| 1276 | 26.09 | 18:03 | QUSDT | LONG | ongoing | осторожно 64% |
| 1275 | 26.09 | 13:36 | CLUSDT | LONG | ongoing | осторожно 65% |
| 1274 | 26.09 | 11:01 | 2ZUSDT | LONG | ongoing | осторожно 61% |
| 1273 | 25.09 | 22:34 | CLUSDT | SHORT | SL_clean | осторожно 62% |
| 1272 | 25.09 | 22:02 | XPLUSDT | LONG | SL_clean | осторожно 68% |
| 1271 | 25.09 | 21:08 | PENDLEUSDT | SHORT | Sideways | осторожно 61% |
| 1270 | 25.09 | 20:04 | UNIUSDT | LONG | TP_clean | осторожно 62% |
| 1269 | 25.09 | 18:32 | INJUSDT | LONG | SL_clean | осторожно 60% |
| 1268 | 25.09 | 18:31 | PHAUSDT | LONG | SL_clean | осторожно 61% |
| 1267 | 25.09 | 17:34 | VETUSDT | LONG | TP_clean | осторожно 90% |
| 1266 | 25.09 | 14:07 | CLUSDT | SHORT | SL_clean | осторожно 70% |
| 1265 | 25.09 | 10:32 | BIOUSDT | SHORT | SL_clean | входить 86% |
| 1264 | 25.09 | 06:03 | SUIUSDT | LONG | TP_clean | осторожно 63% |
| 1263 | 25.09 | 06:01 | PHAUSDT | SHORT | SL_clean | осторожно 69% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-09-28 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-28 00:30 UTC
- mmscan-snapshot: next run 2026-09-28 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
