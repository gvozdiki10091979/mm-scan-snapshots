# MM Scan Shadow Snapshot
Generated: 2026-11-20T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 582.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-20T04:39:41+0000 (#2072 AEROUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-19T06:00:02Z → 2026-11-20T06:00:02Z)
- New signals: 11 (LONG 5 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 582.6h, restarts: 8
- Last closer: 2026-11-20T03:00:56Z
- Last backfill: 2026-11-20T05:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 2

## Health 7d (window: 2026-11-13T06:00:02Z → 2026-11-20T06:00:02Z)
- New signals: 113 (~16.1/day)
- Closed: 100 (TP 58, SL 28, SL→rev 0, Sideways 14, N/A 0)
- Ongoing: 13
- TP rate 7d: 67.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2072
- Closed: 2059 (TP_clean 1053, SL_clean 717, SL→reverse 0, Sideways 289, N/A 0)
- Ongoing (<24h): 13
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.1% pointwise (excl N/A)

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
| 2072 | 20.11 | 07:39 | AEROUSDT | SHORT | ongoing | осторожно 63% |
| 2071 | 20.11 | 05:34 | RAREUSDT | LONG | ongoing | осторожно 74% |
| 2070 | 19.11 | 23:37 | AEROUSDT | SHORT | ongoing | осторожно 62% |
| 2069 | 19.11 | 23:11 | QCOMUSDT | SHORT | ongoing | осторожно 62% |
| 2068 | 19.11 | 21:08 | CAPUSDT | SHORT | ongoing | осторожно 68% |
| 2067 | 19.11 | 20:09 | GRASSUSDT | SHORT | ongoing | осторожно 73% |
| 2066 | 19.11 | 20:09 | AMZNUSDT | SHORT | ongoing | осторожно 70% |
| 2065 | 19.11 | 13:05 | ZHIPUUSDT | LONG | ongoing | осторожно 76% |
| 2064 | 19.11 | 12:31 | 1000LUNCUSDT | LONG | ongoing | осторожно 64% |
| 2063 | 19.11 | 10:35 | ZKCUSDT | LONG | ongoing | осторожно 61% |
| 2062 | 19.11 | 09:02 | SOXLUSDT | LONG | ongoing | осторожно 62% |
| 2061 | 19.11 | 07:40 | QCOMUSDT | SHORT | ongoing | осторожно 76% |
| 2060 | 19.11 | 06:10 | ONDOUSDT | SHORT | ongoing | осторожно 62% |
| 2059 | 19.11 | 05:04 | RKLBUSDT | SHORT | SL_clean | осторожно 60% |
| 2058 | 19.11 | 04:34 | AAVEUSDT | SHORT | TP_clean | осторожно 62% |
| 2057 | 19.11 | 02:08 | XAGUSDT | SHORT | TP_clean | осторожно 63% |
| 2056 | 19.11 | 01:08 | ARBUSDT | SHORT | TP_clean | осторожно 65% |
| 2055 | 19.11 | 00:04 | XPLUSDT | SHORT | SL_clean | осторожно 68% |
| 2054 | 18.11 | 23:41 | ONDOUSDT | SHORT | Sideways | осторожно 60% |
| 2053 | 18.11 | 23:34 | HYPEUSDT | SHORT | SL_clean | осторожно 82% |
| 2052 | 18.11 | 23:34 | BLESSUSDT | SHORT | TP_clean | осторожно 60% |
| 2051 | 18.11 | 23:12 | BMNRUSDT | SHORT | SL_clean | осторожно 62% |
| 2050 | 18.11 | 23:11 | SKHYUSDT | SHORT | SL_clean | осторожно 73% |
| 2049 | 18.11 | 23:11 | BREVUSDT | LONG | SL_clean | осторожно 66% |
| 2048 | 18.11 | 23:11 | FILUSDT | SHORT | TP_clean | осторожно 68% |
| 2047 | 18.11 | 23:11 | IDOLUSDT | LONG | TP_clean | осторожно 64% |
| 2046 | 18.11 | 21:02 | ZKCUSDT | LONG | TP_clean | осторожно 67% |
| 2045 | 18.11 | 19:07 | MOCAUSDT | LONG | TP_clean | осторожно 61% |
| 2044 | 18.11 | 17:39 | KAVAUSDT | LONG | TP_clean | осторожно 67% |
| 2043 | 18.11 | 12:31 | ZKPUSDT | LONG | SL_clean | осторожно 66% |
| 2042 | 18.11 | 12:05 | TRUSTUSDT | LONG | TP_clean | осторожно 60% |
| 2041 | 18.11 | 11:32 | SPACEUSDT | SHORT | TP_clean | осторожно 63% |
| 2040 | 18.11 | 05:02 | VVVUSDT | SHORT | TP_clean | осторожно 62% |
| 2039 | 18.11 | 03:13 | TLMUSDT | LONG | TP_clean | осторожно 66% |
| 2038 | 18.11 | 02:01 | SOXSUSDT | LONG | SL_clean | осторожно 67% |
| 2037 | 18.11 | 01:32 | HUMAUSDT | LONG | SL_clean | осторожно 72% |
| 2036 | 17.11 | 21:39 | MUUSDT | SHORT | SL_clean | осторожно 78% |
| 2035 | 17.11 | 20:02 | GLWUSDT | SHORT | SL_clean | осторожно 70% |
| 2034 | 17.11 | 19:30 | BLURUSDT | LONG | SL_clean | осторожно 61% |
| 2033 | 17.11 | 12:31 | 1000LUNCUSDT | LONG | TP_clean | осторожно 67% |
| 2032 | 17.11 | 11:07 | TSLAUSDT | SHORT | Sideways | осторожно 79% |
| 2031 | 17.11 | 10:38 | BTWUSDT | SHORT | TP_clean | осторожно 64% |
| 2030 | 17.11 | 09:33 | NIGHTUSDT | SHORT | TP_clean | осторожно 65% |
| 2029 | 17.11 | 09:11 | AXTIUSDT | SHORT | TP_clean | осторожно 62% |
| 2028 | 17.11 | 09:08 | LITEUSDT | SHORT | TP_clean | осторожно 62% |
| 2027 | 17.11 | 09:07 | MUUSDT | SHORT | TP_clean | осторожно 74% |
| 2026 | 17.11 | 07:06 | ARMUSDT | SHORT | TP_clean | осторожно 76% |
| 2025 | 17.11 | 07:06 | TQQQUSDT | SHORT | TP_clean | осторожно 79% |
| 2024 | 17.11 | 07:04 | SNXXUSDT | SHORT | TP_clean | осторожно 62% |
| 2023 | 17.11 | 06:34 | BMNRUSDT | LONG | SL_clean | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-20 06:30 UTC
- mmscan-snapshot: next run 2026-11-20 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
