# MM Scan Shadow Snapshot
Generated: 2026-11-14T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 438.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-14T00:40:21+0000 (#1974 TSMUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-13T06:00:01Z → 2026-11-14T06:00:01Z)
- New signals: 15 (LONG 6 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 438.6h, restarts: 8
- Last closer: 2026-11-14T03:00:49Z
- Last backfill: 2026-11-14T05:30:03Z
- Anomalies: listener рестартов: 8

## Health 7d (window: 2026-11-07T06:00:01Z → 2026-11-14T06:00:01Z)
- New signals: 81 (~11.6/day)
- Closed: 66 (TP 28, SL 27, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 15
- TP rate 7d: 50.9%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1974
- Closed: 1959 (TP_clean 995, SL_clean 689, SL→reverse 0, Sideways 275, N/A 0)
- Ongoing (<24h): 15
- TP rate: 59.1% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1974 | 14.11 | 03:40 | TSMUSDT | SHORT | ongoing | осторожно 63% |
| 1973 | 14.11 | 03:37 | INTCUSDT | SHORT | ongoing | осторожно 74% |
| 1972 | 14.11 | 03:03 | DRAMUSDT | SHORT | ongoing | осторожно 68% |
| 1971 | 13.11 | 22:03 | DASHUSDT | LONG | ongoing | осторожно 66% |
| 1970 | 13.11 | 21:34 | UNIUSDT | SHORT | ongoing | осторожно 68% |
| 1969 | 13.11 | 19:05 | CYBERUSDT | LONG | ongoing | осторожно 70% |
| 1968 | 13.11 | 18:34 | CAPUSDT | LONG | ongoing | осторожно 61% |
| 1967 | 13.11 | 18:04 | ZHIPUUSDT | SHORT | ongoing | осторожно 68% |
| 1966 | 13.11 | 16:03 | MARSCOINUSDT | SHORT | ongoing | осторожно 61% |
| 1965 | 13.11 | 16:01 | BTWUSDT | SHORT | ongoing | осторожно 68% |
| 1964 | 13.11 | 12:32 | AVAXUSDT | LONG | ongoing | осторожно 60% |
| 1963 | 13.11 | 11:01 | ATOMUSDT | SHORT | ongoing | осторожно 62% |
| 1962 | 13.11 | 11:00 | BARDUSDT | LONG | ongoing | осторожно 61% |
| 1961 | 13.11 | 10:32 | SNXXUSDT | LONG | ongoing | осторожно 63% |
| 1960 | 13.11 | 09:34 | TRUMPUSDT | SHORT | ongoing | осторожно 68% |
| 1959 | 13.11 | 00:33 | ZHONGJIUSDT | LONG | TP_clean | осторожно 74% |
| 1958 | 12.11 | 23:01 | BARDUSDT | LONG | TP_clean | осторожно 61% |
| 1957 | 12.11 | 21:33 | OPUSDT | LONG | SL_clean | осторожно 69% |
| 1956 | 12.11 | 20:33 | LITEUSDT | LONG | TP_clean | осторожно 66% |
| 1955 | 12.11 | 20:10 | METAUSDT | SHORT | Sideways | осторожно 64% |
| 1954 | 12.11 | 19:31 | TRUMPUSDT | SHORT | TP_clean | осторожно 66% |
| 1953 | 12.11 | 17:38 | COHRUSDT | LONG | TP_clean | осторожно 73% |
| 1952 | 12.11 | 17:38 | NVDAUSDT | SHORT | SL_clean | осторожно 62% |
| 1951 | 12.11 | 17:36 | NVDLUSDT | SHORT | SL_clean | осторожно 65% |
| 1950 | 12.11 | 14:32 | SXTUSDT | LONG | SL_clean | осторожно 65% |
| 1949 | 12.11 | 13:30 | HUMAUSDT | SHORT | TP_clean | осторожно 72% |
| 1948 | 12.11 | 13:01 | XMRUSDT | SHORT | TP_clean | осторожно 77% |
| 1947 | 12.11 | 11:41 | DELLUSDT | LONG | SL_clean | осторожно 60% |
| 1946 | 12.11 | 11:39 | METAUSDT | SHORT | Sideways | осторожно 73% |
| 1945 | 12.11 | 07:35 | AEROUSDT | SHORT | TP_clean | осторожно 75% |
| 1944 | 12.11 | 07:05 | SOXSUSDT | SHORT | TP_clean | осторожно 72% |
| 1943 | 12.11 | 04:01 | CRWVUSDT | LONG | SL_clean | осторожно 61% |
| 1942 | 11.11 | 23:35 | CSOPSKHYNIX2LUSDT | LONG | SL_clean | осторожно 64% |
| 1941 | 11.11 | 22:37 | NEARUSDT | LONG | SL_clean | осторожно 64% |
| 1940 | 11.11 | 21:32 | PYTHUSDT | SHORT | TP_clean | осторожно 60% |
| 1939 | 11.11 | 12:34 | ETHUSDT | SHORT | Sideways | осторожно 86% |
| 1938 | 11.11 | 12:02 | BCHUSDT | SHORT | Sideways | осторожно 66% |
| 1937 | 11.11 | 07:07 | BCHUSDT | SHORT | Sideways | осторожно 62% |
| 1936 | 11.11 | 06:01 | BIRBUSDT | SHORT | TP_clean | осторожно 60% |
| 1935 | 11.11 | 06:00 | UAIUSDT | SHORT | SL_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-15 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-14 06:30 UTC
- mmscan-snapshot: next run 2026-11-14 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
