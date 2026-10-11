# MM Scan Shadow Snapshot
Generated: 2026-10-11T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1454.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-11T17:31:07+0000 (#1475 ZKUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-10T18:00:02Z → 2026-10-11T18:00:02Z)
- New signals: 9 (LONG 5 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1454.2h, restarts: 0
- Last closer: 2026-10-11T03:00:35Z
- Last backfill: 2026-10-11T17:30:03Z
- Anomalies: ongoing >24h без закрытия: 6

## Health 7d (window: 2026-10-04T18:00:02Z → 2026-10-11T18:00:02Z)
- New signals: 96 (~13.7/day)
- Closed: 81 (TP 43, SL 22, SL→rev 0, Sideways 16, N/A 0)
- Ongoing: 15
- TP rate 7d: 66.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1475
- Closed: 1460 (TP_clean 739, SL_clean 510, SL→reverse 0, Sideways 211, N/A 0)
- Ongoing (<24h): 15
- TP rate: 59.2% decided (TP/(TP+SL)) · 50.6% pointwise (excl N/A)

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
| 1475 | 11.10 | 20:31 | ZKUSDT | LONG | ongoing | осторожно 65% |
| 1474 | 11.10 | 20:30 | CHIPUSDT | LONG | ongoing | осторожно 77% |
| 1473 | 11.10 | 09:32 | METUSDT | SHORT | ongoing | осторожно 73% |
| 1472 | 11.10 | 09:12 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 1471 | 11.10 | 06:09 | ICPUSDT | SHORT | ongoing | осторожно 66% |
| 1470 | 11.10 | 05:32 | KAIAUSDT | LONG | ongoing | осторожно 77% |
| 1469 | 11.10 | 04:04 | SEIUSDT | SHORT | ongoing | осторожно 79% |
| 1468 | 11.10 | 04:00 | VVVUSDT | LONG | ongoing | осторожно 60% |
| 1467 | 11.10 | 02:32 | CAPUSDT | LONG | ongoing | осторожно 60% |
| 1466 | 10.10 | 17:01 | ERAUSDT | LONG | ongoing | осторожно 71% |
| 1465 | 10.10 | 14:34 | VETUSDT | LONG | ongoing | осторожно 67% |
| 1464 | 10.10 | 13:06 | PHAUSDT | SHORT | ongoing | осторожно 61% |
| 1463 | 10.10 | 12:08 | CTUSDT | SHORT | ongoing | осторожно 60% |
| 1462 | 10.10 | 11:01 | LPTUSDT | LONG | ongoing | осторожно 79% |
| 1461 | 10.10 | 08:35 | BOMEUSDT | LONG | ongoing | осторожно 61% |
| 1460 | 10.10 | 04:31 | USUSDT | LONG | TP_clean | осторожно 65% |
| 1459 | 10.10 | 03:13 | FARTCOINUSDT | LONG | Sideways | осторожно 60% |
| 1458 | 10.10 | 03:03 | AKEUSDT | LONG | Sideways | осторожно 63% |
| 1457 | 10.10 | 02:36 | APTUSDT | LONG | TP_clean | осторожно 62% |
| 1456 | 10.10 | 01:08 | IRENUSDT | SHORT | Sideways | осторожно 68% |
| 1455 | 09.10 | 22:39 | SKHYUSDT | SHORT | Sideways | осторожно 74% |
| 1454 | 09.10 | 20:09 | SNDKUSDT | SHORT | Sideways | осторожно 68% |
| 1453 | 09.10 | 19:10 | CRWVUSDT | SHORT | Sideways | осторожно 72% |
| 1452 | 09.10 | 19:02 | KORUUSDT | SHORT | Sideways | осторожно 68% |
| 1451 | 09.10 | 18:00 | KAIAUSDT | LONG | TP_clean | осторожно 71% |
| 1450 | 09.10 | 17:34 | SKHYNIXUSDT | SHORT | Sideways | осторожно 74% |
| 1449 | 09.10 | 17:09 | KAITOUSDT | SHORT | Sideways | осторожно 62% |
| 1448 | 09.10 | 16:38 | RENDERUSDT | SHORT | SL_clean | осторожно 70% |
| 1447 | 09.10 | 16:07 | GRIFFAINUSDT | SHORT | SL_clean | осторожно 82% |
| 1446 | 09.10 | 15:03 | 2ZUSDT | SHORT | SL_clean | осторожно 69% |
| 1445 | 09.10 | 14:05 | INTCUSDT | SHORT | TP_clean | осторожно 70% |
| 1444 | 09.10 | 14:03 | BILLUSDT | SHORT | TP_clean | осторожно 68% |
| 1443 | 09.10 | 13:04 | ORDIUSDT | SHORT | SL_clean | осторожно 62% |
| 1442 | 09.10 | 12:05 | KAITOUSDT | SHORT | Sideways | осторожно 81% |
| 1441 | 09.10 | 11:32 | MINAUSDT | SHORT | SL_clean | осторожно 61% |
| 1440 | 09.10 | 08:02 | ORCAUSDT | SHORT | TP_clean | осторожно 68% |
| 1439 | 09.10 | 05:04 | CAKEUSDT | SHORT | Sideways | осторожно 62% |
| 1438 | 09.10 | 01:31 | BRUSDT | SHORT | TP_clean | осторожно 61% |
| 1437 | 08.10 | 23:08 | NILUSDT | SHORT | Sideways | осторожно 71% |
| 1436 | 08.10 | 21:33 | SKLUSDT | SHORT | SL_clean | осторожно 70% |
| 1435 | 08.10 | 21:33 | USUSDT | LONG | TP_clean | осторожно 63% |
| 1434 | 08.10 | 21:01 | LPTUSDT | SHORT | TP_clean | осторожно 74% |
| 1433 | 08.10 | 18:12 | LINKUSDT | SHORT | TP_clean | осторожно 66% |
| 1432 | 08.10 | 18:07 | ENSUSDT | SHORT | TP_clean | осторожно 74% |
| 1431 | 08.10 | 18:04 | CRVUSDT | SHORT | TP_clean | осторожно 76% |
| 1430 | 08.10 | 15:33 | CTUSDT | SHORT | TP_clean | осторожно 61% |
| 1429 | 08.10 | 11:32 | ERAUSDT | LONG | TP_clean | осторожно 65% |
| 1428 | 08.10 | 11:06 | SKDDUSDT | LONG | TP_clean | осторожно 60% |
| 1427 | 08.10 | 06:36 | EWYUSDT | SHORT | TP_clean | осторожно 75% |
| 1426 | 08.10 | 06:07 | NIGHTUSDT | SHORT | TP_clean | осторожно 70% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-12 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-11 18:30 UTC
- mmscan-snapshot: next run 2026-10-12 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
