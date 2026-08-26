# MM Scan Shadow Snapshot
Generated: 2026-08-26T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 338.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-08-26T04:06:03+0000 (#915 MVLLUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-08-25T06:00:01Z → 2026-08-26T06:00:01Z)
- New signals: 17 (LONG 9 / SHORT 8)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 338.2h, restarts: 0
- Last closer: 2026-08-26T03:00:14Z
- Last backfill: 2026-08-26T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 3

## Health 7d (window: 2026-08-19T06:00:01Z → 2026-08-26T06:00:01Z)
- New signals: 78 (~11.1/day)
- Closed: 58 (TP 32, SL 19, SL→rev 0, Sideways 7, N/A 0)
- Ongoing: 20
- TP rate 7d: 62.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 915
- Closed: 895 (TP_clean 461, SL_clean 303, SL→reverse 0, Sideways 131, N/A 0)
- Ongoing (<24h): 20
- TP rate: 60.3% decided (TP/(TP+SL)) · 51.5% pointwise (excl N/A)

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
| 915 | 26.08 | 07:06 | MVLLUSDT | LONG | ongoing | осторожно 60% |
| 914 | 26.08 | 06:39 | DOSUSDT | SHORT | ongoing | осторожно 66% |
| 913 | 26.08 | 02:37 | STORJUSDT | LONG | ongoing | осторожно 69% |
| 912 | 26.08 | 02:03 | JASMYUSDT | LONG | ongoing | осторожно 64% |
| 911 | 26.08 | 02:00 | BMTUSDT | LONG | ongoing | осторожно 61% |
| 910 | 25.08 | 23:08 | ETHUSDT | SHORT | ongoing | осторожно 62% |
| 909 | 25.08 | 23:01 | STXUSDT | LONG | ongoing | осторожно 64% |
| 908 | 25.08 | 21:39 | CLUSDT | SHORT | ongoing | осторожно 73% |
| 907 | 25.08 | 21:07 | TACUSDT | LONG | ongoing | осторожно 65% |
| 906 | 25.08 | 20:02 | ACEUSDT | SHORT | ongoing | осторожно 66% |
| 905 | 25.08 | 19:10 | CBRSUSDT | SHORT | ongoing | осторожно 64% |
| 904 | 25.08 | 19:10 | AXTIUSDT | SHORT | ongoing | осторожно 62% |
| 903 | 25.08 | 19:04 | SPKUSDT | SHORT | ongoing | осторожно 71% |
| 902 | 25.08 | 18:32 | REUSDT | LONG | ongoing | осторожно 62% |
| 901 | 25.08 | 16:34 | BABAUSDT | LONG | ongoing | осторожно 71% |
| 900 | 25.08 | 14:36 | LITUSDT | LONG | ongoing | осторожно 67% |
| 899 | 25.08 | 14:03 | MONUSDT | SHORT | ongoing | осторожно 62% |
| 898 | 25.08 | 08:09 | ASTERUSDT | LONG | ongoing | осторожно 62% |
| 897 | 25.08 | 08:01 | XRPUSDT | LONG | ongoing | осторожно 64% |
| 896 | 25.08 | 06:06 | CBRSUSDT | SHORT | ongoing | осторожно 65% |
| 895 | 25.08 | 01:01 | COTIUSDT | LONG | TP_clean | осторожно 61% |
| 894 | 24.08 | 19:01 | SUPERUSDT | LONG | SL_clean | входить 82% |
| 893 | 24.08 | 13:03 | HEMIUSDT | SHORT | TP_clean | осторожно 64% |
| 892 | 24.08 | 09:37 | GRAMUSDT | SHORT | Sideways | осторожно 61% |
| 891 | 24.08 | 03:40 | SKHYNIXUSDT | SHORT | TP_clean | осторожно 64% |
| 890 | 24.08 | 03:31 | ONTUSDT | LONG | TP_clean | осторожно 66% |
| 889 | 24.08 | 02:30 | SPKUSDT | LONG | TP_clean | осторожно 74% |
| 888 | 24.08 | 00:12 | TACUSDT | SHORT | TP_clean | осторожно 78% |
| 887 | 23.08 | 23:32 | 1000RATSUSDT | SHORT | TP_clean | входить 80% |
| 886 | 23.08 | 23:01 | COTIUSDT | LONG | TP_clean | осторожно 61% |
| 885 | 23.08 | 16:08 | ZECUSDT | LONG | TP_clean | осторожно 70% |
| 884 | 23.08 | 13:07 | DOGEUSDT | LONG | TP_clean | осторожно 67% |
| 883 | 23.08 | 09:03 | PYTHUSDT | LONG | TP_clean | осторожно 77% |
| 882 | 23.08 | 05:32 | BICOUSDT | LONG | SL_clean | осторожно 63% |
| 881 | 23.08 | 04:04 | POWRUSDT | LONG | SL_clean | осторожно 71% |
| 880 | 23.08 | 04:01 | GASUSDT | LONG | SL_clean | осторожно 63% |
| 879 | 23.08 | 00:03 | PRLUSDT | SHORT | TP_clean | осторожно 73% |
| 878 | 22.08 | 23:07 | HYPEUSDT | LONG | Sideways | осторожно 64% |
| 877 | 22.08 | 22:42 | AAVEUSDT | LONG | SL_clean | осторожно 62% |
| 876 | 22.08 | 19:30 | USELESSUSDT | LONG | SL_clean | осторожно 65% |
| 875 | 22.08 | 18:04 | LITUSDT | LONG | TP_clean | осторожно 63% |
| 874 | 22.08 | 17:09 | AXTIUSDT | SHORT | Sideways | осторожно 63% |
| 873 | 22.08 | 16:31 | HEIUSDT | SHORT | TP_clean | осторожно 61% |
| 872 | 22.08 | 08:34 | BMNRUSDT | LONG | Sideways | осторожно 61% |
| 871 | 22.08 | 03:37 | SKHYNIXUSDT | SHORT | Sideways | осторожно 73% |
| 870 | 22.08 | 01:09 | RKLBUSDT | SHORT | TP_clean | осторожно 60% |
| 869 | 21.08 | 17:38 | GRVTUSDT | SHORT | SL_clean | осторожно 65% |
| 868 | 21.08 | 16:08 | SCRTUSDT | SHORT | SL_clean | осторожно 72% |
| 867 | 21.08 | 15:11 | LITUSDT | SHORT | SL_clean | осторожно 60% |
| 866 | 21.08 | 11:00 | CXMTUSDT | SHORT | Sideways | входить 81% |

## Cron jobs
- mmscan-daily-closer: next run 2026-08-27 03:00 UTC
- mmscan-hourly-backfill: next run 2026-08-26 06:30 UTC
- mmscan-snapshot: next run 2026-08-26 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
