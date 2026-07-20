# MM Scan Shadow Snapshot
Generated: 2026-07-20T00:00:01Z

## Listener Health
- systemd status: **activating**
- MainPID: 0
- Uptime: 0.0h (active since Sun 2026-07-19 23:59:38 UTC)
- Last signal: 2026-07-18T04:08:18+0000 (#504 KITEUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 4924

## Health 24h (window: 2026-07-19T00:00:01Z → 2026-07-20T00:00:01Z)
- New signals: 0 (LONG 0 / SHORT 0)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 0
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 0.0h, restarts: 4924
- Last closer: 2026-07-19T03:00:26Z
- Last backfill: 2026-07-19T23:30:02Z
- Anomalies: listener рестартов: 4924; ongoing >24h без закрытия: 5

## Health 7d (window: 2026-07-13T00:00:01Z → 2026-07-20T00:00:01Z)
- New signals: 59 (~8.4/day)
- Closed: 54 (TP 31, SL 18, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 5
- TP rate 7d: 63.3%
- Listener uptime 7d: 0.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 504
- Closed: 499 (TP_clean 253, SL_clean 178, SL→reverse 0, Sideways 68, N/A 0)
- Ongoing (<24h): 5
- TP rate: 58.7% decided (TP/(TP+SL)) · 50.7% pointwise (excl N/A)

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
| 504 | 18.07 | 07:08 | KITEUSDT | SHORT | ongoing | осторожно 60% |
| 503 | 18.07 | 07:04 | MVLLUSDT | SHORT | ongoing | осторожно 62% |
| 502 | 18.07 | 06:40 | METAUSDT | SHORT | ongoing | осторожно 62% |
| 501 | 18.07 | 06:34 | KORUUSDT | SHORT | ongoing | осторожно 63% |
| 500 | 18.07 | 06:02 | CHZUSDT | SHORT | ongoing | осторожно 68% |
| 499 | 18.07 | 02:38 | TUSDT | LONG | TP_clean | осторожно 61% |
| 498 | 18.07 | 01:06 | MVLLUSDT | SHORT | Sideways | осторожно 66% |
| 497 | 17.07 | 22:33 | REUSDT | SHORT | TP_clean | осторожно 66% |
| 496 | 17.07 | 22:32 | KORUUSDT | SHORT | TP_clean | осторожно 77% |
| 495 | 17.07 | 22:04 | MUUSDT | LONG | Sideways | осторожно 60% |
| 494 | 17.07 | 14:08 | AAVEUSDT | SHORT | TP_clean | осторожно 74% |
| 493 | 17.07 | 14:07 | CBRSUSDT | SHORT | TP_clean | осторожно 66% |
| 492 | 17.07 | 13:38 | SKLUSDT | SHORT | TP_clean | осторожно 72% |
| 491 | 17.07 | 12:32 | SENTUSDT | LONG | TP_clean | осторожно 60% |
| 490 | 17.07 | 11:37 | XRPUSDT | SHORT | Sideways | осторожно 74% |
| 489 | 17.07 | 11:10 | ZECUSDT | SHORT | SL_clean | осторожно 69% |
| 488 | 17.07 | 11:09 | UNIUSDT | SHORT | Sideways | осторожно 61% |
| 487 | 17.07 | 07:31 | VELVETUSDT | LONG | TP_clean | осторожно 69% |
| 486 | 17.07 | 06:38 | KATUSDT | SHORT | TP_clean | осторожно 62% |
| 485 | 17.07 | 06:32 | AGLDUSDT | SHORT | SL_clean | осторожно 61% |
| 484 | 17.07 | 06:10 | ARMUSDT | SHORT | TP_clean | осторожно 69% |
| 483 | 17.07 | 01:07 | ARMUSDT | SHORT | TP_clean | осторожно 77% |
| 482 | 17.07 | 00:12 | UBUSDT | LONG | SL_clean | осторожно 67% |
| 481 | 16.07 | 23:12 | GWEIUSDT | SHORT | SL_clean | осторожно 63% |
| 480 | 16.07 | 21:33 | AGLDUSDT | SHORT | TP_clean | осторожно 63% |
| 479 | 16.07 | 19:31 | 1000BONKUSDT | SHORT | TP_clean | осторожно 62% |
| 478 | 16.07 | 19:02 | MRVLUSDT | SHORT | TP_clean | осторожно 62% |
| 477 | 16.07 | 16:01 | ARMUSDT | SHORT | TP_clean | осторожно 61% |
| 476 | 16.07 | 15:38 | EVAAUSDT | SHORT | SL_clean | осторожно 70% |
| 475 | 16.07 | 15:06 | BEATUSDT | SHORT | TP_clean | осторожно 65% |
| 474 | 16.07 | 14:35 | BEUSDT | SHORT | SL_clean | осторожно 62% |
| 473 | 16.07 | 14:30 | DEXEUSDT | SHORT | TP_clean | осторожно 63% |
| 472 | 16.07 | 14:05 | HYPEUSDT | SHORT | TP_clean | осторожно 63% |
| 471 | 16.07 | 07:07 | EWYUSDT | SHORT | TP_clean | осторожно 68% |
| 470 | 16.07 | 06:02 | BEUSDT | SHORT | TP_clean | осторожно 60% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-07-20 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-20 00:30 UTC
- mmscan-snapshot: next run 2026-07-20 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
