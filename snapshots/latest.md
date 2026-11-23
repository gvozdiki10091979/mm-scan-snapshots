# MM Scan Shadow Snapshot
Generated: 2026-11-23T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 654.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-23T02:01:02+0000 (#2138 AKEUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-22T06:00:01Z → 2026-11-23T06:00:01Z)
- New signals: 13 (LONG 8 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 13
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 654.6h, restarts: 8
- Last closer: 2026-11-23T03:01:09Z
- Last backfill: 2026-11-23T05:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-11-16T06:00:01Z → 2026-11-23T06:00:01Z)
- New signals: 128 (~18.3/day)
- Closed: 111 (TP 68, SL 38, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 17
- TP rate 7d: 64.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2138
- Closed: 2121 (TP_clean 1090, SL_clean 740, SL→reverse 0, Sideways 291, N/A 0)
- Ongoing (<24h): 17
- TP rate: 59.6% decided (TP/(TP+SL)) · 51.4% pointwise (excl N/A)

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
| 2138 | 23.11 | 05:01 | AKEUSDT | SHORT | ongoing | входить 90% |
| 2137 | 23.11 | 01:03 | IRYSUSDT | SHORT | ongoing | осторожно 61% |
| 2136 | 23.11 | 00:01 | BREVUSDT | SHORT | ongoing | осторожно 66% |
| 2135 | 22.11 | 21:30 | HUMAUSDT | LONG | ongoing | осторожно 67% |
| 2134 | 22.11 | 20:35 | YBUSDT | LONG | ongoing | осторожно 62% |
| 2133 | 22.11 | 18:02 | KERNELUSDT | SHORT | ongoing | осторожно 72% |
| 2132 | 22.11 | 16:31 | COOKIEUSDT | LONG | ongoing | осторожно 79% |
| 2131 | 22.11 | 14:34 | AAVEUSDT | LONG | ongoing | осторожно 62% |
| 2130 | 22.11 | 12:35 | SQQQUSDT | LONG | ongoing | осторожно 60% |
| 2129 | 22.11 | 11:08 | ZECUSDT | LONG | ongoing | осторожно 69% |
| 2128 | 22.11 | 11:00 | AIGENSYNUSDT | LONG | ongoing | осторожно 61% |
| 2127 | 22.11 | 09:08 | ANTUSDT | LONG | ongoing | осторожно 61% |
| 2126 | 22.11 | 09:02 | JCTUSDT | SHORT | ongoing | осторожно 64% |
| 2125 | 22.11 | 08:40 | SUIUSDT | SHORT | ongoing | осторожно 62% |
| 2124 | 22.11 | 08:33 | WLDUSDT | SHORT | ongoing | осторожно 81% |
| 2123 | 22.11 | 08:08 | HYPEUSDT | SHORT | ongoing | осторожно 67% |
| 2122 | 22.11 | 08:06 | HBARUSDT | SHORT | ongoing | осторожно 61% |
| 2121 | 22.11 | 05:33 | CRVUSDT | SHORT | SL_clean | осторожно 65% |
| 2120 | 22.11 | 01:06 | AAVEUSDT | SHORT | Sideways | осторожно 62% |
| 2119 | 22.11 | 00:08 | HUMAUSDT | SHORT | TP_clean | осторожно 61% |
| 2118 | 22.11 | 00:03 | INITUSDT | SHORT | SL_clean | осторожно 61% |
| 2117 | 21.11 | 22:08 | 1000LUNCUSDT | SHORT | TP_clean | осторожно 68% |
| 2116 | 21.11 | 19:41 | CSOPSKHYNIX2LUSDT | SHORT | SL_clean | осторожно 63% |
| 2115 | 21.11 | 19:37 | RIVERUSDT | SHORT | TP_clean | осторожно 76% |
| 2114 | 21.11 | 19:03 | ERAUSDT | LONG | TP_clean | осторожно 61% |
| 2113 | 21.11 | 17:30 | MAGMAUSDT | SHORT | TP_clean | входить 86% |
| 2112 | 21.11 | 17:03 | HUSDT | SHORT | TP_clean | осторожно 77% |
| 2111 | 21.11 | 16:07 | BMTUSDT | LONG | TP_clean | осторожно 61% |
| 2110 | 21.11 | 15:05 | YBUSDT | SHORT | SL_clean | осторожно 60% |
| 2109 | 21.11 | 14:04 | SNXXUSDT | SHORT | SL_clean | осторожно 60% |
| 2108 | 21.11 | 12:39 | 1000BONKUSDT | SHORT | Sideways | осторожно 70% |
| 2107 | 21.11 | 12:38 | BOMEUSDT | SHORT | SL_clean | осторожно 68% |
| 2106 | 21.11 | 12:36 | AVAXUSDT | SHORT | SL_clean | осторожно 62% |
| 2105 | 21.11 | 12:36 | RENDERUSDT | SHORT | SL_clean | осторожно 62% |
| 2104 | 21.11 | 12:33 | FARTCOINUSDT | SHORT | SL_clean | осторожно 68% |
| 2103 | 21.11 | 12:08 | BTCUSDT | SHORT | SL_clean | осторожно 64% |
| 2102 | 21.11 | 12:06 | SKDDUSDT | LONG | SL_clean | осторожно 74% |
| 2101 | 21.11 | 07:34 | MVLLUSDT | SHORT | SL_clean | осторожно 78% |
| 2100 | 21.11 | 07:33 | CSOPSKHYNIX2LUSDT | SHORT | SL_clean | осторожно 72% |
| 2099 | 21.11 | 07:08 | RAMUSDT | SHORT | SL_clean | осторожно 60% |
| 2098 | 21.11 | 07:04 | SKUUUSDT | SHORT | SL_clean | осторожно 61% |
| 2097 | 21.11 | 05:11 | COINUSDT | SHORT | TP_clean | осторожно 62% |
| 2096 | 21.11 | 04:36 | AVAXUSDT | SHORT | TP_clean | осторожно 64% |
| 2095 | 21.11 | 04:06 | XRPUSDT | SHORT | TP_clean | осторожно 60% |
| 2094 | 21.11 | 03:33 | LABUSDT | SHORT | TP_clean | осторожно 60% |
| 2093 | 21.11 | 02:39 | QNTUSDT | SHORT | TP_clean | осторожно 81% |
| 2092 | 21.11 | 02:08 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 63% |
| 2091 | 21.11 | 01:13 | FILUSDT | SHORT | TP_clean | осторожно 62% |
| 2090 | 21.11 | 01:12 | TAOUSDT | SHORT | TP_clean | осторожно 62% |
| 2089 | 21.11 | 00:40 | ETCUSDT | SHORT | TP_clean | осторожно 63% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-24 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-23 06:30 UTC
- mmscan-snapshot: next run 2026-11-23 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
