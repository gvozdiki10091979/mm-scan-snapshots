# MM Scan Shadow Snapshot
Generated: 2026-10-03T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1262.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-03T17:04:36+0000 (#1371 COTIUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-02T18:00:02Z → 2026-10-03T18:00:02Z)
- New signals: 19 (LONG 6 / SHORT 13)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 19
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1262.2h, restarts: 0
- Last closer: 2026-10-03T03:01:08Z
- Last backfill: 2026-10-03T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 7

## Health 7d (window: 2026-09-26T18:00:02Z → 2026-10-03T18:00:02Z)
- New signals: 95 (~13.6/day)
- Closed: 69 (TP 33, SL 32, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 26
- TP rate 7d: 50.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1371
- Closed: 1345 (TP_clean 681, SL_clean 482, SL→reverse 0, Sideways 182, N/A 0)
- Ongoing (<24h): 26
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
| 1371 | 03.10 | 20:04 | COTIUSDT | LONG | ongoing | осторожно 65% |
| 1370 | 03.10 | 18:34 | 2ZUSDT | SHORT | ongoing | осторожно 79% |
| 1369 | 03.10 | 18:33 | LITUSDT | SHORT | ongoing | осторожно 64% |
| 1368 | 03.10 | 17:38 | CTUSDT | LONG | ongoing | осторожно 65% |
| 1367 | 03.10 | 13:07 | ASTERUSDT | SHORT | ongoing | осторожно 62% |
| 1366 | 03.10 | 13:01 | STRKUSDT | LONG | ongoing | осторожно 64% |
| 1365 | 03.10 | 10:33 | 1000BONKUSDT | SHORT | ongoing | осторожно 60% |
| 1364 | 03.10 | 09:12 | BEUSDT | SHORT | ongoing | осторожно 71% |
| 1363 | 03.10 | 09:09 | CRWVUSDT | SHORT | ongoing | осторожно 62% |
| 1362 | 03.10 | 09:07 | ONDOUSDT | SHORT | ongoing | осторожно 68% |
| 1361 | 03.10 | 08:06 | APTUSDT | SHORT | ongoing | осторожно 74% |
| 1360 | 03.10 | 06:32 | NEOUSDT | SHORT | ongoing | осторожно 68% |
| 1359 | 03.10 | 06:02 | SUPERUSDT | LONG | ongoing | осторожно 64% |
| 1358 | 03.10 | 03:30 | SANDUSDT | LONG | ongoing | осторожно 90% |
| 1357 | 03.10 | 00:35 | AXSUSDT | LONG | ongoing | осторожно 78% |
| 1356 | 03.10 | 00:11 | ONDOUSDT | SHORT | ongoing | осторожно 62% |
| 1355 | 02.10 | 21:12 | SOLUSDT | SHORT | ongoing | осторожно 79% |
| 1354 | 02.10 | 21:09 | POLUSDT | SHORT | ongoing | осторожно 62% |
| 1353 | 02.10 | 21:05 | IRENUSDT | SHORT | ongoing | осторожно 70% |
| 1352 | 02.10 | 20:37 | VIRTUALUSDT | SHORT | ongoing | осторожно 67% |
| 1351 | 02.10 | 20:01 | CRWVUSDT | SHORT | ongoing | осторожно 62% |
| 1350 | 02.10 | 19:09 | ENJUSDT | LONG | ongoing | осторожно 80% |
| 1349 | 02.10 | 14:30 | QNTUSDT | SHORT | ongoing | осторожно 75% |
| 1348 | 02.10 | 13:01 | ZAMAUSDT | SHORT | ongoing | осторожно 63% |
| 1347 | 02.10 | 07:01 | MEGAUSDT | LONG | ongoing | осторожно 63% |
| 1346 | 02.10 | 06:09 | IBMUSDT | LONG | ongoing | осторожно 67% |
| 1345 | 02.10 | 05:03 | ACEUSDT | SHORT | SL_clean | осторожно 62% |
| 1344 | 02.10 | 02:30 | COTIUSDT | LONG | TP_clean | осторожно 77% |
| 1343 | 02.10 | 01:04 | SKHYUSDT | LONG | Sideways | осторожно 61% |
| 1342 | 02.10 | 01:01 | SUIUSDT | LONG | TP_clean | осторожно 65% |
| 1341 | 01.10 | 22:08 | VVVUSDT | LONG | SL_clean | осторожно 75% |
| 1340 | 01.10 | 20:45 | SAGAUSDT | SHORT | SL_clean | осторожно 65% |
| 1339 | 01.10 | 19:09 | DYDXUSDT | LONG | TP_clean | осторожно 60% |
| 1338 | 01.10 | 16:03 | MRVLUSDT | SHORT | SL_clean | осторожно 60% |
| 1337 | 01.10 | 16:01 | SOXLUSDT | SHORT | TP_clean | осторожно 70% |
| 1336 | 01.10 | 15:35 | TRXUSDT | LONG | Sideways | осторожно 65% |
| 1335 | 01.10 | 14:32 | FLOCKUSDT | SHORT | TP_clean | осторожно 73% |
| 1334 | 01.10 | 13:10 | CELOUSDT | SHORT | TP_clean | осторожно 70% |
| 1333 | 01.10 | 13:03 | SKYUSDT | SHORT | SL_clean | осторожно 65% |
| 1332 | 01.10 | 13:02 | ARKUSDT | SHORT | TP_clean | осторожно 74% |
| 1331 | 01.10 | 10:05 | HYPEUSDT | LONG | SL_clean | осторожно 66% |
| 1330 | 01.10 | 07:04 | RUNEUSDT | SHORT | TP_clean | осторожно 66% |
| 1329 | 01.10 | 03:01 | TRBUSDT | LONG | SL_clean | осторожно 64% |
| 1328 | 30.09 | 21:15 | USUSDT | SHORT | TP_clean | входить 84% |
| 1327 | 30.09 | 19:33 | METUSDT | LONG | SL_clean | осторожно 63% |
| 1326 | 30.09 | 15:36 | INJUSDT | LONG | SL_clean | осторожно 67% |
| 1325 | 30.09 | 14:34 | FFUSDT | SHORT | Sideways | осторожно 63% |
| 1324 | 30.09 | 14:05 | EIGENUSDT | SHORT | TP_clean | осторожно 61% |
| 1323 | 30.09 | 13:01 | RAREUSDT | SHORT | TP_clean | осторожно 63% |
| 1322 | 30.09 | 09:01 | TAOUSDT | LONG | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-04 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-03 18:30 UTC
- mmscan-snapshot: next run 2026-10-04 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
