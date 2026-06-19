# MM Scan Shadow Snapshot
Generated: 2026-06-19T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 165.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-19T08:41:06+0000 (#105 BTWUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-18T12:00:01Z → 2026-06-19T12:00:01Z)
- New signals: 15 (LONG 6 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 165.7h, restarts: 0
- Last closer: 2026-06-19T03:00:38Z
- Last backfill: 2026-06-19T11:30:02Z
- Anomalies: ongoing >24h без закрытия: 4

## Health 7d (window: 2026-06-12T12:00:01Z → 2026-06-19T12:00:01Z)
- New signals: 65 (~9.3/day)
- Closed: 46 (TP 19, SL 24, SL→rev 0, Sideways 3, N/A 0)
- Ongoing: 19
- TP rate 7d: 44.2%
- Listener uptime 7d: 98.6% (continuous since unit start)

## Shadow Journal Live
- Total signals: 105
- Closed: 86 (TP_clean 40, SL_clean 39, SL→reverse 0, Sideways 7, N/A 0)
- Ongoing (<24h): 19
- TP rate: 50.6% decided (TP/(TP+SL)) · 46.5% pointwise (excl N/A)

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
| 105 | 19.06 | 11:41 | BTWUSDT | SHORT | ongoing | осторожно 74% |
| 104 | 19.06 | 10:10 | XRPUSDT | SHORT | ongoing | осторожно 63% |
| 103 | 19.06 | 10:09 | SOLUSDT | SHORT | ongoing | осторожно 68% |
| 102 | 19.06 | 10:05 | AERGOUSDT | SHORT | ongoing | осторожно 69% |
| 101 | 19.06 | 09:13 | PORTALUSDT | LONG | ongoing | осторожно 75% |
| 100 | 19.06 | 07:31 | INTCUSDT | LONG | ongoing | осторожно 60% |
| 99 | 19.06 | 07:03 | HOMEUSDT | LONG | ongoing | осторожно 69% |
| 98 | 19.06 | 06:09 | SUIUSDT | SHORT | ongoing | осторожно 62% |
| 97 | 19.06 | 05:02 | IDUSDT | LONG | ongoing | осторожно 67% |
| 96 | 19.06 | 04:01 | BLESSUSDT | SHORT | ongoing | осторожно 77% |
| 95 | 19.06 | 03:02 | TRUSTUSDT | LONG | ongoing | осторожно 61% |
| 94 | 18.06 | 23:01 | ALLOUSDT | LONG | ongoing | осторожно 61% |
| 93 | 18.06 | 22:41 | CRVUSDT | SHORT | ongoing | осторожно 60% |
| 92 | 18.06 | 21:31 | USELESSUSDT | SHORT | ongoing | осторожно 69% |
| 91 | 18.06 | 18:00 | VELVETUSDT | SHORT | ongoing | осторожно 64% |
| 90 | 18.06 | 11:04 | JTOUSDT | SHORT | ongoing | осторожно 86% |
| 89 | 18.06 | 10:07 | RIVERUSDT | SHORT | ongoing | осторожно 71% |
| 88 | 18.06 | 07:03 | XLMUSDT | LONG | ongoing | осторожно 64% |
| 87 | 18.06 | 07:03 | BABYUSDT | SHORT | ongoing | осторожно 65% |
| 86 | 18.06 | 04:37 | DEXEUSDT | SHORT | TP_clean | осторожно 63% |
| 85 | 18.06 | 00:09 | BABYUSDT | SHORT | TP_clean | осторожно 73% |
| 84 | 18.06 | 00:08 | VVVUSDT | SHORT | TP_clean | осторожно 81% |
| 83 | 17.06 | 19:04 | AXTIUSDT | SHORT | TP_clean | осторожно 70% |
| 82 | 17.06 | 19:02 | BASEDUSDT | LONG | SL_clean | осторожно 68% |
| 81 | 17.06 | 15:36 | SIRENUSDT | SHORT | TP_clean | входить 80% |
| 80 | 17.06 | 11:34 | HOMEUSDT | LONG | SL_clean | осторожно 65% |
| 79 | 17.06 | 11:32 | FARTCOINUSDT | SHORT | SL_clean | осторожно 66% |
| 78 | 17.06 | 10:05 | CRCLUSDT | SHORT | SL_clean | осторожно 65% |
| 77 | 17.06 | 07:07 | ETHUSDT | LONG | SL_clean | осторожно 62% |
| 76 | 17.06 | 07:02 | WLDUSDT | LONG | SL_clean | осторожно 61% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-06-20 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-19 12:30 UTC
- mmscan-snapshot: next run 2026-06-19 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
