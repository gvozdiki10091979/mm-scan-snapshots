# MM Scan Shadow Snapshot
Generated: 2026-07-17T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 533.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-17T04:31:05+0000 (#487 VELVETUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-16T06:00:01Z → 2026-07-17T06:00:01Z)
- New signals: 16 (LONG 2 / SHORT 14)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 16
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 533.3h, restarts: 143
- Last closer: 2026-07-17T03:00:18Z
- Last backfill: 2026-07-17T05:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 2

## Health 7d (window: 2026-07-10T06:00:01Z → 2026-07-17T06:00:01Z)
- New signals: 66 (~9.4/day)
- Closed: 48 (TP 22, SL 19, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 18
- TP rate 7d: 53.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 487
- Closed: 469 (TP_clean 233, SL_clean 172, SL→reverse 0, Sideways 64, N/A 0)
- Ongoing (<24h): 18
- TP rate: 57.5% decided (TP/(TP+SL)) · 49.7% pointwise (excl N/A)

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
| 487 | 17.07 | 07:31 | VELVETUSDT | LONG | ongoing | осторожно 69% |
| 486 | 17.07 | 06:38 | KATUSDT | SHORT | ongoing | осторожно 62% |
| 485 | 17.07 | 06:32 | AGLDUSDT | SHORT | ongoing | осторожно 61% |
| 484 | 17.07 | 06:10 | ARMUSDT | SHORT | ongoing | осторожно 69% |
| 483 | 17.07 | 01:07 | ARMUSDT | SHORT | ongoing | осторожно 77% |
| 482 | 17.07 | 00:12 | UBUSDT | LONG | ongoing | осторожно 67% |
| 481 | 16.07 | 23:12 | GWEIUSDT | SHORT | ongoing | осторожно 63% |
| 480 | 16.07 | 21:33 | AGLDUSDT | SHORT | ongoing | осторожно 63% |
| 479 | 16.07 | 19:31 | 1000BONKUSDT | SHORT | ongoing | осторожно 62% |
| 478 | 16.07 | 19:02 | MRVLUSDT | SHORT | ongoing | осторожно 62% |
| 477 | 16.07 | 16:01 | ARMUSDT | SHORT | ongoing | осторожно 61% |
| 476 | 16.07 | 15:38 | EVAAUSDT | SHORT | ongoing | осторожно 70% |
| 475 | 16.07 | 15:06 | BEATUSDT | SHORT | ongoing | осторожно 65% |
| 474 | 16.07 | 14:35 | BEUSDT | SHORT | ongoing | осторожно 62% |
| 473 | 16.07 | 14:30 | DEXEUSDT | SHORT | ongoing | осторожно 63% |
| 472 | 16.07 | 14:05 | HYPEUSDT | SHORT | ongoing | осторожно 63% |
| 471 | 16.07 | 07:07 | EWYUSDT | SHORT | ongoing | осторожно 68% |
| 470 | 16.07 | 06:02 | BEUSDT | SHORT | ongoing | осторожно 60% |
| 469 | 16.07 | 03:31 | GWEIUSDT | SHORT | TP_clean | осторожно 66% |
| 468 | 16.07 | 01:34 | SAMSUNGUSDT | SHORT | TP_clean | осторожно 65% |
| 467 | 16.07 | 01:00 | HOMEUSDT | LONG | TP_clean | осторожно 61% |
| 466 | 15.07 | 15:36 | ARXUSDT | SHORT | TP_clean | осторожно 71% |
| 465 | 15.07 | 14:10 | 0GUSDT | LONG | TP_clean | осторожно 61% |
| 464 | 15.07 | 13:34 | ZBTUSDT | SHORT | SL_clean | осторожно 81% |
| 463 | 15.07 | 09:05 | 1000PEPEUSDT | SHORT | SL_clean | осторожно 60% |
| 462 | 15.07 | 08:31 | ETHFIUSDT | SHORT | SL_clean | осторожно 76% |
| 461 | 15.07 | 06:07 | 1000XECUSDT | SHORT | SL_clean | осторожно 73% |
| 460 | 14.07 | 22:07 | SNDKUSDT | SHORT | TP_clean | осторожно 70% |
| 459 | 14.07 | 19:35 | EIGENUSDT | LONG | SL_clean | осторожно 61% |
| 458 | 14.07 | 18:36 | 1000XECUSDT | LONG | SL_clean | осторожно 66% |
| 457 | 14.07 | 16:34 | ARXUSDT | SHORT | TP_clean | осторожно 63% |
| 456 | 14.07 | 12:31 | VANAUSDT | LONG | SL_clean | осторожно 68% |
| 455 | 14.07 | 09:07 | XLMUSDT | SHORT | SL_clean | осторожно 69% |
| 454 | 14.07 | 06:33 | REUSDT | SHORT | TP_clean | осторожно 69% |
| 453 | 14.07 | 04:34 | SKLUSDT | SHORT | TP_clean | осторожно 71% |
| 452 | 14.07 | 04:31 | TUSDT | SHORT | SL_clean | осторожно 70% |
| 451 | 14.07 | 02:40 | CLOUSDT | SHORT | TP_clean | осторожно 71% |
| 450 | 14.07 | 01:04 | AAOIUSDT | SHORT | SL_clean | осторожно 62% |
| 449 | 14.07 | 00:05 | ADAUSDT | SHORT | SL_clean | осторожно 73% |
| 448 | 13.07 | 23:36 | REUSDT | SHORT | SL_clean | осторожно 66% |
| 447 | 13.07 | 17:32 | KAITOUSDT | LONG | TP_clean | осторожно 69% |
| 446 | 13.07 | 08:08 | MORPHOUSDT | SHORT | Sideways | осторожно 60% |
| 445 | 12.07 | 22:09 | MORPHOUSDT | SHORT | Sideways | осторожно 63% |
| 444 | 12.07 | 15:31 | BLUAIUSDT | LONG | SL_clean | осторожно 60% |
| 443 | 12.07 | 15:30 | SXTUSDT | LONG | TP_clean | осторожно 69% |
| 442 | 12.07 | 14:08 | XLMUSDT | SHORT | SL_clean | осторожно 65% |
| 441 | 12.07 | 14:05 | ZECUSDT | LONG | TP_clean | осторожно 70% |
| 440 | 12.07 | 12:37 | SOLUSDT | LONG | Sideways | осторожно 60% |
| 439 | 12.07 | 10:04 | LITUSDT | LONG | SL_clean | осторожно 66% |
| 438 | 12.07 | 09:36 | OPNUSDT | LONG | TP_clean | осторожно 70% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-18 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-17 06:30 UTC
- mmscan-snapshot: next run 2026-07-17 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
