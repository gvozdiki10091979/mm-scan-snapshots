# MM Scan Shadow Snapshot
Generated: 2026-10-20T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1652.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-19T23:35:03+0000 (#1601 SKDDUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-19T00:00:01Z → 2026-10-20T00:00:01Z)
- New signals: 10 (LONG 5 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1652.2h, restarts: 0
- Last closer: 2026-10-19T03:00:43Z
- Last backfill: 2026-10-19T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 13

## Health 7d (window: 2026-10-13T00:00:01Z → 2026-10-20T00:00:01Z)
- New signals: 112 (~16.0/day)
- Closed: 89 (TP 52, SL 27, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 23
- TP rate 7d: 65.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1601
- Closed: 1578 (TP_clean 805, SL_clean 551, SL→reverse 0, Sideways 222, N/A 0)
- Ongoing (<24h): 23
- TP rate: 59.4% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 1601 | 20.10 | 02:35 | SKDDUSDT | SHORT | ongoing | осторожно 65% |
| 1600 | 20.10 | 01:38 | CRWVUSDT | SHORT | ongoing | осторожно 77% |
| 1599 | 19.10 | 22:37 | COHRUSDT | SHORT | ongoing | осторожно 62% |
| 1598 | 19.10 | 22:03 | ALTUSDT | LONG | ongoing | осторожно 69% |
| 1597 | 19.10 | 21:32 | DOTUSDT | LONG | ongoing | осторожно 61% |
| 1596 | 19.10 | 18:04 | MINIMAXUSDT | SHORT | ongoing | осторожно 61% |
| 1595 | 19.10 | 17:37 | SKDDUSDT | SHORT | ongoing | осторожно 69% |
| 1594 | 19.10 | 13:35 | DUSKUSDT | LONG | ongoing | осторожно 62% |
| 1593 | 19.10 | 08:01 | UNITREEUSDT | LONG | ongoing | осторожно 64% |
| 1592 | 19.10 | 03:02 | SOXSUSDT | LONG | ongoing | осторожно 62% |
| 1591 | 18.10 | 23:02 | BRUSDT | LONG | ongoing | осторожно 61% |
| 1590 | 18.10 | 22:40 | TRUMPUSDT | SHORT | ongoing | осторожно 67% |
| 1589 | 18.10 | 22:35 | HYPEUSDT | SHORT | ongoing | осторожно 72% |
| 1588 | 18.10 | 22:33 | VVVUSDT | SHORT | ongoing | осторожно 70% |
| 1587 | 18.10 | 16:09 | SIRENUSDT | SHORT | ongoing | осторожно 75% |
| 1586 | 18.10 | 16:06 | XMRUSDT | LONG | ongoing | осторожно 66% |
| 1585 | 18.10 | 15:00 | WALUSDT | SHORT | ongoing | осторожно 76% |
| 1584 | 18.10 | 14:01 | MAGICUSDT | SHORT | ongoing | осторожно 66% |
| 1583 | 18.10 | 13:34 | OGNUSDT | LONG | ongoing | осторожно 60% |
| 1582 | 18.10 | 13:32 | AXLUSDT | LONG | ongoing | осторожно 72% |
| 1581 | 18.10 | 11:02 | QNTUSDT | SHORT | ongoing | осторожно 63% |
| 1580 | 18.10 | 10:31 | AVAUSDT | LONG | ongoing | осторожно 61% |
| 1579 | 18.10 | 08:09 | MARSCOINUSDT | SHORT | ongoing | осторожно 69% |
| 1578 | 18.10 | 04:12 | XPLUSDT | SHORT | TP_clean | осторожно 63% |
| 1577 | 18.10 | 03:18 | FARTCOINUSDT | SHORT | TP_clean | осторожно 62% |
| 1576 | 18.10 | 03:15 | MARSCOINUSDT | SHORT | TP_clean | осторожно 68% |
| 1575 | 17.10 | 22:10 | UNIUSDT | SHORT | Sideways | осторожно 69% |
| 1574 | 17.10 | 22:03 | ZKUSDT | SHORT | TP_clean | осторожно 60% |
| 1573 | 17.10 | 21:38 | TRUMPUSDT | SHORT | TP_clean | осторожно 62% |
| 1572 | 17.10 | 19:40 | ZEREBROUSDT | SHORT | TP_clean | осторожно 64% |
| 1571 | 17.10 | 19:31 | ALTUSDT | LONG | TP_clean | осторожно 72% |
| 1570 | 17.10 | 18:39 | CRWVUSDT | SHORT | TP_clean | осторожно 62% |
| 1569 | 17.10 | 18:36 | SUIUSDT | SHORT | TP_clean | осторожно 63% |
| 1568 | 17.10 | 18:15 | ALGOUSDT | SHORT | TP_clean | осторожно 68% |
| 1567 | 17.10 | 15:07 | AVAXUSDT | SHORT | TP_clean | осторожно 64% |
| 1566 | 17.10 | 14:38 | ZEREBROUSDT | SHORT | TP_clean | осторожно 72% |
| 1565 | 17.10 | 13:01 | KMNOUSDT | LONG | SL_clean | осторожно 64% |
| 1564 | 17.10 | 08:33 | LTCUSDT | SHORT | TP_clean | осторожно 83% |
| 1563 | 17.10 | 07:31 | POLUSDT | SHORT | TP_clean | осторожно 82% |
| 1562 | 17.10 | 06:07 | DOGEUSDT | SHORT | TP_clean | осторожно 60% |
| 1561 | 17.10 | 06:04 | KMNOUSDT | LONG | TP_clean | осторожно 63% |
| 1560 | 17.10 | 06:01 | MAGICUSDT | LONG | SL_clean | осторожно 60% |
| 1559 | 17.10 | 04:32 | MINAUSDT | LONG | TP_clean | осторожно 67% |
| 1558 | 17.10 | 03:02 | BATUSDT | LONG | TP_clean | осторожно 61% |
| 1557 | 17.10 | 02:04 | TRUMPUSDT | LONG | SL_clean | осторожно 62% |
| 1556 | 17.10 | 01:38 | SOLUSDT | SHORT | TP_clean | осторожно 77% |
| 1555 | 17.10 | 01:38 | QCOMUSDT | SHORT | Sideways | осторожно 77% |
| 1554 | 17.10 | 00:38 | 1000BONKUSDT | SHORT | TP_clean | осторожно 66% |
| 1553 | 17.10 | 00:35 | NIGHTUSDT | SHORT | SL_clean | осторожно 68% |
| 1552 | 16.10 | 23:05 | PEOPLEUSDT | LONG | Sideways | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-20 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-20 00:30 UTC
- mmscan-snapshot: next run 2026-10-20 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
