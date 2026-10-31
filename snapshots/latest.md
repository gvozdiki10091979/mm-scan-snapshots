# MM Scan Shadow Snapshot
Generated: 2026-10-31T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 114.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-10-31T17:31:26+0000 (#1797 LSKUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-10-30T18:00:01Z → 2026-10-31T18:00:01Z)
- New signals: 20 (LONG 8 / SHORT 12)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 20
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 114.6h, restarts: 8
- Last closer: 2026-10-31T03:00:40Z
- Last backfill: 2026-10-31T17:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 27

## Health 7d (window: 2026-10-24T18:00:01Z → 2026-10-31T18:00:01Z)
- New signals: 115 (~16.4/day)
- Closed: 68 (TP 35, SL 24, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 47
- TP rate 7d: 59.3%
- Listener uptime 7d: 68.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1797
- Closed: 1750 (TP_clean 901, SL_clean 610, SL→reverse 0, Sideways 239, N/A 0)
- Ongoing (<24h): 47
- TP rate: 59.6% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 1797 | 31.10 | 20:31 | LSKUSDT | LONG | ongoing | осторожно 66% |
| 1796 | 31.10 | 20:01 | WETUSDT | LONG | ongoing | осторожно 70% |
| 1795 | 31.10 | 15:40 | BTWUSDT | SHORT | ongoing | входить 87% |
| 1794 | 31.10 | 15:38 | BXUSDT | LONG | ongoing | осторожно 72% |
| 1793 | 31.10 | 12:12 | CRWVUSDT | SHORT | ongoing | осторожно 62% |
| 1792 | 31.10 | 08:06 | IRYSUSDT | SHORT | ongoing | осторожно 72% |
| 1791 | 31.10 | 07:05 | RUNEUSDT | LONG | ongoing | осторожно 61% |
| 1790 | 31.10 | 06:40 | CSOPSKHYNIX2LUSDT | SHORT | ongoing | осторожно 77% |
| 1789 | 31.10 | 06:14 | SKHYNIXUSDT | SHORT | ongoing | осторожно 62% |
| 1788 | 31.10 | 06:00 | AVAUSDT | LONG | ongoing | осторожно 80% |
| 1787 | 31.10 | 05:42 | BTWUSDT | SHORT | ongoing | входить 81% |
| 1786 | 31.10 | 04:33 | ERAUSDT | SHORT | ongoing | осторожно 66% |
| 1785 | 31.10 | 03:11 | COHRUSDT | SHORT | ongoing | осторожно 68% |
| 1784 | 31.10 | 01:41 | MUUUSDT | SHORT | ongoing | осторожно 65% |
| 1783 | 31.10 | 01:12 | SKUUUSDT | SHORT | ongoing | осторожно 63% |
| 1782 | 30.10 | 23:40 | SKDDUSDT | LONG | ongoing | осторожно 61% |
| 1781 | 30.10 | 23:32 | WLDUSDT | SHORT | ongoing | осторожно 61% |
| 1780 | 30.10 | 23:05 | SOPHUSDT | LONG | ongoing | входить 83% |
| 1779 | 30.10 | 22:35 | 1000PEPEUSDT | LONG | ongoing | осторожно 62% |
| 1778 | 30.10 | 21:33 | NILUSDT | SHORT | ongoing | осторожно 63% |
| 1777 | 30.10 | 20:14 | SKHYNIXUSDT | SHORT | ongoing | осторожно 81% |
| 1776 | 30.10 | 19:38 | IOSTUSDT | SHORT | ongoing | осторожно 64% |
| 1775 | 30.10 | 19:09 | EWYUSDT | SHORT | ongoing | осторожно 67% |
| 1774 | 30.10 | 19:04 | SKHYUSDT | SHORT | ongoing | осторожно 72% |
| 1773 | 30.10 | 19:02 | ALPINEUSDT | SHORT | ongoing | осторожно 64% |
| 1772 | 30.10 | 18:33 | AVAUSDT | SHORT | ongoing | осторожно 69% |
| 1771 | 30.10 | 17:44 | MUUUSDT | SHORT | ongoing | входить 90% |
| 1770 | 30.10 | 17:43 | MVLLUSDT | SHORT | ongoing | осторожно 60% |
| 1769 | 30.10 | 17:42 | COHRUSDT | SHORT | ongoing | осторожно 80% |
| 1768 | 30.10 | 17:41 | KORUUSDT | SHORT | ongoing | осторожно 71% |
| 1767 | 30.10 | 16:38 | TQQQUSDT | SHORT | ongoing | осторожно 64% |
| 1766 | 30.10 | 16:36 | BIRBUSDT | SHORT | ongoing | осторожно 65% |
| 1765 | 30.10 | 16:07 | MRVLUSDT | SHORT | ongoing | осторожно 67% |
| 1764 | 30.10 | 15:32 | DOODUSDT | SHORT | ongoing | осторожно 71% |
| 1763 | 30.10 | 14:41 | IOSTUSDT | SHORT | ongoing | осторожно 61% |
| 1762 | 30.10 | 13:42 | SKHYNIXUSDT | SHORT | ongoing | осторожно 62% |
| 1761 | 30.10 | 13:37 | HAEDALUSDT | SHORT | ongoing | осторожно 69% |
| 1760 | 30.10 | 13:34 | BNCUSDT | SHORT | ongoing | осторожно 70% |
| 1759 | 30.10 | 13:34 | LSKUSDT | LONG | ongoing | осторожно 66% |
| 1758 | 30.10 | 13:34 | TRXUSDT | LONG | ongoing | осторожно 73% |
| 1757 | 30.10 | 13:31 | ALPINEUSDT | LONG | ongoing | осторожно 61% |
| 1756 | 30.10 | 12:10 | CXMTUSDT | SHORT | ongoing | осторожно 71% |
| 1755 | 30.10 | 12:06 | ZHONGJIUSDT | SHORT | ongoing | осторожно 62% |
| 1754 | 30.10 | 11:09 | DRAMUSDT | SHORT | ongoing | осторожно 63% |
| 1753 | 30.10 | 10:11 | USUSDT | SHORT | ongoing | осторожно 66% |
| 1752 | 30.10 | 09:11 | BNBUSDT | SHORT | ongoing | осторожно 67% |
| 1751 | 30.10 | 08:05 | MAGMAUSDT | SHORT | ongoing | осторожно 83% |
| 1750 | 30.10 | 03:36 | TRXUSDT | LONG | SL_clean | осторожно 73% |
| 1749 | 30.10 | 00:04 | ZHONGJIUSDT | SHORT | TP_clean | осторожно 74% |
| 1748 | 29.10 | 21:04 | LSKUSDT | LONG | SL_clean | осторожно 63% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-01 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-31 18:30 UTC
- mmscan-snapshot: next run 2026-11-01 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
