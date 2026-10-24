# MM Scan Shadow Snapshot
Generated: 2026-10-24T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1754.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-24T05:31:06+0000 (#1674 TREEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-23T06:00:01Z → 2026-10-24T06:00:01Z)
- New signals: 22 (LONG 7 / SHORT 15)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 22
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1754.2h, restarts: 0
- Last closer: 2026-10-24T03:00:46Z
- Last backfill: 2026-10-24T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-10-17T06:00:01Z → 2026-10-24T06:00:01Z)
- New signals: 110 (~15.7/day)
- Closed: 85 (TP 52, SL 27, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 25
- TP rate 7d: 65.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1674
- Closed: 1649 (TP_clean 845, SL_clean 577, SL→reverse 0, Sideways 227, N/A 0)
- Ongoing (<24h): 25
- TP rate: 59.4% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 1674 | 24.10 | 08:31 | TREEUSDT | LONG | ongoing | осторожно 65% |
| 1673 | 24.10 | 08:10 | BILLUSDT | SHORT | ongoing | осторожно 68% |
| 1672 | 24.10 | 07:06 | DASHUSDT | SHORT | ongoing | осторожно 69% |
| 1671 | 24.10 | 06:38 | BOMEUSDT | LONG | ongoing | осторожно 60% |
| 1670 | 24.10 | 05:06 | NEARUSDT | SHORT | ongoing | осторожно 63% |
| 1669 | 24.10 | 01:35 | AEROUSDT | SHORT | ongoing | осторожно 61% |
| 1668 | 24.10 | 01:10 | CSOPSKHYNIX2LUSDT | SHORT | ongoing | осторожно 61% |
| 1667 | 24.10 | 01:01 | SOONUSDT | SHORT | ongoing | осторожно 62% |
| 1666 | 23.10 | 23:32 | ENAUSDT | LONG | ongoing | осторожно 63% |
| 1665 | 23.10 | 21:02 | USELESSUSDT | SHORT | ongoing | осторожно 60% |
| 1664 | 23.10 | 19:35 | ERAUSDT | LONG | ongoing | осторожно 63% |
| 1663 | 23.10 | 19:03 | CTUSDT | SHORT | ongoing | осторожно 68% |
| 1662 | 23.10 | 17:33 | NILUSDT | SHORT | ongoing | осторожно 74% |
| 1661 | 23.10 | 16:37 | DOTUSDT | SHORT | ongoing | осторожно 62% |
| 1660 | 23.10 | 15:01 | BTWUSDT | LONG | ongoing | осторожно 61% |
| 1659 | 23.10 | 14:41 | BEUSDT | SHORT | ongoing | осторожно 66% |
| 1658 | 23.10 | 14:40 | WLFIUSDT | SHORT | ongoing | осторожно 63% |
| 1657 | 23.10 | 14:03 | CBRSUSDT | SHORT | ongoing | осторожно 67% |
| 1656 | 23.10 | 13:04 | GRASSUSDT | SHORT | ongoing | осторожно 62% |
| 1655 | 23.10 | 11:32 | BILLUSDT | LONG | ongoing | осторожно 60% |
| 1654 | 23.10 | 09:08 | CXMTUSDT | SHORT | ongoing | осторожно 64% |
| 1653 | 23.10 | 09:03 | MEWUSDT | LONG | ongoing | осторожно 73% |
| 1652 | 23.10 | 07:09 | ZECUSDT | SHORT | ongoing | осторожно 73% |
| 1651 | 23.10 | 06:35 | SKUUUSDT | SHORT | ongoing | осторожно 63% |
| 1650 | 23.10 | 06:08 | STXUSDT | SHORT | ongoing | осторожно 67% |
| 1649 | 23.10 | 05:34 | EIGENUSDT | SHORT | TP_clean | осторожно 62% |
| 1648 | 23.10 | 05:02 | UNITREEUSDT | LONG | TP_clean | осторожно 62% |
| 1647 | 23.10 | 03:06 | INJUSDT | SHORT | SL_clean | осторожно 76% |
| 1646 | 23.10 | 02:06 | GRVTUSDT | SHORT | TP_clean | осторожно 64% |
| 1645 | 23.10 | 02:04 | NBISUSDT | SHORT | SL_clean | осторожно 66% |
| 1644 | 23.10 | 01:02 | AVAUSDT | LONG | TP_clean | осторожно 62% |
| 1643 | 22.10 | 22:37 | ALTUSDT | SHORT | TP_clean | осторожно 63% |
| 1642 | 22.10 | 22:34 | SMCIUSDT | SHORT | Sideways | осторожно 60% |
| 1641 | 22.10 | 22:33 | AKEUSDT | SHORT | SL_clean | осторожно 65% |
| 1640 | 22.10 | 22:01 | EWYUSDT | SHORT | Sideways | осторожно 62% |
| 1639 | 22.10 | 21:03 | CTUSDT | SHORT | TP_clean | осторожно 78% |
| 1638 | 22.10 | 19:10 | BCHUSDT | SHORT | SL_clean | осторожно 64% |
| 1637 | 22.10 | 19:04 | SKHYUSDT | SHORT | TP_clean | осторожно 60% |
| 1636 | 22.10 | 18:31 | ZHIPUUSDT | SHORT | SL_clean | осторожно 74% |
| 1635 | 22.10 | 16:01 | MASKUSDT | LONG | SL_clean | осторожно 61% |
| 1634 | 22.10 | 15:02 | INJUSDT | SHORT | TP_clean | осторожно 74% |
| 1633 | 22.10 | 13:31 | JCTUSDT | SHORT | SL_clean | осторожно 72% |
| 1632 | 22.10 | 11:11 | ETCUSDT | SHORT | Sideways | осторожно 68% |
| 1631 | 22.10 | 05:36 | BTWUSDT | LONG | TP_clean | осторожно 64% |
| 1630 | 22.10 | 05:02 | UNITREEUSDT | LONG | SL_clean | осторожно 67% |
| 1629 | 22.10 | 01:31 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 78% |
| 1628 | 21.10 | 23:06 | MOODENGUSDT | LONG | SL_clean | осторожно 60% |
| 1627 | 21.10 | 21:40 | KORUUSDT | LONG | SL_clean | осторожно 60% |
| 1626 | 21.10 | 21:08 | REZUSDT | LONG | SL_clean | осторожно 62% |
| 1625 | 21.10 | 20:38 | ZHONGJIUSDT | LONG | SL_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-25 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-24 06:30 UTC
- mmscan-snapshot: next run 2026-10-24 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
