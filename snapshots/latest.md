# MM Scan Shadow Snapshot
Generated: 2026-08-06T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 328.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-08-06T06:36:35+0000 (#724 SKRUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-08-05T12:00:01Z → 2026-08-06T12:00:01Z)
- New signals: 12 (LONG 9 / SHORT 3)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 328.1h, restarts: 12064
- Last closer: 2026-08-06T03:00:25Z
- Last backfill: 2026-08-06T11:30:02Z
- Anomalies: listener рестартов: 12064; ongoing >24h без закрытия: 6

## Health 7d (window: 2026-07-30T12:00:01Z → 2026-08-06T12:00:01Z)
- New signals: 68 (~9.7/day)
- Closed: 50 (TP 24, SL 20, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 18
- TP rate 7d: 54.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 724
- Closed: 706 (TP_clean 367, SL_clean 237, SL→reverse 0, Sideways 102, N/A 0)
- Ongoing (<24h): 18
- TP rate: 60.8% decided (TP/(TP+SL)) · 52.0% pointwise (excl N/A)

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
| 724 | 06.08 | 09:36 | SKRUSDT | LONG | ongoing | входить 87% |
| 723 | 06.08 | 07:09 | KITEUSDT | LONG | ongoing | осторожно 61% |
| 722 | 06.08 | 01:08 | KORUUSDT | LONG | ongoing | осторожно 63% |
| 721 | 06.08 | 00:35 | EPICUSDT | SHORT | ongoing | осторожно 68% |
| 720 | 05.08 | 23:02 | HOMEUSDT | LONG | ongoing | осторожно 60% |
| 719 | 05.08 | 22:31 | MMTUSDT | LONG | ongoing | осторожно 62% |
| 718 | 05.08 | 21:40 | CRCLUSDT | LONG | ongoing | осторожно 68% |
| 717 | 05.08 | 20:30 | CYSUSDT | LONG | ongoing | осторожно 72% |
| 716 | 05.08 | 19:41 | XMRUSDT | SHORT | ongoing | осторожно 60% |
| 715 | 05.08 | 19:05 | SAMSUNGUSDT | LONG | ongoing | осторожно 65% |
| 714 | 05.08 | 18:34 | DEXEUSDT | LONG | ongoing | осторожно 62% |
| 713 | 05.08 | 17:03 | VVVUSDT | SHORT | ongoing | осторожно 62% |
| 712 | 05.08 | 12:38 | SKHYNIXUSDT | LONG | ongoing | осторожно 61% |
| 711 | 05.08 | 11:33 | FIDAUSDT | LONG | ongoing | осторожно 61% |
| 710 | 05.08 | 11:04 | CYSUSDT | LONG | ongoing | осторожно 61% |
| 709 | 05.08 | 11:01 | VANRYUSDT | SHORT | ongoing | осторожно 65% |
| 708 | 05.08 | 09:01 | HEIUSDT | LONG | ongoing | осторожно 65% |
| 707 | 05.08 | 08:02 | SKRUSDT | LONG | ongoing | осторожно 61% |
| 706 | 05.08 | 05:36 | 1000RATSUSDT | SHORT | TP_clean | осторожно 71% |
| 705 | 05.08 | 03:05 | AAOIUSDT | LONG | TP_clean | осторожно 68% |
| 704 | 04.08 | 22:11 | PTBUSDT | SHORT | SL_clean | входить 82% |
| 703 | 04.08 | 20:05 | ESPUSDT | SHORT | Sideways | осторожно 67% |
| 702 | 04.08 | 17:31 | COTIUSDT | SHORT | SL_clean | осторожно 72% |
| 701 | 04.08 | 16:34 | CBRSUSDT | LONG | TP_clean | осторожно 67% |
| 700 | 04.08 | 16:07 | ARBUSDT | SHORT | Sideways | осторожно 67% |
| 699 | 04.08 | 13:06 | ZHIPUUSDT | LONG | TP_clean | осторожно 63% |
| 698 | 04.08 | 12:31 | EULUSDT | SHORT | SL_clean | осторожно 75% |
| 697 | 04.08 | 11:30 | HOMEUSDT | LONG | TP_clean | осторожно 71% |
| 696 | 04.08 | 11:02 | UAIUSDT | SHORT | TP_clean | осторожно 70% |
| 695 | 04.08 | 10:31 | LITUSDT | LONG | TP_clean | осторожно 62% |
| 694 | 04.08 | 10:05 | VANRYUSDT | SHORT | SL_clean | осторожно 63% |
| 693 | 04.08 | 09:06 | COINUSDT | LONG | Sideways | осторожно 61% |
| 692 | 04.08 | 04:37 | UAIUSDT | SHORT | SL_clean | осторожно 77% |
| 691 | 04.08 | 04:31 | HOMEUSDT | SHORT | SL_clean | осторожно 73% |
| 690 | 03.08 | 22:36 | BICOUSDT | LONG | SL_clean | осторожно 68% |
| 689 | 03.08 | 20:36 | EWYUSDT | LONG | TP_clean | осторожно 69% |
| 688 | 03.08 | 20:33 | SKHYUSDT | LONG | TP_clean | осторожно 61% |
| 687 | 03.08 | 20:10 | SPCXUSDT | LONG | TP_clean | осторожно 64% |
| 686 | 03.08 | 15:37 | SKHYNIXUSDT | LONG | TP_clean | осторожно 70% |
| 685 | 03.08 | 13:00 | VANRYUSDT | SHORT | TP_clean | осторожно 74% |
| 684 | 03.08 | 12:07 | ACEUSDT | LONG | SL_clean | осторожно 65% |
| 683 | 03.08 | 09:38 | BEATUSDT | SHORT | TP_clean | осторожно 67% |
| 682 | 02.08 | 18:06 | CAPUSDT | SHORT | TP_clean | осторожно 78% |
| 681 | 02.08 | 15:38 | BTWUSDT | SHORT | SL_clean | осторожно 76% |
| 680 | 02.08 | 11:30 | TLMUSDT | LONG | TP_clean | осторожно 67% |
| 679 | 02.08 | 07:33 | CFXUSDT | LONG | Sideways | осторожно 65% |
| 678 | 02.08 | 05:37 | CAPUSDT | SHORT | SL_clean | осторожно 77% |
| 677 | 02.08 | 01:01 | CFXUSDT | LONG | Sideways | осторожно 61% |
| 676 | 02.08 | 00:12 | AAVEUSDT | SHORT | SL_clean | осторожно 62% |
| 675 | 01.08 | 20:31 | AEVOUSDT | LONG | SL_clean | осторожно 67% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-07 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-06 12:30 UTC
- mmscan-snapshot: next run 2026-08-06 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
