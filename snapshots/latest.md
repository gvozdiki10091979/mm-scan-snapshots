# MM Scan Shadow Snapshot
Generated: 2026-10-21T12:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1688.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-21T09:39:37+0000 (#1622 DOODUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-20T12:00:02Z → 2026-10-21T12:00:02Z)
- New signals: 15 (LONG 10 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1688.2h, restarts: 0
- Last closer: 2026-10-21T03:00:19Z
- Last backfill: 2026-10-21T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-10-14T12:00:02Z → 2026-10-21T12:00:02Z)
- New signals: 113 (~16.1/day)
- Closed: 93 (TP 58, SL 26, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 20
- TP rate 7d: 69.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1622
- Closed: 1602 (TP_clean 821, SL_clean 558, SL→reverse 0, Sideways 223, N/A 0)
- Ongoing (<24h): 20
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 1622 | 21.10 | 12:39 | DOODUSDT | LONG | ongoing | осторожно 76% |
| 1621 | 21.10 | 12:31 | AVAUSDT | SHORT | ongoing | осторожно 78% |
| 1620 | 21.10 | 10:06 | ARCUSDT | LONG | ongoing | осторожно 67% |
| 1619 | 21.10 | 09:32 | PONSUSDT | LONG | ongoing | осторожно 67% |
| 1618 | 21.10 | 09:30 | IOSTUSDT | LONG | ongoing | входить 90% |
| 1617 | 21.10 | 08:34 | MUUUSDT | LONG | ongoing | осторожно 66% |
| 1616 | 21.10 | 07:33 | ARBUSDT | LONG | ongoing | осторожно 65% |
| 1615 | 21.10 | 07:02 | ZHIPUUSDT | SHORT | ongoing | осторожно 62% |
| 1614 | 21.10 | 07:01 | BIRBUSDT | LONG | ongoing | осторожно 63% |
| 1613 | 21.10 | 05:00 | MEWUSDT | LONG | ongoing | осторожно 61% |
| 1612 | 20.10 | 20:02 | SIRENUSDT | SHORT | ongoing | осторожно 67% |
| 1611 | 20.10 | 19:06 | BEUSDT | LONG | ongoing | осторожно 70% |
| 1610 | 20.10 | 17:32 | BMTUSDT | LONG | ongoing | осторожно 61% |
| 1609 | 20.10 | 17:31 | SOPHUSDT | SHORT | ongoing | осторожно 62% |
| 1608 | 20.10 | 15:07 | ENSOUSDT | SHORT | ongoing | осторожно 74% |
| 1607 | 20.10 | 14:10 | MUBARAKUSDT | SHORT | ongoing | осторожно 89% |
| 1606 | 20.10 | 13:37 | ARIAUSDT | SHORT | ongoing | осторожно 66% |
| 1605 | 20.10 | 10:34 | ARMUSDT | SHORT | ongoing | осторожно 67% |
| 1604 | 20.10 | 07:30 | PHAUSDT | LONG | ongoing | осторожно 77% |
| 1603 | 20.10 | 06:40 | DELLUSDT | SHORT | ongoing | осторожно 74% |
| 1602 | 20.10 | 03:38 | SIRENUSDT | SHORT | SL_clean | входить 90% |
| 1601 | 20.10 | 02:35 | SKDDUSDT | SHORT | SL_clean | осторожно 65% |
| 1600 | 20.10 | 01:38 | CRWVUSDT | SHORT | TP_clean | осторожно 77% |
| 1599 | 19.10 | 22:37 | COHRUSDT | SHORT | TP_clean | осторожно 62% |
| 1598 | 19.10 | 22:03 | ALTUSDT | LONG | TP_clean | осторожно 69% |
| 1597 | 19.10 | 21:32 | DOTUSDT | LONG | TP_clean | осторожно 61% |
| 1596 | 19.10 | 18:04 | MINIMAXUSDT | SHORT | TP_clean | осторожно 61% |
| 1595 | 19.10 | 17:37 | SKDDUSDT | SHORT | SL_clean | осторожно 69% |
| 1594 | 19.10 | 13:35 | DUSKUSDT | LONG | TP_clean | осторожно 62% |
| 1593 | 19.10 | 08:01 | UNITREEUSDT | LONG | TP_clean | осторожно 64% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-22 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-21 12:30 UTC
- mmscan-snapshot: next run 2026-10-21 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
