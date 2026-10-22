# MM Scan Shadow Snapshot
Generated: 2026-10-22T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1718.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-22T16:10:30+0000 (#1638 BCHUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-21T18:00:02Z → 2026-10-22T18:00:02Z)
- New signals: 13 (LONG 7 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1718.2h, restarts: 0
- Last closer: 2026-10-22T03:00:23Z
- Last backfill: 2026-10-22T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 12

## Health 7d (window: 2026-10-15T18:00:02Z → 2026-10-22T18:00:02Z)
- New signals: 104 (~14.9/day)
- Closed: 79 (TP 49, SL 22, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 25
- TP rate 7d: 69.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1638
- Closed: 1613 (TP_clean 828, SL_clean 561, SL→reverse 0, Sideways 224, N/A 0)
- Ongoing (<24h): 25
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
| 1638 | 22.10 | 19:10 | BCHUSDT | SHORT | ongoing | осторожно 64% |
| 1637 | 22.10 | 19:04 | SKHYUSDT | SHORT | ongoing | осторожно 60% |
| 1636 | 22.10 | 18:31 | ZHIPUUSDT | SHORT | ongoing | осторожно 74% |
| 1635 | 22.10 | 16:01 | MASKUSDT | LONG | ongoing | осторожно 61% |
| 1634 | 22.10 | 15:02 | INJUSDT | SHORT | ongoing | осторожно 74% |
| 1633 | 22.10 | 13:31 | JCTUSDT | SHORT | ongoing | осторожно 72% |
| 1632 | 22.10 | 11:11 | ETCUSDT | SHORT | ongoing | осторожно 68% |
| 1631 | 22.10 | 05:36 | BTWUSDT | LONG | ongoing | осторожно 64% |
| 1630 | 22.10 | 05:02 | UNITREEUSDT | LONG | ongoing | осторожно 67% |
| 1629 | 22.10 | 01:31 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 78% |
| 1628 | 21.10 | 23:06 | MOODENGUSDT | LONG | ongoing | осторожно 60% |
| 1627 | 21.10 | 21:40 | KORUUSDT | LONG | ongoing | осторожно 60% |
| 1626 | 21.10 | 21:08 | REZUSDT | LONG | ongoing | осторожно 62% |
| 1625 | 21.10 | 20:38 | ZHONGJIUSDT | LONG | ongoing | осторожно 61% |
| 1624 | 21.10 | 19:02 | MVLLUSDT | LONG | ongoing | осторожно 63% |
| 1623 | 21.10 | 18:31 | WALUSDT | LONG | ongoing | осторожно 61% |
| 1622 | 21.10 | 12:39 | DOODUSDT | LONG | ongoing | осторожно 76% |
| 1621 | 21.10 | 12:31 | AVAUSDT | SHORT | ongoing | осторожно 78% |
| 1620 | 21.10 | 10:06 | ARCUSDT | LONG | ongoing | осторожно 67% |
| 1619 | 21.10 | 09:32 | PONSUSDT | LONG | ongoing | осторожно 67% |
| 1618 | 21.10 | 09:30 | IOSTUSDT | LONG | ongoing | входить 90% |
| 1617 | 21.10 | 08:34 | MUUUSDT | LONG | ongoing | осторожно 66% |
| 1616 | 21.10 | 07:33 | ARBUSDT | LONG | ongoing | осторожно 65% |
| 1615 | 21.10 | 07:02 | ZHIPUUSDT | SHORT | ongoing | осторожно 62% |
| 1614 | 21.10 | 07:01 | BIRBUSDT | LONG | ongoing | осторожно 63% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-22 18:30 UTC
- mmscan-snapshot: next run 2026-10-23 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
