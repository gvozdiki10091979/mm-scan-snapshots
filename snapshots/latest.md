# MM Scan Shadow Snapshot
Generated: 2026-11-02T12:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 156.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-02T07:03:26+0000 (#1812 STXUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-01T12:00:02Z → 2026-11-02T12:00:02Z)
- New signals: 8 (LONG 3 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 156.6h, restarts: 8
- Last closer: 2026-11-02T03:00:31Z
- Last backfill: 2026-11-02T11:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 1

## Health 7d (window: 2026-10-26T12:00:02Z → 2026-11-02T12:00:02Z)
- New signals: 104 (~14.9/day)
- Closed: 95 (TP 50, SL 27, SL→rev 0, Sideways 18, N/A 0)
- Ongoing: 9
- TP rate 7d: 64.9%
- Listener uptime 7d: 93.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1812
- Closed: 1803 (TP_clean 928, SL_clean 621, SL→reverse 0, Sideways 254, N/A 0)
- Ongoing (<24h): 9
- TP rate: 59.9% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 1812 | 02.11 | 10:03 | STXUSDT | LONG | ongoing | осторожно 60% |
| 1811 | 02.11 | 09:04 | LINKUSDT | SHORT | ongoing | осторожно 62% |
| 1810 | 02.11 | 04:04 | POWRUSDT | SHORT | ongoing | осторожно 66% |
| 1809 | 01.11 | 22:05 | UNIUSDT | SHORT | ongoing | осторожно 71% |
| 1808 | 01.11 | 22:03 | BLESSUSDT | LONG | ongoing | осторожно 64% |
| 1807 | 01.11 | 21:10 | AVAXUSDT | SHORT | ongoing | осторожно 85% |
| 1806 | 01.11 | 19:05 | USELESSUSDT | SHORT | ongoing | осторожно 70% |
| 1805 | 01.11 | 17:30 | FLOCKUSDT | LONG | ongoing | осторожно 61% |
| 1804 | 01.11 | 08:33 | REUSDT | SHORT | ongoing | осторожно 76% |
| 1803 | 01.11 | 05:32 | ZECUSDT | SHORT | TP_clean | осторожно 85% |
| 1802 | 01.11 | 03:30 | POWRUSDT | LONG | TP_clean | осторожно 60% |
| 1801 | 01.11 | 02:00 | QUSDT | SHORT | TP_clean | осторожно 65% |
| 1800 | 01.11 | 01:04 | RSRUSDT | LONG | TP_clean | осторожно 61% |
| 1799 | 31.10 | 21:08 | HYPERUSDT | LONG | SL_clean | осторожно 78% |
| 1798 | 31.10 | 21:06 | PARTIUSDT | SHORT | TP_clean | осторожно 62% |
| 1797 | 31.10 | 20:31 | LSKUSDT | LONG | SL_clean | осторожно 66% |
| 1796 | 31.10 | 20:01 | WETUSDT | LONG | TP_clean | осторожно 70% |
| 1795 | 31.10 | 15:40 | BTWUSDT | SHORT | TP_clean | входить 87% |
| 1794 | 31.10 | 15:38 | BXUSDT | LONG | Sideways | осторожно 72% |
| 1793 | 31.10 | 12:12 | CRWVUSDT | SHORT | Sideways | осторожно 62% |
| 1792 | 31.10 | 08:06 | IRYSUSDT | SHORT | SL_clean | осторожно 72% |
| 1791 | 31.10 | 07:05 | RUNEUSDT | LONG | TP_clean | осторожно 61% |
| 1790 | 31.10 | 06:40 | CSOPSKHYNIX2LUSDT | SHORT | Sideways | осторожно 77% |
| 1789 | 31.10 | 06:14 | SKHYNIXUSDT | SHORT | Sideways | осторожно 62% |
| 1788 | 31.10 | 06:00 | AVAUSDT | LONG | SL_clean | осторожно 80% |
| 1787 | 31.10 | 05:42 | BTWUSDT | SHORT | TP_clean | входить 81% |
| 1786 | 31.10 | 04:33 | ERAUSDT | SHORT | TP_clean | осторожно 66% |
| 1785 | 31.10 | 03:11 | COHRUSDT | SHORT | Sideways | осторожно 68% |
| 1784 | 31.10 | 01:41 | MUUUSDT | SHORT | Sideways | осторожно 65% |
| 1783 | 31.10 | 01:12 | SKUUUSDT | SHORT | Sideways | осторожно 63% |
| 1782 | 30.10 | 23:40 | SKDDUSDT | LONG | Sideways | осторожно 61% |
| 1781 | 30.10 | 23:32 | WLDUSDT | SHORT | Sideways | осторожно 61% |
| 1780 | 30.10 | 23:05 | SOPHUSDT | LONG | SL_clean | входить 83% |
| 1779 | 30.10 | 22:35 | 1000PEPEUSDT | LONG | SL_clean | осторожно 62% |
| 1778 | 30.10 | 21:33 | NILUSDT | SHORT | SL_clean | осторожно 63% |
| 1777 | 30.10 | 20:14 | SKHYNIXUSDT | SHORT | Sideways | осторожно 81% |
| 1776 | 30.10 | 19:38 | IOSTUSDT | SHORT | Sideways | осторожно 64% |
| 1775 | 30.10 | 19:09 | EWYUSDT | SHORT | Sideways | осторожно 67% |
| 1774 | 30.10 | 19:04 | SKHYUSDT | SHORT | Sideways | осторожно 72% |
| 1773 | 30.10 | 19:02 | ALPINEUSDT | SHORT | SL_clean | осторожно 64% |
| 1772 | 30.10 | 18:33 | AVAUSDT | SHORT | TP_clean | осторожно 69% |
| 1771 | 30.10 | 17:44 | MUUUSDT | SHORT | TP_clean | входить 90% |
| 1770 | 30.10 | 17:43 | MVLLUSDT | SHORT | TP_clean | осторожно 60% |
| 1769 | 30.10 | 17:42 | COHRUSDT | SHORT | Sideways | осторожно 80% |
| 1768 | 30.10 | 17:41 | KORUUSDT | SHORT | TP_clean | осторожно 71% |
| 1767 | 30.10 | 16:38 | TQQQUSDT | SHORT | TP_clean | осторожно 64% |
| 1766 | 30.10 | 16:36 | BIRBUSDT | SHORT | SL_clean | осторожно 65% |
| 1765 | 30.10 | 16:07 | MRVLUSDT | SHORT | TP_clean | осторожно 67% |
| 1764 | 30.10 | 15:32 | DOODUSDT | SHORT | TP_clean | осторожно 71% |
| 1763 | 30.10 | 14:41 | IOSTUSDT | SHORT | Sideways | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-03 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-02 12:30 UTC
- mmscan-snapshot: next run 2026-11-02 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
