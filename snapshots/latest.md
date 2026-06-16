# MM Scan Shadow Snapshot
Generated: 2026-06-16T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 81.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-15T18:13:47+0000 (#67 IOUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-15T00:00:01Z → 2026-06-16T00:00:01Z)
- New signals: 6 (LONG 4 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 6
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 81.7h, restarts: 0
- Last closer: 2026-06-15T03:00:23Z
- Last backfill: 2026-06-15T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 11

## Health 7d (window: 2026-06-09T00:00:01Z → 2026-06-16T00:00:01Z)
- New signals: 63 (~9.0/day)
- Closed: 46 (TP 21, SL 20, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 17
- TP rate 7d: 51.2%
- Listener uptime 7d: 48.6% (continuous since unit start)

## Shadow Journal Live
- Total signals: 67
- Closed: 50 (TP_clean 24, SL_clean 21, SL→reverse 0, Sideways 5, N/A 0)
- Ongoing (<24h): 17
- TP rate: 53.3% decided (TP/(TP+SL)) · 48.0% pointwise (excl N/A)

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
| 67 | 15.06 | 21:13 | IOUSDT | SHORT | ongoing | осторожно 60% |
| 66 | 15.06 | 19:32 | CHIPUSDT | LONG | ongoing | осторожно 61% |
| 65 | 15.06 | 09:02 | ZKCUSDT | LONG | ongoing | осторожно 62% |
| 64 | 15.06 | 08:33 | HMSTRUSDT | SHORT | ongoing | осторожно 65% |
| 63 | 15.06 | 04:33 | BIOUSDT | LONG | ongoing | осторожно 61% |
| 62 | 15.06 | 03:08 | XPLUSDT | LONG | ongoing | осторожно 64% |
| 61 | 14.06 | 21:42 | STGUSDT | SHORT | ongoing | входить 90% |
| 60 | 14.06 | 17:01 | MIRAUSDT | LONG | ongoing | осторожно 73% |
| 59 | 14.06 | 15:31 | SKRUSDT | LONG | ongoing | осторожно 63% |
| 58 | 14.06 | 11:02 | ORCAUSDT | SHORT | ongoing | осторожно 65% |
| 57 | 14.06 | 09:05 | ONDOUSDT | SHORT | ongoing | осторожно 67% |
| 56 | 14.06 | 08:06 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 55 | 14.06 | 08:04 | ALLOUSDT | SHORT | ongoing | осторожно 68% |
| 54 | 14.06 | 08:00 | CLOUSDT | SHORT | ongoing | осторожно 72% |
| 53 | 14.06 | 07:33 | ZROUSDT | SHORT | ongoing | осторожно 65% |
| 52 | 14.06 | 07:01 | ZKPUSDT | LONG | ongoing | осторожно 66% |
| 51 | 14.06 | 06:03 | MEGAUSDT | LONG | ongoing | осторожно 63% |
| 50 | 14.06 | 03:31 | CHZUSDT | LONG | SL_clean | осторожно 68% |
| 49 | 14.06 | 00:37 | ORCAUSDT | LONG | SL_clean | осторожно 60% |
| 48 | 13.06 | 23:11 | BILLUSDT | SHORT | SL_clean | осторожно 64% |
| 47 | 13.06 | 20:03 | BABYUSDT | LONG | TP_clean | осторожно 65% |
| 46 | 13.06 | 17:06 | RKLBUSDT | SHORT | SL_clean | входить 90% |
| 45 | 13.06 | 17:03 | AIOUSDT | SHORT | TP_clean | входить 83% |
| 44 | 13.06 | 10:34 | CHZUSDT | LONG | Sideways | осторожно 69% |
| 43 | 13.06 | 10:03 | AXLUSDT | LONG | SL_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-06-16 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-16 00:30 UTC
- mmscan-snapshot: next run 2026-06-16 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
