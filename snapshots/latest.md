# MM Scan Shadow Snapshot
Generated: 2026-08-11T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 3826545
- Uptime: 442.1h (active since Thu 2026-07-23 19:52:31 UTC)
- Last signal: 2026-08-11T04:02:57+0000 (#761 MUUUSDT LONG, ongoing)
- Auto-restarts (since unit start): 12064

## Health 24h (window: 2026-08-10T06:00:01Z → 2026-08-11T06:00:01Z)
- New signals: 6 (LONG 3 / SHORT 3)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 442.1h, restarts: 12064
- Last closer: 2026-08-11T03:00:10Z
- Last backfill: 2026-08-11T05:30:02Z
- Anomalies: listener рестартов: 12064

## Health 7d (window: 2026-08-04T06:00:01Z → 2026-08-11T06:00:01Z)
- New signals: 69 (~9.9/day)
- Closed: 63 (TP 32, SL 20, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 6
- TP rate 7d: 61.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 761
- Closed: 755 (TP_clean 392, SL_clean 253, SL→reverse 0, Sideways 110, N/A 0)
- Ongoing (<24h): 6
- TP rate: 60.8% decided (TP/(TP+SL)) · 51.9% pointwise (excl N/A)

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
| 761 | 11.08 | 07:02 | MUUUSDT | LONG | ongoing | осторожно 64% |
| 760 | 11.08 | 04:32 | MEUSDT | LONG | ongoing | осторожно 68% |
| 759 | 10.08 | 21:03 | MUUUSDT | SHORT | ongoing | осторожно 64% |
| 758 | 10.08 | 15:01 | GUNUSDT | LONG | ongoing | осторожно 61% |
| 757 | 10.08 | 13:34 | RENDERUSDT | SHORT | ongoing | осторожно 62% |
| 756 | 10.08 | 13:02 | ORDIUSDT | SHORT | ongoing | осторожно 60% |
| 755 | 10.08 | 05:33 | WIFUSDT | SHORT | Sideways | осторожно 68% |
| 754 | 10.08 | 00:02 | SIRENUSDT | LONG | TP_clean | осторожно 64% |
| 753 | 09.08 | 23:34 | IOTXUSDT | LONG | SL_clean | осторожно 77% |
| 752 | 09.08 | 13:06 | UBUSDT | LONG | TP_clean | осторожно 61% |
| 751 | 09.08 | 05:32 | LAUSDT | LONG | TP_clean | осторожно 67% |
| 750 | 09.08 | 04:05 | ONUSDT | SHORT | SL_clean | осторожно 60% |
| 749 | 09.08 | 04:02 | CYSUSDT | LONG | SL_clean | осторожно 71% |
| 748 | 08.08 | 15:35 | HYPEUSDT | LONG | Sideways | осторожно 66% |
| 747 | 08.08 | 09:05 | NEARUSDT | SHORT | Sideways | осторожно 65% |
| 746 | 08.08 | 05:01 | ACEUSDT | LONG | TP_clean | осторожно 90% |
| 745 | 08.08 | 04:03 | LAUSDT | LONG | TP_clean | осторожно 64% |
| 744 | 08.08 | 04:02 | ZBTUSDT | SHORT | TP_clean | входить 86% |
| 743 | 08.08 | 03:31 | BICOUSDT | LONG | SL_clean | осторожно 62% |
| 742 | 08.08 | 01:38 | SPCXUSDT | LONG | TP_clean | осторожно 61% |
| 741 | 08.08 | 01:33 | ONDOUSDT | SHORT | Sideways | осторожно 63% |
| 740 | 08.08 | 00:32 | ENAUSDT | LONG | SL_clean | осторожно 62% |
| 739 | 07.08 | 23:03 | NEARUSDT | SHORT | Sideways | осторожно 75% |
| 738 | 07.08 | 18:38 | BEATUSDT | SHORT | TP_clean | осторожно 69% |
| 737 | 07.08 | 18:05 | CLUSDT | LONG | Sideways | осторожно 62% |
| 736 | 07.08 | 17:31 | HOODUSDT | SHORT | TP_clean | осторожно 71% |
| 735 | 07.08 | 16:34 | HYPERUSDT | LONG | TP_clean | осторожно 61% |
| 734 | 07.08 | 14:38 | CLUSDT | SHORT | Sideways | осторожно 81% |
| 733 | 07.08 | 14:08 | INJUSDT | SHORT | TP_clean | осторожно 61% |
| 732 | 07.08 | 11:01 | XAIUSDT | LONG | TP_clean | осторожно 61% |
| 731 | 07.08 | 10:34 | NEARUSDT | LONG | SL_clean | осторожно 60% |
| 730 | 07.08 | 06:34 | LITEUSDT | LONG | TP_clean | осторожно 63% |
| 729 | 07.08 | 02:33 | SKHYUSDT | SHORT | TP_clean | осторожно 64% |
| 728 | 06.08 | 23:10 | SNXXUSDT | SHORT | SL_clean | осторожно 69% |
| 727 | 06.08 | 20:30 | ACEUSDT | LONG | TP_clean | осторожно 62% |
| 726 | 06.08 | 18:34 | BEATUSDT | SHORT | SL_clean | осторожно 73% |
| 725 | 06.08 | 18:31 | VANRYUSDT | LONG | SL_clean | осторожно 69% |
| 724 | 06.08 | 09:36 | SKRUSDT | LONG | TP_clean | входить 87% |
| 723 | 06.08 | 07:09 | KITEUSDT | LONG | TP_clean | осторожно 61% |
| 722 | 06.08 | 01:08 | KORUUSDT | LONG | TP_clean | осторожно 63% |
| 721 | 06.08 | 00:35 | EPICUSDT | SHORT | TP_clean | осторожно 68% |
| 720 | 05.08 | 23:02 | HOMEUSDT | LONG | SL_clean | осторожно 60% |
| 719 | 05.08 | 22:31 | MMTUSDT | LONG | TP_clean | осторожно 62% |
| 718 | 05.08 | 21:40 | CRCLUSDT | LONG | SL_clean | осторожно 68% |
| 717 | 05.08 | 20:30 | CYSUSDT | LONG | TP_clean | осторожно 72% |
| 716 | 05.08 | 19:41 | XMRUSDT | SHORT | SL_clean | осторожно 60% |
| 715 | 05.08 | 19:05 | SAMSUNGUSDT | LONG | SL_clean | осторожно 65% |
| 714 | 05.08 | 18:34 | DEXEUSDT | LONG | Sideways | осторожно 62% |
| 713 | 05.08 | 17:03 | VVVUSDT | SHORT | SL_clean | осторожно 62% |
| 712 | 05.08 | 12:38 | SKHYNIXUSDT | LONG | TP_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-12 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-11 06:30 UTC
- mmscan-snapshot: next run 2026-08-11 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
