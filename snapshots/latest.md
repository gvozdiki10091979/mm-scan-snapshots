# MM Scan Shadow Snapshot
Generated: 2026-11-27T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 3053496
- Uptime: 101.0h (active since Mon 2026-11-23 12:58:26 UTC)
- Last signal: 2026-11-27T17:40:27+0000 (#2202 LDOUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12

## Health 24h (window: 2026-11-26T18:00:02Z → 2026-11-27T18:00:02Z)
- New signals: 12 (LONG 2 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 101.0h, restarts: 12
- Last closer: 2026-11-27T03:00:47Z
- Last backfill: 2026-11-27T17:30:02Z
- Anomalies: listener рестартов: 12; ongoing >24h без закрытия: 7

## Health 7d (window: 2026-11-20T18:00:02Z → 2026-11-27T18:00:02Z)
- New signals: 118 (~16.9/day)
- Closed: 99 (TP 53, SL 38, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 19
- TP rate 7d: 58.2%
- Listener uptime 7d: 60.1% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2202
- Closed: 2183 (TP_clean 1123, SL_clean 763, SL→reverse 0, Sideways 297, N/A 0)
- Ongoing (<24h): 19
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.4% pointwise (excl N/A)

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
| 2202 | 27.11 | 20:40 | LDOUSDT | SHORT | ongoing | осторожно 64% |
| 2201 | 27.11 | 19:33 | MMTUSDT | SHORT | ongoing | осторожно 66% |
| 2200 | 27.11 | 12:31 | SKDDUSDT | SHORT | ongoing | осторожно 68% |
| 2199 | 27.11 | 09:34 | BLESSUSDT | SHORT | ongoing | осторожно 62% |
| 2198 | 27.11 | 05:01 | SSVUSDT | LONG | ongoing | осторожно 75% |
| 2197 | 27.11 | 05:00 | OPGUSDT | SHORT | ongoing | входить 90% |
| 2196 | 27.11 | 02:00 | SKHYNIXUSDT | SHORT | ongoing | осторожно 60% |
| 2195 | 26.11 | 23:36 | SKHYUSDT | SHORT | ongoing | осторожно 62% |
| 2194 | 26.11 | 23:07 | SKUUUSDT | LONG | ongoing | осторожно 60% |
| 2193 | 26.11 | 22:33 | SKDDUSDT | SHORT | ongoing | осторожно 74% |
| 2192 | 26.11 | 22:01 | MMTUSDT | SHORT | ongoing | осторожно 72% |
| 2191 | 26.11 | 21:34 | UNIUSDT | SHORT | ongoing | осторожно 68% |
| 2190 | 26.11 | 20:02 | SKYUSDT | LONG | ongoing | осторожно 64% |
| 2189 | 26.11 | 18:33 | 2ZUSDT | LONG | ongoing | осторожно 62% |
| 2188 | 26.11 | 17:33 | SLXUSDT | LONG | ongoing | осторожно 63% |
| 2187 | 26.11 | 13:04 | BIGTIMEUSDT | LONG | ongoing | осторожно 75% |
| 2186 | 26.11 | 11:31 | MOODENGUSDT | LONG | ongoing | осторожно 85% |
| 2185 | 26.11 | 07:01 | MEUSDT | LONG | ongoing | осторожно 73% |
| 2184 | 26.11 | 06:40 | ELSAUSDT | SHORT | ongoing | входить 90% |
| 2183 | 26.11 | 03:39 | MVLLUSDT | SHORT | SL_clean | осторожно 63% |
| 2182 | 26.11 | 01:35 | DOSUSDT | SHORT | TP_clean | осторожно 63% |
| 2181 | 25.11 | 22:39 | MSTUUSDT | SHORT | TP_clean | осторожно 60% |
| 2180 | 25.11 | 20:12 | CSOPSKHYNIX2LUSDT | SHORT | SL_clean | осторожно 69% |
| 2179 | 25.11 | 16:38 | ELSAUSDT | SHORT | TP_clean | осторожно 71% |
| 2178 | 25.11 | 15:13 | PLTRUSDT | SHORT | SL_clean | осторожно 62% |
| 2177 | 25.11 | 15:09 | QQQUSDT | SHORT | Sideways | осторожно 82% |
| 2176 | 25.11 | 15:07 | GOOGLUSDT | SHORT | Sideways | осторожно 73% |
| 2175 | 25.11 | 14:11 | XAUTUSDT | SHORT | Sideways | осторожно 64% |
| 2174 | 25.11 | 12:40 | MUUUSDT | SHORT | TP_clean | осторожно 67% |
| 2173 | 25.11 | 12:39 | KORUUSDT | SHORT | TP_clean | осторожно 78% |
| 2172 | 25.11 | 12:01 | WAXPUSDT | LONG | TP_clean | осторожно 61% |
| 2171 | 25.11 | 10:33 | AIGENSYNUSDT | LONG | TP_clean | осторожно 61% |
| 2170 | 25.11 | 10:05 | GLWUSDT | SHORT | TP_clean | осторожно 63% |
| 2169 | 25.11 | 10:01 | SLXUSDT | LONG | TP_clean | входить 80% |
| 2168 | 25.11 | 07:07 | SPCXUSDT | SHORT | TP_clean | осторожно 69% |
| 2167 | 25.11 | 07:07 | BMNRUSDT | SHORT | TP_clean | осторожно 68% |
| 2166 | 25.11 | 07:03 | AMATUSDT | SHORT | TP_clean | осторожно 74% |
| 2165 | 25.11 | 06:39 | PIEVERSEUSDT | SHORT | TP_clean | осторожно 65% |
| 2164 | 25.11 | 06:07 | EWYUSDT | SHORT | TP_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-11-28 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-27 18:30 UTC
- mmscan-snapshot: next run 2026-11-28 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
