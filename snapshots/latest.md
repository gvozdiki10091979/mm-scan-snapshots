# MM Scan Shadow Snapshot
Generated: 2026-07-07T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 287.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-06T16:33:43+0000 (#342 DELLUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-06T00:00:01Z → 2026-07-07T00:00:01Z)
- New signals: 20 (LONG 13 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 20
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 287.3h, restarts: 143
- Last closer: 2026-07-07T00:00:01Z
- Last backfill: 2026-07-07T00:00:01Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 9

## Health 7d (window: 2026-06-30T00:00:01Z → 2026-07-07T00:00:01Z)
- New signals: 110 (~15.7/day)
- Closed: 81 (TP 48, SL 30, SL→rev 0, Sideways 3, N/A 0)
- Ongoing: 29
- TP rate 7d: 61.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 342
- Closed: 313 (TP_clean 173, SL_clean 111, SL→reverse 0, Sideways 29, N/A 0)
- Ongoing (<24h): 29
- TP rate: 60.9% decided (TP/(TP+SL)) · 55.3% pointwise (excl N/A)

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
| 342 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 341 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 340 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 339 | 06.07 | 23:33 | 1000BONKUSDT | SHORT | ongoing | осторожно 76% |
| 338 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 337 | 06.07 | 23:06 | SKHYNIXUSDT | SHORT | ongoing | осторожно 68% |
| 336 | 06.07 | 22:32 | REUSDT | SHORT | ongoing | входить 82% |
| 335 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 334 | 06.07 | 22:02 | BLURUSDT | LONG | ongoing | осторожно 62% |
| 333 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 332 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 331 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 330 | 06.07 | 19:07 | BCHUSDT | LONG | ongoing | осторожно 67% |
| 329 | 06.07 | 15:06 | BELUSDT | LONG | ongoing | осторожно 60% |
| 328 | 06.07 | 15:05 | MINAUSDT | SHORT | ongoing | осторожно 62% |
| 327 | 06.07 | 13:06 | SOLUSDT | SHORT | ongoing | осторожно 62% |
| 326 | 06.07 | 12:01 | KORUUSDT | LONG | ongoing | осторожно 78% |
| 325 | 06.07 | 11:33 | HUSDT | SHORT | ongoing | осторожно 60% |
| 324 | 06.07 | 08:01 | VANRYUSDT | LONG | ongoing | осторожно 61% |
| 323 | 06.07 | 05:02 | USELESSUSDT | SHORT | ongoing | осторожно 62% |
| 322 | 06.07 | 02:34 | RPLUSDT | LONG | ongoing | осторожно 65% |
| 321 | 06.07 | 00:05 | AEROUSDT | SHORT | ongoing | осторожно 60% |
| 320 | 05.07 | 21:10 | USELESSUSDT | LONG | ongoing | осторожно 63% |
| 319 | 05.07 | 16:32 | RPLUSDT | LONG | ongoing | осторожно 65% |
| 318 | 05.07 | 16:05 | PENDLEUSDT | SHORT | ongoing | осторожно 67% |
| 317 | 05.07 | 10:31 | LABUSDT | LONG | ongoing | осторожно 68% |
| 316 | 05.07 | 07:34 | KITEUSDT | LONG | ongoing | осторожно 61% |
| 315 | 05.07 | 07:06 | ARXUSDT | LONG | ongoing | осторожно 64% |
| 314 | 05.07 | 07:03 | CAPUSDT | SHORT | ongoing | осторожно 61% |
| 313 | 05.07 | 04:30 | RPLUSDT | LONG | TP_clean | осторожно 66% |
| 312 | 04.07 | 23:31 | AIGENSYNUSDT | SHORT | SL_clean | осторожно 63% |
| 311 | 04.07 | 23:08 | XLMUSDT | LONG | SL_clean | осторожно 61% |
| 310 | 04.07 | 21:33 | GUNUSDT | LONG | SL_clean | осторожно 70% |
| 309 | 04.07 | 20:03 | BICOUSDT | LONG | TP_clean | осторожно 65% |
| 308 | 04.07 | 13:08 | MEGAUSDT | LONG | TP_clean | осторожно 61% |
| 307 | 04.07 | 10:04 | NEARUSDT | SHORT | Sideways | осторожно 60% |
| 306 | 04.07 | 07:02 | HEIUSDT | SHORT | SL_clean | осторожно 60% |
| 305 | 04.07 | 07:02 | ESPORTSUSDT | SHORT | SL_clean | осторожно 62% |
| 304 | 04.07 | 05:37 | LABUSDT | SHORT | SL_clean | входить 87% |
| 303 | 04.07 | 03:09 | BREVUSDT | SHORT | TP_clean | осторожно 75% |
| 302 | 03.07 | 16:01 | SLPUSDT | LONG | SL_clean | осторожно 61% |
| 301 | 03.07 | 14:31 | THEUSDT | LONG | TP_clean | осторожно 79% |
| 300 | 03.07 | 13:31 | REUSDT | SHORT | SL_clean | осторожно 66% |
| 299 | 03.07 | 11:32 | MUSDT | LONG | TP_clean | осторожно 63% |
| 298 | 03.07 | 10:03 | AERGOUSDT | LONG | SL_clean | осторожно 63% |
| 297 | 03.07 | 09:34 | MRVLUSDT | SHORT | SL_clean | осторожно 65% |
| 296 | 03.07 | 08:10 | LITUSDT | LONG | SL_clean | осторожно 65% |
| 295 | 03.07 | 06:31 | ALLOUSDT | LONG | SL_clean | осторожно 69% |
| 294 | 03.07 | 06:05 | MIRAUSDT | LONG | TP_clean | осторожно 67% |
| 293 | 03.07 | 06:01 | CAPUSDT | SHORT | TP_clean | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-07 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-07 00:30 UTC
- mmscan-snapshot: next run 2026-07-07 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
