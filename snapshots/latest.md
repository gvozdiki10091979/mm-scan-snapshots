# MM Scan Shadow Snapshot
Generated: 2026-10-29T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 54.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-10-29T05:33:00+0000 (#1737 OPUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-10-28T06:00:01Z → 2026-10-29T06:00:01Z)
- New signals: 9 (LONG 3 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 54.6h, restarts: 8
- Last closer: 2026-10-29T03:00:35Z
- Last backfill: 2026-10-29T05:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 1

## Health 7d (window: 2026-10-22T06:00:01Z → 2026-10-29T06:00:01Z)
- New signals: 106 (~15.1/day)
- Closed: 96 (TP 49, SL 32, SL→rev 0, Sideways 15, N/A 0)
- Ongoing: 10
- TP rate 7d: 60.5%
- Listener uptime 7d: 32.5% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1737
- Closed: 1727 (TP_clean 886, SL_clean 602, SL→reverse 0, Sideways 239, N/A 0)
- Ongoing (<24h): 10
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
| 1737 | 29.10 | 08:33 | OPUSDT | SHORT | ongoing | осторожно 68% |
| 1736 | 29.10 | 07:02 | SKDDUSDT | SHORT | ongoing | осторожно 69% |
| 1735 | 29.10 | 04:32 | COHRUSDT | LONG | ongoing | осторожно 62% |
| 1734 | 29.10 | 03:39 | DASHUSDT | SHORT | ongoing | осторожно 62% |
| 1733 | 29.10 | 00:30 | AKEUSDT | SHORT | ongoing | осторожно 72% |
| 1732 | 28.10 | 18:36 | TAOUSDT | SHORT | ongoing | осторожно 66% |
| 1731 | 28.10 | 14:01 | ENAUSDT | SHORT | ongoing | осторожно 80% |
| 1730 | 28.10 | 12:35 | ZHONGJIUSDT | LONG | ongoing | осторожно 63% |
| 1729 | 28.10 | 10:30 | XANUSDT | LONG | ongoing | входить 86% |
| 1728 | 28.10 | 06:01 | AVAUSDT | SHORT | ongoing | осторожно 76% |
| 1727 | 28.10 | 05:02 | CTUSDT | LONG | SL_clean | осторожно 61% |
| 1726 | 27.10 | 22:09 | 1000PEPEUSDT | LONG | TP_clean | осторожно 71% |
| 1725 | 27.10 | 21:42 | HAEDALUSDT | LONG | TP_clean | осторожно 63% |
| 1724 | 27.10 | 21:39 | IOSTUSDT | LONG | TP_clean | осторожно 60% |
| 1723 | 27.10 | 19:02 | GLWUSDT | SHORT | Sideways | осторожно 65% |
| 1722 | 27.10 | 19:01 | SQQQUSDT | SHORT | Sideways | осторожно 64% |
| 1721 | 27.10 | 18:35 | AVAUSDT | SHORT | TP_clean | осторожно 64% |
| 1720 | 27.10 | 17:34 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 65% |
| 1719 | 27.10 | 13:03 | BEATUSDT | LONG | TP_clean | осторожно 62% |
| 1718 | 27.10 | 11:08 | ARIAUSDT | LONG | SL_clean | входить 85% |
| 1717 | 27.10 | 07:05 | KATUSDT | LONG | SL_clean | осторожно 70% |
| 1716 | 27.10 | 06:02 | IRYSUSDT | SHORT | TP_clean | осторожно 61% |
| 1715 | 27.10 | 05:07 | HYPEUSDT | SHORT | SL_clean | осторожно 73% |
| 1714 | 27.10 | 05:01 | UNITREEUSDT | LONG | SL_clean | осторожно 61% |
| 1713 | 27.10 | 03:30 | BIRBUSDT | SHORT | SL_clean | входить 90% |
| 1712 | 27.10 | 01:09 | ERAUSDT | LONG | SL_clean | осторожно 68% |
| 1711 | 26.10 | 22:01 | FARTCOINUSDT | SHORT | Sideways | осторожно 63% |
| 1710 | 26.10 | 16:36 | QUSDT | SHORT | TP_clean | осторожно 63% |
| 1709 | 26.10 | 15:32 | GRASSUSDT | LONG | SL_clean | осторожно 60% |
| 1708 | 26.10 | 14:01 | IOSTUSDT | LONG | TP_clean | осторожно 65% |
| 1707 | 26.10 | 12:06 | ZHONGJIUSDT | LONG | TP_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-30 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-29 06:30 UTC
- mmscan-snapshot: next run 2026-10-29 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
