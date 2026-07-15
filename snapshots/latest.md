# MM Scan Shadow Snapshot
Generated: 2026-07-15T00:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 479.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-14T19:07:29+0000 (#460 SNDKUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-14T00:00:02Z → 2026-07-15T00:00:02Z)
- New signals: 9 (LONG 3 / SHORT 6)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 479.3h, restarts: 143
- Last closer: 2026-07-14T03:00:26Z
- Last backfill: 2026-07-14T23:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 6

## Health 7d (window: 2026-07-08T00:00:02Z → 2026-07-15T00:00:02Z)
- New signals: 66 (~9.4/day)
- Closed: 51 (TP 28, SL 14, SL→rev 0, Sideways 9, N/A 0)
- Ongoing: 15
- TP rate 7d: 66.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 460
- Closed: 445 (TP_clean 222, SL_clean 160, SL→reverse 0, Sideways 63, N/A 0)
- Ongoing (<24h): 15
- TP rate: 58.1% decided (TP/(TP+SL)) · 49.9% pointwise (excl N/A)

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
| 460 | 14.07 | 22:07 | SNDKUSDT | SHORT | ongoing | осторожно 70% |
| 459 | 14.07 | 19:35 | EIGENUSDT | LONG | ongoing | осторожно 61% |
| 458 | 14.07 | 18:36 | 1000XECUSDT | LONG | ongoing | осторожно 66% |
| 457 | 14.07 | 16:34 | ARXUSDT | SHORT | ongoing | осторожно 63% |
| 456 | 14.07 | 12:31 | VANAUSDT | LONG | ongoing | осторожно 68% |
| 455 | 14.07 | 09:07 | XLMUSDT | SHORT | ongoing | осторожно 69% |
| 454 | 14.07 | 06:33 | REUSDT | SHORT | ongoing | осторожно 69% |
| 453 | 14.07 | 04:34 | SKLUSDT | SHORT | ongoing | осторожно 71% |
| 452 | 14.07 | 04:31 | TUSDT | SHORT | ongoing | осторожно 70% |
| 451 | 14.07 | 02:40 | CLOUSDT | SHORT | ongoing | осторожно 71% |
| 450 | 14.07 | 01:04 | AAOIUSDT | SHORT | ongoing | осторожно 62% |
| 449 | 14.07 | 00:05 | ADAUSDT | SHORT | ongoing | осторожно 73% |
| 448 | 13.07 | 23:36 | REUSDT | SHORT | ongoing | осторожно 66% |
| 447 | 13.07 | 17:32 | KAITOUSDT | LONG | ongoing | осторожно 69% |
| 446 | 13.07 | 08:08 | MORPHOUSDT | SHORT | ongoing | осторожно 60% |
| 445 | 12.07 | 22:09 | MORPHOUSDT | SHORT | Sideways | осторожно 63% |
| 444 | 12.07 | 15:31 | BLUAIUSDT | LONG | SL_clean | осторожно 60% |
| 443 | 12.07 | 15:30 | SXTUSDT | LONG | TP_clean | осторожно 69% |
| 442 | 12.07 | 14:08 | XLMUSDT | SHORT | SL_clean | осторожно 65% |
| 441 | 12.07 | 14:05 | ZECUSDT | LONG | TP_clean | осторожно 70% |
| 440 | 12.07 | 12:37 | SOLUSDT | LONG | Sideways | осторожно 60% |
| 439 | 12.07 | 10:04 | LITUSDT | LONG | SL_clean | осторожно 66% |
| 438 | 12.07 | 09:36 | OPNUSDT | LONG | TP_clean | осторожно 70% |
| 437 | 12.07 | 09:01 | SXTUSDT | LONG | SL_clean | осторожно 60% |
| 436 | 12.07 | 08:04 | JTOUSDT | SHORT | SL_clean | осторожно 60% |
| 435 | 12.07 | 05:03 | PENDLEUSDT | SHORT | Sideways | осторожно 70% |
| 434 | 12.07 | 03:30 | TACUSDT | SHORT | TP_clean | осторожно 73% |
| 433 | 11.07 | 17:03 | SLXUSDT | SHORT | TP_clean | осторожно 64% |
| 432 | 11.07 | 16:02 | INJUSDT | SHORT | TP_clean | осторожно 71% |
| 431 | 11.07 | 14:06 | INTCUSDT | SHORT | Sideways | осторожно 90% |
| 430 | 11.07 | 13:04 | UNIUSDT | LONG | TP_clean | осторожно 60% |
| 429 | 11.07 | 12:02 | TLMUSDT | SHORT | TP_clean | входить 90% |
| 428 | 11.07 | 11:01 | VANRYUSDT | SHORT | TP_clean | осторожно 63% |
| 427 | 11.07 | 09:36 | SENTUSDT | SHORT | TP_clean | осторожно 67% |
| 426 | 11.07 | 05:31 | IOTAUSDT | LONG | TP_clean | осторожно 68% |
| 425 | 11.07 | 04:04 | BEUSDT | SHORT | Sideways | осторожно 76% |
| 424 | 10.07 | 23:33 | MAGMAUSDT | LONG | SL_clean | осторожно 61% |
| 423 | 10.07 | 20:07 | DASHUSDT | SHORT | Sideways | осторожно 60% |
| 422 | 10.07 | 18:03 | IOTAUSDT | LONG | SL_clean | осторожно 60% |
| 421 | 10.07 | 07:09 | SOXLUSDT | LONG | SL_clean | осторожно 67% |
| 420 | 10.07 | 06:37 | BANANAS31USDT | SHORT | TP_clean | осторожно 68% |
| 419 | 10.07 | 06:09 | AAOIUSDT | LONG | SL_clean | осторожно 60% |
| 418 | 10.07 | 05:03 | 1000BONKUSDT | LONG | TP_clean | осторожно 67% |
| 417 | 10.07 | 03:35 | HEIUSDT | SHORT | TP_clean | осторожно 60% |
| 416 | 10.07 | 01:07 | SNDKUSDT | LONG | SL_clean | осторожно 61% |
| 415 | 09.07 | 21:12 | APEUSDT | LONG | TP_clean | осторожно 62% |
| 414 | 09.07 | 16:01 | GWEIUSDT | SHORT | TP_clean | осторожно 69% |
| 413 | 09.07 | 15:31 | THEUSDT | LONG | TP_clean | осторожно 64% |
| 412 | 09.07 | 12:06 | GRASSUSDT | SHORT | TP_clean | осторожно 62% |
| 411 | 09.07 | 06:05 | RAVEUSDT | SHORT | SL_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-15 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-15 00:30 UTC
- mmscan-snapshot: next run 2026-07-15 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
