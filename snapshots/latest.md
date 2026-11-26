# MM Scan Shadow Snapshot
Generated: 2026-11-26T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3053496
- Uptime: 71.0h (active since Mon 2026-11-23 12:58:26 UTC)
- Last signal: 2026-11-26T10:04:38+0000 (#2187 BIGTIMEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12

## Health 24h (window: 2026-11-25T12:00:01Z → 2026-11-26T12:00:01Z)
- New signals: 12 (LONG 3 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 71.0h, restarts: 12
- Last closer: 2026-11-26T03:00:50Z
- Last backfill: 2026-11-26T11:30:02Z
- Anomalies: listener рестартов: 12; ongoing >24h без закрытия: 12

## Health 7d (window: 2026-11-19T12:00:01Z → 2026-11-26T12:00:01Z)
- New signals: 122 (~17.4/day)
- Closed: 98 (TP 53, SL 40, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 24
- TP rate 7d: 57.0%
- Listener uptime 7d: 42.3% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2187
- Closed: 2163 (TP_clean 1109, SL_clean 760, SL→reverse 0, Sideways 294, N/A 0)
- Ongoing (<24h): 24
- TP rate: 59.3% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 2187 | 26.11 | 13:04 | BIGTIMEUSDT | LONG | ongoing | осторожно 75% |
| 2186 | 26.11 | 11:31 | MOODENGUSDT | LONG | ongoing | осторожно 85% |
| 2185 | 26.11 | 07:01 | MEUSDT | LONG | ongoing | осторожно 73% |
| 2184 | 26.11 | 06:40 | ELSAUSDT | SHORT | ongoing | входить 90% |
| 2183 | 26.11 | 03:39 | MVLLUSDT | SHORT | ongoing | осторожно 63% |
| 2182 | 26.11 | 01:35 | DOSUSDT | SHORT | ongoing | осторожно 63% |
| 2181 | 25.11 | 22:39 | MSTUUSDT | SHORT | ongoing | осторожно 60% |
| 2180 | 25.11 | 20:12 | CSOPSKHYNIX2LUSDT | SHORT | ongoing | осторожно 69% |
| 2179 | 25.11 | 16:38 | ELSAUSDT | SHORT | ongoing | осторожно 71% |
| 2178 | 25.11 | 15:13 | PLTRUSDT | SHORT | ongoing | осторожно 62% |
| 2177 | 25.11 | 15:09 | QQQUSDT | SHORT | ongoing | осторожно 82% |
| 2176 | 25.11 | 15:07 | GOOGLUSDT | SHORT | ongoing | осторожно 73% |
| 2175 | 25.11 | 14:11 | XAUTUSDT | SHORT | ongoing | осторожно 64% |
| 2174 | 25.11 | 12:40 | MUUUSDT | SHORT | ongoing | осторожно 67% |
| 2173 | 25.11 | 12:39 | KORUUSDT | SHORT | ongoing | осторожно 78% |
| 2172 | 25.11 | 12:01 | WAXPUSDT | LONG | ongoing | осторожно 61% |
| 2171 | 25.11 | 10:33 | AIGENSYNUSDT | LONG | ongoing | осторожно 61% |
| 2170 | 25.11 | 10:05 | GLWUSDT | SHORT | ongoing | осторожно 63% |
| 2169 | 25.11 | 10:01 | SLXUSDT | LONG | ongoing | входить 80% |
| 2168 | 25.11 | 07:07 | SPCXUSDT | SHORT | ongoing | осторожно 69% |
| 2167 | 25.11 | 07:07 | BMNRUSDT | SHORT | ongoing | осторожно 68% |
| 2166 | 25.11 | 07:03 | AMATUSDT | SHORT | ongoing | осторожно 74% |
| 2165 | 25.11 | 06:39 | PIEVERSEUSDT | SHORT | ongoing | осторожно 65% |
| 2164 | 25.11 | 06:07 | EWYUSDT | SHORT | ongoing | осторожно 61% |
| 2163 | 25.11 | 05:07 | QQQUSDT | SHORT | TP_clean | осторожно 67% |
| 2162 | 25.11 | 03:31 | CSOPSKHYNIX2LUSDT | SHORT | TP_clean | осторожно 60% |
| 2161 | 25.11 | 03:01 | SOXSUSDT | SHORT | SL_clean | осторожно 60% |
| 2160 | 25.11 | 02:00 | AVAAIUSDT | LONG | SL_clean | осторожно 66% |
| 2159 | 24.11 | 22:08 | AVGOUSDT | SHORT | TP_clean | осторожно 64% |
| 2158 | 24.11 | 20:32 | CSOPSAMSUNG2LUSDT | SHORT | TP_clean | осторожно 62% |
| 2157 | 24.11 | 19:34 | SKHYNIXUSDT | LONG | SL_clean | осторожно 60% |
| 2156 | 24.11 | 19:34 | CXMTUSDT | LONG | TP_clean | осторожно 63% |
| 2155 | 24.11 | 18:32 | ZHIPUUSDT | LONG | TP_clean | осторожно 62% |
| 2154 | 24.11 | 18:32 | SAMSUNGUSDT | SHORT | TP_clean | осторожно 60% |
| 2153 | 24.11 | 17:39 | FLNCUSDT | LONG | SL_clean | осторожно 67% |
| 2152 | 24.11 | 17:07 | RPLUSDT | LONG | TP_clean | осторожно 79% |
| 2151 | 24.11 | 14:03 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 65% |
| 2150 | 24.11 | 12:38 | MINIMAXUSDT | LONG | SL_clean | входить 88% |
| 2149 | 24.11 | 09:31 | SAHARAUSDT | LONG | TP_clean | осторожно 62% |
| 2148 | 24.11 | 08:37 | RKLBUSDT | LONG | SL_clean | осторожно 61% |
| 2147 | 24.11 | 08:34 | ACEUSDT | SHORT | TP_clean | осторожно 65% |
| 2146 | 24.11 | 04:36 | DASHUSDT | LONG | SL_clean | осторожно 61% |
| 2145 | 24.11 | 03:34 | XLMUSDT | LONG | SL_clean | осторожно 65% |
| 2144 | 24.11 | 02:00 | SKDDUSDT | SHORT | SL_clean | осторожно 83% |
| 2143 | 23.11 | 23:32 | CRDOUSDT | LONG | TP_clean | осторожно 64% |
| 2142 | 23.11 | 21:32 | LITUSDT | LONG | SL_clean | осторожно 64% |
| 2141 | 23.11 | 20:32 | 1000PEPEUSDT | LONG | SL_clean | осторожно 67% |
| 2140 | 23.11 | 17:38 | IDOLUSDT | SHORT | SL_clean | осторожно 62% |
| 2139 | 23.11 | 11:04 | BEATUSDT | LONG | TP_clean | осторожно 62% |
| 2138 | 23.11 | 05:01 | AKEUSDT | SHORT | TP_clean | входить 90% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-27 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-26 12:30 UTC
- mmscan-snapshot: next run 2026-11-26 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
