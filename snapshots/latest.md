# MM Scan Shadow Snapshot
Generated: 2026-10-09T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1394.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-09T05:02:51+0000 (#1440 ORCAUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-08T06:00:01Z → 2026-10-09T06:00:01Z)
- New signals: 13 (LONG 3 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1394.2h, restarts: 0
- Last closer: 2026-10-09T03:00:47Z
- Last backfill: 2026-10-09T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 2

## Health 7d (window: 2026-10-02T06:00:01Z → 2026-10-09T06:00:01Z)
- New signals: 93 (~13.3/day)
- Closed: 78 (TP 40, SL 22, SL→rev 0, Sideways 16, N/A 0)
- Ongoing: 15
- TP rate 7d: 64.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1440
- Closed: 1425 (TP_clean 722, SL_clean 504, SL→reverse 0, Sideways 199, N/A 0)
- Ongoing (<24h): 15
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
| 1440 | 09.10 | 08:02 | ORCAUSDT | SHORT | ongoing | осторожно 68% |
| 1439 | 09.10 | 05:04 | CAKEUSDT | SHORT | ongoing | осторожно 62% |
| 1438 | 09.10 | 01:31 | BRUSDT | SHORT | ongoing | осторожно 61% |
| 1437 | 08.10 | 23:08 | NILUSDT | SHORT | ongoing | осторожно 71% |
| 1436 | 08.10 | 21:33 | SKLUSDT | SHORT | ongoing | осторожно 70% |
| 1435 | 08.10 | 21:33 | USUSDT | LONG | ongoing | осторожно 63% |
| 1434 | 08.10 | 21:01 | LPTUSDT | SHORT | ongoing | осторожно 74% |
| 1433 | 08.10 | 18:12 | LINKUSDT | SHORT | ongoing | осторожно 66% |
| 1432 | 08.10 | 18:07 | ENSUSDT | SHORT | ongoing | осторожно 74% |
| 1431 | 08.10 | 18:04 | CRVUSDT | SHORT | ongoing | осторожно 76% |
| 1430 | 08.10 | 15:33 | CTUSDT | SHORT | ongoing | осторожно 61% |
| 1429 | 08.10 | 11:32 | ERAUSDT | LONG | ongoing | осторожно 65% |
| 1428 | 08.10 | 11:06 | SKDDUSDT | LONG | ongoing | осторожно 60% |
| 1427 | 08.10 | 06:36 | EWYUSDT | SHORT | ongoing | осторожно 75% |
| 1426 | 08.10 | 06:07 | NIGHTUSDT | SHORT | ongoing | осторожно 70% |
| 1425 | 08.10 | 04:32 | ACEUSDT | SHORT | TP_clean | осторожно 61% |
| 1424 | 08.10 | 03:01 | INJUSDT | LONG | SL_clean | осторожно 62% |
| 1423 | 07.10 | 22:39 | HYPEUSDT | SHORT | TP_clean | осторожно 62% |
| 1422 | 07.10 | 21:39 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 64% |
| 1421 | 07.10 | 20:34 | LINKUSDT | SHORT | TP_clean | осторожно 67% |
| 1420 | 07.10 | 19:37 | SKHYUSDT | SHORT | TP_clean | осторожно 72% |
| 1419 | 07.10 | 19:04 | COTIUSDT | SHORT | TP_clean | осторожно 68% |
| 1418 | 07.10 | 19:04 | HUMAUSDT | SHORT | TP_clean | осторожно 67% |
| 1417 | 07.10 | 18:08 | ATOMUSDT | SHORT | SL_clean | осторожно 61% |
| 1416 | 07.10 | 18:02 | LYNUSDT | SHORT | TP_clean | осторожно 63% |
| 1415 | 07.10 | 17:30 | SANDUSDT | LONG | TP_clean | осторожно 72% |
| 1414 | 07.10 | 16:30 | CAPUSDT | LONG | TP_clean | входить 81% |
| 1413 | 07.10 | 14:05 | ARMUSDT | SHORT | TP_clean | осторожно 65% |
| 1412 | 07.10 | 12:30 | USUSDT | LONG | SL_clean | осторожно 71% |
| 1411 | 07.10 | 12:13 | TRUMPUSDT | SHORT | TP_clean | осторожно 60% |
| 1410 | 07.10 | 09:06 | BRUSDT | LONG | SL_clean | осторожно 74% |
| 1409 | 07.10 | 08:31 | ESPUSDT | LONG | SL_clean | осторожно 71% |
| 1408 | 07.10 | 07:34 | BZUSDT | LONG | Sideways | осторожно 61% |
| 1407 | 07.10 | 07:30 | UMAUSDT | LONG | SL_clean | осторожно 67% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-10 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-09 06:30 UTC
- mmscan-snapshot: next run 2026-10-09 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
