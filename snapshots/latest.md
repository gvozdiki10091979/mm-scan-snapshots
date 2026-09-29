# MM Scan Shadow Snapshot
Generated: 2026-09-29T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1154.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-29T04:34:20+0000 (#1313 VIRTUALUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-28T06:00:01Z → 2026-09-29T06:00:01Z)
- New signals: 18 (LONG 1 / SHORT 17)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 18
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1154.2h, restarts: 0
- Last closer: 2026-09-29T03:00:42Z
- Last backfill: 2026-09-29T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 2

## Health 7d (window: 2026-09-22T06:00:01Z → 2026-09-29T06:00:01Z)
- New signals: 93 (~13.3/day)
- Closed: 73 (TP 34, SL 31, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 20
- TP rate 7d: 52.3%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1313
- Closed: 1293 (TP_clean 654, SL_clean 460, SL→reverse 0, Sideways 179, N/A 0)
- Ongoing (<24h): 20
- TP rate: 58.7% decided (TP/(TP+SL)) · 50.6% pointwise (excl N/A)

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
| 1313 | 29.09 | 07:34 | VIRTUALUSDT | SHORT | ongoing | осторожно 63% |
| 1312 | 29.09 | 01:11 | AKEUSDT | SHORT | ongoing | осторожно 76% |
| 1311 | 29.09 | 01:07 | AAOIUSDT | SHORT | ongoing | осторожно 62% |
| 1310 | 29.09 | 01:06 | FLOCKUSDT | SHORT | ongoing | осторожно 70% |
| 1309 | 28.09 | 22:41 | CRCLUSDT | SHORT | ongoing | осторожно 63% |
| 1308 | 28.09 | 22:37 | SPXUSDT | SHORT | ongoing | осторожно 66% |
| 1307 | 28.09 | 22:32 | WIFUSDT | SHORT | ongoing | осторожно 60% |
| 1306 | 28.09 | 21:38 | ZAMAUSDT | SHORT | ongoing | осторожно 75% |
| 1305 | 28.09 | 20:04 | TRUMPUSDT | SHORT | ongoing | осторожно 64% |
| 1304 | 28.09 | 20:02 | AXSUSDT | SHORT | ongoing | осторожно 68% |
| 1303 | 28.09 | 20:01 | ORDIUSDT | SHORT | ongoing | осторожно 83% |
| 1302 | 28.09 | 19:39 | FLOCKUSDT | SHORT | ongoing | осторожно 78% |
| 1301 | 28.09 | 19:01 | NMRUSDT | LONG | ongoing | осторожно 79% |
| 1300 | 28.09 | 17:32 | CAKEUSDT | SHORT | ongoing | осторожно 67% |
| 1299 | 28.09 | 13:30 | ZAMAUSDT | SHORT | ongoing | осторожно 67% |
| 1298 | 28.09 | 12:30 | SAGAUSDT | SHORT | ongoing | осторожно 84% |
| 1297 | 28.09 | 11:31 | DASHUSDT | SHORT | ongoing | осторожно 61% |
| 1296 | 28.09 | 10:38 | ARXUSDT | SHORT | ongoing | осторожно 75% |
| 1295 | 28.09 | 08:06 | ZECUSDT | SHORT | ongoing | осторожно 68% |
| 1294 | 28.09 | 06:12 | MUUSDT | LONG | ongoing | осторожно 68% |
| 1293 | 28.09 | 05:01 | KORUUSDT | LONG | SL_clean | осторожно 62% |
| 1292 | 28.09 | 04:30 | TRUSTUSDT | LONG | SL_clean | осторожно 65% |
| 1291 | 28.09 | 04:02 | ICPUSDT | SHORT | TP_clean | осторожно 77% |
| 1290 | 28.09 | 03:31 | INUSDT | LONG | SL_clean | осторожно 62% |
| 1289 | 28.09 | 01:08 | KITEUSDT | LONG | SL_clean | осторожно 63% |
| 1288 | 28.09 | 00:03 | XAIUSDT | LONG | SL_clean | осторожно 62% |
| 1287 | 27.09 | 22:36 | TUSDT | LONG | SL_clean | осторожно 65% |
| 1286 | 27.09 | 21:37 | ZECUSDT | LONG | SL_clean | осторожно 64% |
| 1285 | 27.09 | 20:02 | BTWUSDT | SHORT | SL_clean | осторожно 73% |
| 1284 | 27.09 | 13:31 | WUSDT | LONG | SL_clean | осторожно 61% |
| 1283 | 27.09 | 08:30 | RAREUSDT | LONG | SL_clean | осторожно 79% |
| 1282 | 27.09 | 07:01 | QNTUSDT | LONG | TP_clean | входить 81% |
| 1281 | 27.09 | 06:11 | VETUSDT | SHORT | TP_clean | осторожно 68% |
| 1280 | 27.09 | 04:31 | ESPUSDT | LONG | TP_clean | осторожно 65% |
| 1279 | 27.09 | 03:01 | SUIUSDT | LONG | TP_clean | осторожно 69% |
| 1278 | 26.09 | 22:00 | RAREUSDT | LONG | TP_clean | осторожно 61% |
| 1277 | 26.09 | 21:32 | DOTUSDT | LONG | Sideways | осторожно 60% |
| 1276 | 26.09 | 18:03 | QUSDT | LONG | TP_clean | осторожно 64% |
| 1275 | 26.09 | 13:36 | CLUSDT | LONG | Sideways | осторожно 65% |
| 1274 | 26.09 | 11:01 | 2ZUSDT | LONG | TP_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-09-30 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-29 06:30 UTC
- mmscan-snapshot: next run 2026-09-29 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
