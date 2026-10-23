# MM Scan Shadow Snapshot
Generated: 2026-10-23T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1730.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-23T04:09:31+0000 (#1652 ZECUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-22T06:00:01Z → 2026-10-23T06:00:01Z)
- New signals: 21 (LONG 3 / SHORT 18)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 21
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1730.2h, restarts: 0
- Last closer: 2026-10-23T03:00:33Z
- Last backfill: 2026-10-23T05:30:02Z
- Anomalies: none

## Health 7d (window: 2026-10-16T06:00:01Z → 2026-10-23T06:00:01Z)
- New signals: 110 (~15.7/day)
- Closed: 89 (TP 55, SL 27, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 21
- TP rate 7d: 67.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1652
- Closed: 1631 (TP_clean 837, SL_clean 570, SL→reverse 0, Sideways 224, N/A 0)
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
| 1652 | 23.10 | 07:09 | ZECUSDT | SHORT | ongoing | осторожно 73% |
| 1651 | 23.10 | 06:35 | SKUUUSDT | SHORT | ongoing | осторожно 63% |
| 1650 | 23.10 | 06:08 | STXUSDT | SHORT | ongoing | осторожно 67% |
| 1649 | 23.10 | 05:34 | EIGENUSDT | SHORT | ongoing | осторожно 62% |
| 1648 | 23.10 | 05:02 | UNITREEUSDT | LONG | ongoing | осторожно 62% |
| 1647 | 23.10 | 03:06 | INJUSDT | SHORT | ongoing | осторожно 76% |
| 1646 | 23.10 | 02:06 | GRVTUSDT | SHORT | ongoing | осторожно 64% |
| 1645 | 23.10 | 02:04 | NBISUSDT | SHORT | ongoing | осторожно 66% |
| 1644 | 23.10 | 01:02 | AVAUSDT | LONG | ongoing | осторожно 62% |
| 1643 | 22.10 | 22:37 | ALTUSDT | SHORT | ongoing | осторожно 63% |
| 1642 | 22.10 | 22:34 | SMCIUSDT | SHORT | ongoing | осторожно 60% |
| 1641 | 22.10 | 22:33 | AKEUSDT | SHORT | ongoing | осторожно 65% |
| 1640 | 22.10 | 22:01 | EWYUSDT | SHORT | ongoing | осторожно 62% |
| 1639 | 22.10 | 21:03 | CTUSDT | SHORT | ongoing | осторожно 78% |
| 1638 | 22.10 | 19:10 | BCHUSDT | SHORT | ongoing | осторожно 64% |
| 1637 | 22.10 | 19:04 | SKHYUSDT | SHORT | ongoing | осторожно 60% |
| 1636 | 22.10 | 18:31 | ZHIPUUSDT | SHORT | ongoing | осторожно 74% |
| 1635 | 22.10 | 16:01 | MASKUSDT | LONG | ongoing | осторожно 61% |
| 1634 | 22.10 | 15:02 | INJUSDT | SHORT | ongoing | осторожно 74% |
| 1633 | 22.10 | 13:31 | JCTUSDT | SHORT | ongoing | осторожно 72% |
| 1632 | 22.10 | 11:11 | ETCUSDT | SHORT | ongoing | осторожно 68% |
| 1631 | 22.10 | 05:36 | BTWUSDT | LONG | TP_clean | осторожно 64% |
| 1630 | 22.10 | 05:02 | UNITREEUSDT | LONG | SL_clean | осторожно 67% |
| 1629 | 22.10 | 01:31 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 78% |
| 1628 | 21.10 | 23:06 | MOODENGUSDT | LONG | SL_clean | осторожно 60% |
| 1627 | 21.10 | 21:40 | KORUUSDT | LONG | SL_clean | осторожно 60% |
| 1626 | 21.10 | 21:08 | REZUSDT | LONG | SL_clean | осторожно 62% |
| 1625 | 21.10 | 20:38 | ZHONGJIUSDT | LONG | SL_clean | осторожно 61% |
| 1624 | 21.10 | 19:02 | MVLLUSDT | LONG | SL_clean | осторожно 63% |
| 1623 | 21.10 | 18:31 | WALUSDT | LONG | SL_clean | осторожно 61% |
| 1622 | 21.10 | 12:39 | DOODUSDT | LONG | TP_clean | осторожно 76% |
| 1621 | 21.10 | 12:31 | AVAUSDT | SHORT | SL_clean | осторожно 78% |
| 1620 | 21.10 | 10:06 | ARCUSDT | LONG | TP_clean | осторожно 67% |
| 1619 | 21.10 | 09:32 | PONSUSDT | LONG | TP_clean | осторожно 67% |
| 1618 | 21.10 | 09:30 | IOSTUSDT | LONG | TP_clean | входить 90% |
| 1617 | 21.10 | 08:34 | MUUUSDT | LONG | SL_clean | осторожно 66% |
| 1616 | 21.10 | 07:33 | ARBUSDT | LONG | TP_clean | осторожно 65% |
| 1615 | 21.10 | 07:02 | ZHIPUUSDT | SHORT | TP_clean | осторожно 62% |
| 1614 | 21.10 | 07:01 | BIRBUSDT | LONG | TP_clean | осторожно 63% |
| 1613 | 21.10 | 05:00 | MEWUSDT | LONG | TP_clean | осторожно 61% |
| 1612 | 20.10 | 20:02 | SIRENUSDT | SHORT | SL_clean | осторожно 67% |
| 1611 | 20.10 | 19:06 | BEUSDT | LONG | TP_clean | осторожно 70% |
| 1610 | 20.10 | 17:32 | BMTUSDT | LONG | TP_clean | осторожно 61% |
| 1609 | 20.10 | 17:31 | SOPHUSDT | SHORT | TP_clean | осторожно 62% |
| 1608 | 20.10 | 15:07 | ENSOUSDT | SHORT | SL_clean | осторожно 74% |
| 1607 | 20.10 | 14:10 | MUBARAKUSDT | SHORT | TP_clean | осторожно 89% |
| 1606 | 20.10 | 13:37 | ARIAUSDT | SHORT | SL_clean | осторожно 66% |
| 1605 | 20.10 | 10:34 | ARMUSDT | SHORT | Sideways | осторожно 67% |
| 1604 | 20.10 | 07:30 | PHAUSDT | LONG | TP_clean | осторожно 77% |
| 1603 | 20.10 | 06:40 | DELLUSDT | SHORT | TP_clean | осторожно 74% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-24 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-23 06:30 UTC
- mmscan-snapshot: next run 2026-10-23 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
