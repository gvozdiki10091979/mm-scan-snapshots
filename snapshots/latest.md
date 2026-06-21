# MM Scan Shadow Snapshot
Generated: 2026-06-21T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 201.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-20T20:31:05+0000 (#120 RAREUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-20T00:00:01Z → 2026-06-21T00:00:01Z)
- New signals: 9 (LONG 6 / SHORT 3)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 201.7h, restarts: 0
- Last closer: 2026-06-20T03:00:32Z
- Last backfill: 2026-06-20T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 14

## Health 7d (window: 2026-06-14T00:00:01Z → 2026-06-21T00:00:01Z)
- New signals: 71 (~10.1/day)
- Closed: 48 (TP 24, SL 22, SL→rev 0, Sideways 2, N/A 0)
- Ongoing: 23
- TP rate 7d: 52.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 120
- Closed: 97 (TP_clean 48, SL_clean 42, SL→reverse 0, Sideways 7, N/A 0)
- Ongoing (<24h): 23
- TP rate: 53.3% decided (TP/(TP+SL)) · 49.5% pointwise (excl N/A)

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
| 120 | 20.06 | 23:31 | RAREUSDT | LONG | ongoing | осторожно 77% |
| 119 | 20.06 | 22:07 | SEIUSDT | SHORT | ongoing | осторожно 68% |
| 118 | 20.06 | 18:00 | SANDUSDT | LONG | ongoing | осторожно 77% |
| 117 | 20.06 | 16:33 | AXSUSDT | LONG | ongoing | осторожно 63% |
| 116 | 20.06 | 06:34 | FOLKSUSDT | SHORT | ongoing | осторожно 69% |
| 115 | 20.06 | 05:07 | ALLOUSDT | LONG | ongoing | осторожно 63% |
| 114 | 20.06 | 05:06 | INTCUSDT | LONG | ongoing | осторожно 66% |
| 113 | 20.06 | 04:33 | HUSDT | SHORT | ongoing | осторожно 73% |
| 112 | 20.06 | 04:01 | BICOUSDT | LONG | ongoing | осторожно 75% |
| 111 | 20.06 | 01:08 | CLOUSDT | LONG | ongoing | осторожно 70% |
| 110 | 20.06 | 00:32 | CHZUSDT | SHORT | ongoing | осторожно 70% |
| 109 | 19.06 | 22:39 | PENDLEUSDT | SHORT | ongoing | осторожно 69% |
| 108 | 19.06 | 22:03 | GENIUSUSDT | SHORT | ongoing | осторожно 74% |
| 107 | 19.06 | 21:12 | IBMUSDT | SHORT | ongoing | осторожно 60% |
| 106 | 19.06 | 19:34 | BELUSDT | LONG | ongoing | осторожно 76% |
| 105 | 19.06 | 11:41 | BTWUSDT | SHORT | ongoing | осторожно 74% |
| 104 | 19.06 | 10:10 | XRPUSDT | SHORT | ongoing | осторожно 63% |
| 103 | 19.06 | 10:09 | SOLUSDT | SHORT | ongoing | осторожно 68% |
| 102 | 19.06 | 10:05 | AERGOUSDT | SHORT | ongoing | осторожно 69% |
| 101 | 19.06 | 09:13 | PORTALUSDT | LONG | ongoing | осторожно 75% |
| 100 | 19.06 | 07:31 | INTCUSDT | LONG | ongoing | осторожно 60% |
| 99 | 19.06 | 07:03 | HOMEUSDT | LONG | ongoing | осторожно 69% |
| 98 | 19.06 | 06:09 | SUIUSDT | SHORT | ongoing | осторожно 62% |
| 97 | 19.06 | 05:02 | IDUSDT | LONG | SL_clean | осторожно 67% |
| 96 | 19.06 | 04:01 | BLESSUSDT | SHORT | TP_clean | осторожно 77% |
| 95 | 19.06 | 03:02 | TRUSTUSDT | LONG | TP_clean | осторожно 61% |
| 94 | 18.06 | 23:01 | ALLOUSDT | LONG | TP_clean | осторожно 61% |
| 93 | 18.06 | 22:41 | CRVUSDT | SHORT | TP_clean | осторожно 60% |
| 92 | 18.06 | 21:31 | USELESSUSDT | SHORT | TP_clean | осторожно 69% |
| 91 | 18.06 | 18:00 | VELVETUSDT | SHORT | SL_clean | осторожно 64% |
| 90 | 18.06 | 11:04 | JTOUSDT | SHORT | SL_clean | осторожно 86% |
| 89 | 18.06 | 10:07 | RIVERUSDT | SHORT | TP_clean | осторожно 71% |
| 88 | 18.06 | 07:03 | XLMUSDT | LONG | TP_clean | осторожно 64% |
| 87 | 18.06 | 07:03 | BABYUSDT | SHORT | TP_clean | осторожно 65% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-06-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-21 00:30 UTC
- mmscan-snapshot: next run 2026-06-21 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
