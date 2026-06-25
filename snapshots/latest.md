# MM Scan Shadow Snapshot
Generated: 2026-06-25T06:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 5.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-06-25T05:07:50+0000 (#171 ALGOUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-06-24T06:00:01Z → 2026-06-25T06:00:01Z)
- New signals: 14 (LONG 3 / SHORT 11)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 5.3h, restarts: 143
- Last closer: 2026-06-25T03:00:29Z
- Last backfill: 2026-06-25T05:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-06-18T06:00:01Z → 2026-06-25T06:00:01Z)
- New signals: 83 (~11.9/day)
- Closed: 65 (TP 37, SL 22, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 18
- TP rate 7d: 62.7%
- Listener uptime 7d: 3.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 171
- Closed: 153 (TP_clean 79, SL_clean 61, SL→reverse 0, Sideways 13, N/A 0)
- Ongoing (<24h): 18
- TP rate: 56.4% decided (TP/(TP+SL)) · 51.6% pointwise (excl N/A)

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
| 171 | 25.06 | 08:07 | ALGOUSDT | LONG | ongoing | осторожно 62% |
| 170 | 25.06 | 06:40 | XAUUSDT | SHORT | ongoing | осторожно 62% |
| 169 | 25.06 | 06:01 | LABUSDT | SHORT | ongoing | осторожно 66% |
| 168 | 25.06 | 05:37 | MYXUSDT | SHORT | ongoing | осторожно 60% |
| 167 | 24.06 | 19:35 | INJUSDT | SHORT | ongoing | осторожно 63% |
| 166 | 24.06 | 18:34 | BLESSUSDT | SHORT | ongoing | осторожно 80% |
| 165 | 24.06 | 16:39 | AVNTUSDT | SHORT | ongoing | осторожно 68% |
| 164 | 24.06 | 14:34 | WLFIUSDT | SHORT | ongoing | осторожно 62% |
| 163 | 24.06 | 13:36 | UBUSDT | SHORT | ongoing | входить 86% |
| 162 | 24.06 | 13:31 | ALICEUSDT | LONG | ongoing | осторожно 68% |
| 161 | 24.06 | 11:31 | DYDXUSDT | LONG | ongoing | осторожно 64% |
| 160 | 24.06 | 10:07 | WUSDT | SHORT | ongoing | осторожно 61% |
| 159 | 24.06 | 09:35 | GRASSUSDT | SHORT | ongoing | осторожно 71% |
| 158 | 24.06 | 09:02 | ALICEUSDT | SHORT | ongoing | осторожно 67% |
| 157 | 24.06 | 08:37 | WLDUSDT | SHORT | ongoing | осторожно 60% |
| 156 | 24.06 | 07:11 | AAOIUSDT | SHORT | ongoing | осторожно 65% |
| 155 | 24.06 | 06:32 | MUUSDT | SHORT | ongoing | осторожно 68% |
| 154 | 24.06 | 06:07 | 1000PEPEUSDT | SHORT | ongoing | осторожно 74% |
| 153 | 24.06 | 04:34 | BTWUSDT | SHORT | TP_clean | входить 90% |
| 152 | 24.06 | 03:04 | SIRENUSDT | LONG | TP_clean | осторожно 64% |
| 151 | 23.06 | 23:40 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 68% |
| 150 | 23.06 | 21:36 | ALGOUSDT | LONG | TP_clean | осторожно 63% |
| 149 | 23.06 | 21:10 | PENGUUSDT | SHORT | TP_clean | осторожно 74% |
| 148 | 23.06 | 20:34 | CHIPUSDT | LONG | SL_clean | осторожно 74% |
| 147 | 23.06 | 19:06 | WIFUSDT | SHORT | TP_clean | осторожно 62% |
| 146 | 23.06 | 16:04 | SUIUSDT | SHORT | Sideways | осторожно 68% |
| 145 | 23.06 | 16:03 | CHIPUSDT | SHORT | SL_clean | осторожно 65% |
| 144 | 23.06 | 13:31 | HUSDT | SHORT | SL_clean | осторожно 62% |
| 143 | 23.06 | 11:31 | XANUSDT | LONG | TP_clean | осторожно 65% |
| 142 | 23.06 | 04:34 | SOXLUSDT | SHORT | TP_clean | осторожно 86% |
| 141 | 23.06 | 04:32 | TNSRUSDT | SHORT | TP_clean | осторожно 70% |
| 140 | 23.06 | 03:32 | XMRUSDT | LONG | SL_clean | осторожно 90% |
| 139 | 23.06 | 02:34 | EDGEUSDT | SHORT | TP_clean | осторожно 72% |
| 138 | 23.06 | 00:30 | FIDAUSDT | LONG | TP_clean | осторожно 61% |
| 137 | 22.06 | 21:35 | UAIUSDT | LONG | TP_clean | осторожно 63% |
| 136 | 22.06 | 21:08 | BILLUSDT | SHORT | TP_clean | осторожно 64% |
| 135 | 22.06 | 17:02 | TNSRUSDT | LONG | TP_clean | входить 81% |
| 134 | 22.06 | 13:07 | FILUSDT | LONG | SL_clean | осторожно 67% |
| 133 | 22.06 | 13:02 | IDUSDT | LONG | SL_clean | осторожно 73% |
| 132 | 22.06 | 11:34 | DEXEUSDT | SHORT | SL_clean | входить 87% |
| 131 | 22.06 | 07:00 | ALICEUSDT | SHORT | TP_clean | осторожно 60% |
| 130 | 22.06 | 06:35 | ALGOUSDT | SHORT | Sideways | осторожно 74% |
| 129 | 22.06 | 00:02 | STGUSDT | SHORT | SL_clean | осторожно 82% |
| 128 | 21.06 | 19:36 | LABUSDT | SHORT | SL_clean | осторожно 63% |
| 127 | 21.06 | 14:32 | HYPEUSDT | SHORT | TP_clean | осторожно 75% |
| 126 | 21.06 | 13:01 | TNSRUSDT | LONG | SL_clean | осторожно 61% |
| 125 | 21.06 | 11:07 | LABUSDT | SHORT | SL_clean | осторожно 64% |
| 124 | 21.06 | 09:31 | ALICEUSDT | LONG | SL_clean | осторожно 76% |
| 123 | 21.06 | 06:04 | SUSDT | SHORT | TP_clean | осторожно 76% |
| 122 | 21.06 | 06:02 | SANDUSDT | LONG | SL_clean | входить 90% |

## Cron jobs
- mmscan-daily-closer: next run 2026-06-26 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-25 06:30 UTC
- mmscan-snapshot: next run 2026-06-25 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
