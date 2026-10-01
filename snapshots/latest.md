# MM Scan Shadow Snapshot
Generated: 2026-10-01T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1208.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-01T11:32:00+0000 (#1335 FLOCKUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-30T12:00:01Z → 2026-10-01T12:00:01Z)
- New signals: 10 (LONG 4 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1208.2h, restarts: 0
- Last closer: 2026-10-01T03:00:34Z
- Last backfill: 2026-10-01T11:30:03Z
- Anomalies: ongoing >24h без закрытия: 4

## Health 7d (window: 2026-09-24T12:00:01Z → 2026-10-01T12:00:01Z)
- New signals: 82 (~11.7/day)
- Closed: 68 (TP 32, SL 33, SL→rev 0, Sideways 3, N/A 0)
- Ongoing: 14
- TP rate 7d: 49.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1335
- Closed: 1321 (TP_clean 669, SL_clean 473, SL→reverse 0, Sideways 179, N/A 0)
- Ongoing (<24h): 14
- TP rate: 58.6% decided (TP/(TP+SL)) · 50.6% pointwise (excl N/A)

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
| 1335 | 01.10 | 14:32 | FLOCKUSDT | SHORT | ongoing | осторожно 73% |
| 1334 | 01.10 | 13:10 | CELOUSDT | SHORT | ongoing | осторожно 70% |
| 1333 | 01.10 | 13:03 | SKYUSDT | SHORT | ongoing | осторожно 65% |
| 1332 | 01.10 | 13:02 | ARKUSDT | SHORT | ongoing | осторожно 74% |
| 1331 | 01.10 | 10:05 | HYPEUSDT | LONG | ongoing | осторожно 66% |
| 1330 | 01.10 | 07:04 | RUNEUSDT | SHORT | ongoing | осторожно 66% |
| 1329 | 01.10 | 03:01 | TRBUSDT | LONG | ongoing | осторожно 64% |
| 1328 | 30.09 | 21:15 | USUSDT | SHORT | ongoing | входить 84% |
| 1327 | 30.09 | 19:33 | METUSDT | LONG | ongoing | осторожно 63% |
| 1326 | 30.09 | 15:36 | INJUSDT | LONG | ongoing | осторожно 67% |
| 1325 | 30.09 | 14:34 | FFUSDT | SHORT | ongoing | осторожно 63% |
| 1324 | 30.09 | 14:05 | EIGENUSDT | SHORT | ongoing | осторожно 61% |
| 1323 | 30.09 | 13:01 | RAREUSDT | SHORT | ongoing | осторожно 63% |
| 1322 | 30.09 | 09:01 | TAOUSDT | LONG | ongoing | осторожно 62% |
| 1321 | 30.09 | 05:32 | NMRUSDT | LONG | SL_clean | осторожно 66% |
| 1320 | 30.09 | 02:10 | AAOIUSDT | SHORT | TP_clean | осторожно 67% |
| 1319 | 29.09 | 21:30 | NILUSDT | SHORT | TP_clean | осторожно 60% |
| 1318 | 29.09 | 20:37 | BRUSDT | SHORT | TP_clean | осторожно 62% |
| 1317 | 29.09 | 10:34 | APRUSDT | SHORT | SL_clean | входить 81% |
| 1316 | 29.09 | 09:30 | NMRUSDT | LONG | TP_clean | осторожно 73% |
| 1315 | 29.09 | 09:07 | ACEUSDT | SHORT | TP_clean | осторожно 60% |
| 1314 | 29.09 | 09:02 | ZROUSDT | SHORT | SL_clean | осторожно 61% |
| 1313 | 29.09 | 07:34 | VIRTUALUSDT | SHORT | TP_clean | осторожно 63% |
| 1312 | 29.09 | 01:11 | AKEUSDT | SHORT | SL_clean | осторожно 76% |
| 1311 | 29.09 | 01:07 | AAOIUSDT | SHORT | SL_clean | осторожно 62% |
| 1310 | 29.09 | 01:06 | FLOCKUSDT | SHORT | SL_clean | осторожно 70% |
| 1309 | 28.09 | 22:41 | CRCLUSDT | SHORT | TP_clean | осторожно 63% |
| 1308 | 28.09 | 22:37 | SPXUSDT | SHORT | TP_clean | осторожно 66% |
| 1307 | 28.09 | 22:32 | WIFUSDT | SHORT | SL_clean | осторожно 60% |
| 1306 | 28.09 | 21:38 | ZAMAUSDT | SHORT | TP_clean | осторожно 75% |
| 1305 | 28.09 | 20:04 | TRUMPUSDT | SHORT | TP_clean | осторожно 64% |
| 1304 | 28.09 | 20:02 | AXSUSDT | SHORT | SL_clean | осторожно 68% |
| 1303 | 28.09 | 20:01 | ORDIUSDT | SHORT | SL_clean | осторожно 83% |
| 1302 | 28.09 | 19:39 | FLOCKUSDT | SHORT | SL_clean | осторожно 78% |
| 1301 | 28.09 | 19:01 | NMRUSDT | LONG | TP_clean | осторожно 79% |
| 1300 | 28.09 | 17:32 | CAKEUSDT | SHORT | TP_clean | осторожно 67% |
| 1299 | 28.09 | 13:30 | ZAMAUSDT | SHORT | TP_clean | осторожно 67% |
| 1298 | 28.09 | 12:30 | SAGAUSDT | SHORT | SL_clean | осторожно 84% |
| 1297 | 28.09 | 11:31 | DASHUSDT | SHORT | TP_clean | осторожно 61% |
| 1296 | 28.09 | 10:38 | ARXUSDT | SHORT | SL_clean | осторожно 75% |
| 1295 | 28.09 | 08:06 | ZECUSDT | SHORT | TP_clean | осторожно 68% |
| 1294 | 28.09 | 06:12 | MUUSDT | LONG | SL_clean | осторожно 68% |
| 1293 | 28.09 | 05:01 | KORUUSDT | LONG | SL_clean | осторожно 62% |
| 1292 | 28.09 | 04:30 | TRUSTUSDT | LONG | SL_clean | осторожно 65% |
| 1291 | 28.09 | 04:02 | ICPUSDT | SHORT | TP_clean | осторожно 77% |
| 1290 | 28.09 | 03:31 | INUSDT | LONG | SL_clean | осторожно 62% |
| 1289 | 28.09 | 01:08 | KITEUSDT | LONG | SL_clean | осторожно 63% |
| 1288 | 28.09 | 00:03 | XAIUSDT | LONG | SL_clean | осторожно 62% |
| 1287 | 27.09 | 22:36 | TUSDT | LONG | SL_clean | осторожно 65% |
| 1286 | 27.09 | 21:37 | ZECUSDT | LONG | SL_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-02 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-01 12:30 UTC
- mmscan-snapshot: next run 2026-10-01 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
