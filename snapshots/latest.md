# MM Scan Shadow Snapshot
Generated: 2026-11-24T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3053496
- Uptime: 29.0h (active since Mon 2026-11-23 12:58:26 UTC)
- Last signal: 2026-11-24T17:32:32+0000 (#2158 CSOPSAMSUNG2LUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12

## Health 24h (window: 2026-11-23T18:00:01Z → 2026-11-24T18:00:01Z)
- New signals: 17 (LONG 13 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 29.0h, restarts: 12
- Last closer: 2026-11-24T03:01:03Z
- Last backfill: 2026-11-24T17:30:02Z
- Anomalies: listener рестартов: 12; ongoing >24h без закрытия: 3

## Health 7d (window: 2026-11-17T18:00:01Z → 2026-11-24T18:00:01Z)
- New signals: 123 (~17.6/day)
- Closed: 103 (TP 56, SL 41, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 20
- TP rate 7d: 57.7%
- Listener uptime 7d: 17.3% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2158
- Closed: 2138 (TP_clean 1096, SL_clean 748, SL→reverse 0, Sideways 294, N/A 0)
- Ongoing (<24h): 20
- TP rate: 59.4% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 2158 | 24.11 | 20:32 | CSOPSAMSUNG2LUSDT | SHORT | ongoing | осторожно 62% |
| 2157 | 24.11 | 19:34 | SKHYNIXUSDT | LONG | ongoing | осторожно 60% |
| 2156 | 24.11 | 19:34 | CXMTUSDT | LONG | ongoing | осторожно 63% |
| 2155 | 24.11 | 18:32 | ZHIPUUSDT | LONG | ongoing | осторожно 62% |
| 2154 | 24.11 | 18:32 | SAMSUNGUSDT | SHORT | ongoing | осторожно 60% |
| 2153 | 24.11 | 17:39 | FLNCUSDT | LONG | ongoing | осторожно 67% |
| 2152 | 24.11 | 17:07 | RPLUSDT | LONG | ongoing | осторожно 79% |
| 2151 | 24.11 | 14:03 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 65% |
| 2150 | 24.11 | 12:38 | MINIMAXUSDT | LONG | ongoing | входить 88% |
| 2149 | 24.11 | 09:31 | SAHARAUSDT | LONG | ongoing | осторожно 62% |
| 2148 | 24.11 | 08:37 | RKLBUSDT | LONG | ongoing | осторожно 61% |
| 2147 | 24.11 | 08:34 | ACEUSDT | SHORT | ongoing | осторожно 65% |
| 2146 | 24.11 | 04:36 | DASHUSDT | LONG | ongoing | осторожно 61% |
| 2145 | 24.11 | 03:34 | XLMUSDT | LONG | ongoing | осторожно 65% |
| 2144 | 24.11 | 02:00 | SKDDUSDT | SHORT | ongoing | осторожно 83% |
| 2143 | 23.11 | 23:32 | CRDOUSDT | LONG | ongoing | осторожно 64% |
| 2142 | 23.11 | 21:32 | LITUSDT | LONG | ongoing | осторожно 64% |
| 2141 | 23.11 | 20:32 | 1000PEPEUSDT | LONG | ongoing | осторожно 67% |
| 2140 | 23.11 | 17:38 | IDOLUSDT | SHORT | ongoing | осторожно 62% |
| 2139 | 23.11 | 11:04 | BEATUSDT | LONG | ongoing | осторожно 62% |
| 2138 | 23.11 | 05:01 | AKEUSDT | SHORT | TP_clean | входить 90% |
| 2137 | 23.11 | 01:03 | IRYSUSDT | SHORT | TP_clean | осторожно 61% |
| 2136 | 23.11 | 00:01 | BREVUSDT | SHORT | SL_clean | осторожно 66% |
| 2135 | 22.11 | 21:30 | HUMAUSDT | LONG | SL_clean | осторожно 67% |
| 2134 | 22.11 | 20:35 | YBUSDT | LONG | TP_clean | осторожно 62% |
| 2133 | 22.11 | 18:02 | KERNELUSDT | SHORT | SL_clean | осторожно 72% |
| 2132 | 22.11 | 16:31 | COOKIEUSDT | LONG | Sideways | осторожно 79% |
| 2131 | 22.11 | 14:34 | AAVEUSDT | LONG | Sideways | осторожно 62% |
| 2130 | 22.11 | 12:35 | SQQQUSDT | LONG | SL_clean | осторожно 60% |
| 2129 | 22.11 | 11:08 | ZECUSDT | LONG | TP_clean | осторожно 69% |
| 2128 | 22.11 | 11:00 | AIGENSYNUSDT | LONG | SL_clean | осторожно 61% |
| 2127 | 22.11 | 09:08 | ANTUSDT | LONG | TP_clean | осторожно 61% |
| 2126 | 22.11 | 09:02 | JCTUSDT | SHORT | TP_clean | осторожно 64% |
| 2125 | 22.11 | 08:40 | SUIUSDT | SHORT | SL_clean | осторожно 62% |
| 2124 | 22.11 | 08:33 | WLDUSDT | SHORT | SL_clean | осторожно 81% |
| 2123 | 22.11 | 08:08 | HYPEUSDT | SHORT | SL_clean | осторожно 67% |
| 2122 | 22.11 | 08:06 | HBARUSDT | SHORT | Sideways | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-25 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-24 18:30 UTC
- mmscan-snapshot: next run 2026-11-25 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
