# MM Scan Shadow Snapshot
Generated: 2026-11-18T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 534.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-18T02:02:33+0000 (#2040 VVVUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-17T06:00:01Z → 2026-11-18T06:00:01Z)
- New signals: 14 (LONG 5 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 534.6h, restarts: 8
- Last closer: 2026-11-18T03:00:29Z
- Last backfill: 2026-11-18T05:30:02Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-11-11T06:00:01Z → 2026-11-18T06:00:01Z)
- New signals: 103 (~14.7/day)
- Closed: 85 (TP 46, SL 23, SL→rev 0, Sideways 16, N/A 0)
- Ongoing: 18
- TP rate 7d: 66.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2040
- Closed: 2022 (TP_clean 1031, SL_clean 704, SL→reverse 0, Sideways 287, N/A 0)
- Ongoing (<24h): 18
- TP rate: 59.4% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 2040 | 18.11 | 05:02 | VVVUSDT | SHORT | ongoing | осторожно 62% |
| 2039 | 18.11 | 03:13 | TLMUSDT | LONG | ongoing | осторожно 66% |
| 2038 | 18.11 | 02:01 | SOXSUSDT | LONG | ongoing | осторожно 67% |
| 2037 | 18.11 | 01:32 | HUMAUSDT | LONG | ongoing | осторожно 72% |
| 2036 | 17.11 | 21:39 | MUUSDT | SHORT | ongoing | осторожно 78% |
| 2035 | 17.11 | 20:02 | GLWUSDT | SHORT | ongoing | осторожно 70% |
| 2034 | 17.11 | 19:30 | BLURUSDT | LONG | ongoing | осторожно 61% |
| 2033 | 17.11 | 12:31 | 1000LUNCUSDT | LONG | ongoing | осторожно 67% |
| 2032 | 17.11 | 11:07 | TSLAUSDT | SHORT | ongoing | осторожно 79% |
| 2031 | 17.11 | 10:38 | BTWUSDT | SHORT | ongoing | осторожно 64% |
| 2030 | 17.11 | 09:33 | NIGHTUSDT | SHORT | ongoing | осторожно 65% |
| 2029 | 17.11 | 09:11 | AXTIUSDT | SHORT | ongoing | осторожно 62% |
| 2028 | 17.11 | 09:08 | LITEUSDT | SHORT | ongoing | осторожно 62% |
| 2027 | 17.11 | 09:07 | MUUSDT | SHORT | ongoing | осторожно 74% |
| 2026 | 17.11 | 07:06 | ARMUSDT | SHORT | ongoing | осторожно 76% |
| 2025 | 17.11 | 07:06 | TQQQUSDT | SHORT | ongoing | осторожно 79% |
| 2024 | 17.11 | 07:04 | SNXXUSDT | SHORT | ongoing | осторожно 62% |
| 2023 | 17.11 | 06:34 | BMNRUSDT | LONG | ongoing | осторожно 60% |
| 2022 | 17.11 | 03:31 | LITUSDT | SHORT | TP_clean | осторожно 68% |
| 2021 | 17.11 | 02:35 | PLTRUSDT | SHORT | TP_clean | осторожно 62% |
| 2020 | 17.11 | 02:32 | SKDDUSDT | LONG | SL_clean | осторожно 67% |
| 2019 | 17.11 | 01:32 | ZILUSDT | SHORT | TP_clean | осторожно 79% |
| 2018 | 16.11 | 23:32 | CBRSUSDT | SHORT | TP_clean | осторожно 62% |
| 2017 | 16.11 | 21:33 | SNDKUSDT | SHORT | TP_clean | осторожно 60% |
| 2016 | 16.11 | 21:11 | TQQQUSDT | SHORT | TP_clean | осторожно 79% |
| 2015 | 16.11 | 18:32 | IDOLUSDT | LONG | SL_clean | осторожно 61% |
| 2014 | 16.11 | 17:36 | NIGHTUSDT | SHORT | TP_clean | осторожно 61% |
| 2013 | 16.11 | 14:02 | ENAUSDT | SHORT | TP_clean | осторожно 63% |
| 2012 | 16.11 | 13:33 | SKDDUSDT | LONG | TP_clean | осторожно 68% |
| 2011 | 16.11 | 09:06 | WIFUSDT | SHORT | Sideways | осторожно 71% |
| 2010 | 16.11 | 05:07 | UNITREEUSDT | LONG | TP_clean | осторожно 77% |
| 2009 | 16.11 | 05:04 | DASHUSDT | SHORT | Sideways | осторожно 62% |
| 2008 | 16.11 | 05:02 | NEARUSDT | SHORT | SL_clean | осторожно 62% |
| 2007 | 16.11 | 03:09 | MRVLUSDT | SHORT | TP_clean | осторожно 90% |
| 2006 | 16.11 | 01:03 | ZECUSDT | LONG | SL_clean | осторожно 66% |
| 2005 | 15.11 | 22:08 | SKYUSDT | SHORT | TP_clean | осторожно 62% |
| 2004 | 15.11 | 22:06 | LABUSDT | SHORT | Sideways | осторожно 64% |
| 2003 | 15.11 | 22:06 | XRPUSDT | SHORT | Sideways | осторожно 60% |
| 2002 | 15.11 | 22:00 | KAVAUSDT | SHORT | TP_clean | осторожно 76% |
| 2001 | 15.11 | 21:35 | WIFUSDT | SHORT | Sideways | входить 86% |
| 2000 | 15.11 | 17:34 | DOTUSDT | SHORT | Sideways | осторожно 65% |
| 1999 | 15.11 | 17:31 | ERAUSDT | SHORT | TP_clean | осторожно 60% |
| 1998 | 15.11 | 16:09 | OPUSDT | SHORT | TP_clean | осторожно 66% |
| 1997 | 15.11 | 15:38 | FARTCOINUSDT | SHORT | SL_clean | осторожно 68% |
| 1996 | 15.11 | 15:02 | SKYUSDT | SHORT | TP_clean | осторожно 63% |
| 1995 | 15.11 | 14:34 | BATUSDT | SHORT | SL_clean | осторожно 62% |
| 1994 | 15.11 | 08:38 | AEROUSDT | SHORT | TP_clean | осторожно 62% |
| 1993 | 15.11 | 08:38 | ETHUSDT | SHORT | Sideways | осторожно 68% |
| 1992 | 15.11 | 08:07 | LITUSDT | SHORT | TP_clean | осторожно 78% |
| 1991 | 15.11 | 07:35 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 64% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-19 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-18 06:30 UTC
- mmscan-snapshot: next run 2026-11-18 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
