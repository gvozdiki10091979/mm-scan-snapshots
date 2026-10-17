# MM Scan Shadow Snapshot
Generated: 2026-10-17T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1592.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-17T11:38:18+0000 (#1566 ZEREBROUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-16T12:00:01Z → 2026-10-17T12:00:01Z)
- New signals: 22 (LONG 9 / SHORT 13)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 22
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1592.2h, restarts: 0
- Last closer: 2026-10-17T03:00:41Z
- Last backfill: 2026-10-17T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 2

## Health 7d (window: 2026-10-10T12:00:01Z → 2026-10-17T12:00:01Z)
- New signals: 101 (~14.4/day)
- Closed: 77 (TP 40, SL 32, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 24
- TP rate 7d: 55.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1566
- Closed: 1542 (TP_clean 782, SL_clean 543, SL→reverse 0, Sideways 217, N/A 0)
- Ongoing (<24h): 24
- TP rate: 59.0% decided (TP/(TP+SL)) · 50.7% pointwise (excl N/A)

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
| 1566 | 17.10 | 14:38 | ZEREBROUSDT | SHORT | ongoing | осторожно 72% |
| 1565 | 17.10 | 13:01 | KMNOUSDT | LONG | ongoing | осторожно 64% |
| 1564 | 17.10 | 08:33 | LTCUSDT | SHORT | ongoing | осторожно 83% |
| 1563 | 17.10 | 07:31 | POLUSDT | SHORT | ongoing | осторожно 82% |
| 1562 | 17.10 | 06:07 | DOGEUSDT | SHORT | ongoing | осторожно 60% |
| 1561 | 17.10 | 06:04 | KMNOUSDT | LONG | ongoing | осторожно 63% |
| 1560 | 17.10 | 06:01 | MAGICUSDT | LONG | ongoing | осторожно 60% |
| 1559 | 17.10 | 04:32 | MINAUSDT | LONG | ongoing | осторожно 67% |
| 1558 | 17.10 | 03:02 | BATUSDT | LONG | ongoing | осторожно 61% |
| 1557 | 17.10 | 02:04 | TRUMPUSDT | LONG | ongoing | осторожно 62% |
| 1556 | 17.10 | 01:38 | SOLUSDT | SHORT | ongoing | осторожно 77% |
| 1555 | 17.10 | 01:38 | QCOMUSDT | SHORT | ongoing | осторожно 77% |
| 1554 | 17.10 | 00:38 | 1000BONKUSDT | SHORT | ongoing | осторожно 66% |
| 1553 | 17.10 | 00:35 | NIGHTUSDT | SHORT | ongoing | осторожно 68% |
| 1552 | 16.10 | 23:05 | PEOPLEUSDT | LONG | ongoing | осторожно 60% |
| 1551 | 16.10 | 21:06 | WDCUSDT | SHORT | ongoing | осторожно 62% |
| 1550 | 16.10 | 20:41 | AKEUSDT | LONG | ongoing | осторожно 65% |
| 1549 | 16.10 | 20:08 | KMNOUSDT | SHORT | ongoing | осторожно 73% |
| 1548 | 16.10 | 19:36 | ZHONGJIUSDT | LONG | ongoing | осторожно 61% |
| 1547 | 16.10 | 19:07 | SAMSUNGUSDT | SHORT | ongoing | осторожно 72% |
| 1546 | 16.10 | 19:05 | EWYUSDT | SHORT | ongoing | осторожно 67% |
| 1545 | 16.10 | 15:02 | SANDUSDT | SHORT | ongoing | осторожно 68% |
| 1544 | 16.10 | 12:31 | ZKUSDT | LONG | ongoing | осторожно 76% |
| 1543 | 16.10 | 12:30 | SUSDT | SHORT | ongoing | осторожно 79% |
| 1542 | 16.10 | 05:02 | WALUSDT | LONG | SL_clean | осторожно 60% |
| 1541 | 16.10 | 04:33 | AVAUSDT | SHORT | TP_clean | осторожно 71% |
| 1540 | 16.10 | 03:36 | SKUUUSDT | SHORT | SL_clean | входить 86% |
| 1539 | 16.10 | 01:08 | RIVERUSDT | SHORT | SL_clean | осторожно 64% |
| 1538 | 15.10 | 23:31 | DOSUSDT | SHORT | TP_clean | осторожно 70% |
| 1537 | 15.10 | 21:39 | MONUSDT | SHORT | TP_clean | осторожно 62% |
| 1536 | 15.10 | 21:36 | MINAUSDT | LONG | Sideways | осторожно 61% |
| 1535 | 15.10 | 21:02 | SOXLUSDT | SHORT | SL_clean | осторожно 63% |
| 1534 | 15.10 | 20:32 | NILUSDT | LONG | TP_clean | осторожно 60% |
| 1533 | 15.10 | 19:08 | AAOIUSDT | SHORT | TP_clean | осторожно 77% |
| 1532 | 15.10 | 19:07 | COHRUSDT | SHORT | SL_clean | осторожно 63% |
| 1531 | 15.10 | 17:36 | KORUUSDT | SHORT | SL_clean | осторожно 61% |
| 1530 | 15.10 | 16:34 | RKLBUSDT | SHORT | TP_clean | осторожно 71% |
| 1529 | 15.10 | 16:04 | USUSDT | SHORT | TP_clean | осторожно 77% |
| 1528 | 15.10 | 15:02 | BSPUSDT | LONG | SL_clean | осторожно 61% |
| 1527 | 15.10 | 14:06 | SNDKUSDT | SHORT | TP_clean | осторожно 64% |
| 1526 | 15.10 | 13:06 | ARBUSDT | SHORT | SL_clean | осторожно 62% |
| 1525 | 15.10 | 11:33 | ICPUSDT | SHORT | SL_clean | осторожно 60% |
| 1524 | 15.10 | 11:10 | ZHONGJIUSDT | SHORT | TP_clean | осторожно 70% |
| 1523 | 15.10 | 08:35 | XPLUSDT | SHORT | SL_clean | осторожно 62% |
| 1522 | 15.10 | 08:03 | 1000BONKUSDT | SHORT | Sideways | осторожно 60% |
| 1521 | 15.10 | 08:02 | SUIUSDT | SHORT | TP_clean | осторожно 61% |
| 1520 | 15.10 | 08:01 | DUSKUSDT | LONG | TP_clean | осторожно 60% |
| 1519 | 15.10 | 02:10 | DOGEUSDT | SHORT | TP_clean | осторожно 61% |
| 1518 | 15.10 | 02:10 | ADAUSDT | SHORT | TP_clean | осторожно 60% |
| 1517 | 15.10 | 02:09 | SOLUSDT | SHORT | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-18 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-17 12:30 UTC
- mmscan-snapshot: next run 2026-10-17 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
