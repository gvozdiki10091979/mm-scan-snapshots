# MM Scan Shadow Snapshot
Generated: 2026-11-14T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 432.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-13T19:03:06+0000 (#1971 DASHUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-13T00:00:01Z → 2026-11-14T00:00:01Z)
- New signals: 12 (LONG 6 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 432.6h, restarts: 8
- Last closer: 2026-11-13T03:00:29Z
- Last backfill: 2026-11-13T23:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 16

## Health 7d (window: 2026-11-07T00:00:01Z → 2026-11-14T00:00:01Z)
- New signals: 80 (~11.4/day)
- Closed: 52 (TP 20, SL 22, SL→rev 0, Sideways 10, N/A 0)
- Ongoing: 28
- TP rate 7d: 47.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1971
- Closed: 1943 (TP_clean 986, SL_clean 684, SL→reverse 0, Sideways 273, N/A 0)
- Ongoing (<24h): 28
- TP rate: 59.0% decided (TP/(TP+SL)) · 50.7% pointwise (excl N/A)

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
| 1959 | 13.11 | 00:33 | ZHONGJIUSDT | LONG | ongoing | осторожно 74% |
| 1958 | 12.11 | 23:01 | BARDUSDT | LONG | ongoing | осторожно 61% |
| 1957 | 12.11 | 21:33 | OPUSDT | LONG | ongoing | осторожно 69% |
| 1956 | 12.11 | 20:33 | LITEUSDT | LONG | ongoing | осторожно 66% |
| 1955 | 12.11 | 20:10 | METAUSDT | SHORT | ongoing | осторожно 64% |
| 1954 | 12.11 | 19:31 | TRUMPUSDT | SHORT | ongoing | осторожно 66% |
| 1953 | 12.11 | 17:38 | COHRUSDT | LONG | ongoing | осторожно 73% |
| 1952 | 12.11 | 17:38 | NVDAUSDT | SHORT | ongoing | осторожно 62% |
| 1951 | 12.11 | 17:36 | NVDLUSDT | SHORT | ongoing | осторожно 65% |
| 1950 | 12.11 | 14:32 | SXTUSDT | LONG | ongoing | осторожно 65% |
| 1949 | 12.11 | 13:30 | HUMAUSDT | SHORT | ongoing | осторожно 72% |
| 1948 | 12.11 | 13:01 | XMRUSDT | SHORT | ongoing | осторожно 77% |
| 1947 | 12.11 | 11:41 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 1946 | 12.11 | 11:39 | METAUSDT | SHORT | ongoing | осторожно 73% |
| 1945 | 12.11 | 07:35 | AEROUSDT | SHORT | ongoing | осторожно 75% |
| 1944 | 12.11 | 07:05 | SOXSUSDT | SHORT | ongoing | осторожно 72% |
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
| 1924 | 10.11 | 03:05 | SEIUSDT | SHORT | TP_clean | осторожно 69% |
| 1923 | 09.11 | 21:31 | 1000PEPEUSDT | LONG | TP_clean | осторожно 75% |
| 1922 | 09.11 | 20:31 | IRENUSDT | LONG | SL_clean | осторожно 63% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-14 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-14 00:30 UTC
- mmscan-snapshot: next run 2026-11-14 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
