# MM Scan Shadow Snapshot
Generated: 2026-10-02T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1238.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-02T17:37:32+0000 (#1352 VIRTUALUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-01T18:00:01Z → 2026-10-02T18:00:01Z)
- New signals: 12 (LONG 7 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1238.2h, restarts: 0
- Last closer: 2026-10-02T03:00:24Z
- Last backfill: 2026-10-02T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 11

## Health 7d (window: 2026-09-25T18:00:01Z → 2026-10-02T18:00:01Z)
- New signals: 82 (~11.7/day)
- Closed: 59 (TP 27, SL 28, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 23
- TP rate 7d: 49.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1352
- Closed: 1329 (TP_clean 673, SL_clean 476, SL→reverse 0, Sideways 180, N/A 0)
- Ongoing (<24h): 23
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
| 1352 | 02.10 | 20:37 | VIRTUALUSDT | SHORT | ongoing | осторожно 67% |
| 1351 | 02.10 | 20:01 | CRWVUSDT | SHORT | ongoing | осторожно 62% |
| 1350 | 02.10 | 19:09 | ENJUSDT | LONG | ongoing | осторожно 80% |
| 1349 | 02.10 | 14:30 | QNTUSDT | SHORT | ongoing | осторожно 75% |
| 1348 | 02.10 | 13:01 | ZAMAUSDT | SHORT | ongoing | осторожно 63% |
| 1347 | 02.10 | 07:01 | MEGAUSDT | LONG | ongoing | осторожно 63% |
| 1346 | 02.10 | 06:09 | IBMUSDT | LONG | ongoing | осторожно 67% |
| 1345 | 02.10 | 05:03 | ACEUSDT | SHORT | ongoing | осторожно 62% |
| 1344 | 02.10 | 02:30 | COTIUSDT | LONG | ongoing | осторожно 77% |
| 1343 | 02.10 | 01:04 | SKHYUSDT | LONG | ongoing | осторожно 61% |
| 1342 | 02.10 | 01:01 | SUIUSDT | LONG | ongoing | осторожно 65% |
| 1341 | 01.10 | 22:08 | VVVUSDT | LONG | ongoing | осторожно 75% |
| 1340 | 01.10 | 20:45 | SAGAUSDT | SHORT | ongoing | осторожно 65% |
| 1339 | 01.10 | 19:09 | DYDXUSDT | LONG | ongoing | осторожно 60% |
| 1338 | 01.10 | 16:03 | MRVLUSDT | SHORT | ongoing | осторожно 60% |
| 1337 | 01.10 | 16:01 | SOXLUSDT | SHORT | ongoing | осторожно 70% |
| 1336 | 01.10 | 15:35 | TRXUSDT | LONG | ongoing | осторожно 65% |
| 1335 | 01.10 | 14:32 | FLOCKUSDT | SHORT | ongoing | осторожно 73% |
| 1334 | 01.10 | 13:10 | CELOUSDT | SHORT | ongoing | осторожно 70% |
| 1333 | 01.10 | 13:03 | SKYUSDT | SHORT | ongoing | осторожно 65% |
| 1332 | 01.10 | 13:02 | ARKUSDT | SHORT | ongoing | осторожно 74% |
| 1331 | 01.10 | 10:05 | HYPEUSDT | LONG | ongoing | осторожно 66% |
| 1330 | 01.10 | 07:04 | RUNEUSDT | SHORT | ongoing | осторожно 66% |
| 1329 | 01.10 | 03:01 | TRBUSDT | LONG | SL_clean | осторожно 64% |
| 1328 | 30.09 | 21:15 | USUSDT | SHORT | TP_clean | входить 84% |
| 1327 | 30.09 | 19:33 | METUSDT | LONG | SL_clean | осторожно 63% |
| 1326 | 30.09 | 15:36 | INJUSDT | LONG | SL_clean | осторожно 67% |
| 1325 | 30.09 | 14:34 | FFUSDT | SHORT | Sideways | осторожно 63% |
| 1324 | 30.09 | 14:05 | EIGENUSDT | SHORT | TP_clean | осторожно 61% |
| 1323 | 30.09 | 13:01 | RAREUSDT | SHORT | TP_clean | осторожно 63% |
| 1322 | 30.09 | 09:01 | TAOUSDT | LONG | TP_clean | осторожно 62% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-03 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-02 18:30 UTC
- mmscan-snapshot: next run 2026-10-03 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
