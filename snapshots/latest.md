# MM Scan Shadow Snapshot
Generated: 2026-10-27T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 0.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-10-26T22:09:09+0000 (#1712 ERAUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-10-26T00:00:01Z → 2026-10-27T00:00:01Z)
- New signals: 8 (LONG 4 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 0.6h, restarts: 8
- Last closer: 2026-10-27T00:00:00Z
- Last backfill: 2026-10-27T00:00:00Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 13

## Health 7d (window: 2026-10-20T00:00:01Z → 2026-10-27T00:00:01Z)
- New signals: 111 (~15.9/day)
- Closed: 90 (TP 47, SL 33, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 21
- TP rate 7d: 58.8%
- Listener uptime 7d: 0.4% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1712
- Closed: 1691 (TP_clean 868, SL_clean 590, SL→reverse 0, Sideways 233, N/A 0)
- Ongoing (<24h): 21
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 1712 | 27.10 | 01:09 | ERAUSDT | LONG | ongoing | осторожно 68% |
| 1711 | 26.10 | 22:01 | FARTCOINUSDT | SHORT | ongoing | осторожно 63% |
| 1710 | 26.10 | 16:36 | QUSDT | SHORT | ongoing | осторожно 63% |
| 1709 | 26.10 | 15:32 | GRASSUSDT | LONG | ongoing | осторожно 60% |
| 1708 | 26.10 | 14:01 | IOSTUSDT | LONG | ongoing | осторожно 65% |
| 1707 | 26.10 | 12:06 | ZHONGJIUSDT | LONG | ongoing | осторожно 61% |
| 1706 | 26.10 | 04:30 | ERAUSDT | SHORT | ongoing | осторожно 60% |
| 1705 | 26.10 | 03:35 | BMTUSDT | SHORT | ongoing | осторожно 60% |
| 1704 | 26.10 | 01:35 | XMRUSDT | LONG | ongoing | осторожно 63% |
| 1703 | 25.10 | 19:07 | SANDUSDT | SHORT | ongoing | осторожно 62% |
| 1702 | 25.10 | 18:31 | MEGAUSDT | LONG | ongoing | осторожно 70% |
| 1701 | 25.10 | 17:34 | GRASSUSDT | LONG | ongoing | осторожно 61% |
| 1700 | 25.10 | 17:04 | BABYUSDT | LONG | ongoing | осторожно 83% |
| 1699 | 25.10 | 14:40 | SANDUSDT | SHORT | ongoing | осторожно 63% |
| 1698 | 25.10 | 14:33 | TREEUSDT | SHORT | ongoing | осторожно 71% |
| 1697 | 25.10 | 14:14 | XMRUSDT | SHORT | ongoing | осторожно 65% |
| 1696 | 25.10 | 13:05 | BMTUSDT | LONG | ongoing | осторожно 73% |
| 1695 | 25.10 | 13:03 | POLYXUSDT | LONG | ongoing | осторожно 61% |
| 1694 | 25.10 | 11:32 | 1000XECUSDT | LONG | ongoing | осторожно 73% |
| 1693 | 25.10 | 08:41 | AKEUSDT | SHORT | ongoing | осторожно 78% |
| 1692 | 25.10 | 07:34 | SANDUSDT | SHORT | ongoing | осторожно 80% |
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
| 1667 | 24.10 | 01:01 | SOONUSDT | SHORT | Sideways | осторожно 62% |
| 1666 | 23.10 | 23:32 | ENAUSDT | LONG | SL_clean | осторожно 63% |
| 1665 | 23.10 | 21:02 | USELESSUSDT | SHORT | TP_clean | осторожно 60% |
| 1664 | 23.10 | 19:35 | ERAUSDT | LONG | SL_clean | осторожно 63% |
| 1663 | 23.10 | 19:03 | CTUSDT | SHORT | TP_clean | осторожно 68% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-27 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-27 00:30 UTC
- mmscan-snapshot: next run 2026-10-27 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
