# MM Scan Shadow Snapshot
Generated: 2026-11-22T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 630.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-22T05:40:19+0000 (#2125 SUIUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-21T06:00:01Z → 2026-11-22T06:00:01Z)
- New signals: 24 (LONG 3 / SHORT 21)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 24
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 630.6h, restarts: 8
- Last closer: 2026-11-22T03:00:49Z
- Last backfill: 2026-11-22T05:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-11-15T06:00:01Z → 2026-11-22T06:00:01Z)
- New signals: 131 (~18.7/day)
- Closed: 103 (TP 68, SL 27, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 28
- TP rate 7d: 71.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2125
- Closed: 2097 (TP_clean 1083, SL_clean 725, SL→reverse 0, Sideways 289, N/A 0)
- Ongoing (<24h): 28
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
| 2125 | 22.11 | 08:40 | SUIUSDT | SHORT | ongoing | осторожно 62% |
| 2124 | 22.11 | 08:33 | WLDUSDT | SHORT | ongoing | осторожно 81% |
| 2123 | 22.11 | 08:08 | HYPEUSDT | SHORT | ongoing | осторожно 67% |
| 2122 | 22.11 | 08:06 | HBARUSDT | SHORT | ongoing | осторожно 61% |
| 2121 | 22.11 | 05:33 | CRVUSDT | SHORT | ongoing | осторожно 65% |
| 2120 | 22.11 | 01:06 | AAVEUSDT | SHORT | ongoing | осторожно 62% |
| 2119 | 22.11 | 00:08 | HUMAUSDT | SHORT | ongoing | осторожно 61% |
| 2118 | 22.11 | 00:03 | INITUSDT | SHORT | ongoing | осторожно 61% |
| 2117 | 21.11 | 22:08 | 1000LUNCUSDT | SHORT | ongoing | осторожно 68% |
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
| 2097 | 21.11 | 05:11 | COINUSDT | SHORT | TP_clean | осторожно 62% |
| 2096 | 21.11 | 04:36 | AVAXUSDT | SHORT | TP_clean | осторожно 64% |
| 2095 | 21.11 | 04:06 | XRPUSDT | SHORT | TP_clean | осторожно 60% |
| 2094 | 21.11 | 03:33 | LABUSDT | SHORT | TP_clean | осторожно 60% |
| 2093 | 21.11 | 02:39 | QNTUSDT | SHORT | TP_clean | осторожно 81% |
| 2092 | 21.11 | 02:08 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 63% |
| 2091 | 21.11 | 01:13 | FILUSDT | SHORT | TP_clean | осторожно 62% |
| 2090 | 21.11 | 01:12 | TAOUSDT | SHORT | TP_clean | осторожно 62% |
| 2089 | 21.11 | 00:40 | ETCUSDT | SHORT | TP_clean | осторожно 63% |
| 2088 | 21.11 | 00:33 | PENGUUSDT | SHORT | TP_clean | осторожно 62% |
| 2087 | 20.11 | 22:32 | AIGENSYNUSDT | LONG | TP_clean | осторожно 90% |
| 2086 | 20.11 | 21:33 | ENAUSDT | SHORT | TP_clean | осторожно 73% |
| 2085 | 20.11 | 21:10 | SOLUSDT | SHORT | TP_clean | осторожно 62% |
| 2084 | 20.11 | 20:07 | CARVUSDT | LONG | TP_clean | осторожно 67% |
| 2083 | 20.11 | 18:35 | KERNELUSDT | LONG | SL_clean | осторожно 69% |
| 2082 | 20.11 | 17:35 | ENSOUSDT | LONG | SL_clean | осторожно 60% |
| 2081 | 20.11 | 15:36 | SKDDUSDT | LONG | TP_clean | осторожно 79% |
| 2080 | 20.11 | 14:32 | CYBERUSDT | LONG | SL_clean | осторожно 61% |
| 2079 | 20.11 | 14:03 | APTUSDT | SHORT | TP_clean | осторожно 63% |
| 2078 | 20.11 | 13:08 | ARBUSDT | SHORT | TP_clean | осторожно 71% |
| 2077 | 20.11 | 12:39 | MUUUSDT | SHORT | TP_clean | осторожно 64% |
| 2076 | 20.11 | 11:03 | XMRUSDT | SHORT | TP_clean | осторожно 71% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-22 06:30 UTC
- mmscan-snapshot: next run 2026-11-22 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
