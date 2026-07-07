# MM Scan Shadow Snapshot
Generated: 2026-07-07T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 305.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-07T17:36:53+0000 (#366 SNDKUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-06T18:00:01Z → 2026-07-07T18:00:01Z)
- New signals: 11 (LONG 2 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 305.3h, restarts: 143
- Last closer: 2026-07-07T03:00:25Z
- Last backfill: 2026-07-07T17:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 32

## Health 7d (window: 2026-06-30T18:00:01Z → 2026-07-07T18:00:01Z)
- New signals: 127 (~18.1/day)
- Closed: 84 (TP 53, SL 28, SL→rev 0, Sideways 3, N/A 0)
- Ongoing: 43
- TP rate 7d: 65.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 366
- Closed: 323 (TP_clean 181, SL_clean 113, SL→reverse 0, Sideways 29, N/A 0)
- Ongoing (<24h): 43
- TP rate: 61.6% decided (TP/(TP+SL)) · 56.0% pointwise (excl N/A)

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
| 366 | 07.07 | 20:36 | SNDKUSDT | SHORT | ongoing | осторожно 89% |
| 365 | 07.07 | 19:41 | EVAAUSDT | LONG | ongoing | осторожно 61% |
| 364 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 363 | 07.07 | 19:07 | WLDUSDT | SHORT | ongoing | осторожно 62% |
| 362 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 361 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 360 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 359 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 358 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 357 | 07.07 | 14:03 | BEUSDT | SHORT | ongoing | осторожно 64% |
| 356 | 07.07 | 13:41 | ETHFIUSDT | SHORT | ongoing | осторожно 80% |
| 355 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 354 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 353 | 07.07 | 11:35 | WLDUSDT | SHORT | ongoing | осторожно 62% |
| 352 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 351 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 350 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 349 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 348 | 07.07 | 08:10 | SUIUSDT | SHORT | ongoing | осторожно 72% |
| 347 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 346 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 345 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 344 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
| 343 | 06.07 | 19:33 | DELLUSDT | LONG | ongoing | осторожно 60% |
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
| 323 | 06.07 | 05:02 | USELESSUSDT | SHORT | TP_clean | осторожно 62% |
| 322 | 06.07 | 02:34 | RPLUSDT | LONG | TP_clean | осторожно 65% |
| 321 | 06.07 | 00:05 | AEROUSDT | SHORT | TP_clean | осторожно 60% |
| 320 | 05.07 | 21:10 | USELESSUSDT | LONG | TP_clean | осторожно 63% |
| 319 | 05.07 | 16:32 | RPLUSDT | LONG | SL_clean | осторожно 65% |
| 318 | 05.07 | 16:05 | PENDLEUSDT | SHORT | TP_clean | осторожно 67% |
| 317 | 05.07 | 10:31 | LABUSDT | LONG | SL_clean | осторожно 68% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-08 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-07 18:30 UTC
- mmscan-snapshot: next run 2026-07-08 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
