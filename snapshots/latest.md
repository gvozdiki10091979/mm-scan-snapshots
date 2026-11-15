# MM Scan Shadow Snapshot
Generated: 2026-11-15T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 462.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-15T05:38:59+0000 (#1994 AEROUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-14T06:00:02Z → 2026-11-15T06:00:02Z)
- New signals: 19 (LONG 3 / SHORT 16)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 19
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 462.6h, restarts: 8
- Last closer: 2026-11-15T03:00:33Z
- Last backfill: 2026-11-15T05:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 1

## Health 7d (window: 2026-11-08T06:00:02Z → 2026-11-15T06:00:02Z)
- New signals: 99 (~14.1/day)
- Closed: 79 (TP 35, SL 31, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 20
- TP rate 7d: 53.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1994
- Closed: 1974 (TP_clean 1003, SL_clean 694, SL→reverse 0, Sideways 277, N/A 0)
- Ongoing (<24h): 20
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
| 1994 | 15.11 | 08:38 | AEROUSDT | SHORT | ongoing | осторожно 62% |
| 1993 | 15.11 | 08:38 | ETHUSDT | SHORT | ongoing | осторожно 68% |
| 1992 | 15.11 | 08:07 | LITUSDT | SHORT | ongoing | осторожно 78% |
| 1991 | 15.11 | 07:35 | 1000PEPEUSDT | SHORT | ongoing | осторожно 64% |
| 1990 | 15.11 | 05:39 | HYPEUSDT | SHORT | ongoing | осторожно 62% |
| 1989 | 15.11 | 05:38 | GRASSUSDT | SHORT | ongoing | осторожно 68% |
| 1988 | 15.11 | 05:37 | UNIUSDT | SHORT | ongoing | осторожно 64% |
| 1987 | 15.11 | 04:02 | MSTUUSDT | SHORT | ongoing | осторожно 63% |
| 1986 | 15.11 | 03:33 | XRPUSDT | SHORT | ongoing | осторожно 64% |
| 1985 | 14.11 | 22:11 | KORUUSDT | SHORT | ongoing | осторожно 60% |
| 1984 | 14.11 | 20:08 | CRWVUSDT | SHORT | ongoing | осторожно 65% |
| 1983 | 14.11 | 20:01 | BARDUSDT | LONG | ongoing | осторожно 64% |
| 1982 | 14.11 | 19:39 | XAUUSDT | LONG | ongoing | осторожно 60% |
| 1981 | 14.11 | 19:37 | NBISUSDT | SHORT | ongoing | осторожно 61% |
| 1980 | 14.11 | 15:12 | QQQUSDT | SHORT | ongoing | осторожно 60% |
| 1979 | 14.11 | 13:05 | PENGUUSDT | SHORT | ongoing | осторожно 74% |
| 1978 | 14.11 | 12:09 | INTCUSDT | SHORT | ongoing | осторожно 68% |
| 1977 | 14.11 | 10:05 | ETCUSDT | SHORT | ongoing | осторожно 70% |
| 1976 | 14.11 | 09:32 | BARDUSDT | LONG | ongoing | осторожно 70% |
| 1975 | 14.11 | 08:41 | DRAMUSDT | SHORT | ongoing | осторожно 78% |
| 1974 | 14.11 | 03:40 | TSMUSDT | SHORT | Sideways | осторожно 63% |
| 1973 | 14.11 | 03:37 | INTCUSDT | SHORT | TP_clean | осторожно 74% |
| 1972 | 14.11 | 03:03 | DRAMUSDT | SHORT | TP_clean | осторожно 68% |
| 1971 | 13.11 | 22:03 | DASHUSDT | LONG | SL_clean | осторожно 66% |
| 1970 | 13.11 | 21:34 | UNIUSDT | SHORT | TP_clean | осторожно 68% |
| 1969 | 13.11 | 19:05 | CYBERUSDT | LONG | SL_clean | осторожно 70% |
| 1968 | 13.11 | 18:34 | CAPUSDT | LONG | TP_clean | осторожно 61% |
| 1967 | 13.11 | 18:04 | ZHIPUUSDT | SHORT | Sideways | осторожно 68% |
| 1966 | 13.11 | 16:03 | MARSCOINUSDT | SHORT | TP_clean | осторожно 61% |
| 1965 | 13.11 | 16:01 | BTWUSDT | SHORT | SL_clean | осторожно 68% |
| 1964 | 13.11 | 12:32 | AVAXUSDT | LONG | TP_clean | осторожно 60% |
| 1963 | 13.11 | 11:01 | ATOMUSDT | SHORT | TP_clean | осторожно 62% |
| 1962 | 13.11 | 11:00 | BARDUSDT | LONG | TP_clean | осторожно 61% |
| 1961 | 13.11 | 10:32 | SNXXUSDT | LONG | SL_clean | осторожно 63% |
| 1960 | 13.11 | 09:34 | TRUMPUSDT | SHORT | SL_clean | осторожно 68% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-16 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-15 06:30 UTC
- mmscan-snapshot: next run 2026-11-15 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
