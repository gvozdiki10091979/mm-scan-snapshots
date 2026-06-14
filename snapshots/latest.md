# MM Scan Shadow Snapshot
Generated: 2026-06-14T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 39.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-14T05:06:07+0000 (#56 SEIUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-13T06:00:01Z → 2026-06-14T06:00:01Z)
- New signals: 14 (LONG 7 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 39.7h, restarts: 0
- Last closer: 2026-06-14T03:00:19Z
- Last backfill: 2026-06-14T05:30:02Z
- Anomalies: none

## Health 7d (window: 2026-06-07T06:00:01Z → 2026-06-14T06:00:01Z)
- New signals: 56 (~8.0/day)
- Closed: 42 (TP 22, SL 16, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 14
- TP rate 7d: 57.9%
- Listener uptime 7d: 23.6% (continuous since unit start)

## Shadow Journal Live
- Total signals: 56
- Closed: 42 (TP_clean 22, SL_clean 16, SL→reverse 0, Sideways 4, N/A 0)
- Ongoing (<24h): 14
- TP rate: 57.9% decided (TP/(TP+SL)) · 52.4% pointwise (excl N/A)

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
| 56 | 14.06 | 08:06 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 55 | 14.06 | 08:04 | ALLOUSDT | SHORT | ongoing | осторожно 68% |
| 54 | 14.06 | 08:00 | CLOUSDT | SHORT | ongoing | осторожно 72% |
| 53 | 14.06 | 07:33 | ZROUSDT | SHORT | ongoing | осторожно 65% |
| 52 | 14.06 | 07:01 | ZKPUSDT | LONG | ongoing | осторожно 66% |
| 51 | 14.06 | 06:03 | MEGAUSDT | LONG | ongoing | осторожно 63% |
| 50 | 14.06 | 03:31 | CHZUSDT | LONG | ongoing | осторожно 68% |
| 49 | 14.06 | 00:37 | ORCAUSDT | LONG | ongoing | осторожно 60% |
| 48 | 13.06 | 23:11 | BILLUSDT | SHORT | ongoing | осторожно 64% |
| 47 | 13.06 | 20:03 | BABYUSDT | LONG | ongoing | осторожно 65% |
| 46 | 13.06 | 17:06 | RKLBUSDT | SHORT | ongoing | входить 90% |
| 45 | 13.06 | 17:03 | AIOUSDT | SHORT | ongoing | входить 83% |
| 44 | 13.06 | 10:34 | CHZUSDT | LONG | ongoing | осторожно 69% |
| 43 | 13.06 | 10:03 | AXLUSDT | LONG | ongoing | осторожно 61% |
| 42 | 13.06 | 01:05 | SOXLUSDT | LONG | TP_clean | осторожно 78% |
| 41 | 12.06 | 15:04 | TRUMPUSDT | LONG | SL_clean | осторожно 62% |
| 40 | 12.06 | 14:01 | SOXLUSDT | LONG | SL_clean | осторожно 66% |
| 39 | 12.06 | 06:01 | CCUSDT | LONG | Sideways | осторожно 64% |
| 38 | 12.06 | 00:31 | IOUSDT | LONG | TP_clean | осторожно 66% |
| 37 | 12.06 | 00:01 | IDUSDT | LONG | SL_clean | осторожно 61% |
| 36 | 11.06 | 17:02 | HOMEUSDT | SHORT | SL_clean | осторожно 64% |
| 35 | 11.06 | 15:38 | CHIPUSDT | SHORT | SL_clean | осторожно 62% |
| 34 | 11.06 | 12:31 | AIOUSDT | LONG | SL_clean | осторожно 77% |
| 33 | 11.06 | 08:07 | XAUTUSDT | SHORT | SL_clean | осторожно 68% |
| 32 | 11.06 | 07:00 | ALGOUSDT | LONG | Sideways | осторожно 64% |
| 31 | 11.06 | 04:39 | LAUSDT | SHORT | SL_clean | осторожно 89% |
| 30 | 11.06 | 00:09 | XRPUSDT | SHORT | SL_clean | осторожно 60% |
| 29 | 10.06 | 20:30 | HMSTRUSDT | LONG | TP_clean | осторожно 69% |
| 28 | 10.06 | 20:12 | BZUSDT | LONG | Sideways | осторожно 65% |
| 27 | 10.06 | 20:10 | AAOIUSDT | SHORT | SL_clean | осторожно 66% |
| 26 | 10.06 | 20:02 | SNDKUSDT | LONG | TP_clean | осторожно 76% |
| 25 | 10.06 | 18:01 | BABYUSDT | LONG | SL_clean | осторожно 61% |
| 24 | 10.06 | 15:32 | HOMEUSDT | LONG | TP_clean | осторожно 67% |
| 23 | 10.06 | 14:34 | INTCUSDT | SHORT | SL_clean | осторожно 64% |
| 22 | 10.06 | 14:11 | XRPUSDT | SHORT | Sideways | осторожно 61% |
| 21 | 10.06 | 11:39 | BLESSUSDT | SHORT | TP_clean | входить 90% |
| 20 | 10.06 | 07:02 | RUNEUSDT | LONG | TP_clean | осторожно 61% |
| 19 | 10.06 | 06:09 | XPLUSDT | SHORT | TP_clean | осторожно 65% |
| 18 | 10.06 | 04:36 | CLOUSDT | SHORT | TP_clean | осторожно 60% |
| 17 | 10.06 | 03:03 | WLDUSDT | LONG | SL_clean | осторожно 61% |
| 16 | 10.06 | 02:07 | MONUSDT | SHORT | TP_clean | осторожно 66% |
| 15 | 10.06 | 01:36 | NBISUSDT | SHORT | TP_clean | осторожно 62% |
| 14 | 09.06 | 23:06 | MEUSDT | LONG | TP_clean | осторожно 62% |
| 13 | 09.06 | 23:01 | SAHARAUSDT | SHORT | TP_clean | входить 90% |
| 12 | 09.06 | 21:03 | EDENUSDT | SHORT | TP_clean | осторожно 64% |
| 11 | 09.06 | 20:03 | MOVEUSDT | LONG | TP_clean | входить 89% |
| 10 | 08.06 | 18:30 | SIRENUSDT | LONG | TP_clean | осторожно 64% |
| 9 | 08.06 | 21:01 | BEATUSDT | LONG | TP_clean | осторожно 63% |
| 8 | 08.06 | 21:35 | ZESTUSDT | SHORT | TP_clean | осторожно 60% |
| 7 | 09.06 | 01:31 | APRUSDT | SHORT | SL_clean | входить 85% |

## Cron jobs
- mmscan-daily-closer: next run 2026-06-15 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-14 06:30 UTC
- mmscan-snapshot: next run 2026-06-14 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
