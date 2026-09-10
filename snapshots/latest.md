# MM Scan Shadow Snapshot
Generated: 2026-09-10T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 698.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-10T04:40:51+0000 (#1064 SOXLUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-09T06:00:01Z → 2026-09-10T06:00:01Z)
- New signals: 12 (LONG 5 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 698.2h, restarts: 0
- Last closer: 2026-09-10T03:00:21Z
- Last backfill: 2026-09-10T05:30:02Z
- Anomalies: none

## Health 7d (window: 2026-09-03T06:00:01Z → 2026-09-10T06:00:01Z)
- New signals: 54 (~7.7/day)
- Closed: 42 (TP 25, SL 12, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 12
- TP rate 7d: 67.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1064
- Closed: 1052 (TP_clean 534, SL_clean 363, SL→reverse 0, Sideways 155, N/A 0)
- Ongoing (<24h): 12
- TP rate: 59.5% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1064 | 10.09 | 07:40 | SOXLUSDT | LONG | ongoing | осторожно 66% |
| 1063 | 10.09 | 06:39 | POLUSDT | LONG | ongoing | осторожно 63% |
| 1062 | 10.09 | 04:32 | DEXEUSDT | SHORT | ongoing | осторожно 69% |
| 1061 | 10.09 | 04:04 | SNXXUSDT | SHORT | ongoing | осторожно 60% |
| 1060 | 10.09 | 02:34 | SKHYUSDT | LONG | ongoing | осторожно 63% |
| 1059 | 10.09 | 01:37 | DELLUSDT | SHORT | ongoing | осторожно 65% |
| 1058 | 09.09 | 20:32 | CRDOUSDT | SHORT | ongoing | осторожно 61% |
| 1057 | 09.09 | 19:06 | AVGOUSDT | SHORT | ongoing | осторожно 60% |
| 1056 | 09.09 | 15:00 | KATUSDT | LONG | ongoing | осторожно 83% |
| 1055 | 09.09 | 11:33 | INJUSDT | LONG | ongoing | осторожно 70% |
| 1054 | 09.09 | 10:31 | XANUSDT | SHORT | ongoing | осторожно 61% |
| 1053 | 09.09 | 09:07 | ICPUSDT | SHORT | ongoing | осторожно 70% |
| 1052 | 09.09 | 05:01 | MIRAUSDT | LONG | TP_clean | осторожно 61% |
| 1051 | 09.09 | 01:31 | SKRUSDT | LONG | TP_clean | осторожно 60% |
| 1050 | 08.09 | 23:09 | POLUSDT | LONG | TP_clean | осторожно 61% |
| 1049 | 08.09 | 18:04 | DOODUSDT | SHORT | TP_clean | входить 90% |
| 1048 | 08.09 | 14:37 | HBARUSDT | SHORT | Sideways | осторожно 67% |
| 1047 | 08.09 | 14:31 | TUTUSDT | LONG | SL_clean | осторожно 64% |
| 1046 | 08.09 | 12:30 | SOPHUSDT | LONG | TP_clean | входить 90% |
| 1045 | 08.09 | 12:13 | ASTERUSDT | SHORT | TP_clean | осторожно 64% |
| 1044 | 08.09 | 09:03 | CSOPSKHYNIX2LUSDT | LONG | TP_clean | осторожно 63% |
| 1043 | 08.09 | 07:32 | WLDUSDT | LONG | TP_clean | осторожно 77% |
| 1042 | 08.09 | 06:04 | HOODUSDT | SHORT | TP_clean | осторожно 65% |
| 1041 | 08.09 | 00:10 | APRUSDT | SHORT | TP_clean | осторожно 70% |
| 1040 | 07.09 | 22:08 | SOXSUSDT | SHORT | SL_clean | осторожно 60% |
| 1039 | 07.09 | 14:01 | AKEUSDT | SHORT | SL_clean | осторожно 66% |
| 1038 | 07.09 | 14:01 | FIDAUSDT | LONG | TP_clean | осторожно 83% |
| 1037 | 07.09 | 12:34 | MARSCOINUSDT | SHORT | TP_clean | входить 90% |
| 1036 | 07.09 | 02:32 | LAUSDT | LONG | SL_clean | осторожно 71% |
| 1035 | 07.09 | 00:07 | ARUSDT | LONG | TP_clean | осторожно 64% |
| 1034 | 07.09 | 00:01 | ZENUSDT | LONG | SL_clean | осторожно 65% |
| 1033 | 06.09 | 18:02 | AKEUSDT | LONG | TP_clean | входить 82% |
| 1032 | 06.09 | 17:04 | ORCAUSDT | LONG | TP_clean | осторожно 61% |
| 1031 | 06.09 | 10:05 | VVVUSDT | SHORT | SL_clean | осторожно 62% |
| 1030 | 06.09 | 09:31 | ETHFIUSDT | SHORT | TP_clean | осторожно 60% |
| 1029 | 06.09 | 07:36 | PENDLEUSDT | LONG | TP_clean | осторожно 69% |
| 1028 | 05.09 | 23:36 | VELVETUSDT | SHORT | TP_clean | осторожно 63% |
| 1027 | 05.09 | 23:35 | 1000PEPEUSDT | LONG | Sideways | осторожно 60% |
| 1026 | 05.09 | 18:04 | SPXUSDT | SHORT | SL_clean | осторожно 61% |
| 1025 | 05.09 | 14:01 | FLOCKUSDT | LONG | TP_clean | входить 81% |
| 1024 | 05.09 | 12:32 | COTIUSDT | LONG | TP_clean | осторожно 60% |
| 1023 | 05.09 | 03:36 | XRPUSDT | SHORT | Sideways | осторожно 62% |
| 1022 | 05.09 | 03:08 | ETHUSDT | SHORT | Sideways | осторожно 61% |
| 1021 | 05.09 | 01:37 | RENDERUSDT | SHORT | SL_clean | осторожно 71% |
| 1020 | 04.09 | 21:09 | WLFIUSDT | SHORT | Sideways | осторожно 60% |
| 1019 | 04.09 | 20:05 | DOTUSDT | SHORT | SL_clean | осторожно 60% |
| 1018 | 04.09 | 19:04 | COTIUSDT | LONG | TP_clean | осторожно 76% |
| 1017 | 04.09 | 15:32 | ASTERUSDT | SHORT | SL_clean | осторожно 70% |
| 1016 | 04.09 | 13:01 | BICOUSDT | LONG | TP_clean | осторожно 71% |
| 1015 | 04.09 | 12:38 | UAIUSDT | SHORT | SL_clean | осторожно 73% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-11 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-10 06:30 UTC
- mmscan-snapshot: next run 2026-09-10 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
