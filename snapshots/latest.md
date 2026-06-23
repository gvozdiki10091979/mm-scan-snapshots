# MM Scan Shadow Snapshot
Generated: 2026-06-23T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 957084
- Uptime: 249.7h (active since Fri 2026-06-12 14:15:27 UTC)
- Last signal: 2026-06-22T23:34:20+0000 (#139 EDGEUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-06-22T00:00:01Z → 2026-06-23T00:00:01Z)
- New signals: 10 (LONG 5 / SHORT 5)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 10
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 249.7h, restarts: 0
- Last closer: 2026-06-22T03:00:23Z
- Last backfill: 2026-06-22T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 8

## Health 7d (window: 2026-06-16T00:00:01Z → 2026-06-23T00:00:01Z)
- New signals: 72 (~10.3/day)
- Closed: 54 (TP 29, SL 21, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 18
- TP rate 7d: 58.0%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 139
- Closed: 121 (TP_clean 62, SL_clean 48, SL→reverse 0, Sideways 11, N/A 0)
- Ongoing (<24h): 18
- TP rate: 56.4% decided (TP/(TP+SL)) · 51.2% pointwise (excl N/A)

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
| 139 | 23.06 | 02:34 | EDGEUSDT | SHORT | ongoing | осторожно 72% |
| 138 | 23.06 | 00:30 | FIDAUSDT | LONG | ongoing | осторожно 61% |
| 137 | 22.06 | 21:35 | UAIUSDT | LONG | ongoing | осторожно 63% |
| 136 | 22.06 | 21:08 | BILLUSDT | SHORT | ongoing | осторожно 64% |
| 135 | 22.06 | 17:02 | TNSRUSDT | LONG | ongoing | входить 81% |
| 134 | 22.06 | 13:07 | FILUSDT | LONG | ongoing | осторожно 67% |
| 133 | 22.06 | 13:02 | IDUSDT | LONG | ongoing | осторожно 73% |
| 132 | 22.06 | 11:34 | DEXEUSDT | SHORT | ongoing | входить 87% |
| 131 | 22.06 | 07:00 | ALICEUSDT | SHORT | ongoing | осторожно 60% |
| 130 | 22.06 | 06:35 | ALGOUSDT | SHORT | ongoing | осторожно 74% |
| 129 | 22.06 | 00:02 | STGUSDT | SHORT | ongoing | осторожно 82% |
| 128 | 21.06 | 19:36 | LABUSDT | SHORT | ongoing | осторожно 63% |
| 127 | 21.06 | 14:32 | HYPEUSDT | SHORT | ongoing | осторожно 75% |
| 126 | 21.06 | 13:01 | TNSRUSDT | LONG | ongoing | осторожно 61% |
| 125 | 21.06 | 11:07 | LABUSDT | SHORT | ongoing | осторожно 64% |
| 124 | 21.06 | 09:31 | ALICEUSDT | LONG | ongoing | осторожно 76% |
| 123 | 21.06 | 06:04 | SUSDT | SHORT | ongoing | осторожно 76% |
| 122 | 21.06 | 06:02 | SANDUSDT | LONG | ongoing | входить 90% |
| 121 | 21.06 | 04:32 | AXSUSDT | LONG | SL_clean | осторожно 63% |
| 120 | 20.06 | 23:31 | RAREUSDT | LONG | TP_clean | осторожно 77% |
| 119 | 20.06 | 22:07 | SEIUSDT | SHORT | SL_clean | осторожно 68% |
| 118 | 20.06 | 18:00 | SANDUSDT | LONG | TP_clean | осторожно 77% |
| 117 | 20.06 | 16:33 | AXSUSDT | LONG | TP_clean | осторожно 63% |
| 116 | 20.06 | 06:34 | FOLKSUSDT | SHORT | TP_clean | осторожно 69% |
| 115 | 20.06 | 05:07 | ALLOUSDT | LONG | SL_clean | осторожно 63% |
| 114 | 20.06 | 05:06 | INTCUSDT | LONG | TP_clean | осторожно 66% |
| 113 | 20.06 | 04:33 | HUSDT | SHORT | TP_clean | осторожно 73% |
| 112 | 20.06 | 04:01 | BICOUSDT | LONG | SL_clean | осторожно 75% |
| 111 | 20.06 | 01:08 | CLOUSDT | LONG | TP_clean | осторожно 70% |
| 110 | 20.06 | 00:32 | CHZUSDT | SHORT | Sideways | осторожно 70% |
| 109 | 19.06 | 22:39 | PENDLEUSDT | SHORT | Sideways | осторожно 69% |
| 108 | 19.06 | 22:03 | GENIUSUSDT | SHORT | TP_clean | осторожно 74% |
| 107 | 19.06 | 21:12 | IBMUSDT | SHORT | Sideways | осторожно 60% |
| 106 | 19.06 | 19:34 | BELUSDT | LONG | TP_clean | осторожно 76% |
| 105 | 19.06 | 11:41 | BTWUSDT | SHORT | TP_clean | осторожно 74% |
| 104 | 19.06 | 10:10 | XRPUSDT | SHORT | Sideways | осторожно 63% |
| 103 | 19.06 | 10:09 | SOLUSDT | SHORT | SL_clean | осторожно 68% |
| 102 | 19.06 | 10:05 | AERGOUSDT | SHORT | TP_clean | осторожно 69% |
| 101 | 19.06 | 09:13 | PORTALUSDT | LONG | TP_clean | осторожно 75% |
| 100 | 19.06 | 07:31 | INTCUSDT | LONG | TP_clean | осторожно 60% |
| 99 | 19.06 | 07:03 | HOMEUSDT | LONG | SL_clean | осторожно 69% |
| 98 | 19.06 | 06:09 | SUIUSDT | SHORT | TP_clean | осторожно 62% |
| 97 | 19.06 | 05:02 | IDUSDT | LONG | SL_clean | осторожно 67% |
| 96 | 19.06 | 04:01 | BLESSUSDT | SHORT | TP_clean | осторожно 77% |
| 95 | 19.06 | 03:02 | TRUSTUSDT | LONG | TP_clean | осторожно 61% |
| 94 | 18.06 | 23:01 | ALLOUSDT | LONG | TP_clean | осторожно 61% |
| 93 | 18.06 | 22:41 | CRVUSDT | SHORT | TP_clean | осторожно 60% |
| 92 | 18.06 | 21:31 | USELESSUSDT | SHORT | TP_clean | осторожно 69% |
| 91 | 18.06 | 18:00 | VELVETUSDT | SHORT | SL_clean | осторожно 64% |
| 90 | 18.06 | 11:04 | JTOUSDT | SHORT | SL_clean | осторожно 86% |

## Cron jobs
- mmscan-daily-closer: next run 2026-06-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-23 00:30 UTC
- mmscan-snapshot: next run 2026-06-23 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
