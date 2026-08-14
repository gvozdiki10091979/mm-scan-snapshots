# MM Scan Shadow Snapshot
Generated: 2026-08-14T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 44.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-13T22:37:45+0000 (#794 ESPUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-13T00:00:01Z → 2026-08-14T00:00:01Z)
- New signals: 15 (LONG 10 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 44.2h, restarts: 0
- Last closer: 2026-08-13T03:00:10Z
- Last backfill: 2026-08-13T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 14

## Health 7d (window: 2026-08-07T00:00:01Z → 2026-08-14T00:00:01Z)
- New signals: 65 (~9.3/day)
- Closed: 36 (TP 18, SL 11, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 29
- TP rate 7d: 62.1%
- Listener uptime 7d: 26.3% (continuous since unit start)

## Shadow Journal Live
- Total signals: 794
- Closed: 765 (TP_clean 397, SL_clean 258, SL→reverse 0, Sideways 110, N/A 0)
- Ongoing (<24h): 29
- TP rate: 60.6% decided (TP/(TP+SL)) · 51.9% pointwise (excl N/A)

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
| 794 | 14.08 | 01:37 | ESPUSDT | SHORT | ongoing | осторожно 62% |
| 793 | 14.08 | 01:36 | SMCIUSDT | LONG | ongoing | осторожно 70% |
| 792 | 14.08 | 01:34 | NBISUSDT | LONG | ongoing | осторожно 66% |
| 791 | 13.08 | 19:02 | DOSUSDT | SHORT | ongoing | входить 86% |
| 790 | 13.08 | 17:36 | BICOUSDT | SHORT | ongoing | осторожно 68% |
| 789 | 13.08 | 14:38 | ENAUSDT | SHORT | ongoing | осторожно 62% |
| 788 | 13.08 | 14:35 | SPCXUSDT | LONG | ongoing | осторожно 61% |
| 787 | 13.08 | 14:09 | BRUSDT | LONG | ongoing | осторожно 71% |
| 786 | 13.08 | 12:01 | MINIMAXUSDT | LONG | ongoing | осторожно 61% |
| 785 | 13.08 | 10:34 | ROBOUSDT | LONG | ongoing | осторожно 64% |
| 784 | 13.08 | 08:30 | IDUSDT | LONG | ongoing | осторожно 71% |
| 783 | 13.08 | 05:34 | SAMSUNGUSDT | LONG | ongoing | осторожно 62% |
| 782 | 13.08 | 03:39 | 1000LUNCUSDT | SHORT | ongoing | осторожно 76% |
| 781 | 13.08 | 03:36 | VIRTUALUSDT | LONG | ongoing | осторожно 65% |
| 780 | 13.08 | 03:33 | HOMEUSDT | LONG | ongoing | осторожно 70% |
| 779 | 13.08 | 02:30 | APRUSDT | LONG | ongoing | осторожно 74% |
| 778 | 13.08 | 01:06 | UNIUSDT | SHORT | ongoing | осторожно 62% |
| 777 | 13.08 | 00:34 | KAITOUSDT | SHORT | ongoing | осторожно 61% |
| 776 | 13.08 | 00:31 | EULUSDT | SHORT | ongoing | осторожно 65% |
| 775 | 13.08 | 00:05 | ICPUSDT | SHORT | ongoing | осторожно 73% |
| 774 | 12.08 | 22:36 | ESPUSDT | LONG | ongoing | осторожно 61% |
| 773 | 12.08 | 19:01 | LSKUSDT | LONG | ongoing | осторожно 61% |
| 772 | 12.08 | 18:04 | SQDUSDT | LONG | ongoing | осторожно 63% |
| 771 | 12.08 | 17:05 | ZBTUSDT | SHORT | ongoing | осторожно 65% |
| 770 | 12.08 | 14:07 | APTUSDT | SHORT | ongoing | осторожно 62% |
| 769 | 12.08 | 14:06 | ESPUSDT | SHORT | ongoing | осторожно 79% |
| 768 | 12.08 | 12:06 | AVAXUSDT | SHORT | ongoing | осторожно 62% |
| 767 | 12.08 | 07:07 | EULUSDT | SHORT | ongoing | осторожно 73% |
| 766 | 12.08 | 07:06 | BZUSDT | LONG | ongoing | осторожно 67% |
| 765 | 11.08 | 18:04 | UAIUSDT | LONG | SL_clean | осторожно 61% |
| 764 | 11.08 | 17:04 | ZECUSDT | SHORT | TP_clean | осторожно 72% |
| 763 | 11.08 | 14:04 | AKEUSDT | LONG | TP_clean | осторожно 67% |
| 762 | 11.08 | 14:03 | DELLUSDT | LONG | SL_clean | осторожно 62% |
| 761 | 11.08 | 07:02 | MUUUSDT | LONG | SL_clean | осторожно 64% |
| 760 | 11.08 | 04:32 | MEUSDT | LONG | SL_clean | осторожно 68% |
| 759 | 10.08 | 21:03 | MUUUSDT | SHORT | TP_clean | осторожно 64% |
| 758 | 10.08 | 15:01 | GUNUSDT | LONG | SL_clean | осторожно 61% |
| 757 | 10.08 | 13:34 | RENDERUSDT | SHORT | TP_clean | осторожно 62% |
| 756 | 10.08 | 13:02 | ORDIUSDT | SHORT | TP_clean | осторожно 60% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-08-14 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-14 00:30 UTC
- mmscan-snapshot: next run 2026-08-14 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
