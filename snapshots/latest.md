# MM Scan Shadow Snapshot
Generated: 2026-10-25T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1778.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-25T05:41:48+0000 (#1693 AKEUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-24T06:00:02Z → 2026-10-25T06:00:02Z)
- New signals: 19 (LONG 7 / SHORT 12)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 19
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1778.2h, restarts: 0
- Last closer: 2026-10-25T03:00:54Z
- Last backfill: 2026-10-25T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 4

## Health 7d (window: 2026-10-18T06:00:02Z → 2026-10-25T06:00:02Z)
- New signals: 114 (~16.3/day)
- Closed: 91 (TP 51, SL 32, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 23
- TP rate 7d: 61.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1693
- Closed: 1670 (TP_clean 857, SL_clean 583, SL→reverse 0, Sideways 230, N/A 0)
- Ongoing (<24h): 23
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
| 1693 | 25.10 | 08:41 | AKEUSDT | SHORT | ongoing | осторожно 78% |
| 1692 | 25.10 | 07:34 | SANDUSDT | SHORT | ongoing | осторожно 80% |
| 1691 | 25.10 | 05:04 | ATOMUSDT | SHORT | ongoing | осторожно 62% |
| 1690 | 25.10 | 04:30 | STEEMUSDT | SHORT | ongoing | осторожно 62% |
| 1689 | 25.10 | 03:38 | CTUSDT | SHORT | ongoing | осторожно 63% |
| 1688 | 25.10 | 00:41 | MARSCOINUSDT | SHORT | ongoing | осторожно 68% |
| 1687 | 25.10 | 00:09 | ARBUSDT | SHORT | ongoing | осторожно 69% |
| 1686 | 24.10 | 23:08 | MAGMAUSDT | SHORT | ongoing | осторожно 65% |
| 1685 | 24.10 | 21:33 | QUSDT | SHORT | ongoing | осторожно 78% |
| 1684 | 24.10 | 21:09 | SEIUSDT | SHORT | ongoing | осторожно 60% |
| 1683 | 24.10 | 21:00 | ERAUSDT | LONG | ongoing | осторожно 64% |
| 1682 | 24.10 | 18:07 | BTWUSDT | LONG | ongoing | осторожно 68% |
| 1681 | 24.10 | 17:33 | ANIMEUSDT | LONG | ongoing | осторожно 60% |
| 1680 | 24.10 | 16:09 | TRUSTUSDT | LONG | ongoing | осторожно 66% |
| 1679 | 24.10 | 16:06 | APRUSDT | LONG | ongoing | осторожно 63% |
| 1678 | 24.10 | 15:00 | KATUSDT | LONG | ongoing | осторожно 74% |
| 1677 | 24.10 | 12:06 | EIGENUSDT | SHORT | ongoing | осторожно 64% |
| 1676 | 24.10 | 11:31 | ERAUSDT | LONG | ongoing | осторожно 71% |
| 1675 | 24.10 | 10:04 | XPLUSDT | SHORT | ongoing | осторожно 60% |
| 1674 | 24.10 | 08:31 | TREEUSDT | LONG | ongoing | осторожно 65% |
| 1673 | 24.10 | 08:10 | BILLUSDT | SHORT | ongoing | осторожно 68% |
| 1672 | 24.10 | 07:06 | DASHUSDT | SHORT | ongoing | осторожно 69% |
| 1671 | 24.10 | 06:38 | BOMEUSDT | LONG | ongoing | осторожно 60% |
| 1670 | 24.10 | 05:06 | NEARUSDT | SHORT | TP_clean | осторожно 63% |
| 1669 | 24.10 | 01:35 | AEROUSDT | SHORT | TP_clean | осторожно 61% |
| 1668 | 24.10 | 01:10 | CSOPSKHYNIX2LUSDT | SHORT | TP_clean | осторожно 61% |
| 1667 | 24.10 | 01:01 | SOONUSDT | SHORT | Sideways | осторожно 62% |
| 1666 | 23.10 | 23:32 | ENAUSDT | LONG | SL_clean | осторожно 63% |
| 1665 | 23.10 | 21:02 | USELESSUSDT | SHORT | TP_clean | осторожно 60% |
| 1664 | 23.10 | 19:35 | ERAUSDT | LONG | SL_clean | осторожно 63% |
| 1663 | 23.10 | 19:03 | CTUSDT | SHORT | TP_clean | осторожно 68% |
| 1662 | 23.10 | 17:33 | NILUSDT | SHORT | TP_clean | осторожно 74% |
| 1661 | 23.10 | 16:37 | DOTUSDT | SHORT | TP_clean | осторожно 62% |
| 1660 | 23.10 | 15:01 | BTWUSDT | LONG | TP_clean | осторожно 61% |
| 1659 | 23.10 | 14:41 | BEUSDT | SHORT | TP_clean | осторожно 66% |
| 1658 | 23.10 | 14:40 | WLFIUSDT | SHORT | Sideways | осторожно 63% |
| 1657 | 23.10 | 14:03 | CBRSUSDT | SHORT | SL_clean | осторожно 67% |
| 1656 | 23.10 | 13:04 | GRASSUSDT | SHORT | SL_clean | осторожно 62% |
| 1655 | 23.10 | 11:32 | BILLUSDT | LONG | SL_clean | осторожно 60% |
| 1654 | 23.10 | 09:08 | CXMTUSDT | SHORT | Sideways | осторожно 64% |
| 1653 | 23.10 | 09:03 | MEWUSDT | LONG | TP_clean | осторожно 73% |
| 1652 | 23.10 | 07:09 | ZECUSDT | SHORT | TP_clean | осторожно 73% |
| 1651 | 23.10 | 06:35 | SKUUUSDT | SHORT | SL_clean | осторожно 63% |
| 1650 | 23.10 | 06:08 | STXUSDT | SHORT | TP_clean | осторожно 67% |
| 1649 | 23.10 | 05:34 | EIGENUSDT | SHORT | TP_clean | осторожно 62% |
| 1648 | 23.10 | 05:02 | UNITREEUSDT | LONG | TP_clean | осторожно 62% |
| 1647 | 23.10 | 03:06 | INJUSDT | SHORT | SL_clean | осторожно 76% |
| 1646 | 23.10 | 02:06 | GRVTUSDT | SHORT | TP_clean | осторожно 64% |
| 1645 | 23.10 | 02:04 | NBISUSDT | SHORT | SL_clean | осторожно 66% |
| 1644 | 23.10 | 01:02 | AVAUSDT | LONG | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-26 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-25 06:30 UTC
- mmscan-snapshot: next run 2026-10-25 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
