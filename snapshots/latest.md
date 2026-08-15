# MM Scan Shadow Snapshot
Generated: 2026-08-15T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 80.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-15T09:39:56+0000 (#808 BMTUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-14T12:00:01Z → 2026-08-15T12:00:01Z)
- New signals: 11 (LONG 6 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 11
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 80.2h, restarts: 0
- Last closer: 2026-08-15T03:00:20Z
- Last backfill: 2026-08-15T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-08-08T12:00:01Z → 2026-08-15T12:00:01Z)
- New signals: 61 (~8.7/day)
- Closed: 47 (TP 24, SL 15, SL→rev 0, Sideways 8, N/A 0)
- Ongoing: 14
- TP rate 7d: 61.5%
- Listener uptime 7d: 47.7% (continuous since unit start)

## Shadow Journal Live
- Total signals: 808
- Closed: 794 (TP_clean 413, SL_clean 265, SL→reverse 0, Sideways 116, N/A 0)
- Ongoing (<24h): 14
- TP rate: 60.9% decided (TP/(TP+SL)) · 52.0% pointwise (excl N/A)

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
| 808 | 15.08 | 12:39 | BMTUSDT | SHORT | ongoing | осторожно 74% |
| 807 | 15.08 | 11:02 | ONGUSDT | LONG | ongoing | осторожно 80% |
| 806 | 15.08 | 11:01 | BTWUSDT | LONG | ongoing | осторожно 69% |
| 805 | 15.08 | 10:01 | 1000BONKUSDT | SHORT | ongoing | осторожно 62% |
| 804 | 15.08 | 09:31 | ALICEUSDT | LONG | ongoing | осторожно 65% |
| 803 | 15.08 | 08:33 | AVAXUSDT | LONG | ongoing | осторожно 60% |
| 802 | 15.08 | 08:08 | CBRSUSDT | SHORT | ongoing | осторожно 60% |
| 801 | 15.08 | 01:34 | STORJUSDT | LONG | ongoing | осторожно 61% |
| 800 | 14.08 | 22:05 | ENAUSDT | SHORT | ongoing | осторожно 72% |
| 799 | 14.08 | 19:34 | HOMEUSDT | LONG | ongoing | осторожно 70% |
| 798 | 14.08 | 19:05 | CRCLUSDT | SHORT | ongoing | осторожно 67% |
| 797 | 14.08 | 10:35 | BSPUSDT | SHORT | ongoing | осторожно 73% |
| 796 | 14.08 | 06:33 | MRVLUSDT | LONG | ongoing | осторожно 69% |
| 795 | 14.08 | 06:11 | NBISUSDT | LONG | ongoing | осторожно 60% |
| 794 | 14.08 | 01:37 | ESPUSDT | SHORT | TP_clean | осторожно 62% |
| 793 | 14.08 | 01:36 | SMCIUSDT | LONG | TP_clean | осторожно 70% |
| 792 | 14.08 | 01:34 | NBISUSDT | LONG | TP_clean | осторожно 66% |
| 791 | 13.08 | 19:02 | DOSUSDT | SHORT | SL_clean | входить 86% |
| 790 | 13.08 | 17:36 | BICOUSDT | SHORT | TP_clean | осторожно 68% |
| 789 | 13.08 | 14:38 | ENAUSDT | SHORT | Sideways | осторожно 62% |
| 788 | 13.08 | 14:35 | SPCXUSDT | LONG | SL_clean | осторожно 61% |
| 787 | 13.08 | 14:09 | BRUSDT | LONG | TP_clean | осторожно 71% |
| 786 | 13.08 | 12:01 | MINIMAXUSDT | LONG | TP_clean | осторожно 61% |
| 785 | 13.08 | 10:34 | ROBOUSDT | LONG | TP_clean | осторожно 64% |
| 784 | 13.08 | 08:30 | IDUSDT | LONG | TP_clean | осторожно 71% |
| 783 | 13.08 | 05:34 | SAMSUNGUSDT | LONG | TP_clean | осторожно 62% |
| 782 | 13.08 | 03:39 | 1000LUNCUSDT | SHORT | Sideways | осторожно 76% |
| 781 | 13.08 | 03:36 | VIRTUALUSDT | LONG | SL_clean | осторожно 65% |
| 780 | 13.08 | 03:33 | HOMEUSDT | LONG | TP_clean | осторожно 70% |
| 779 | 13.08 | 02:30 | APRUSDT | LONG | TP_clean | осторожно 74% |
| 778 | 13.08 | 01:06 | UNIUSDT | SHORT | Sideways | осторожно 62% |
| 777 | 13.08 | 00:34 | KAITOUSDT | SHORT | TP_clean | осторожно 61% |
| 776 | 13.08 | 00:31 | EULUSDT | SHORT | TP_clean | осторожно 65% |
| 775 | 13.08 | 00:05 | ICPUSDT | SHORT | Sideways | осторожно 73% |
| 774 | 12.08 | 22:36 | ESPUSDT | LONG | TP_clean | осторожно 61% |
| 773 | 12.08 | 19:01 | LSKUSDT | LONG | TP_clean | осторожно 61% |
| 772 | 12.08 | 18:04 | SQDUSDT | LONG | SL_clean | осторожно 63% |
| 771 | 12.08 | 17:05 | ZBTUSDT | SHORT | Sideways | осторожно 65% |
| 770 | 12.08 | 14:07 | APTUSDT | SHORT | TP_clean | осторожно 62% |
| 769 | 12.08 | 14:06 | ESPUSDT | SHORT | SL_clean | осторожно 79% |
| 768 | 12.08 | 12:06 | AVAXUSDT | SHORT | SL_clean | осторожно 62% |
| 767 | 12.08 | 07:07 | EULUSDT | SHORT | SL_clean | осторожно 73% |
| 766 | 12.08 | 07:06 | BZUSDT | LONG | Sideways | осторожно 67% |
| 765 | 11.08 | 18:04 | UAIUSDT | LONG | SL_clean | осторожно 61% |
| 764 | 11.08 | 17:04 | ZECUSDT | SHORT | TP_clean | осторожно 72% |
| 763 | 11.08 | 14:04 | AKEUSDT | LONG | TP_clean | осторожно 67% |
| 762 | 11.08 | 14:03 | DELLUSDT | LONG | SL_clean | осторожно 62% |
| 761 | 11.08 | 07:02 | MUUUSDT | LONG | SL_clean | осторожно 64% |
| 760 | 11.08 | 04:32 | MEUSDT | LONG | SL_clean | осторожно 68% |
| 759 | 10.08 | 21:03 | MUUUSDT | SHORT | TP_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-16 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-15 12:30 UTC
- mmscan-snapshot: next run 2026-08-15 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
