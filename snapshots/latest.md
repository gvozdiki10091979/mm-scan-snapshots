# MM Scan Shadow Snapshot
Generated: 2026-06-29T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 113.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-06-29T17:01:30+0000 (#229 AGLDUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-06-28T18:00:01Z → 2026-06-29T18:00:01Z)
- New signals: 8 (LONG 4 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 8
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 113.3h, restarts: 143
- Last closer: 2026-06-29T03:00:26Z
- Last backfill: 2026-06-29T17:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 5

## Health 7d (window: 2026-06-22T18:00:01Z → 2026-06-29T18:00:01Z)
- New signals: 94 (~13.4/day)
- Closed: 81 (TP 49, SL 20, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 13
- TP rate 7d: 71.0%
- Listener uptime 7d: 67.4% (continuous since unit start)

## Shadow Journal Live
- Total signals: 229
- Closed: 216 (TP_clean 115, SL_clean 77, SL→reverse 0, Sideways 24, N/A 0)
- Ongoing (<24h): 13
- TP rate: 59.9% decided (TP/(TP+SL)) · 53.2% pointwise (excl N/A)

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
| 229 | 29.06 | 20:01 | AGLDUSDT | SHORT | ongoing | осторожно 61% |
| 228 | 29.06 | 18:01 | PIEVERSEUSDT | SHORT | ongoing | осторожно 63% |
| 227 | 29.06 | 14:31 | ALICEUSDT | LONG | ongoing | осторожно 63% |
| 226 | 29.06 | 13:31 | SLXUSDT | LONG | ongoing | осторожно 62% |
| 225 | 29.06 | 12:04 | ANIMEUSDT | LONG | ongoing | осторожно 67% |
| 224 | 29.06 | 05:32 | PUNDIXUSDT | SHORT | ongoing | осторожно 70% |
| 223 | 29.06 | 03:38 | SOXLUSDT | SHORT | ongoing | осторожно 72% |
| 222 | 28.06 | 23:01 | MAGICUSDT | LONG | ongoing | осторожно 61% |
| 221 | 28.06 | 17:37 | BTWUSDT | SHORT | ongoing | осторожно 74% |
| 220 | 28.06 | 16:07 | RENDERUSDT | SHORT | ongoing | осторожно 62% |
| 219 | 28.06 | 14:05 | CELOUSDT | LONG | ongoing | осторожно 73% |
| 218 | 28.06 | 09:39 | BTWUSDT | SHORT | ongoing | осторожно 62% |
| 217 | 28.06 | 06:31 | SUSDT | LONG | ongoing | осторожно 65% |
| 216 | 28.06 | 04:02 | GLMUSDT | LONG | TP_clean | осторожно 60% |
| 215 | 27.06 | 22:02 | BICOUSDT | LONG | TP_clean | осторожно 61% |
| 214 | 27.06 | 18:33 | ARXUSDT | LONG | SL_clean | осторожно 71% |
| 213 | 27.06 | 17:35 | SEIUSDT | SHORT | TP_clean | осторожно 64% |
| 212 | 27.06 | 17:00 | STGUSDT | LONG | TP_clean | осторожно 71% |
| 211 | 27.06 | 16:05 | IDUSDT | LONG | SL_clean | осторожно 61% |
| 210 | 27.06 | 16:02 | AGLDUSDT | LONG | TP_clean | осторожно 61% |
| 209 | 27.06 | 15:07 | SNDKUSDT | SHORT | Sideways | осторожно 60% |
| 208 | 27.06 | 13:32 | GLMUSDT | LONG | TP_clean | осторожно 78% |
| 207 | 27.06 | 08:09 | BCHUSDT | LONG | Sideways | осторожно 62% |
| 206 | 27.06 | 08:03 | ARKUSDT | LONG | TP_clean | осторожно 66% |
| 205 | 27.06 | 05:32 | OUSDT | SHORT | SL_clean | входить 87% |
| 204 | 27.06 | 02:35 | SNDKUSDT | SHORT | Sideways | осторожно 82% |
| 203 | 27.06 | 02:34 | DRAMUSDT | SHORT | Sideways | осторожно 66% |
| 202 | 27.06 | 02:09 | SPCXUSDT | LONG | Sideways | осторожно 62% |
| 201 | 27.06 | 02:02 | ICNTUSDT | LONG | SL_clean | осторожно 63% |
| 200 | 26.06 | 21:31 | KORUUSDT | SHORT | TP_clean | осторожно 76% |
| 199 | 26.06 | 21:06 | BTWUSDT | LONG | SL_clean | осторожно 64% |
| 198 | 26.06 | 20:37 | RPLUSDT | LONG | TP_clean | осторожно 61% |
| 197 | 26.06 | 20:01 | SLXUSDT | LONG | TP_clean | осторожно 66% |
| 196 | 26.06 | 19:09 | DRAMUSDT | SHORT | Sideways | осторожно 60% |
| 195 | 26.06 | 18:03 | HMSTRUSDT | LONG | TP_clean | осторожно 67% |
| 194 | 26.06 | 13:37 | XLMUSDT | SHORT | Sideways | осторожно 75% |
| 193 | 26.06 | 13:32 | BTWUSDT | LONG | SL_clean | осторожно 61% |
| 192 | 26.06 | 13:01 | LABUSDT | SHORT | SL_clean | осторожно 60% |
| 191 | 26.06 | 12:31 | ICNTUSDT | LONG | TP_clean | осторожно 61% |
| 190 | 26.06 | 12:01 | TRUMPUSDT | LONG | TP_clean | осторожно 60% |
| 189 | 26.06 | 08:33 | SNDKUSDT | LONG | SL_clean | осторожно 77% |
| 188 | 26.06 | 08:11 | LINKUSDT | SHORT | Sideways | осторожно 63% |
| 187 | 26.06 | 08:10 | SANDUSDT | SHORT | SL_clean | осторожно 66% |
| 186 | 26.06 | 05:31 | IDUSDT | LONG | TP_clean | осторожно 74% |
| 185 | 26.06 | 04:07 | XLMUSDT | SHORT | TP_clean | осторожно 62% |
| 184 | 26.06 | 03:00 | FOGOUSDT | LONG | SL_clean | осторожно 67% |
| 183 | 26.06 | 02:10 | SNDKUSDT | LONG | SL_clean | осторожно 61% |
| 182 | 25.06 | 23:39 | LINKUSDT | SHORT | Sideways | осторожно 76% |
| 181 | 25.06 | 22:34 | BCHUSDT | SHORT | SL_clean | осторожно 62% |
| 180 | 25.06 | 21:13 | ADAUSDT | SHORT | TP_clean | осторожно 62% |

## Cron jobs
- mmscan-daily-closer: next run 2026-06-30 03:00 UTC
- mmscan-hourly-backfill: next run 2026-06-29 18:30 UTC
- mmscan-snapshot: next run 2026-06-30 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
