# MM Scan Shadow Snapshot
Generated: 2026-10-08T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1376.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-08T08:32:28+0000 (#1429 ERAUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-07T12:00:01Z → 2026-10-08T12:00:01Z)
- New signals: 16 (LONG 5 / SHORT 11)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 16
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1376.2h, restarts: 0
- Last closer: 2026-10-08T03:00:29Z
- Last backfill: 2026-10-08T11:30:03Z
- Anomalies: ongoing >24h без закрытия: 7

## Health 7d (window: 2026-10-01T12:00:01Z → 2026-10-08T12:00:01Z)
- New signals: 94 (~13.4/day)
- Closed: 71 (TP 33, SL 20, SL→rev 0, Sideways 18, N/A 0)
- Ongoing: 23
- TP rate 7d: 62.3%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1429
- Closed: 1406 (TP_clean 710, SL_clean 498, SL→reverse 0, Sideways 198, N/A 0)
- Ongoing (<24h): 23
- TP rate: 58.8% decided (TP/(TP+SL)) · 50.5% pointwise (excl N/A)

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
| 1429 | 08.10 | 11:32 | ERAUSDT | LONG | ongoing | осторожно 65% |
| 1428 | 08.10 | 11:06 | SKDDUSDT | LONG | ongoing | осторожно 60% |
| 1427 | 08.10 | 06:36 | EWYUSDT | SHORT | ongoing | осторожно 75% |
| 1426 | 08.10 | 06:07 | NIGHTUSDT | SHORT | ongoing | осторожно 70% |
| 1425 | 08.10 | 04:32 | ACEUSDT | SHORT | ongoing | осторожно 61% |
| 1424 | 08.10 | 03:01 | INJUSDT | LONG | ongoing | осторожно 62% |
| 1423 | 07.10 | 22:39 | HYPEUSDT | SHORT | ongoing | осторожно 62% |
| 1422 | 07.10 | 21:39 | 1000PEPEUSDT | SHORT | ongoing | осторожно 64% |
| 1421 | 07.10 | 20:34 | LINKUSDT | SHORT | ongoing | осторожно 67% |
| 1420 | 07.10 | 19:37 | SKHYUSDT | SHORT | ongoing | осторожно 72% |
| 1419 | 07.10 | 19:04 | COTIUSDT | SHORT | ongoing | осторожно 68% |
| 1418 | 07.10 | 19:04 | HUMAUSDT | SHORT | ongoing | осторожно 67% |
| 1417 | 07.10 | 18:08 | ATOMUSDT | SHORT | ongoing | осторожно 61% |
| 1416 | 07.10 | 18:02 | LYNUSDT | SHORT | ongoing | осторожно 63% |
| 1415 | 07.10 | 17:30 | SANDUSDT | LONG | ongoing | осторожно 72% |
| 1414 | 07.10 | 16:30 | CAPUSDT | LONG | ongoing | входить 81% |
| 1413 | 07.10 | 14:05 | ARMUSDT | SHORT | ongoing | осторожно 65% |
| 1412 | 07.10 | 12:30 | USUSDT | LONG | ongoing | осторожно 71% |
| 1411 | 07.10 | 12:13 | TRUMPUSDT | SHORT | ongoing | осторожно 60% |
| 1410 | 07.10 | 09:06 | BRUSDT | LONG | ongoing | осторожно 74% |
| 1409 | 07.10 | 08:31 | ESPUSDT | LONG | ongoing | осторожно 71% |
| 1408 | 07.10 | 07:34 | BZUSDT | LONG | ongoing | осторожно 61% |
| 1407 | 07.10 | 07:30 | UMAUSDT | LONG | ongoing | осторожно 67% |
| 1406 | 07.10 | 05:32 | SANDUSDT | SHORT | TP_clean | осторожно 63% |
| 1405 | 07.10 | 03:04 | FARTCOINUSDT | SHORT | TP_clean | осторожно 67% |
| 1404 | 07.10 | 01:33 | USELESSUSDT | SHORT | TP_clean | осторожно 65% |
| 1403 | 07.10 | 00:34 | ADAUSDT | SHORT | TP_clean | осторожно 63% |
| 1402 | 07.10 | 00:32 | ENAUSDT | LONG | SL_clean | осторожно 64% |
| 1401 | 06.10 | 22:06 | FARTCOINUSDT | SHORT | TP_clean | осторожно 62% |
| 1400 | 06.10 | 20:35 | FILUSDT | LONG | SL_clean | осторожно 62% |
| 1399 | 06.10 | 15:39 | MORPHOUSDT | LONG | SL_clean | осторожно 81% |
| 1398 | 06.10 | 15:09 | ICPUSDT | SHORT | TP_clean | осторожно 63% |
| 1397 | 06.10 | 13:02 | MINAUSDT | SHORT | TP_clean | осторожно 68% |
| 1396 | 06.10 | 10:32 | ORCAUSDT | LONG | TP_clean | осторожно 62% |
| 1395 | 06.10 | 07:33 | MANAUSDT | LONG | SL_clean | осторожно 62% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-09 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-08 12:30 UTC
- mmscan-snapshot: next run 2026-10-08 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
