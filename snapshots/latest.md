# MM Scan Shadow Snapshot
Generated: 2026-08-27T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 368.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-27T11:08:22+0000 (#938 SQQQUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-26T12:00:01Z → 2026-08-27T12:00:01Z)
- New signals: 17 (LONG 7 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 368.2h, restarts: 0
- Last closer: 2026-08-27T03:00:34Z
- Last backfill: 2026-08-27T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 8

## Health 7d (window: 2026-08-20T12:00:01Z → 2026-08-27T12:00:01Z)
- New signals: 85 (~12.1/day)
- Closed: 60 (TP 35, SL 14, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 25
- TP rate 7d: 71.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 938
- Closed: 913 (TP_clean 471, SL_clean 307, SL→reverse 0, Sideways 135, N/A 0)
- Ongoing (<24h): 25
- TP rate: 60.5% decided (TP/(TP+SL)) · 51.6% pointwise (excl N/A)

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
| 938 | 27.08 | 14:08 | SQQQUSDT | SHORT | ongoing | осторожно 62% |
| 937 | 27.08 | 12:35 | ZHIPUUSDT | LONG | ongoing | осторожно 61% |
| 936 | 27.08 | 12:02 | KITEUSDT | LONG | ongoing | осторожно 65% |
| 935 | 27.08 | 11:31 | RUNEUSDT | LONG | ongoing | осторожно 63% |
| 934 | 27.08 | 09:04 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 67% |
| 933 | 27.08 | 09:03 | ARBUSDT | SHORT | ongoing | осторожно 68% |
| 932 | 27.08 | 08:35 | BICOUSDT | LONG | ongoing | осторожно 61% |
| 931 | 27.08 | 07:08 | HEMIUSDT | SHORT | ongoing | осторожно 65% |
| 930 | 27.08 | 04:03 | GASUSDT | LONG | ongoing | осторожно 67% |
| 929 | 26.08 | 22:10 | BCHUSDT | SHORT | ongoing | осторожно 78% |
| 928 | 26.08 | 21:40 | ARBUSDT | SHORT | ongoing | осторожно 62% |
| 927 | 26.08 | 21:34 | MUUUSDT | LONG | ongoing | осторожно 66% |
| 926 | 26.08 | 20:03 | BOMEUSDT | SHORT | ongoing | осторожно 72% |
| 925 | 26.08 | 18:35 | INJUSDT | SHORT | ongoing | осторожно 64% |
| 924 | 26.08 | 16:03 | GRVTUSDT | SHORT | ongoing | осторожно 68% |
| 923 | 26.08 | 15:37 | BMNRUSDT | SHORT | ongoing | осторожно 65% |
| 922 | 26.08 | 15:08 | 1000PEPEUSDT | SHORT | ongoing | осторожно 62% |
| 921 | 26.08 | 13:32 | PEOPLEUSDT | SHORT | ongoing | осторожно 71% |
| 920 | 26.08 | 11:36 | MONUSDT | SHORT | ongoing | осторожно 61% |
| 919 | 26.08 | 11:06 | INJUSDT | SHORT | ongoing | осторожно 68% |
| 918 | 26.08 | 10:34 | MOVEUSDT | LONG | ongoing | осторожно 66% |
| 917 | 26.08 | 09:39 | MRVLUSDT | LONG | ongoing | осторожно 63% |
| 916 | 26.08 | 09:35 | ETHFIUSDT | SHORT | ongoing | осторожно 75% |
| 915 | 26.08 | 07:06 | MVLLUSDT | LONG | ongoing | осторожно 60% |
| 914 | 26.08 | 06:39 | DOSUSDT | SHORT | ongoing | осторожно 66% |
| 913 | 26.08 | 02:37 | STORJUSDT | LONG | SL_clean | осторожно 69% |
| 912 | 26.08 | 02:03 | JASMYUSDT | LONG | SL_clean | осторожно 64% |
| 911 | 26.08 | 02:00 | BMTUSDT | LONG | SL_clean | осторожно 61% |
| 910 | 25.08 | 23:08 | ETHUSDT | SHORT | Sideways | осторожно 62% |
| 909 | 25.08 | 23:01 | STXUSDT | LONG | TP_clean | осторожно 64% |
| 908 | 25.08 | 21:39 | CLUSDT | SHORT | TP_clean | осторожно 73% |
| 907 | 25.08 | 21:07 | TACUSDT | LONG | TP_clean | осторожно 65% |
| 906 | 25.08 | 20:02 | ACEUSDT | SHORT | TP_clean | осторожно 66% |
| 905 | 25.08 | 19:10 | CBRSUSDT | SHORT | TP_clean | осторожно 64% |
| 904 | 25.08 | 19:10 | AXTIUSDT | SHORT | TP_clean | осторожно 62% |
| 903 | 25.08 | 19:04 | SPKUSDT | SHORT | TP_clean | осторожно 71% |
| 902 | 25.08 | 18:32 | REUSDT | LONG | TP_clean | осторожно 62% |
| 901 | 25.08 | 16:34 | BABAUSDT | LONG | Sideways | осторожно 71% |
| 900 | 25.08 | 14:36 | LITUSDT | LONG | TP_clean | осторожно 67% |
| 899 | 25.08 | 14:03 | MONUSDT | SHORT | TP_clean | осторожно 62% |
| 898 | 25.08 | 08:09 | ASTERUSDT | LONG | Sideways | осторожно 62% |
| 897 | 25.08 | 08:01 | XRPUSDT | LONG | SL_clean | осторожно 64% |
| 896 | 25.08 | 06:06 | CBRSUSDT | SHORT | Sideways | осторожно 65% |
| 895 | 25.08 | 01:01 | COTIUSDT | LONG | TP_clean | осторожно 61% |
| 894 | 24.08 | 19:01 | SUPERUSDT | LONG | SL_clean | входить 82% |
| 893 | 24.08 | 13:03 | HEMIUSDT | SHORT | TP_clean | осторожно 64% |
| 892 | 24.08 | 09:37 | GRAMUSDT | SHORT | Sideways | осторожно 61% |
| 891 | 24.08 | 03:40 | SKHYNIXUSDT | SHORT | TP_clean | осторожно 64% |
| 890 | 24.08 | 03:31 | ONTUSDT | LONG | TP_clean | осторожно 66% |
| 889 | 24.08 | 02:30 | SPKUSDT | LONG | TP_clean | осторожно 74% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-28 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-27 12:30 UTC
- mmscan-snapshot: next run 2026-08-27 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
