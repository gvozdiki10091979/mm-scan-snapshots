# MM Scan Shadow Snapshot
Generated: 2026-11-21T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 618.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-21T16:41:48+0000 (#2116 CSOPSKHYNIX2LUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-20T18:00:01Z → 2026-11-21T18:00:01Z)
- New signals: 32 (LONG 4 / SHORT 28)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 32
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 618.6h, restarts: 8
- Last closer: 2026-11-21T03:00:37Z
- Last backfill: 2026-11-21T17:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 13

## Health 7d (window: 2026-11-14T18:00:01Z → 2026-11-21T18:00:01Z)
- New signals: 132 (~18.9/day)
- Closed: 87 (TP 52, SL 26, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 45
- TP rate 7d: 66.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2116
- Closed: 2071 (TP_clean 1061, SL_clean 721, SL→reverse 0, Sideways 289, N/A 0)
- Ongoing (<24h): 45
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 2116 | 21.11 | 19:41 | CSOPSKHYNIX2LUSDT | SHORT | ongoing | осторожно 63% |
| 2115 | 21.11 | 19:37 | RIVERUSDT | SHORT | ongoing | осторожно 76% |
| 2114 | 21.11 | 19:03 | ERAUSDT | LONG | ongoing | осторожно 61% |
| 2113 | 21.11 | 17:30 | MAGMAUSDT | SHORT | ongoing | входить 86% |
| 2112 | 21.11 | 17:03 | HUSDT | SHORT | ongoing | осторожно 77% |
| 2111 | 21.11 | 16:07 | BMTUSDT | LONG | ongoing | осторожно 61% |
| 2110 | 21.11 | 15:05 | YBUSDT | SHORT | ongoing | осторожно 60% |
| 2109 | 21.11 | 14:04 | SNXXUSDT | SHORT | ongoing | осторожно 60% |
| 2108 | 21.11 | 12:39 | 1000BONKUSDT | SHORT | ongoing | осторожно 70% |
| 2107 | 21.11 | 12:38 | BOMEUSDT | SHORT | ongoing | осторожно 68% |
| 2106 | 21.11 | 12:36 | AVAXUSDT | SHORT | ongoing | осторожно 62% |
| 2105 | 21.11 | 12:36 | RENDERUSDT | SHORT | ongoing | осторожно 62% |
| 2104 | 21.11 | 12:33 | FARTCOINUSDT | SHORT | ongoing | осторожно 68% |
| 2103 | 21.11 | 12:08 | BTCUSDT | SHORT | ongoing | осторожно 64% |
| 2102 | 21.11 | 12:06 | SKDDUSDT | LONG | ongoing | осторожно 74% |
| 2101 | 21.11 | 07:34 | MVLLUSDT | SHORT | ongoing | осторожно 78% |
| 2100 | 21.11 | 07:33 | CSOPSKHYNIX2LUSDT | SHORT | ongoing | осторожно 72% |
| 2099 | 21.11 | 07:08 | RAMUSDT | SHORT | ongoing | осторожно 60% |
| 2098 | 21.11 | 07:04 | SKUUUSDT | SHORT | ongoing | осторожно 61% |
| 2097 | 21.11 | 05:11 | COINUSDT | SHORT | ongoing | осторожно 62% |
| 2096 | 21.11 | 04:36 | AVAXUSDT | SHORT | ongoing | осторожно 64% |
| 2095 | 21.11 | 04:06 | XRPUSDT | SHORT | ongoing | осторожно 60% |
| 2094 | 21.11 | 03:33 | LABUSDT | SHORT | ongoing | осторожно 60% |
| 2093 | 21.11 | 02:39 | QNTUSDT | SHORT | ongoing | осторожно 81% |
| 2092 | 21.11 | 02:08 | 1000PEPEUSDT | SHORT | ongoing | осторожно 63% |
| 2091 | 21.11 | 01:13 | FILUSDT | SHORT | ongoing | осторожно 62% |
| 2090 | 21.11 | 01:12 | TAOUSDT | SHORT | ongoing | осторожно 62% |
| 2089 | 21.11 | 00:40 | ETCUSDT | SHORT | ongoing | осторожно 63% |
| 2088 | 21.11 | 00:33 | PENGUUSDT | SHORT | ongoing | осторожно 62% |
| 2087 | 20.11 | 22:32 | AIGENSYNUSDT | LONG | ongoing | осторожно 90% |
| 2086 | 20.11 | 21:33 | ENAUSDT | SHORT | ongoing | осторожно 73% |
| 2085 | 20.11 | 21:10 | SOLUSDT | SHORT | ongoing | осторожно 62% |
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
| 2071 | 20.11 | 05:34 | RAREUSDT | LONG | SL_clean | осторожно 74% |
| 2070 | 19.11 | 23:37 | AEROUSDT | SHORT | TP_clean | осторожно 62% |
| 2069 | 19.11 | 23:11 | QCOMUSDT | SHORT | TP_clean | осторожно 62% |
| 2068 | 19.11 | 21:08 | CAPUSDT | SHORT | TP_clean | осторожно 68% |
| 2067 | 19.11 | 20:09 | GRASSUSDT | SHORT | TP_clean | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-22 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-21 18:30 UTC
- mmscan-snapshot: next run 2026-11-22 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
