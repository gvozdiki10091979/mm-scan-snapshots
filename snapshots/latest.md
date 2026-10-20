# MM Scan Shadow Snapshot
Generated: 2026-10-20T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1658.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-20T04:30:46+0000 (#1604 PHAUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-19T06:00:01Z → 2026-10-20T06:00:01Z)
- New signals: 11 (LONG 4 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1658.2h, restarts: 0
- Last closer: 2026-10-20T03:00:29Z
- Last backfill: 2026-10-20T05:30:03Z
- Anomalies: ongoing >24h без закрытия: 1

## Health 7d (window: 2026-10-13T06:00:01Z → 2026-10-20T06:00:01Z)
- New signals: 111 (~15.9/day)
- Closed: 99 (TP 59, SL 30, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 12
- TP rate 7d: 66.3%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1604
- Closed: 1592 (TP_clean 814, SL_clean 555, SL→reverse 0, Sideways 223, N/A 0)
- Ongoing (<24h): 12
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.1% pointwise (excl N/A)

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
| 1604 | 20.10 | 07:30 | PHAUSDT | LONG | ongoing | осторожно 77% |
| 1603 | 20.10 | 06:40 | DELLUSDT | SHORT | ongoing | осторожно 74% |
| 1602 | 20.10 | 03:38 | SIRENUSDT | SHORT | ongoing | входить 90% |
| 1601 | 20.10 | 02:35 | SKDDUSDT | SHORT | ongoing | осторожно 65% |
| 1600 | 20.10 | 01:38 | CRWVUSDT | SHORT | ongoing | осторожно 77% |
| 1599 | 19.10 | 22:37 | COHRUSDT | SHORT | ongoing | осторожно 62% |
| 1598 | 19.10 | 22:03 | ALTUSDT | LONG | ongoing | осторожно 69% |
| 1597 | 19.10 | 21:32 | DOTUSDT | LONG | ongoing | осторожно 61% |
| 1596 | 19.10 | 18:04 | MINIMAXUSDT | SHORT | ongoing | осторожно 61% |
| 1595 | 19.10 | 17:37 | SKDDUSDT | SHORT | ongoing | осторожно 69% |
| 1594 | 19.10 | 13:35 | DUSKUSDT | LONG | ongoing | осторожно 62% |
| 1593 | 19.10 | 08:01 | UNITREEUSDT | LONG | ongoing | осторожно 64% |
| 1592 | 19.10 | 03:02 | SOXSUSDT | LONG | SL_clean | осторожно 62% |
| 1591 | 18.10 | 23:02 | BRUSDT | LONG | TP_clean | осторожно 61% |
| 1590 | 18.10 | 22:40 | TRUMPUSDT | SHORT | Sideways | осторожно 67% |
| 1589 | 18.10 | 22:35 | HYPEUSDT | SHORT | SL_clean | осторожно 72% |
| 1588 | 18.10 | 22:33 | VVVUSDT | SHORT | TP_clean | осторожно 70% |
| 1587 | 18.10 | 16:09 | SIRENUSDT | SHORT | SL_clean | осторожно 75% |
| 1586 | 18.10 | 16:06 | XMRUSDT | LONG | TP_clean | осторожно 66% |
| 1585 | 18.10 | 15:00 | WALUSDT | SHORT | TP_clean | осторожно 76% |
| 1584 | 18.10 | 14:01 | MAGICUSDT | SHORT | TP_clean | осторожно 66% |
| 1583 | 18.10 | 13:34 | OGNUSDT | LONG | TP_clean | осторожно 60% |
| 1582 | 18.10 | 13:32 | AXLUSDT | LONG | SL_clean | осторожно 72% |
| 1581 | 18.10 | 11:02 | QNTUSDT | SHORT | TP_clean | осторожно 63% |
| 1580 | 18.10 | 10:31 | AVAUSDT | LONG | TP_clean | осторожно 61% |
| 1579 | 18.10 | 08:09 | MARSCOINUSDT | SHORT | TP_clean | осторожно 69% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-20 06:30 UTC
- mmscan-snapshot: next run 2026-10-20 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
