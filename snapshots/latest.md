# MM Scan Shadow Snapshot
Generated: 2026-11-12T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 390.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-12T04:35:40+0000 (#1945 AEROUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-11T06:00:01Z → 2026-11-12T06:00:01Z)
- New signals: 8 (LONG 3 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 390.6h, restarts: 8
- Last closer: 2026-11-12T03:00:33Z
- Last backfill: 2026-11-12T05:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 3

## Health 7d (window: 2026-11-05T06:00:01Z → 2026-11-12T06:00:01Z)
- New signals: 86 (~12.3/day)
- Closed: 75 (TP 26, SL 37, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 11
- TP rate 7d: 41.3%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1945
- Closed: 1934 (TP_clean 984, SL_clean 680, SL→reverse 0, Sideways 270, N/A 0)
- Ongoing (<24h): 11
- TP rate: 59.1% decided (TP/(TP+SL)) · 50.9% pointwise (excl N/A)

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
| 1945 | 12.11 | 07:35 | AEROUSDT | SHORT | ongoing | осторожно 75% |
| 1944 | 12.11 | 07:05 | SOXSUSDT | SHORT | ongoing | осторожно 72% |
| 1943 | 12.11 | 04:01 | CRWVUSDT | LONG | ongoing | осторожно 61% |
| 1942 | 11.11 | 23:35 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 64% |
| 1941 | 11.11 | 22:37 | NEARUSDT | LONG | ongoing | осторожно 64% |
| 1940 | 11.11 | 21:32 | PYTHUSDT | SHORT | ongoing | осторожно 60% |
| 1939 | 11.11 | 12:34 | ETHUSDT | SHORT | ongoing | осторожно 86% |
| 1938 | 11.11 | 12:02 | BCHUSDT | SHORT | ongoing | осторожно 66% |
| 1937 | 11.11 | 07:07 | BCHUSDT | SHORT | ongoing | осторожно 62% |
| 1936 | 11.11 | 06:01 | BIRBUSDT | SHORT | ongoing | осторожно 60% |
| 1935 | 11.11 | 06:00 | UAIUSDT | SHORT | ongoing | осторожно 61% |
| 1934 | 11.11 | 04:00 | BEUSDT | LONG | TP_clean | осторожно 63% |
| 1933 | 11.11 | 02:32 | AVAXUSDT | LONG | TP_clean | осторожно 68% |
| 1932 | 11.11 | 02:10 | ETHUSDT | SHORT | Sideways | осторожно 62% |
| 1931 | 11.11 | 00:40 | HUMAUSDT | SHORT | TP_clean | осторожно 62% |
| 1930 | 10.11 | 23:05 | BABAUSDT | SHORT | Sideways | осторожно 63% |
| 1929 | 10.11 | 21:35 | RSRUSDT | SHORT | TP_clean | осторожно 66% |
| 1928 | 10.11 | 20:35 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 78% |
| 1927 | 10.11 | 19:01 | CYBERUSDT | LONG | SL_clean | осторожно 60% |
| 1926 | 10.11 | 13:00 | INITUSDT | LONG | TP_clean | осторожно 67% |
| 1925 | 10.11 | 06:37 | LDOUSDT | SHORT | Sideways | осторожно 62% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-13 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-12 06:30 UTC
- mmscan-snapshot: next run 2026-11-12 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
