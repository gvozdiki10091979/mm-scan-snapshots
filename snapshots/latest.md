# MM Scan Shadow Snapshot
Generated: 2026-07-10T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 365.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-10T04:09:19+0000 (#421 SOXLUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-09T06:00:02Z → 2026-07-10T06:00:02Z)
- New signals: 10 (LONG 6 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 365.3h, restarts: 143
- Last closer: 2026-07-10T03:00:27Z
- Last backfill: 2026-07-10T05:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 1

## Health 7d (window: 2026-07-03T06:00:02Z → 2026-07-10T06:00:02Z)
- New signals: 125 (~17.9/day)
- Closed: 114 (TP 37, SL 48, SL→rev 0, Sideways 29, N/A 0)
- Ongoing: 11
- TP rate 7d: 43.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 421
- Closed: 410 (TP_clean 204, SL_clean 149, SL→reverse 0, Sideways 57, N/A 0)
- Ongoing (<24h): 11
- TP rate: 57.8% decided (TP/(TP+SL)) · 49.8% pointwise (excl N/A)

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
| 421 | 10.07 | 07:09 | SOXLUSDT | LONG | ongoing | осторожно 67% |
| 420 | 10.07 | 06:37 | BANANAS31USDT | SHORT | ongoing | осторожно 68% |
| 419 | 10.07 | 06:09 | AAOIUSDT | LONG | ongoing | осторожно 60% |
| 418 | 10.07 | 05:03 | 1000BONKUSDT | LONG | ongoing | осторожно 67% |
| 417 | 10.07 | 03:35 | HEIUSDT | SHORT | ongoing | осторожно 60% |
| 416 | 10.07 | 01:07 | SNDKUSDT | LONG | ongoing | осторожно 61% |
| 415 | 09.07 | 21:12 | APEUSDT | LONG | ongoing | осторожно 62% |
| 414 | 09.07 | 16:01 | GWEIUSDT | SHORT | ongoing | осторожно 69% |
| 413 | 09.07 | 15:31 | THEUSDT | LONG | ongoing | осторожно 64% |
| 412 | 09.07 | 12:06 | GRASSUSDT | SHORT | ongoing | осторожно 62% |
| 411 | 09.07 | 06:05 | RAVEUSDT | SHORT | ongoing | осторожно 64% |
| 410 | 09.07 | 04:31 | SLXUSDT | SHORT | TP_clean | осторожно 64% |
| 409 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 408 | 09.07 | 00:11 | TRIAUSDT | SHORT | TP_clean | осторожно 75% |
| 407 | 08.07 | 23:31 | GWEIUSDT | SHORT | TP_clean | входить 90% |
| 406 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 405 | 08.07 | 23:06 | ENAUSDT | SHORT | SL_clean | осторожно 65% |
| 404 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 403 | 08.07 | 22:05 | DEXEUSDT | LONG | TP_clean | осторожно 61% |
| 402 | 08.07 | 22:03 | ONDOUSDT | SHORT | Sideways | осторожно 69% |
| 401 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 400 | 08.07 | 21:15 | TAOUSDT | SHORT | Sideways | осторожно 65% |
| 399 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 398 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 397 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 396 | 08.07 | 18:02 | PIPPINUSDT | SHORT | SL_clean | осторожно 81% |
| 395 | 08.07 | 17:36 | TRIAUSDT | SHORT | TP_clean | осторожно 73% |
| 394 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 393 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 392 | 08.07 | 16:03 | ALGOUSDT | SHORT | Sideways | осторожно 61% |
| 391 | 08.07 | 15:31 | VELVETUSDT | SHORT | TP_clean | осторожно 63% |
| 390 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 389 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 388 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 387 | 08.07 | 12:36 | MAGMAUSDT | SHORT | SL_clean | осторожно 66% |
| 386 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 385 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 384 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 383 | 08.07 | 09:35 | TAOUSDT | SHORT | TP_clean | осторожно 62% |
| 382 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 381 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 380 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 379 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 378 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 377 | 08.07 | 04:36 | HMSTRUSDT | SHORT | TP_clean | входить 87% |
| 376 | 08.07 | 04:33 | MIRAUSDT | SHORT | TP_clean | осторожно 73% |
| 375 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 374 | 08.07 | 03:41 | MAGMAUSDT | SHORT | TP_clean | осторожно 61% |
| 373 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |
| 372 | 08.07 | 00:30 | YFIUSDT | LONG | SL_clean | входить 89% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-11 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-10 06:30 UTC
- mmscan-snapshot: next run 2026-07-10 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
