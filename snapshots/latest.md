# MM Scan Shadow Snapshot
Generated: 2026-10-18T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1610.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-18T05:09:40+0000 (#1579 MARSCOINUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-17T06:00:02Z → 2026-10-18T06:00:02Z)
- New signals: 15 (LONG 2 / SHORT 13)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1610.2h, restarts: 0
- Last closer: 2026-10-18T03:00:32Z
- Last backfill: 2026-10-18T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-10-11T06:00:02Z → 2026-10-18T06:00:02Z)
- New signals: 108 (~15.4/day)
- Closed: 88 (TP 44, SL 35, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 20
- TP rate 7d: 55.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1579
- Closed: 1559 (TP_clean 789, SL_clean 549, SL→reverse 0, Sideways 221, N/A 0)
- Ongoing (<24h): 20
- TP rate: 59.0% decided (TP/(TP+SL)) · 50.6% pointwise (excl N/A)

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
| 1579 | 18.10 | 08:09 | MARSCOINUSDT | SHORT | ongoing | осторожно 69% |
| 1578 | 18.10 | 04:12 | XPLUSDT | SHORT | ongoing | осторожно 63% |
| 1577 | 18.10 | 03:18 | FARTCOINUSDT | SHORT | ongoing | осторожно 62% |
| 1576 | 18.10 | 03:15 | MARSCOINUSDT | SHORT | ongoing | осторожно 68% |
| 1575 | 17.10 | 22:10 | UNIUSDT | SHORT | ongoing | осторожно 69% |
| 1574 | 17.10 | 22:03 | ZKUSDT | SHORT | ongoing | осторожно 60% |
| 1573 | 17.10 | 21:38 | TRUMPUSDT | SHORT | ongoing | осторожно 62% |
| 1572 | 17.10 | 19:40 | ZEREBROUSDT | SHORT | ongoing | осторожно 64% |
| 1571 | 17.10 | 19:31 | ALTUSDT | LONG | ongoing | осторожно 72% |
| 1570 | 17.10 | 18:39 | CRWVUSDT | SHORT | ongoing | осторожно 62% |
| 1569 | 17.10 | 18:36 | SUIUSDT | SHORT | ongoing | осторожно 63% |
| 1568 | 17.10 | 18:15 | ALGOUSDT | SHORT | ongoing | осторожно 68% |
| 1567 | 17.10 | 15:07 | AVAXUSDT | SHORT | ongoing | осторожно 64% |
| 1566 | 17.10 | 14:38 | ZEREBROUSDT | SHORT | ongoing | осторожно 72% |
| 1565 | 17.10 | 13:01 | KMNOUSDT | LONG | ongoing | осторожно 64% |
| 1564 | 17.10 | 08:33 | LTCUSDT | SHORT | ongoing | осторожно 83% |
| 1563 | 17.10 | 07:31 | POLUSDT | SHORT | ongoing | осторожно 82% |
| 1562 | 17.10 | 06:07 | DOGEUSDT | SHORT | ongoing | осторожно 60% |
| 1561 | 17.10 | 06:04 | KMNOUSDT | LONG | ongoing | осторожно 63% |
| 1560 | 17.10 | 06:01 | MAGICUSDT | LONG | ongoing | осторожно 60% |
| 1559 | 17.10 | 04:32 | MINAUSDT | LONG | TP_clean | осторожно 67% |
| 1558 | 17.10 | 03:02 | BATUSDT | LONG | TP_clean | осторожно 61% |
| 1557 | 17.10 | 02:04 | TRUMPUSDT | LONG | SL_clean | осторожно 62% |
| 1556 | 17.10 | 01:38 | SOLUSDT | SHORT | TP_clean | осторожно 77% |
| 1555 | 17.10 | 01:38 | QCOMUSDT | SHORT | Sideways | осторожно 77% |
| 1554 | 17.10 | 00:38 | 1000BONKUSDT | SHORT | TP_clean | осторожно 66% |
| 1553 | 17.10 | 00:35 | NIGHTUSDT | SHORT | SL_clean | осторожно 68% |
| 1552 | 16.10 | 23:05 | PEOPLEUSDT | LONG | Sideways | осторожно 60% |
| 1551 | 16.10 | 21:06 | WDCUSDT | SHORT | TP_clean | осторожно 62% |
| 1550 | 16.10 | 20:41 | AKEUSDT | LONG | SL_clean | осторожно 65% |
| 1549 | 16.10 | 20:08 | KMNOUSDT | SHORT | SL_clean | осторожно 73% |
| 1548 | 16.10 | 19:36 | ZHONGJIUSDT | LONG | SL_clean | осторожно 61% |
| 1547 | 16.10 | 19:07 | SAMSUNGUSDT | SHORT | Sideways | осторожно 72% |
| 1546 | 16.10 | 19:05 | EWYUSDT | SHORT | Sideways | осторожно 67% |
| 1545 | 16.10 | 15:02 | SANDUSDT | SHORT | TP_clean | осторожно 68% |
| 1544 | 16.10 | 12:31 | ZKUSDT | LONG | SL_clean | осторожно 76% |
| 1543 | 16.10 | 12:30 | SUSDT | SHORT | TP_clean | осторожно 79% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-19 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-18 06:30 UTC
- mmscan-snapshot: next run 2026-10-18 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
