# MM Scan Shadow Snapshot
Generated: 2026-07-26T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 52.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-07-25T20:38:19+0000 (#584 WLDUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-07-25T00:00:01Z → 2026-07-26T00:00:01Z)
- New signals: 8 (LONG 1 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 52.1h, restarts: 12064
- Last closer: 2026-07-25T03:00:35Z
- Last backfill: 2026-07-25T23:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 20

## Health 7d (window: 2026-07-19T00:00:01Z → 2026-07-26T00:00:01Z)
- New signals: 75 (~10.7/day)
- Closed: 47 (TP 28, SL 11, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 28
- TP rate 7d: 71.8%
- Listener uptime 7d: 31.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 584
- Closed: 556 (TP_clean 285, SL_clean 190, SL→reverse 0, Sideways 81, N/A 0)
- Ongoing (<24h): 28
- TP rate: 60.0% decided (TP/(TP+SL)) · 51.3% pointwise (excl N/A)

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
| 584 | 25.07 | 23:38 | WLDUSDT | SHORT | ongoing | осторожно 70% |
| 583 | 25.07 | 21:05 | LAUSDT | SHORT | ongoing | осторожно 70% |
| 582 | 25.07 | 17:04 | BZUSDT | SHORT | ongoing | осторожно 67% |
| 581 | 25.07 | 17:03 | CLUSDT | SHORT | ongoing | осторожно 66% |
| 580 | 25.07 | 09:37 | CRVUSDT | SHORT | ongoing | осторожно 62% |
| 579 | 25.07 | 08:37 | SKHYNIXUSDT | SHORT | ongoing | осторожно 62% |
| 578 | 25.07 | 07:01 | TNSRUSDT | LONG | ongoing | осторожно 73% |
| 577 | 25.07 | 03:12 | AAVEUSDT | SHORT | ongoing | осторожно 81% |
| 576 | 25.07 | 01:05 | GWEIUSDT | LONG | ongoing | осторожно 68% |
| 575 | 25.07 | 00:35 | B2USDT | SHORT | ongoing | входить 81% |
| 574 | 25.07 | 00:32 | ZBTUSDT | LONG | ongoing | осторожно 63% |
| 573 | 24.07 | 22:02 | ERAUSDT | LONG | ongoing | осторожно 67% |
| 572 | 24.07 | 21:03 | LITUSDT | SHORT | ongoing | осторожно 73% |
| 571 | 24.07 | 20:42 | SOLUSDT | SHORT | ongoing | осторожно 64% |
| 570 | 24.07 | 19:41 | 1000PEPEUSDT | SHORT | ongoing | осторожно 63% |
| 569 | 24.07 | 19:37 | ORCLUSDT | SHORT | ongoing | осторожно 62% |
| 568 | 24.07 | 18:32 | ARXUSDT | SHORT | ongoing | осторожно 67% |
| 567 | 24.07 | 16:05 | DOTUSDT | SHORT | ongoing | осторожно 88% |
| 566 | 24.07 | 16:05 | ETCUSDT | SHORT | ongoing | осторожно 77% |
| 565 | 24.07 | 15:06 | AVAXUSDT | SHORT | ongoing | осторожно 62% |
| 564 | 24.07 | 15:05 | WIFUSDT | SHORT | ongoing | осторожно 62% |
| 563 | 24.07 | 14:06 | EWYUSDT | LONG | ongoing | осторожно 69% |
| 562 | 24.07 | 13:37 | ERAUSDT | SHORT | ongoing | осторожно 60% |
| 561 | 24.07 | 13:31 | VANRYUSDT | LONG | ongoing | осторожно 73% |
| 560 | 24.07 | 11:02 | EWYUSDT | SHORT | ongoing | осторожно 66% |
| 559 | 24.07 | 10:31 | MUUUSDT | LONG | ongoing | осторожно 65% |
| 558 | 24.07 | 09:37 | OPUSDT | LONG | ongoing | осторожно 60% |
| 557 | 24.07 | 08:11 | CBRSUSDT | LONG | ongoing | осторожно 88% |
| 556 | 24.07 | 05:03 | HOMEUSDT | LONG | TP_clean | осторожно 61% |
| 555 | 24.07 | 01:41 | MUUSDT | LONG | SL_clean | осторожно 62% |
| 554 | 24.07 | 01:06 | COINUSDT | SHORT | TP_clean | осторожно 70% |
| 553 | 24.07 | 00:38 | HYPEUSDT | SHORT | Sideways | осторожно 61% |
| 552 | 24.07 | 00:31 | BANKUSDT | LONG | TP_clean | осторожно 65% |
| 551 | 23.07 | 23:33 | LITUSDT | SHORT | TP_clean | осторожно 62% |
| 550 | 23.07 | 23:31 | LAUSDT | LONG | SL_clean | осторожно 62% |
| 549 | 22.07 | 22:04 | SMCIUSDT | LONG | TP_clean | осторожно 74% |
| 548 | 23.07 | 03:08 | XMRUSDT | LONG | Sideways | осторожно 66% |
| 547 | 23.07 | 03:09 | MONUSDT | SHORT | TP_clean | осторожно 61% |
| 546 | 23.07 | 09:05 | MONUSDT | SHORT | TP_clean | осторожно 78% |
| 545 | 23.07 | 10:11 | MORPHOUSDT | SHORT | Sideways | осторожно 62% |
| 544 | 23.07 | 10:34 | VVVUSDT | SHORT | TP_clean | осторожно 73% |
| 543 | 23.07 | 11:30 | ZKCUSDT | LONG | SL_clean | осторожно 61% |
| 542 | 23.07 | 14:07 | BARDUSDT | LONG | TP_clean | осторожно 65% |
| 541 | 23.07 | 16:06 | TLMUSDT | SHORT | TP_clean | осторожно 65% |
| 540 | 23.07 | 18:11 | PENDLEUSDT | SHORT | TP_clean | осторожно 79% |
| 539 | 23.07 | 19:11 | SPCXUSDT | SHORT | Sideways | осторожно 60% |
| 538 | 23.07 | 20:11 | COINUSDT | SHORT | TP_clean | осторожно 60% |
| 537 | 23.07 | 20:38 | SNDKUSDT | LONG | SL_clean | осторожно 66% |
| 536 | 23.07 | 21:07 | MUUUSDT | LONG | SL_clean | осторожно 65% |
| 535 | 23.07 | 21:32 | KAITOUSDT | LONG | SL_clean | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-26 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-26 00:30 UTC
- mmscan-snapshot: next run 2026-07-26 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
