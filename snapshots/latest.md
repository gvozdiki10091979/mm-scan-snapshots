# MM Scan Shadow Snapshot
Generated: 2026-07-08T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 323.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-07T21:30:45+0000 (#389 YFIUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-07T12:00:01Z → 2026-07-08T12:00:01Z)
- New signals: 26 (LONG 16 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 26
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 323.3h, restarts: 143
- Last closer: 2026-07-08T03:00:41Z
- Last backfill: 2026-07-08T11:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-07-01T12:00:01Z → 2026-07-08T12:00:01Z)
- New signals: 119 (~17.0/day)
- Closed: 89 (TP 31, SL 30, SL→rev 0, Sideways 28, N/A 0)
- Ongoing: 30
- TP rate 7d: 50.8%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 389
- Closed: 359 (TP_clean 186, SL_clean 119, SL→reverse 0, Sideways 54, N/A 0)
- Ongoing (<24h): 30
- TP rate: 61.0% decided (TP/(TP+SL)) · 51.8% pointwise (excl N/A)

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
| 389 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 388 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 387 | 08.07 | 12:36 | MAGMAUSDT | SHORT | ongoing | осторожно 66% |
| 386 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 385 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 384 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 383 | 08.07 | 09:35 | TAOUSDT | SHORT | ongoing | осторожно 62% |
| 382 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 381 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 380 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 379 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 378 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 377 | 08.07 | 04:36 | HMSTRUSDT | SHORT | ongoing | входить 87% |
| 376 | 08.07 | 04:33 | MIRAUSDT | SHORT | ongoing | осторожно 73% |
| 375 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 374 | 08.07 | 03:41 | MAGMAUSDT | SHORT | ongoing | осторожно 61% |
| 373 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 372 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 371 | 08.07 | 02:01 | HEIUSDT | SHORT | ongoing | осторожно 71% |
| 370 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 369 | 08.07 | 00:34 | TQQQUSDT | SHORT | ongoing | осторожно 77% |
| 368 | 08.07 | 00:30 | YFIUSDT | LONG | ongoing | входить 89% |
| 367 | 07.07 | 21:32 | GWEIUSDT | SHORT | ongoing | осторожно 62% |
| 366 | 07.07 | 20:36 | SNDKUSDT | SHORT | ongoing | осторожно 89% |
| 365 | 07.07 | 19:41 | EVAAUSDT | LONG | ongoing | осторожно 61% |
| 364 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 363 | 07.07 | 19:07 | WLDUSDT | SHORT | ongoing | осторожно 62% |
| 362 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 361 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 360 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 359 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 358 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 357 | 07.07 | 14:03 | BEUSDT | SHORT | ongoing | осторожно 64% |
| 356 | 07.07 | 13:41 | ETHFIUSDT | SHORT | ongoing | осторожно 80% |
| 355 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 354 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 353 | 07.07 | 11:35 | WLDUSDT | SHORT | ongoing | осторожно 62% |
| 352 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 351 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 350 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 349 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 348 | 07.07 | 08:10 | SUIUSDT | SHORT | ongoing | осторожно 72% |
| 347 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 346 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 345 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 344 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 343 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 342 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 341 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |
| 340 | 06.07 | 19:33 | DELLUSDT | LONG | Sideways | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-09 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-08 12:30 UTC
- mmscan-snapshot: next run 2026-07-08 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
