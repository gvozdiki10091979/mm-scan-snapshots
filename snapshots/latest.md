# MM Scan Shadow Snapshot
Generated: 2026-10-27T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 6.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-10-27T04:05:32+0000 (#1717 KATUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-10-26T06:00:01Z → 2026-10-27T06:00:01Z)
- New signals: 11 (LONG 6 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 6.6h, restarts: 8
- Last closer: 2026-10-27T03:00:35Z
- Last backfill: 2026-10-27T05:30:03Z
- Anomalies: listener рестартов: 8

## Health 7d (window: 2026-10-20T06:00:01Z → 2026-10-27T06:00:01Z)
- New signals: 113 (~16.1/day)
- Closed: 102 (TP 53, SL 36, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 11
- TP rate 7d: 59.6%
- Listener uptime 7d: 3.9% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1717
- Closed: 1706 (TP_clean 876, SL_clean 594, SL→reverse 0, Sideways 236, N/A 0)
- Ongoing (<24h): 11
- TP rate: 59.6% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 1717 | 27.10 | 07:05 | KATUSDT | LONG | ongoing | осторожно 70% |
| 1716 | 27.10 | 06:02 | IRYSUSDT | SHORT | ongoing | осторожно 61% |
| 1715 | 27.10 | 05:07 | HYPEUSDT | SHORT | ongoing | осторожно 73% |
| 1714 | 27.10 | 05:01 | UNITREEUSDT | LONG | ongoing | осторожно 61% |
| 1713 | 27.10 | 03:30 | BIRBUSDT | SHORT | ongoing | входить 90% |
| 1712 | 27.10 | 01:09 | ERAUSDT | LONG | ongoing | осторожно 68% |
| 1711 | 26.10 | 22:01 | FARTCOINUSDT | SHORT | ongoing | осторожно 63% |
| 1710 | 26.10 | 16:36 | QUSDT | SHORT | ongoing | осторожно 63% |
| 1709 | 26.10 | 15:32 | GRASSUSDT | LONG | ongoing | осторожно 60% |
| 1708 | 26.10 | 14:01 | IOSTUSDT | LONG | ongoing | осторожно 65% |
| 1707 | 26.10 | 12:06 | ZHONGJIUSDT | LONG | ongoing | осторожно 61% |
| 1706 | 26.10 | 04:30 | ERAUSDT | SHORT | TP_clean | осторожно 60% |
| 1705 | 26.10 | 03:35 | BMTUSDT | SHORT | SL_clean | осторожно 60% |
| 1704 | 26.10 | 01:35 | XMRUSDT | LONG | Sideways | осторожно 63% |
| 1703 | 25.10 | 19:07 | SANDUSDT | SHORT | Sideways | осторожно 62% |
| 1702 | 25.10 | 18:31 | MEGAUSDT | LONG | SL_clean | осторожно 70% |
| 1701 | 25.10 | 17:34 | GRASSUSDT | LONG | TP_clean | осторожно 61% |
| 1700 | 25.10 | 17:04 | BABYUSDT | LONG | SL_clean | осторожно 83% |
| 1699 | 25.10 | 14:40 | SANDUSDT | SHORT | Sideways | осторожно 63% |
| 1698 | 25.10 | 14:33 | TREEUSDT | SHORT | TP_clean | осторожно 71% |
| 1697 | 25.10 | 14:14 | XMRUSDT | SHORT | TP_clean | осторожно 65% |
| 1696 | 25.10 | 13:05 | BMTUSDT | LONG | SL_clean | осторожно 73% |
| 1695 | 25.10 | 13:03 | POLYXUSDT | LONG | TP_clean | осторожно 61% |
| 1694 | 25.10 | 11:32 | 1000XECUSDT | LONG | TP_clean | осторожно 73% |
| 1693 | 25.10 | 08:41 | AKEUSDT | SHORT | TP_clean | осторожно 78% |
| 1692 | 25.10 | 07:34 | SANDUSDT | SHORT | TP_clean | осторожно 80% |
| 1691 | 25.10 | 05:04 | ATOMUSDT | SHORT | Sideways | осторожно 62% |
| 1690 | 25.10 | 04:30 | STEEMUSDT | SHORT | SL_clean | осторожно 62% |
| 1689 | 25.10 | 03:38 | CTUSDT | SHORT | SL_clean | осторожно 63% |
| 1688 | 25.10 | 00:41 | MARSCOINUSDT | SHORT | SL_clean | осторожно 68% |
| 1687 | 25.10 | 00:09 | ARBUSDT | SHORT | Sideways | осторожно 69% |
| 1686 | 24.10 | 23:08 | MAGMAUSDT | SHORT | TP_clean | осторожно 65% |
| 1685 | 24.10 | 21:33 | QUSDT | SHORT | TP_clean | осторожно 78% |
| 1684 | 24.10 | 21:09 | SEIUSDT | SHORT | Sideways | осторожно 60% |
| 1683 | 24.10 | 21:00 | ERAUSDT | LONG | SL_clean | осторожно 64% |
| 1682 | 24.10 | 18:07 | BTWUSDT | LONG | TP_clean | осторожно 68% |
| 1681 | 24.10 | 17:33 | ANIMEUSDT | LONG | TP_clean | осторожно 60% |
| 1680 | 24.10 | 16:09 | TRUSTUSDT | LONG | SL_clean | осторожно 66% |
| 1679 | 24.10 | 16:06 | APRUSDT | LONG | TP_clean | осторожно 63% |
| 1678 | 24.10 | 15:00 | KATUSDT | LONG | SL_clean | осторожно 74% |
| 1677 | 24.10 | 12:06 | EIGENUSDT | SHORT | TP_clean | осторожно 64% |
| 1676 | 24.10 | 11:31 | ERAUSDT | LONG | TP_clean | осторожно 71% |
| 1675 | 24.10 | 10:04 | XPLUSDT | SHORT | TP_clean | осторожно 60% |
| 1674 | 24.10 | 08:31 | TREEUSDT | LONG | TP_clean | осторожно 65% |
| 1673 | 24.10 | 08:10 | BILLUSDT | SHORT | TP_clean | осторожно 68% |
| 1672 | 24.10 | 07:06 | DASHUSDT | SHORT | TP_clean | осторожно 69% |
| 1671 | 24.10 | 06:38 | BOMEUSDT | LONG | SL_clean | осторожно 60% |
| 1670 | 24.10 | 05:06 | NEARUSDT | SHORT | TP_clean | осторожно 63% |
| 1669 | 24.10 | 01:35 | AEROUSDT | SHORT | TP_clean | осторожно 61% |
| 1668 | 24.10 | 01:10 | CSOPSKHYNIX2LUSDT | SHORT | TP_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-28 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-27 06:30 UTC
- mmscan-snapshot: next run 2026-10-27 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
