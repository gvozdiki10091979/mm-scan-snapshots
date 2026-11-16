# MM Scan Shadow Snapshot
Generated: 2026-11-16T12:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 492.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-16T11:02:11+0000 (#2013 ENAUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-15T12:00:02Z → 2026-11-16T12:00:02Z)
- New signals: 18 (LONG 3 / SHORT 15)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 18
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 492.6h, restarts: 8
- Last closer: 2026-11-16T03:00:50Z
- Last backfill: 2026-11-16T11:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 5

## Health 7d (window: 2026-11-09T12:00:02Z → 2026-11-16T12:00:02Z)
- New signals: 94 (~13.4/day)
- Closed: 71 (TP 38, SL 20, SL→rev 0, Sideways 13, N/A 0)
- Ongoing: 23
- TP rate 7d: 65.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 2013
- Closed: 1990 (TP_clean 1012, SL_clean 698, SL→reverse 0, Sideways 280, N/A 0)
- Ongoing (<24h): 23
- TP rate: 59.2% decided (TP/(TP+SL)) · 50.9% pointwise (excl N/A)

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
| 2013 | 16.11 | 14:02 | ENAUSDT | SHORT | ongoing | осторожно 63% |
| 2012 | 16.11 | 13:33 | SKDDUSDT | LONG | ongoing | осторожно 68% |
| 2011 | 16.11 | 09:06 | WIFUSDT | SHORT | ongoing | осторожно 71% |
| 2010 | 16.11 | 05:07 | UNITREEUSDT | LONG | ongoing | осторожно 77% |
| 2009 | 16.11 | 05:04 | DASHUSDT | SHORT | ongoing | осторожно 62% |
| 2008 | 16.11 | 05:02 | NEARUSDT | SHORT | ongoing | осторожно 62% |
| 2007 | 16.11 | 03:09 | MRVLUSDT | SHORT | ongoing | осторожно 90% |
| 2006 | 16.11 | 01:03 | ZECUSDT | LONG | ongoing | осторожно 66% |
| 2005 | 15.11 | 22:08 | SKYUSDT | SHORT | ongoing | осторожно 62% |
| 2004 | 15.11 | 22:06 | LABUSDT | SHORT | ongoing | осторожно 64% |
| 2003 | 15.11 | 22:06 | XRPUSDT | SHORT | ongoing | осторожно 60% |
| 2002 | 15.11 | 22:00 | KAVAUSDT | SHORT | ongoing | осторожно 76% |
| 2001 | 15.11 | 21:35 | WIFUSDT | SHORT | ongoing | входить 86% |
| 2000 | 15.11 | 17:34 | DOTUSDT | SHORT | ongoing | осторожно 65% |
| 1999 | 15.11 | 17:31 | ERAUSDT | SHORT | ongoing | осторожно 60% |
| 1998 | 15.11 | 16:09 | OPUSDT | SHORT | ongoing | осторожно 66% |
| 1997 | 15.11 | 15:38 | FARTCOINUSDT | SHORT | ongoing | осторожно 68% |
| 1996 | 15.11 | 15:02 | SKYUSDT | SHORT | ongoing | осторожно 63% |
| 1995 | 15.11 | 14:34 | BATUSDT | SHORT | ongoing | осторожно 62% |
| 1994 | 15.11 | 08:38 | AEROUSDT | SHORT | ongoing | осторожно 62% |
| 1993 | 15.11 | 08:38 | ETHUSDT | SHORT | ongoing | осторожно 68% |
| 1992 | 15.11 | 08:07 | LITUSDT | SHORT | ongoing | осторожно 78% |
| 1991 | 15.11 | 07:35 | 1000PEPEUSDT | SHORT | ongoing | осторожно 64% |
| 1990 | 15.11 | 05:39 | HYPEUSDT | SHORT | SL_clean | осторожно 62% |
| 1989 | 15.11 | 05:38 | GRASSUSDT | SHORT | TP_clean | осторожно 68% |
| 1988 | 15.11 | 05:37 | UNIUSDT | SHORT | SL_clean | осторожно 64% |
| 1987 | 15.11 | 04:02 | MSTUUSDT | SHORT | TP_clean | осторожно 63% |
| 1986 | 15.11 | 03:33 | XRPUSDT | SHORT | SL_clean | осторожно 64% |
| 1985 | 14.11 | 22:11 | KORUUSDT | SHORT | TP_clean | осторожно 60% |
| 1984 | 14.11 | 20:08 | CRWVUSDT | SHORT | TP_clean | осторожно 65% |
| 1983 | 14.11 | 20:01 | BARDUSDT | LONG | TP_clean | осторожно 64% |
| 1982 | 14.11 | 19:39 | XAUUSDT | LONG | Sideways | осторожно 60% |
| 1981 | 14.11 | 19:37 | NBISUSDT | SHORT | Sideways | осторожно 61% |
| 1980 | 14.11 | 15:12 | QQQUSDT | SHORT | Sideways | осторожно 60% |
| 1979 | 14.11 | 13:05 | PENGUUSDT | SHORT | TP_clean | осторожно 74% |
| 1978 | 14.11 | 12:09 | INTCUSDT | SHORT | TP_clean | осторожно 68% |
| 1977 | 14.11 | 10:05 | ETCUSDT | SHORT | TP_clean | осторожно 70% |
| 1976 | 14.11 | 09:32 | BARDUSDT | LONG | SL_clean | осторожно 70% |
| 1975 | 14.11 | 08:41 | DRAMUSDT | SHORT | TP_clean | осторожно 78% |
| 1974 | 14.11 | 03:40 | TSMUSDT | SHORT | Sideways | осторожно 63% |
| 1973 | 14.11 | 03:37 | INTCUSDT | SHORT | TP_clean | осторожно 74% |
| 1972 | 14.11 | 03:03 | DRAMUSDT | SHORT | TP_clean | осторожно 68% |
| 1971 | 13.11 | 22:03 | DASHUSDT | LONG | SL_clean | осторожно 66% |
| 1970 | 13.11 | 21:34 | UNIUSDT | SHORT | TP_clean | осторожно 68% |
| 1969 | 13.11 | 19:05 | CYBERUSDT | LONG | SL_clean | осторожно 70% |
| 1968 | 13.11 | 18:34 | CAPUSDT | LONG | TP_clean | осторожно 61% |
| 1967 | 13.11 | 18:04 | ZHIPUUSDT | SHORT | Sideways | осторожно 68% |
| 1966 | 13.11 | 16:03 | MARSCOINUSDT | SHORT | TP_clean | осторожно 61% |
| 1965 | 13.11 | 16:01 | BTWUSDT | SHORT | SL_clean | осторожно 68% |
| 1964 | 13.11 | 12:32 | AVAXUSDT | LONG | TP_clean | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-17 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-16 12:30 UTC
- mmscan-snapshot: next run 2026-11-16 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
