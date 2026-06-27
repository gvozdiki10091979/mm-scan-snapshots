# MM Scan Shadow Snapshot
Generated: 2026-06-27T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 47.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-06-26T23:35:15+0000 (#204 SNDKUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-06-26T00:00:01Z → 2026-06-27T00:00:01Z)
- New signals: 21 (LONG 12 / SHORT 9)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 21
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 47.3h, restarts: 143
- Last closer: 2026-06-26T03:00:46Z
- Last backfill: 2026-06-26T23:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 15

## Health 7d (window: 2026-06-20T00:00:01Z → 2026-06-27T00:00:01Z)
- New signals: 93 (~13.3/day)
- Closed: 57 (TP 36, SL 19, SL→rev 0, Sideways 2, N/A 0)
- Ongoing: 36
- TP rate 7d: 65.5%
- Listener uptime 7d: 28.2% (continuous since unit start)

## Shadow Journal Live
- Total signals: 204
- Closed: 168 (TP_clean 92, SL_clean 63, SL→reverse 0, Sideways 13, N/A 0)
- Ongoing (<24h): 36
- TP rate: 59.4% decided (TP/(TP+SL)) · 54.8% pointwise (excl N/A)

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
| 204 | 27.06 | 02:35 | SNDKUSDT | SHORT | ongoing | осторожно 82% |
| 203 | 27.06 | 02:34 | DRAMUSDT | SHORT | ongoing | осторожно 66% |
| 202 | 27.06 | 02:09 | SPCXUSDT | LONG | ongoing | осторожно 62% |
| 201 | 27.06 | 02:02 | ICNTUSDT | LONG | ongoing | осторожно 63% |
| 200 | 26.06 | 21:31 | KORUUSDT | SHORT | ongoing | осторожно 76% |
| 199 | 26.06 | 21:06 | BTWUSDT | LONG | ongoing | осторожно 64% |
| 198 | 26.06 | 20:37 | RPLUSDT | LONG | ongoing | осторожно 61% |
| 197 | 26.06 | 20:01 | SLXUSDT | LONG | ongoing | осторожно 66% |
| 196 | 26.06 | 19:09 | DRAMUSDT | SHORT | ongoing | осторожно 60% |
| 195 | 26.06 | 18:03 | HMSTRUSDT | LONG | ongoing | осторожно 67% |
| 194 | 26.06 | 13:37 | XLMUSDT | SHORT | ongoing | осторожно 75% |
| 193 | 26.06 | 13:32 | BTWUSDT | LONG | ongoing | осторожно 61% |
| 192 | 26.06 | 13:01 | LABUSDT | SHORT | ongoing | осторожно 60% |
| 191 | 26.06 | 12:31 | ICNTUSDT | LONG | ongoing | осторожно 61% |
| 190 | 26.06 | 12:01 | TRUMPUSDT | LONG | ongoing | осторожно 60% |
| 189 | 26.06 | 08:33 | SNDKUSDT | LONG | ongoing | осторожно 77% |
| 188 | 26.06 | 08:11 | LINKUSDT | SHORT | ongoing | осторожно 63% |
| 187 | 26.06 | 08:10 | SANDUSDT | SHORT | ongoing | осторожно 66% |
| 186 | 26.06 | 05:31 | IDUSDT | LONG | ongoing | осторожно 74% |
| 185 | 26.06 | 04:07 | XLMUSDT | SHORT | ongoing | осторожно 62% |
| 184 | 26.06 | 03:00 | FOGOUSDT | LONG | ongoing | осторожно 67% |
| 183 | 26.06 | 02:10 | SNDKUSDT | LONG | ongoing | осторожно 61% |
| 182 | 25.06 | 23:39 | LINKUSDT | SHORT | ongoing | осторожно 76% |
| 181 | 25.06 | 22:34 | BCHUSDT | SHORT | ongoing | осторожно 62% |
| 180 | 25.06 | 21:13 | ADAUSDT | SHORT | ongoing | осторожно 62% |
| 179 | 25.06 | 21:07 | METAUSDT | SHORT | ongoing | осторожно 62% |
| 178 | 25.06 | 20:32 | DOGEUSDT | SHORT | ongoing | осторожно 77% |
| 177 | 25.06 | 19:41 | TSMUSDT | SHORT | ongoing | осторожно 68% |
| 176 | 25.06 | 19:30 | RESOLVUSDT | SHORT | ongoing | осторожно 62% |
| 175 | 25.06 | 13:02 | FILUSDT | SHORT | ongoing | осторожно 77% |
| 174 | 25.06 | 12:31 | ARXUSDT | SHORT | ongoing | осторожно 65% |
| 173 | 25.06 | 11:38 | VIRTUALUSDT | SHORT | ongoing | осторожно 68% |
| 172 | 25.06 | 09:03 | UBUSDT | SHORT | ongoing | осторожно 66% |
| 171 | 25.06 | 08:07 | ALGOUSDT | LONG | ongoing | осторожно 62% |
| 170 | 25.06 | 06:40 | XAUUSDT | SHORT | ongoing | осторожно 62% |
| 169 | 25.06 | 06:01 | LABUSDT | SHORT | ongoing | осторожно 66% |
| 168 | 25.06 | 05:37 | MYXUSDT | SHORT | TP_clean | осторожно 60% |
| 167 | 24.06 | 19:35 | INJUSDT | SHORT | TP_clean | осторожно 63% |
| 166 | 24.06 | 18:34 | BLESSUSDT | SHORT | TP_clean | осторожно 80% |
| 165 | 24.06 | 16:39 | AVNTUSDT | SHORT | TP_clean | осторожно 68% |
| 164 | 24.06 | 14:34 | WLFIUSDT | SHORT | TP_clean | осторожно 62% |
| 163 | 24.06 | 13:36 | UBUSDT | SHORT | SL_clean | входить 86% |
| 162 | 24.06 | 13:31 | ALICEUSDT | LONG | TP_clean | осторожно 68% |
| 161 | 24.06 | 11:31 | DYDXUSDT | LONG | TP_clean | осторожно 64% |
| 160 | 24.06 | 10:07 | WUSDT | SHORT | TP_clean | осторожно 61% |
| 159 | 24.06 | 09:35 | GRASSUSDT | SHORT | SL_clean | осторожно 71% |
| 158 | 24.06 | 09:02 | ALICEUSDT | SHORT | TP_clean | осторожно 67% |
| 157 | 24.06 | 08:37 | WLDUSDT | SHORT | TP_clean | осторожно 60% |
| 156 | 24.06 | 07:11 | AAOIUSDT | SHORT | TP_clean | осторожно 65% |
| 155 | 24.06 | 06:32 | MUUSDT | SHORT | TP_clean | осторожно 68% |

## Cron jobs
- mmscan-daily-closer: next run 2026-06-27 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-27 00:30 UTC
- mmscan-snapshot: next run 2026-06-27 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
