# MM Scan Shadow Snapshot
Generated: 2026-06-18T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 141.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-18T08:04:30+0000 (#90 JTOUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-17T12:00:01Z → 2026-06-18T12:00:01Z)
- New signals: 10 (LONG 2 / SHORT 8)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 141.7h, restarts: 0
- Last closer: 2026-06-18T03:00:27Z
- Last backfill: 2026-06-18T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 5

## Health 7d (window: 2026-06-11T12:00:01Z → 2026-06-18T12:00:01Z)
- New signals: 56 (~8.0/day)
- Closed: 41 (TP 15, SL 22, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 15
- TP rate 7d: 40.5%
- Listener uptime 7d: 84.3% (continuous since unit start)

## Shadow Journal Live
- Total signals: 90
- Closed: 75 (TP_clean 35, SL_clean 33, SL→reverse 0, Sideways 7, N/A 0)
- Ongoing (<24h): 15
- TP rate: 51.5% decided (TP/(TP+SL)) · 46.7% pointwise (excl N/A)

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
| 90 | 18.06 | 11:04 | JTOUSDT | SHORT | ongoing | осторожно 86% |
| 89 | 18.06 | 10:07 | RIVERUSDT | SHORT | ongoing | осторожно 71% |
| 88 | 18.06 | 07:03 | XLMUSDT | LONG | ongoing | осторожно 64% |
| 87 | 18.06 | 07:03 | BABYUSDT | SHORT | ongoing | осторожно 65% |
| 86 | 18.06 | 04:37 | DEXEUSDT | SHORT | ongoing | осторожно 63% |
| 85 | 18.06 | 00:09 | BABYUSDT | SHORT | ongoing | осторожно 73% |
| 84 | 18.06 | 00:08 | VVVUSDT | SHORT | ongoing | осторожно 81% |
| 83 | 17.06 | 19:04 | AXTIUSDT | SHORT | ongoing | осторожно 70% |
| 82 | 17.06 | 19:02 | BASEDUSDT | LONG | ongoing | осторожно 68% |
| 81 | 17.06 | 15:36 | SIRENUSDT | SHORT | ongoing | входить 80% |
| 80 | 17.06 | 11:34 | HOMEUSDT | LONG | ongoing | осторожно 65% |
| 79 | 17.06 | 11:32 | FARTCOINUSDT | SHORT | ongoing | осторожно 66% |
| 78 | 17.06 | 10:05 | CRCLUSDT | SHORT | ongoing | осторожно 65% |
| 77 | 17.06 | 07:07 | ETHUSDT | LONG | ongoing | осторожно 62% |
| 76 | 17.06 | 07:02 | WLDUSDT | LONG | ongoing | осторожно 61% |
| 75 | 16.06 | 20:10 | SPCXUSDT | LONG | SL_clean | осторожно 63% |
| 74 | 16.06 | 19:37 | LITUSDT | SHORT | SL_clean | осторожно 62% |
| 73 | 16.06 | 18:00 | PORTALUSDT | LONG | SL_clean | осторожно 74% |
| 72 | 16.06 | 13:33 | SEIUSDT | LONG | SL_clean | осторожно 73% |
| 71 | 16.06 | 13:07 | ENAUSDT | LONG | SL_clean | осторожно 60% |
| 70 | 16.06 | 10:08 | SPXUSDT | LONG | TP_clean | осторожно 66% |
| 69 | 16.06 | 07:31 | VELVETUSDT | SHORT | SL_clean | осторожно 60% |
| 68 | 16.06 | 06:33 | MRVLUSDT | LONG | TP_clean | осторожно 60% |
| 67 | 15.06 | 21:13 | IOUSDT | SHORT | TP_clean | осторожно 60% |
| 66 | 15.06 | 19:32 | CHIPUSDT | LONG | TP_clean | осторожно 61% |
| 65 | 15.06 | 09:02 | ZKCUSDT | LONG | SL_clean | осторожно 62% |
| 64 | 15.06 | 08:33 | HMSTRUSDT | SHORT | SL_clean | осторожно 65% |
| 63 | 15.06 | 04:33 | BIOUSDT | LONG | TP_clean | осторожно 61% |
| 62 | 15.06 | 03:08 | XPLUSDT | LONG | TP_clean | осторожно 64% |
| 61 | 14.06 | 21:42 | STGUSDT | SHORT | TP_clean | входить 90% |
| 60 | 14.06 | 17:01 | MIRAUSDT | LONG | SL_clean | осторожно 73% |
| 59 | 14.06 | 15:31 | SKRUSDT | LONG | TP_clean | осторожно 63% |
| 58 | 14.06 | 11:02 | ORCAUSDT | SHORT | Sideways | осторожно 65% |
| 57 | 14.06 | 09:05 | ONDOUSDT | SHORT | TP_clean | осторожно 67% |
| 56 | 14.06 | 08:06 | SEIUSDT | SHORT | Sideways | осторожно 68% |
| 55 | 14.06 | 08:04 | ALLOUSDT | SHORT | TP_clean | осторожно 68% |
| 54 | 14.06 | 08:00 | CLOUSDT | SHORT | SL_clean | осторожно 72% |
| 53 | 14.06 | 07:33 | ZROUSDT | SHORT | SL_clean | осторожно 65% |
| 52 | 14.06 | 07:01 | ZKPUSDT | LONG | TP_clean | осторожно 66% |
| 51 | 14.06 | 06:03 | MEGAUSDT | LONG | SL_clean | осторожно 63% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-06-19 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-18 12:30 UTC
- mmscan-snapshot: next run 2026-06-18 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
