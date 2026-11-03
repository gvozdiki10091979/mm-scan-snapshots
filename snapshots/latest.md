# MM Scan Shadow Snapshot
Generated: 2026-11-03T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 174.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-03T05:33:08+0000 (#1827 BMTUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-02T06:00:02Z → 2026-11-03T06:00:02Z)
- New signals: 17 (LONG 4 / SHORT 13)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 174.6h, restarts: 8
- Last closer: 2026-11-03T03:00:19Z
- Last backfill: 2026-11-03T05:30:02Z
- Anomalies: listener рестартов: 8

## Health 7d (window: 2026-10-27T06:00:02Z → 2026-11-03T06:00:02Z)
- New signals: 110 (~15.7/day)
- Closed: 93 (TP 53, SL 22, SL→rev 0, Sideways 18, N/A 0)
- Ongoing: 17
- TP rate 7d: 70.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1827
- Closed: 1810 (TP_clean 933, SL_clean 622, SL→reverse 0, Sideways 255, N/A 0)
- Ongoing (<24h): 17
- TP rate: 60.0% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 1827 | 03.11 | 08:33 | BMTUSDT | SHORT | ongoing | осторожно 67% |
| 1826 | 03.11 | 08:31 | MARSCOINUSDT | SHORT | ongoing | осторожно 66% |
| 1825 | 03.11 | 08:10 | RENDERUSDT | SHORT | ongoing | осторожно 61% |
| 1824 | 03.11 | 08:10 | ARBUSDT | SHORT | ongoing | осторожно 68% |
| 1823 | 03.11 | 08:09 | ONDOUSDT | SHORT | ongoing | осторожно 60% |
| 1822 | 03.11 | 06:37 | SKHYUSDT | SHORT | ongoing | осторожно 65% |
| 1821 | 03.11 | 06:36 | SAMSUNGUSDT | SHORT | ongoing | осторожно 64% |
| 1820 | 03.11 | 06:04 | SKHYNIXUSDT | SHORT | ongoing | осторожно 69% |
| 1819 | 03.11 | 01:33 | ARBUSDT | SHORT | ongoing | осторожно 72% |
| 1818 | 03.11 | 01:01 | AKEUSDT | SHORT | ongoing | входить 90% |
| 1817 | 03.11 | 00:33 | SKHYNIXUSDT | LONG | ongoing | осторожно 65% |
| 1816 | 03.11 | 00:00 | HAEDALUSDT | LONG | ongoing | осторожно 77% |
| 1815 | 02.11 | 18:32 | HAEDALUSDT | LONG | ongoing | осторожно 66% |
| 1814 | 02.11 | 15:09 | ETHFIUSDT | SHORT | ongoing | осторожно 60% |
| 1813 | 02.11 | 15:06 | TAOUSDT | SHORT | ongoing | осторожно 66% |
| 1812 | 02.11 | 10:03 | STXUSDT | LONG | ongoing | осторожно 60% |
| 1811 | 02.11 | 09:04 | LINKUSDT | SHORT | ongoing | осторожно 62% |
| 1810 | 02.11 | 04:04 | POWRUSDT | SHORT | TP_clean | осторожно 66% |
| 1809 | 01.11 | 22:05 | UNIUSDT | SHORT | Sideways | осторожно 71% |
| 1808 | 01.11 | 22:03 | BLESSUSDT | LONG | TP_clean | осторожно 64% |
| 1807 | 01.11 | 21:10 | AVAXUSDT | SHORT | TP_clean | осторожно 85% |
| 1806 | 01.11 | 19:05 | USELESSUSDT | SHORT | TP_clean | осторожно 70% |
| 1805 | 01.11 | 17:30 | FLOCKUSDT | LONG | SL_clean | осторожно 61% |
| 1804 | 01.11 | 08:33 | REUSDT | SHORT | TP_clean | осторожно 76% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-04 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-03 06:30 UTC
- mmscan-snapshot: next run 2026-11-03 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
