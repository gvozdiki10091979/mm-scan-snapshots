# MM Scan Shadow Snapshot
Generated: 2026-08-31T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 470.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-31T16:30:54+0000 (#974 SNXXUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-30T18:00:01Z → 2026-08-31T18:00:01Z)
- New signals: 15 (LONG 10 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 470.2h, restarts: 0
- Last closer: 2026-08-31T03:00:12Z
- Last backfill: 2026-08-31T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-08-24T18:00:01Z → 2026-08-31T18:00:01Z)
- New signals: 80 (~11.4/day)
- Closed: 60 (TP 28, SL 21, SL→rev 0, Sideways 11, N/A 0)
- Ongoing: 20
- TP rate 7d: 57.1%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 974
- Closed: 954 (TP_clean 488, SL_clean 324, SL→reverse 0, Sideways 142, N/A 0)
- Ongoing (<24h): 20
- TP rate: 60.1% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 974 | 31.08 | 19:30 | SNXXUSDT | LONG | ongoing | осторожно 61% |
| 973 | 31.08 | 17:38 | MAGMAUSDT | SHORT | ongoing | входить 87% |
| 972 | 31.08 | 17:35 | ZKCUSDT | LONG | ongoing | осторожно 60% |
| 971 | 31.08 | 15:07 | DOTUSDT | SHORT | ongoing | осторожно 61% |
| 970 | 31.08 | 15:03 | AXLUSDT | LONG | ongoing | осторожно 67% |
| 969 | 31.08 | 14:43 | HOODUSDT | LONG | ongoing | осторожно 61% |
| 968 | 31.08 | 11:02 | MIRAUSDT | LONG | ongoing | осторожно 62% |
| 967 | 31.08 | 09:04 | CSOPSKHYNIX2LUSDT | LONG | ongoing | осторожно 73% |
| 966 | 31.08 | 07:39 | ROBOUSDT | SHORT | ongoing | осторожно 67% |
| 965 | 31.08 | 05:13 | ICPUSDT | SHORT | ongoing | осторожно 61% |
| 964 | 31.08 | 05:05 | MONUSDT | SHORT | ongoing | осторожно 63% |
| 963 | 31.08 | 03:04 | HOODUSDT | LONG | ongoing | осторожно 81% |
| 962 | 31.08 | 02:31 | SKHYNIXUSDT | LONG | ongoing | осторожно 60% |
| 961 | 31.08 | 00:33 | XPLUSDT | LONG | ongoing | осторожно 65% |
| 960 | 30.08 | 23:06 | ENAUSDT | LONG | ongoing | осторожно 69% |
| 959 | 30.08 | 17:36 | COTIUSDT | LONG | ongoing | осторожно 62% |
| 958 | 30.08 | 15:32 | AUCTIONUSDT | LONG | ongoing | осторожно 73% |
| 957 | 30.08 | 15:01 | ZKCUSDT | LONG | ongoing | входить 85% |
| 956 | 30.08 | 08:06 | ONGUSDT | LONG | ongoing | осторожно 65% |
| 955 | 30.08 | 07:02 | RIVERUSDT | SHORT | ongoing | осторожно 61% |
| 954 | 30.08 | 02:05 | HEIUSDT | SHORT | TP_clean | осторожно 60% |
| 953 | 29.08 | 14:35 | WLFIUSDT | SHORT | Sideways | осторожно 71% |
| 952 | 29.08 | 12:02 | TUTUSDT | SHORT | SL_clean | осторожно 68% |
| 951 | 29.08 | 07:00 | CRVUSDT | SHORT | TP_clean | осторожно 86% |
| 950 | 29.08 | 04:01 | ONGUSDT | SHORT | SL_clean | осторожно 67% |
| 949 | 29.08 | 02:36 | COTIUSDT | LONG | TP_clean | осторожно 61% |
| 948 | 29.08 | 02:04 | RENDERUSDT | SHORT | TP_clean | осторожно 67% |
| 947 | 29.08 | 01:11 | BEUSDT | SHORT | Sideways | осторожно 71% |
| 946 | 28.08 | 17:01 | ONGUSDT | SHORT | TP_clean | осторожно 61% |
| 945 | 28.08 | 11:33 | BICOUSDT | LONG | SL_clean | входить 85% |
| 944 | 28.08 | 08:08 | MINIMAXUSDT | SHORT | TP_clean | осторожно 63% |
| 943 | 28.08 | 06:38 | SNDKUSDT | SHORT | Sideways | осторожно 61% |
| 942 | 28.08 | 05:31 | ONGUSDT | LONG | SL_clean | осторожно 63% |
| 941 | 28.08 | 00:04 | PORTALUSDT | LONG | TP_clean | осторожно 67% |
| 940 | 27.08 | 22:31 | ONTUSDT | LONG | SL_clean | осторожно 61% |
| 939 | 27.08 | 19:06 | MRVLUSDT | SHORT | TP_clean | осторожно 64% |
| 938 | 27.08 | 14:08 | SQQQUSDT | SHORT | Sideways | осторожно 62% |
| 937 | 27.08 | 12:35 | ZHIPUUSDT | LONG | SL_clean | осторожно 61% |
| 936 | 27.08 | 12:02 | KITEUSDT | LONG | TP_clean | осторожно 65% |
| 935 | 27.08 | 11:31 | RUNEUSDT | LONG | SL_clean | осторожно 63% |
| 934 | 27.08 | 09:04 | CSOPSKHYNIX2LUSDT | LONG | SL_clean | осторожно 67% |
| 933 | 27.08 | 09:03 | ARBUSDT | SHORT | Sideways | осторожно 68% |
| 932 | 27.08 | 08:35 | BICOUSDT | LONG | SL_clean | осторожно 61% |
| 931 | 27.08 | 07:08 | HEMIUSDT | SHORT | SL_clean | осторожно 65% |
| 930 | 27.08 | 04:03 | GASUSDT | LONG | TP_clean | осторожно 67% |
| 929 | 26.08 | 22:10 | BCHUSDT | SHORT | SL_clean | осторожно 78% |
| 928 | 26.08 | 21:40 | ARBUSDT | SHORT | SL_clean | осторожно 62% |
| 927 | 26.08 | 21:34 | MUUUSDT | LONG | TP_clean | осторожно 66% |
| 926 | 26.08 | 20:03 | BOMEUSDT | SHORT | SL_clean | осторожно 72% |
| 925 | 26.08 | 18:35 | INJUSDT | SHORT | SL_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-01 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-31 18:30 UTC
- mmscan-snapshot: next run 2026-09-01 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
