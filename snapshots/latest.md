# MM Scan Shadow Snapshot
Generated: 2026-10-06T12:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1328.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-06T10:02:08+0000 (#1397 MINAUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-05T12:00:02Z → 2026-10-06T12:00:02Z)
- New signals: 14 (LONG 9 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1328.2h, restarts: 0
- Last closer: 2026-10-06T03:00:16Z
- Last backfill: 2026-10-06T11:30:03Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-09-29T12:00:02Z → 2026-10-06T12:00:02Z)
- New signals: 80 (~11.4/day)
- Closed: 63 (TP 30, SL 16, SL→rev 0, Sideways 17, N/A 0)
- Ongoing: 17
- TP rate 7d: 65.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1397
- Closed: 1380 (TP_clean 696, SL_clean 488, SL→reverse 0, Sideways 196, N/A 0)
- Ongoing (<24h): 17
- TP rate: 58.8% decided (TP/(TP+SL)) · 50.4% pointwise (excl N/A)

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
| 1397 | 06.10 | 13:02 | MINAUSDT | SHORT | ongoing | осторожно 68% |
| 1396 | 06.10 | 10:32 | ORCAUSDT | LONG | ongoing | осторожно 62% |
| 1395 | 06.10 | 07:33 | MANAUSDT | LONG | ongoing | осторожно 62% |
| 1394 | 06.10 | 05:05 | XLMUSDT | SHORT | ongoing | осторожно 61% |
| 1393 | 06.10 | 02:31 | UMAUSDT | LONG | ongoing | осторожно 79% |
| 1392 | 06.10 | 01:30 | RLCUSDT | LONG | ongoing | осторожно 65% |
| 1391 | 05.10 | 23:09 | MINAUSDT | SHORT | ongoing | осторожно 62% |
| 1390 | 05.10 | 22:09 | FLUIDUSDT | LONG | ongoing | осторожно 66% |
| 1389 | 05.10 | 22:01 | VIRTUALUSDT | LONG | ongoing | осторожно 67% |
| 1388 | 05.10 | 20:41 | PYTHUSDT | LONG | ongoing | осторожно 62% |
| 1387 | 05.10 | 20:08 | SEIUSDT | SHORT | ongoing | осторожно 62% |
| 1386 | 05.10 | 19:31 | RLCUSDT | LONG | ongoing | осторожно 80% |
| 1385 | 05.10 | 18:01 | RVNUSDT | LONG | ongoing | осторожно 67% |
| 1384 | 05.10 | 15:07 | XLMUSDT | SHORT | ongoing | осторожно 62% |
| 1383 | 05.10 | 11:01 | ARKUSDT | SHORT | ongoing | осторожно 61% |
| 1382 | 05.10 | 10:33 | IOTAUSDT | LONG | ongoing | осторожно 68% |
| 1381 | 05.10 | 10:01 | ZROUSDT | SHORT | ongoing | осторожно 66% |
| 1380 | 05.10 | 01:31 | ARKUSDT | LONG | Sideways | осторожно 68% |
| 1379 | 04.10 | 20:34 | MANAUSDT | SHORT | Sideways | осторожно 60% |
| 1378 | 04.10 | 13:02 | EIGENUSDT | SHORT | Sideways | осторожно 78% |
| 1377 | 04.10 | 10:03 | ATUSDT | SHORT | TP_clean | осторожно 64% |
| 1376 | 04.10 | 07:30 | MANAUSDT | LONG | SL_clean | осторожно 67% |
| 1375 | 04.10 | 07:03 | DOTUSDT | SHORT | SL_clean | осторожно 68% |
| 1374 | 04.10 | 06:30 | SANDUSDT | LONG | TP_clean | осторожно 68% |
| 1373 | 04.10 | 04:02 | AXSUSDT | LONG | TP_clean | осторожно 63% |
| 1372 | 04.10 | 00:04 | LITUSDT | SHORT | Sideways | осторожно 68% |
| 1371 | 03.10 | 20:04 | COTIUSDT | LONG | TP_clean | осторожно 65% |
| 1370 | 03.10 | 18:34 | 2ZUSDT | SHORT | TP_clean | осторожно 79% |
| 1369 | 03.10 | 18:33 | LITUSDT | SHORT | SL_clean | осторожно 64% |
| 1368 | 03.10 | 17:38 | CTUSDT | LONG | SL_clean | осторожно 65% |
| 1367 | 03.10 | 13:07 | ASTERUSDT | SHORT | Sideways | осторожно 62% |
| 1366 | 03.10 | 13:01 | STRKUSDT | LONG | TP_clean | осторожно 64% |
| 1365 | 03.10 | 10:33 | 1000BONKUSDT | SHORT | SL_clean | осторожно 60% |
| 1364 | 03.10 | 09:12 | BEUSDT | SHORT | Sideways | осторожно 71% |
| 1363 | 03.10 | 09:09 | CRWVUSDT | SHORT | Sideways | осторожно 62% |
| 1362 | 03.10 | 09:07 | ONDOUSDT | SHORT | SL_clean | осторожно 68% |
| 1361 | 03.10 | 08:06 | APTUSDT | SHORT | Sideways | осторожно 74% |
| 1360 | 03.10 | 06:32 | NEOUSDT | SHORT | Sideways | осторожно 68% |
| 1359 | 03.10 | 06:02 | SUPERUSDT | LONG | TP_clean | осторожно 64% |
| 1358 | 03.10 | 03:30 | SANDUSDT | LONG | TP_clean | осторожно 90% |
| 1357 | 03.10 | 00:35 | AXSUSDT | LONG | TP_clean | осторожно 78% |
| 1356 | 03.10 | 00:11 | ONDOUSDT | SHORT | Sideways | осторожно 62% |
| 1355 | 02.10 | 21:12 | SOLUSDT | SHORT | Sideways | осторожно 79% |
| 1354 | 02.10 | 21:09 | POLUSDT | SHORT | TP_clean | осторожно 62% |
| 1353 | 02.10 | 21:05 | IRENUSDT | SHORT | Sideways | осторожно 70% |
| 1352 | 02.10 | 20:37 | VIRTUALUSDT | SHORT | TP_clean | осторожно 67% |
| 1351 | 02.10 | 20:01 | CRWVUSDT | SHORT | Sideways | осторожно 62% |
| 1350 | 02.10 | 19:09 | ENJUSDT | LONG | TP_clean | осторожно 80% |
| 1349 | 02.10 | 14:30 | QNTUSDT | SHORT | TP_clean | осторожно 75% |
| 1348 | 02.10 | 13:01 | ZAMAUSDT | SHORT | TP_clean | осторожно 63% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-07 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-06 12:30 UTC
- mmscan-snapshot: next run 2026-10-06 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
