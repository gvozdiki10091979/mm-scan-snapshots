# MM Scan Shadow Snapshot
Generated: 2026-11-20T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 594.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-20T17:07:55+0000 (#2084 CARVUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-19T18:00:01Z → 2026-11-20T18:00:01Z)
- New signals: 17 (LONG 8 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 594.6h, restarts: 8
- Last closer: 2026-11-20T03:00:56Z
- Last backfill: 2026-11-20T17:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 8

## Health 7d (window: 2026-11-13T18:00:01Z → 2026-11-20T18:00:01Z)
- New signals: 115 (~16.4/day)
- Closed: 90 (TP 53, SL 24, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 25
- TP rate 7d: 68.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2084
- Closed: 2059 (TP_clean 1053, SL_clean 717, SL→reverse 0, Sideways 289, N/A 0)
- Ongoing (<24h): 25
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
| 2084 | 20.11 | 20:07 | CARVUSDT | LONG | ongoing | осторожно 67% |
| 2083 | 20.11 | 18:35 | KERNELUSDT | LONG | ongoing | осторожно 69% |
| 2082 | 20.11 | 17:35 | ENSOUSDT | LONG | ongoing | осторожно 60% |
| 2081 | 20.11 | 15:36 | SKDDUSDT | LONG | ongoing | осторожно 79% |
| 2080 | 20.11 | 14:32 | CYBERUSDT | LONG | ongoing | осторожно 61% |
| 2079 | 20.11 | 14:03 | APTUSDT | SHORT | ongoing | осторожно 63% |
| 2078 | 20.11 | 13:08 | ARBUSDT | SHORT | ongoing | осторожно 71% |
| 2077 | 20.11 | 12:39 | MUUUSDT | SHORT | ongoing | осторожно 64% |
| 2076 | 20.11 | 11:03 | XMRUSDT | SHORT | ongoing | осторожно 71% |
| 2075 | 20.11 | 10:31 | BARDUSDT | LONG | ongoing | осторожно 61% |
| 2074 | 20.11 | 09:33 | ERAUSDT | LONG | ongoing | осторожно 60% |
| 2073 | 20.11 | 09:06 | FARTCOINUSDT | SHORT | ongoing | осторожно 67% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-20 18:30 UTC
- mmscan-snapshot: next run 2026-11-21 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
