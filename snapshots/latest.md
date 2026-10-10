# MM Scan Shadow Snapshot
Generated: 2026-10-10T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1424.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-10T11:34:01+0000 (#1465 VETUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-09T12:00:01Z → 2026-10-10T12:00:01Z)
- New signals: 20 (LONG 8 / SHORT 12)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 20
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1424.2h, restarts: 0
- Last closer: 2026-10-10T03:00:29Z
- Last backfill: 2026-10-10T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 6

## Health 7d (window: 2026-10-03T12:00:01Z → 2026-10-10T12:00:01Z)
- New signals: 98 (~14.0/day)
- Closed: 72 (TP 42, SL 21, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 26
- TP rate 7d: 66.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1465
- Closed: 1439 (TP_clean 733, SL_clean 505, SL→reverse 0, Sideways 201, N/A 0)
- Ongoing (<24h): 26
- TP rate: 59.2% decided (TP/(TP+SL)) · 50.9% pointwise (excl N/A)

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
| 1465 | 10.10 | 14:34 | VETUSDT | LONG | ongoing | осторожно 67% |
| 1464 | 10.10 | 13:06 | PHAUSDT | SHORT | ongoing | осторожно 61% |
| 1463 | 10.10 | 12:08 | CTUSDT | SHORT | ongoing | осторожно 60% |
| 1462 | 10.10 | 11:01 | LPTUSDT | LONG | ongoing | осторожно 79% |
| 1461 | 10.10 | 08:35 | BOMEUSDT | LONG | ongoing | осторожно 61% |
| 1460 | 10.10 | 04:31 | USUSDT | LONG | ongoing | осторожно 65% |
| 1459 | 10.10 | 03:13 | FARTCOINUSDT | LONG | ongoing | осторожно 60% |
| 1458 | 10.10 | 03:03 | AKEUSDT | LONG | ongoing | осторожно 63% |
| 1457 | 10.10 | 02:36 | APTUSDT | LONG | ongoing | осторожно 62% |
| 1456 | 10.10 | 01:08 | IRENUSDT | SHORT | ongoing | осторожно 68% |
| 1455 | 09.10 | 22:39 | SKHYUSDT | SHORT | ongoing | осторожно 74% |
| 1454 | 09.10 | 20:09 | SNDKUSDT | SHORT | ongoing | осторожно 68% |
| 1453 | 09.10 | 19:10 | CRWVUSDT | SHORT | ongoing | осторожно 72% |
| 1452 | 09.10 | 19:02 | KORUUSDT | SHORT | ongoing | осторожно 68% |
| 1451 | 09.10 | 18:00 | KAIAUSDT | LONG | ongoing | осторожно 71% |
| 1450 | 09.10 | 17:34 | SKHYNIXUSDT | SHORT | ongoing | осторожно 74% |
| 1449 | 09.10 | 17:09 | KAITOUSDT | SHORT | ongoing | осторожно 62% |
| 1448 | 09.10 | 16:38 | RENDERUSDT | SHORT | ongoing | осторожно 70% |
| 1447 | 09.10 | 16:07 | GRIFFAINUSDT | SHORT | ongoing | осторожно 82% |
| 1446 | 09.10 | 15:03 | 2ZUSDT | SHORT | ongoing | осторожно 69% |
| 1445 | 09.10 | 14:05 | INTCUSDT | SHORT | ongoing | осторожно 70% |
| 1444 | 09.10 | 14:03 | BILLUSDT | SHORT | ongoing | осторожно 68% |
| 1443 | 09.10 | 13:04 | ORDIUSDT | SHORT | ongoing | осторожно 62% |
| 1442 | 09.10 | 12:05 | KAITOUSDT | SHORT | ongoing | осторожно 81% |
| 1441 | 09.10 | 11:32 | MINAUSDT | SHORT | ongoing | осторожно 61% |
| 1440 | 09.10 | 08:02 | ORCAUSDT | SHORT | ongoing | осторожно 68% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-11 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-10 12:30 UTC
- mmscan-snapshot: next run 2026-10-10 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
