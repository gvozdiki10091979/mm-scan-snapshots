# MM Scan Shadow Snapshot
Generated: 2026-11-06T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 258.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-06T17:07:20+0000 (#1890 IRENUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-05T18:00:01Z → 2026-11-06T18:00:01Z)
- New signals: 27 (LONG 5 / SHORT 22)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 27
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 258.6h, restarts: 8
- Last closer: 2026-11-06T03:00:52Z
- Last backfill: 2026-11-06T17:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 7

## Health 7d (window: 2026-10-30T18:00:01Z → 2026-11-06T18:00:01Z)
- New signals: 113 (~16.1/day)
- Closed: 79 (TP 39, SL 27, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 34
- TP rate 7d: 59.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1890
- Closed: 1856 (TP_clean 957, SL_clean 641, SL→reverse 0, Sideways 258, N/A 0)
- Ongoing (<24h): 34
- TP rate: 59.9% decided (TP/(TP+SL)) · 51.6% pointwise (excl N/A)

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
| 1890 | 06.11 | 20:07 | IRENUSDT | SHORT | ongoing | осторожно 60% |
| 1889 | 06.11 | 20:05 | LITEUSDT | SHORT | ongoing | осторожно 68% |
| 1888 | 06.11 | 19:03 | CXMTUSDT | SHORT | ongoing | осторожно 72% |
| 1887 | 06.11 | 18:40 | ALABUSDT | SHORT | ongoing | осторожно 62% |
| 1886 | 06.11 | 18:36 | SNXXUSDT | SHORT | ongoing | осторожно 69% |
| 1885 | 06.11 | 18:06 | ARMUSDT | SHORT | ongoing | осторожно 65% |
| 1884 | 06.11 | 16:36 | RUNEUSDT | SHORT | ongoing | осторожно 64% |
| 1883 | 06.11 | 14:00 | UVXYUSDT | LONG | ongoing | осторожно 63% |
| 1882 | 06.11 | 12:35 | XTZUSDT | LONG | ongoing | осторожно 60% |
| 1881 | 06.11 | 10:34 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 1880 | 06.11 | 10:31 | SKDDUSDT | LONG | ongoing | входить 84% |
| 1879 | 06.11 | 10:01 | CYBERUSDT | LONG | ongoing | осторожно 61% |
| 1878 | 06.11 | 05:38 | IRENUSDT | SHORT | ongoing | входить 90% |
| 1877 | 06.11 | 05:10 | SANDUSDT | SHORT | ongoing | осторожно 71% |
| 1876 | 06.11 | 05:08 | IRYSUSDT | SHORT | ongoing | осторожно 61% |
| 1875 | 06.11 | 05:05 | INTCUSDT | SHORT | ongoing | осторожно 61% |
| 1874 | 06.11 | 04:04 | KSTRUSDT | SHORT | ongoing | осторожно 62% |
| 1873 | 06.11 | 03:40 | SKHYUSDT | SHORT | ongoing | осторожно 62% |
| 1872 | 06.11 | 03:35 | MUUUSDT | SHORT | ongoing | входить 85% |
| 1871 | 06.11 | 03:35 | MVLLUSDT | SHORT | ongoing | осторожно 62% |
| 1870 | 06.11 | 02:34 | LSKUSDT | LONG | ongoing | осторожно 75% |
| 1869 | 06.11 | 02:10 | PYTHUSDT | SHORT | ongoing | осторожно 68% |
| 1868 | 06.11 | 00:39 | XMRUSDT | SHORT | ongoing | осторожно 63% |
| 1867 | 05.11 | 22:36 | HUMAUSDT | SHORT | ongoing | осторожно 70% |
| 1866 | 05.11 | 21:39 | WLFIUSDT | SHORT | ongoing | осторожно 62% |
| 1865 | 05.11 | 21:10 | BCHUSDT | SHORT | ongoing | осторожно 74% |
| 1864 | 05.11 | 21:02 | INTCUSDT | SHORT | ongoing | осторожно 68% |
| 1863 | 05.11 | 18:35 | MINIMAXUSDT | LONG | ongoing | осторожно 61% |
| 1862 | 05.11 | 14:03 | AAVEUSDT | LONG | ongoing | осторожно 61% |
| 1861 | 05.11 | 10:09 | SNXXUSDT | SHORT | ongoing | осторожно 63% |
| 1860 | 05.11 | 09:09 | GOOGLUSDT | LONG | ongoing | осторожно 61% |
| 1859 | 05.11 | 07:10 | EWYUSDT | SHORT | ongoing | осторожно 61% |
| 1858 | 05.11 | 07:08 | ZECUSDT | LONG | ongoing | осторожно 69% |
| 1857 | 05.11 | 06:10 | MEGAUSDT | SHORT | ongoing | осторожно 73% |
| 1856 | 05.11 | 04:00 | HUMAUSDT | SHORT | SL_clean | осторожно 71% |
| 1855 | 05.11 | 02:31 | ELSAUSDT | LONG | TP_clean | осторожно 72% |
| 1854 | 05.11 | 01:36 | MARSCOINUSDT | LONG | SL_clean | осторожно 60% |
| 1853 | 05.11 | 01:33 | SOLUSDT | LONG | SL_clean | осторожно 60% |
| 1852 | 05.11 | 00:11 | APTUSDT | LONG | SL_clean | осторожно 61% |
| 1851 | 04.11 | 20:10 | SPCXUSDT | LONG | SL_clean | осторожно 66% |
| 1850 | 04.11 | 17:31 | BMTUSDT | LONG | TP_clean | осторожно 61% |
| 1849 | 04.11 | 17:05 | WLFIUSDT | LONG | SL_clean | осторожно 67% |
| 1848 | 04.11 | 15:07 | SPCXUSDT | SHORT | TP_clean | осторожно 60% |
| 1847 | 04.11 | 15:00 | MUUUSDT | SHORT | TP_clean | осторожно 66% |
| 1846 | 04.11 | 13:32 | BZUSDT | SHORT | TP_clean | осторожно 65% |
| 1845 | 04.11 | 10:05 | TSLAUSDT | SHORT | Sideways | осторожно 69% |
| 1844 | 04.11 | 09:31 | SKDDUSDT | LONG | SL_clean | осторожно 61% |
| 1843 | 04.11 | 09:01 | CXMTUSDT | SHORT | SL_clean | входить 84% |
| 1842 | 04.11 | 07:09 | BZUSDT | SHORT | TP_clean | осторожно 72% |
| 1841 | 04.11 | 06:35 | COINUSDT | SHORT | SL_clean | осторожно 66% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-07 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-06 18:30 UTC
- mmscan-snapshot: next run 2026-11-07 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
