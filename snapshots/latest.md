# MM Scan Shadow Snapshot
Generated: 2026-10-07T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1346.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-07T05:31:10+0000 (#1409 ESPUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-06T06:00:01Z → 2026-10-07T06:00:01Z)
- New signals: 14 (LONG 7 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1346.2h, restarts: 0
- Last closer: 2026-10-07T03:00:39Z
- Last backfill: 2026-10-07T05:30:03Z
- Anomalies: ongoing >24h без закрытия: 1

## Health 7d (window: 2026-09-30T06:00:01Z → 2026-10-07T06:00:01Z)
- New signals: 88 (~12.6/day)
- Closed: 73 (TP 33, SL 21, SL→rev 0, Sideways 19, N/A 0)
- Ongoing: 15
- TP rate 7d: 61.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1409
- Closed: 1394 (TP_clean 702, SL_clean 494, SL→reverse 0, Sideways 198, N/A 0)
- Ongoing (<24h): 15
- TP rate: 58.7% decided (TP/(TP+SL)) · 50.4% pointwise (excl N/A)

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
| 1409 | 07.10 | 08:31 | ESPUSDT | LONG | ongoing | осторожно 71% |
| 1408 | 07.10 | 07:34 | BZUSDT | LONG | ongoing | осторожно 61% |
| 1407 | 07.10 | 07:30 | UMAUSDT | LONG | ongoing | осторожно 67% |
| 1406 | 07.10 | 05:32 | SANDUSDT | SHORT | ongoing | осторожно 63% |
| 1405 | 07.10 | 03:04 | FARTCOINUSDT | SHORT | ongoing | осторожно 67% |
| 1404 | 07.10 | 01:33 | USELESSUSDT | SHORT | ongoing | осторожно 65% |
| 1403 | 07.10 | 00:34 | ADAUSDT | SHORT | ongoing | осторожно 63% |
| 1402 | 07.10 | 00:32 | ENAUSDT | LONG | ongoing | осторожно 64% |
| 1401 | 06.10 | 22:06 | FARTCOINUSDT | SHORT | ongoing | осторожно 62% |
| 1400 | 06.10 | 20:35 | FILUSDT | LONG | ongoing | осторожно 62% |
| 1399 | 06.10 | 15:39 | MORPHOUSDT | LONG | ongoing | осторожно 81% |
| 1398 | 06.10 | 15:09 | ICPUSDT | SHORT | ongoing | осторожно 63% |
| 1397 | 06.10 | 13:02 | MINAUSDT | SHORT | ongoing | осторожно 68% |
| 1396 | 06.10 | 10:32 | ORCAUSDT | LONG | ongoing | осторожно 62% |
| 1395 | 06.10 | 07:33 | MANAUSDT | LONG | ongoing | осторожно 62% |
| 1394 | 06.10 | 05:05 | XLMUSDT | SHORT | TP_clean | осторожно 61% |
| 1393 | 06.10 | 02:31 | UMAUSDT | LONG | TP_clean | осторожно 79% |
| 1392 | 06.10 | 01:30 | RLCUSDT | LONG | SL_clean | осторожно 65% |
| 1391 | 05.10 | 23:09 | MINAUSDT | SHORT | TP_clean | осторожно 62% |
| 1390 | 05.10 | 22:09 | FLUIDUSDT | LONG | SL_clean | осторожно 66% |
| 1389 | 05.10 | 22:01 | VIRTUALUSDT | LONG | SL_clean | осторожно 67% |
| 1388 | 05.10 | 20:41 | PYTHUSDT | LONG | TP_clean | осторожно 62% |
| 1387 | 05.10 | 20:08 | SEIUSDT | SHORT | SL_clean | осторожно 62% |
| 1386 | 05.10 | 19:31 | RLCUSDT | LONG | TP_clean | осторожно 80% |
| 1385 | 05.10 | 18:01 | RVNUSDT | LONG | SL_clean | осторожно 67% |
| 1384 | 05.10 | 15:07 | XLMUSDT | SHORT | TP_clean | осторожно 62% |
| 1383 | 05.10 | 11:01 | ARKUSDT | SHORT | Sideways | осторожно 61% |
| 1382 | 05.10 | 10:33 | IOTAUSDT | LONG | Sideways | осторожно 68% |
| 1381 | 05.10 | 10:01 | ZROUSDT | SHORT | SL_clean | осторожно 66% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-08 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-07 06:30 UTC
- mmscan-snapshot: next run 2026-10-07 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
