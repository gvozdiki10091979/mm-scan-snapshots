# MM Scan Shadow Snapshot
Generated: 2026-10-13T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1490.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-13T03:01:43+0000 (#1493 BLURUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-12T06:00:02Z → 2026-10-13T06:00:02Z)
- New signals: 12 (LONG 5 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1490.2h, restarts: 0
- Last closer: 2026-10-13T03:00:35Z
- Last backfill: 2026-10-13T05:30:03Z
- Anomalies: ongoing >24h без закрытия: 1

## Health 7d (window: 2026-10-06T06:00:02Z → 2026-10-13T06:00:02Z)
- New signals: 98 (~14.0/day)
- Closed: 85 (TP 46, SL 25, SL→rev 0, Sideways 14, N/A 0)
- Ongoing: 13
- TP rate 7d: 64.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1493
- Closed: 1480 (TP_clean 748, SL_clean 520, SL→reverse 0, Sideways 212, N/A 0)
- Ongoing (<24h): 13
- TP rate: 59.0% decided (TP/(TP+SL)) · 50.5% pointwise (excl N/A)

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
| 1493 | 13.10 | 06:01 | BLURUSDT | SHORT | ongoing | осторожно 62% |
| 1492 | 13.10 | 04:34 | UNITREEUSDT | LONG | ongoing | осторожно 63% |
| 1491 | 13.10 | 04:33 | NMRUSDT | SHORT | ongoing | осторожно 62% |
| 1490 | 13.10 | 03:34 | CKBUSDT | LONG | ongoing | осторожно 75% |
| 1489 | 12.10 | 22:40 | ARUSDT | LONG | ongoing | осторожно 63% |
| 1488 | 12.10 | 22:09 | 1000PEPEUSDT | SHORT | ongoing | осторожно 62% |
| 1487 | 12.10 | 22:01 | JCTUSDT | LONG | ongoing | осторожно 61% |
| 1486 | 12.10 | 20:12 | CAKEUSDT | SHORT | ongoing | осторожно 69% |
| 1485 | 12.10 | 16:06 | WIFUSDT | SHORT | ongoing | осторожно 72% |
| 1484 | 12.10 | 14:07 | MUUUSDT | SHORT | ongoing | осторожно 61% |
| 1483 | 12.10 | 13:05 | MINAUSDT | LONG | ongoing | осторожно 61% |
| 1482 | 12.10 | 12:37 | USUSDT | SHORT | ongoing | осторожно 65% |
| 1481 | 12.10 | 07:35 | KORUUSDT | LONG | ongoing | осторожно 64% |
| 1480 | 12.10 | 03:04 | INJUSDT | LONG | TP_clean | осторожно 61% |
| 1479 | 12.10 | 02:34 | WALUSDT | LONG | SL_clean | осторожно 76% |
| 1478 | 11.10 | 22:40 | LAUSDT | LONG | TP_clean | осторожно 60% |
| 1477 | 11.10 | 22:36 | ZROUSDT | LONG | TP_clean | осторожно 61% |
| 1476 | 11.10 | 22:00 | STRKUSDT | LONG | SL_clean | осторожно 60% |
| 1475 | 11.10 | 20:31 | ZKUSDT | LONG | SL_clean | осторожно 65% |
| 1474 | 11.10 | 20:30 | CHIPUSDT | LONG | SL_clean | осторожно 77% |
| 1473 | 11.10 | 09:32 | METUSDT | SHORT | SL_clean | осторожно 73% |
| 1472 | 11.10 | 09:12 | SEIUSDT | SHORT | SL_clean | осторожно 68% |
| 1471 | 11.10 | 06:09 | ICPUSDT | SHORT | SL_clean | осторожно 66% |
| 1470 | 11.10 | 05:32 | KAIAUSDT | LONG | SL_clean | осторожно 77% |
| 1469 | 11.10 | 04:04 | SEIUSDT | SHORT | SL_clean | осторожно 79% |
| 1468 | 11.10 | 04:00 | VVVUSDT | LONG | TP_clean | осторожно 60% |
| 1467 | 11.10 | 02:32 | CAPUSDT | LONG | TP_clean | осторожно 60% |
| 1466 | 10.10 | 17:01 | ERAUSDT | LONG | TP_clean | осторожно 71% |
| 1465 | 10.10 | 14:34 | VETUSDT | LONG | Sideways | осторожно 67% |
| 1464 | 10.10 | 13:06 | PHAUSDT | SHORT | TP_clean | осторожно 61% |
| 1463 | 10.10 | 12:08 | CTUSDT | SHORT | TP_clean | осторожно 60% |
| 1462 | 10.10 | 11:01 | LPTUSDT | LONG | TP_clean | осторожно 79% |
| 1461 | 10.10 | 08:35 | BOMEUSDT | LONG | SL_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-14 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-13 06:30 UTC
- mmscan-snapshot: next run 2026-10-13 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
