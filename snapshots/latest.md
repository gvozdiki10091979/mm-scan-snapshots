# MM Scan Shadow Snapshot
Generated: 2026-07-12T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 407.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-11T14:03:08+0000 (#433 SLXUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-11T00:00:01Z → 2026-07-12T00:00:01Z)
- New signals: 9 (LONG 2 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 407.3h, restarts: 143
- Last closer: 2026-07-11T03:00:33Z
- Last backfill: 2026-07-11T23:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 6

## Health 7d (window: 2026-07-05T00:00:01Z → 2026-07-12T00:00:01Z)
- New signals: 121 (~17.3/day)
- Closed: 106 (TP 38, SL 40, SL→rev 0, Sideways 28, N/A 0)
- Ongoing: 15
- TP rate 7d: 48.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 433
- Closed: 418 (TP_clean 210, SL_clean 151, SL→reverse 0, Sideways 57, N/A 0)
- Ongoing (<24h): 15
- TP rate: 58.2% decided (TP/(TP+SL)) · 50.2% pointwise (excl N/A)

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
| 433 | 11.07 | 17:03 | SLXUSDT | SHORT | ongoing | осторожно 64% |
| 432 | 11.07 | 16:02 | INJUSDT | SHORT | ongoing | осторожно 71% |
| 431 | 11.07 | 14:06 | INTCUSDT | SHORT | ongoing | осторожно 90% |
| 430 | 11.07 | 13:04 | UNIUSDT | LONG | ongoing | осторожно 60% |
| 429 | 11.07 | 12:02 | TLMUSDT | SHORT | ongoing | входить 90% |
| 428 | 11.07 | 11:01 | VANRYUSDT | SHORT | ongoing | осторожно 63% |
| 427 | 11.07 | 09:36 | SENTUSDT | SHORT | ongoing | осторожно 67% |
| 426 | 11.07 | 05:31 | IOTAUSDT | LONG | ongoing | осторожно 68% |
| 425 | 11.07 | 04:04 | BEUSDT | SHORT | ongoing | осторожно 76% |
| 424 | 10.07 | 23:33 | MAGMAUSDT | LONG | ongoing | осторожно 61% |
| 423 | 10.07 | 20:07 | DASHUSDT | SHORT | ongoing | осторожно 60% |
| 422 | 10.07 | 18:03 | IOTAUSDT | LONG | ongoing | осторожно 60% |
| 421 | 10.07 | 07:09 | SOXLUSDT | LONG | ongoing | осторожно 67% |
| 420 | 10.07 | 06:37 | BANANAS31USDT | SHORT | ongoing | осторожно 68% |
| 419 | 10.07 | 06:09 | AAOIUSDT | LONG | ongoing | осторожно 60% |
| 418 | 10.07 | 05:03 | 1000BONKUSDT | LONG | TP_clean | осторожно 67% |
| 417 | 10.07 | 03:35 | HEIUSDT | SHORT | TP_clean | осторожно 60% |
| 416 | 10.07 | 01:07 | SNDKUSDT | LONG | SL_clean | осторожно 61% |
| 415 | 09.07 | 21:12 | APEUSDT | LONG | TP_clean | осторожно 62% |
| 414 | 09.07 | 16:01 | GWEIUSDT | SHORT | TP_clean | осторожно 69% |
| 413 | 09.07 | 15:31 | THEUSDT | LONG | TP_clean | осторожно 64% |
| 412 | 09.07 | 12:06 | GRASSUSDT | SHORT | TP_clean | осторожно 62% |
| 411 | 09.07 | 06:05 | RAVEUSDT | SHORT | SL_clean | осторожно 64% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-07-12 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-12 00:30 UTC
- mmscan-snapshot: next run 2026-07-12 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
