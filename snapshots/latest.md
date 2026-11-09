# MM Scan Shadow Snapshot
Generated: 2026-11-09T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 312.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-08T22:04:14+0000 (#1898 SNDKUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-08T00:00:01Z → 2026-11-09T00:00:01Z)
- New signals: 4 (LONG 2 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 4
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 312.6h, restarts: 8
- Last closer: 2026-11-09T00:00:01Z
- Last backfill: 2026-11-09T00:00:01Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 2

## Health 7d (window: 2026-11-02T00:00:01Z → 2026-11-09T00:00:01Z)
- New signals: 89 (~12.7/day)
- Closed: 83 (TP 35, SL 40, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 6
- TP rate 7d: 46.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1898
- Closed: 1892 (TP_clean 967, SL_clean 662, SL→reverse 0, Sideways 263, N/A 0)
- Ongoing (<24h): 6
- TP rate: 59.4% decided (TP/(TP+SL)) · 51.1% pointwise (excl N/A)

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
| 1898 | 09.11 | 01:04 | SNDKUSDT | LONG | ongoing | осторожно 61% |
| 1897 | 09.11 | 01:03 | SKHYUSDT | LONG | ongoing | осторожно 64% |
| 1896 | 08.11 | 23:03 | CTUSDT | SHORT | ongoing | осторожно 65% |
| 1895 | 08.11 | 07:32 | ZROUSDT | SHORT | ongoing | осторожно 61% |
| 1894 | 07.11 | 09:01 | ZILUSDT | LONG | ongoing | осторожно 63% |
| 1893 | 07.11 | 07:36 | IRENUSDT | LONG | ongoing | осторожно 62% |
| 1892 | 07.11 | 05:30 | CYBERUSDT | LONG | TP_clean | осторожно 80% |
| 1891 | 06.11 | 21:01 | AXTIUSDT | SHORT | SL_clean | осторожно 68% |
| 1890 | 06.11 | 20:07 | IRENUSDT | SHORT | TP_clean | осторожно 60% |
| 1889 | 06.11 | 20:05 | LITEUSDT | SHORT | Sideways | осторожно 68% |
| 1888 | 06.11 | 19:03 | CXMTUSDT | SHORT | Sideways | осторожно 72% |
| 1887 | 06.11 | 18:40 | ALABUSDT | SHORT | SL_clean | осторожно 62% |
| 1886 | 06.11 | 18:36 | SNXXUSDT | SHORT | SL_clean | осторожно 69% |
| 1885 | 06.11 | 18:06 | ARMUSDT | SHORT | Sideways | осторожно 65% |
| 1884 | 06.11 | 16:36 | RUNEUSDT | SHORT | TP_clean | осторожно 64% |
| 1883 | 06.11 | 14:00 | UVXYUSDT | LONG | SL_clean | осторожно 63% |
| 1882 | 06.11 | 12:35 | XTZUSDT | LONG | TP_clean | осторожно 60% |
| 1881 | 06.11 | 10:34 | SEIUSDT | SHORT | SL_clean | осторожно 68% |
| 1880 | 06.11 | 10:31 | SKDDUSDT | LONG | SL_clean | входить 84% |
| 1879 | 06.11 | 10:01 | CYBERUSDT | LONG | TP_clean | осторожно 61% |
| 1878 | 06.11 | 05:38 | IRENUSDT | SHORT | SL_clean | входить 90% |
| 1877 | 06.11 | 05:10 | SANDUSDT | SHORT | Sideways | осторожно 71% |
| 1876 | 06.11 | 05:08 | IRYSUSDT | SHORT | SL_clean | осторожно 61% |
| 1875 | 06.11 | 05:05 | INTCUSDT | SHORT | SL_clean | осторожно 61% |
| 1874 | 06.11 | 04:04 | KSTRUSDT | SHORT | SL_clean | осторожно 62% |
| 1873 | 06.11 | 03:40 | SKHYUSDT | SHORT | SL_clean | осторожно 62% |
| 1872 | 06.11 | 03:35 | MUUUSDT | SHORT | TP_clean | входить 85% |
| 1871 | 06.11 | 03:35 | MVLLUSDT | SHORT | SL_clean | осторожно 62% |
| 1870 | 06.11 | 02:34 | LSKUSDT | LONG | SL_clean | осторожно 75% |
| 1869 | 06.11 | 02:10 | PYTHUSDT | SHORT | SL_clean | осторожно 68% |
| 1868 | 06.11 | 00:39 | XMRUSDT | SHORT | Sideways | осторожно 63% |
| 1867 | 05.11 | 22:36 | HUMAUSDT | SHORT | SL_clean | осторожно 70% |
| 1866 | 05.11 | 21:39 | WLFIUSDT | SHORT | SL_clean | осторожно 62% |
| 1865 | 05.11 | 21:10 | BCHUSDT | SHORT | TP_clean | осторожно 74% |
| 1864 | 05.11 | 21:02 | INTCUSDT | SHORT | TP_clean | осторожно 68% |
| 1863 | 05.11 | 18:35 | MINIMAXUSDT | LONG | SL_clean | осторожно 61% |
| 1862 | 05.11 | 14:03 | AAVEUSDT | LONG | SL_clean | осторожно 61% |
| 1861 | 05.11 | 10:09 | SNXXUSDT | SHORT | TP_clean | осторожно 63% |
| 1860 | 05.11 | 09:09 | GOOGLUSDT | LONG | SL_clean | осторожно 61% |
| 1859 | 05.11 | 07:10 | EWYUSDT | SHORT | TP_clean | осторожно 61% |
| 1858 | 05.11 | 07:08 | ZECUSDT | LONG | SL_clean | осторожно 69% |
| 1857 | 05.11 | 06:10 | MEGAUSDT | SHORT | SL_clean | осторожно 73% |
| 1856 | 05.11 | 04:00 | HUMAUSDT | SHORT | SL_clean | осторожно 71% |
| 1855 | 05.11 | 02:31 | ELSAUSDT | LONG | TP_clean | осторожно 72% |
| 1854 | 05.11 | 01:36 | MARSCOINUSDT | LONG | SL_clean | осторожно 60% |
| 1853 | 05.11 | 01:33 | SOLUSDT | LONG | SL_clean | осторожно 60% |
| 1852 | 05.11 | 00:11 | APTUSDT | LONG | SL_clean | осторожно 61% |
| 1851 | 04.11 | 20:10 | SPCXUSDT | LONG | SL_clean | осторожно 66% |
| 1850 | 04.11 | 17:31 | BMTUSDT | LONG | TP_clean | осторожно 61% |
| 1849 | 04.11 | 17:05 | WLFIUSDT | LONG | SL_clean | осторожно 67% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-09 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-09 00:30 UTC
- mmscan-snapshot: next run 2026-11-09 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
