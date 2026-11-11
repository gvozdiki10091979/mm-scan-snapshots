# MM Scan Shadow Snapshot
Generated: 2026-11-11T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 372.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-11T09:34:37+0000 (#1939 ETHUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-10T12:00:01Z → 2026-11-11T12:00:01Z)
- New signals: 13 (LONG 4 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 372.6h, restarts: 8
- Last closer: 2026-11-11T03:00:59Z
- Last backfill: 2026-11-11T11:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 2

## Health 7d (window: 2026-11-04T12:00:01Z → 2026-11-11T12:00:01Z)
- New signals: 93 (~13.3/day)
- Closed: 78 (TP 25, SL 44, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 15
- TP rate 7d: 36.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1939
- Closed: 1924 (TP_clean 978, SL_clean 679, SL→reverse 0, Sideways 267, N/A 0)
- Ongoing (<24h): 15
- TP rate: 59.0% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1939 | 11.11 | 12:34 | ETHUSDT | SHORT | ongoing | осторожно 86% |
| 1938 | 11.11 | 12:02 | BCHUSDT | SHORT | ongoing | осторожно 66% |
| 1937 | 11.11 | 07:07 | BCHUSDT | SHORT | ongoing | осторожно 62% |
| 1936 | 11.11 | 06:01 | BIRBUSDT | SHORT | ongoing | осторожно 60% |
| 1935 | 11.11 | 06:00 | UAIUSDT | SHORT | ongoing | осторожно 61% |
| 1934 | 11.11 | 04:00 | BEUSDT | LONG | ongoing | осторожно 63% |
| 1933 | 11.11 | 02:32 | AVAXUSDT | LONG | ongoing | осторожно 68% |
| 1932 | 11.11 | 02:10 | ETHUSDT | SHORT | ongoing | осторожно 62% |
| 1931 | 11.11 | 00:40 | HUMAUSDT | SHORT | ongoing | осторожно 62% |
| 1930 | 10.11 | 23:05 | BABAUSDT | SHORT | ongoing | осторожно 63% |
| 1929 | 10.11 | 21:35 | RSRUSDT | SHORT | ongoing | осторожно 66% |
| 1928 | 10.11 | 20:35 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 78% |
| 1927 | 10.11 | 19:01 | CYBERUSDT | LONG | ongoing | осторожно 60% |
| 1926 | 10.11 | 13:00 | INITUSDT | LONG | ongoing | осторожно 67% |
| 1925 | 10.11 | 06:37 | LDOUSDT | SHORT | ongoing | осторожно 62% |
| 1924 | 10.11 | 03:05 | SEIUSDT | SHORT | TP_clean | осторожно 69% |
| 1923 | 09.11 | 21:31 | 1000PEPEUSDT | LONG | TP_clean | осторожно 75% |
| 1922 | 09.11 | 20:31 | IRENUSDT | LONG | SL_clean | осторожно 63% |
| 1921 | 09.11 | 19:34 | CLUSDT | SHORT | TP_clean | осторожно 60% |
| 1920 | 09.11 | 15:36 | LYNUSDT | SHORT | TP_clean | осторожно 62% |
| 1919 | 09.11 | 13:40 | STRKUSDT | SHORT | SL_clean | осторожно 63% |
| 1918 | 09.11 | 13:34 | TAOUSDT | SHORT | SL_clean | осторожно 80% |
| 1917 | 09.11 | 13:31 | SOXLUSDT | SHORT | SL_clean | осторожно 66% |
| 1916 | 09.11 | 13:10 | VIRTUALUSDT | SHORT | SL_clean | осторожно 62% |
| 1915 | 09.11 | 13:08 | SEIUSDT | SHORT | SL_clean | осторожно 74% |
| 1914 | 09.11 | 13:07 | INITUSDT | LONG | TP_clean | осторожно 61% |
| 1913 | 09.11 | 13:06 | SUIUSDT | SHORT | SL_clean | осторожно 71% |
| 1912 | 09.11 | 13:04 | AVAXUSDT | SHORT | SL_clean | осторожно 78% |
| 1911 | 09.11 | 10:35 | PONSUSDT | SHORT | SL_clean | осторожно 62% |
| 1910 | 09.11 | 08:05 | OPUSDT | SHORT | TP_clean | осторожно 67% |
| 1909 | 09.11 | 07:32 | BTWUSDT | LONG | SL_clean | осторожно 64% |
| 1908 | 09.11 | 07:04 | GRAMUSDT | SHORT | SL_clean | осторожно 62% |
| 1907 | 09.11 | 06:32 | ARIAUSDT | LONG | SL_clean | осторожно 62% |
| 1906 | 09.11 | 06:32 | TAOUSDT | SHORT | SL_clean | осторожно 72% |
| 1905 | 09.11 | 05:08 | DOTUSDT | SHORT | Sideways | осторожно 62% |
| 1904 | 09.11 | 04:10 | AVAXUSDT | SHORT | SL_clean | осторожно 64% |
| 1903 | 09.11 | 03:40 | LTCUSDT | SHORT | Sideways | осторожно 62% |
| 1902 | 09.11 | 03:40 | LINKUSDT | SHORT | Sideways | осторожно 64% |
| 1901 | 09.11 | 03:37 | SUIUSDT | SHORT | SL_clean | осторожно 64% |
| 1900 | 09.11 | 03:13 | UNIUSDT | SHORT | SL_clean | осторожно 65% |
| 1899 | 09.11 | 03:11 | XRPUSDT | SHORT | TP_clean | осторожно 62% |
| 1898 | 09.11 | 01:04 | SNDKUSDT | LONG | TP_clean | осторожно 61% |
| 1897 | 09.11 | 01:03 | SKHYUSDT | LONG | TP_clean | осторожно 64% |
| 1896 | 08.11 | 23:03 | CTUSDT | SHORT | TP_clean | осторожно 65% |
| 1895 | 08.11 | 07:32 | ZROUSDT | SHORT | TP_clean | осторожно 61% |
| 1894 | 07.11 | 09:01 | ZILUSDT | LONG | SL_clean | осторожно 63% |
| 1893 | 07.11 | 07:36 | IRENUSDT | LONG | Sideways | осторожно 62% |
| 1892 | 07.11 | 05:30 | CYBERUSDT | LONG | TP_clean | осторожно 80% |
| 1891 | 06.11 | 21:01 | AXTIUSDT | SHORT | SL_clean | осторожно 68% |
| 1890 | 06.11 | 20:07 | IRENUSDT | SHORT | TP_clean | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-12 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-11 12:30 UTC
- mmscan-snapshot: next run 2026-11-11 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
