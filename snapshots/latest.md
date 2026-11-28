# MM Scan Shadow Snapshot
Generated: 2026-11-28T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 3053496
- Uptime: 125.0h (active since Mon 2026-11-23 12:58:26 UTC)
- Last signal: 2026-11-28T16:34:18+0000 (#2225 NEARUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12

## Health 24h (window: 2026-11-27T18:00:02Z → 2026-11-28T18:00:02Z)
- New signals: 23 (LONG 8 / SHORT 15)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 23
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 125.0h, restarts: 12
- Last closer: 2026-11-28T03:00:44Z
- Last backfill: 2026-11-28T17:30:02Z
- Anomalies: listener рестартов: 12; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-11-21T18:00:02Z → 2026-11-28T18:00:02Z)
- New signals: 109 (~15.6/day)
- Closed: 82 (TP 43, SL 32, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 27
- TP rate 7d: 57.3%
- Listener uptime 7d: 74.4% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2225
- Closed: 2198 (TP_clean 1131, SL_clean 770, SL→reverse 0, Sideways 297, N/A 0)
- Ongoing (<24h): 27
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 2225 | 28.11 | 19:34 | NEARUSDT | SHORT | ongoing | осторожно 82% |
| 2224 | 28.11 | 19:03 | BLURUSDT | SHORT | ongoing | входить 81% |
| 2223 | 28.11 | 17:04 | NBISUSDT | SHORT | ongoing | осторожно 72% |
| 2222 | 28.11 | 16:34 | ARBUSDT | SHORT | ongoing | осторожно 72% |
| 2221 | 28.11 | 16:10 | HOODUSDT | SHORT | ongoing | осторожно 79% |
| 2220 | 28.11 | 15:04 | HAEDALUSDT | LONG | ongoing | осторожно 61% |
| 2219 | 28.11 | 14:39 | INITUSDT | SHORT | ongoing | осторожно 61% |
| 2218 | 28.11 | 14:02 | MSTUUSDT | SHORT | ongoing | осторожно 67% |
| 2217 | 28.11 | 14:00 | CFGUSDT | LONG | ongoing | осторожно 68% |
| 2216 | 28.11 | 13:36 | CRCLUSDT | SHORT | ongoing | осторожно 68% |
| 2215 | 28.11 | 13:09 | BLURUSDT | SHORT | ongoing | входить 88% |
| 2214 | 28.11 | 12:13 | AEROUSDT | SHORT | ongoing | осторожно 62% |
| 2213 | 28.11 | 09:31 | 1000LUNCUSDT | LONG | ongoing | осторожно 62% |
| 2212 | 28.11 | 08:32 | ETHFIUSDT | SHORT | ongoing | осторожно 69% |
| 2211 | 28.11 | 07:06 | HOODUSDT | SHORT | ongoing | осторожно 74% |
| 2210 | 28.11 | 05:01 | ZHIPUUSDT | LONG | ongoing | осторожно 61% |
| 2209 | 28.11 | 04:32 | SLXUSDT | LONG | ongoing | осторожно 61% |
| 2208 | 28.11 | 03:36 | BLESSUSDT | SHORT | ongoing | осторожно 61% |
| 2207 | 28.11 | 03:32 | INITUSDT | LONG | ongoing | осторожно 71% |
| 2206 | 28.11 | 00:08 | YBUSDT | LONG | ongoing | осторожно 64% |
| 2205 | 27.11 | 22:10 | DASHUSDT | SHORT | ongoing | осторожно 60% |
| 2204 | 27.11 | 21:31 | SOXLUSDT | LONG | ongoing | осторожно 64% |
| 2203 | 27.11 | 21:09 | AEROUSDT | SHORT | ongoing | осторожно 62% |
| 2202 | 27.11 | 20:40 | LDOUSDT | SHORT | ongoing | осторожно 64% |
| 2201 | 27.11 | 19:33 | MMTUSDT | SHORT | ongoing | осторожно 66% |
| 2200 | 27.11 | 12:31 | SKDDUSDT | SHORT | ongoing | осторожно 68% |
| 2199 | 27.11 | 09:34 | BLESSUSDT | SHORT | ongoing | осторожно 62% |
| 2198 | 27.11 | 05:01 | SSVUSDT | LONG | TP_clean | осторожно 75% |
| 2197 | 27.11 | 05:00 | OPGUSDT | SHORT | SL_clean | входить 90% |
| 2196 | 27.11 | 02:00 | SKHYNIXUSDT | SHORT | SL_clean | осторожно 60% |
| 2195 | 26.11 | 23:36 | SKHYUSDT | SHORT | SL_clean | осторожно 62% |
| 2194 | 26.11 | 23:07 | SKUUUSDT | LONG | TP_clean | осторожно 60% |
| 2193 | 26.11 | 22:33 | SKDDUSDT | SHORT | TP_clean | осторожно 74% |
| 2192 | 26.11 | 22:01 | MMTUSDT | SHORT | TP_clean | осторожно 72% |
| 2191 | 26.11 | 21:34 | UNIUSDT | SHORT | SL_clean | осторожно 68% |
| 2190 | 26.11 | 20:02 | SKYUSDT | LONG | TP_clean | осторожно 64% |
| 2189 | 26.11 | 18:33 | 2ZUSDT | LONG | SL_clean | осторожно 62% |
| 2188 | 26.11 | 17:33 | SLXUSDT | LONG | TP_clean | осторожно 63% |
| 2187 | 26.11 | 13:04 | BIGTIMEUSDT | LONG | TP_clean | осторожно 75% |
| 2186 | 26.11 | 11:31 | MOODENGUSDT | LONG | SL_clean | осторожно 85% |
| 2185 | 26.11 | 07:01 | MEUSDT | LONG | TP_clean | осторожно 73% |
| 2184 | 26.11 | 06:40 | ELSAUSDT | SHORT | SL_clean | входить 90% |
| 2183 | 26.11 | 03:39 | MVLLUSDT | SHORT | SL_clean | осторожно 63% |
| 2182 | 26.11 | 01:35 | DOSUSDT | SHORT | TP_clean | осторожно 63% |
| 2181 | 25.11 | 22:39 | MSTUUSDT | SHORT | TP_clean | осторожно 60% |
| 2180 | 25.11 | 20:12 | CSOPSKHYNIX2LUSDT | SHORT | SL_clean | осторожно 69% |
| 2179 | 25.11 | 16:38 | ELSAUSDT | SHORT | TP_clean | осторожно 71% |
| 2178 | 25.11 | 15:13 | PLTRUSDT | SHORT | SL_clean | осторожно 62% |
| 2177 | 25.11 | 15:09 | QQQUSDT | SHORT | Sideways | осторожно 82% |
| 2176 | 25.11 | 15:07 | GOOGLUSDT | SHORT | Sideways | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-29 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-28 18:30 UTC
- mmscan-snapshot: next run 2026-11-29 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
