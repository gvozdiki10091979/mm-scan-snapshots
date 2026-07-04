# MM Scan Shadow Snapshot
Generated: 2026-07-04T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 215.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-03T13:01:55+0000 (#302 SLPUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-03T00:00:01Z → 2026-07-04T00:00:01Z)
- New signals: 12 (LONG 8 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 12
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 215.3h, restarts: 143
- Last closer: 2026-07-03T03:00:37Z
- Last backfill: 2026-07-03T23:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 14

## Health 7d (window: 2026-06-27T00:00:01Z → 2026-07-04T00:00:01Z)
- New signals: 98 (~14.0/day)
- Closed: 72 (TP 50, SL 17, SL→rev 0, Sideways 5, N/A 0)
- Ongoing: 26
- TP rate 7d: 74.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 302
- Closed: 276 (TP_clean 158, SL_clean 91, SL→reverse 0, Sideways 27, N/A 0)
- Ongoing (<24h): 26
- TP rate: 63.5% decided (TP/(TP+SL)) · 57.2% pointwise (excl N/A)

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
| 302 | 03.07 | 16:01 | SLPUSDT | LONG | ongoing | осторожно 61% |
| 301 | 03.07 | 14:31 | THEUSDT | LONG | ongoing | осторожно 79% |
| 300 | 03.07 | 13:31 | REUSDT | SHORT | ongoing | осторожно 66% |
| 299 | 03.07 | 11:32 | MUSDT | LONG | ongoing | осторожно 63% |
| 298 | 03.07 | 10:03 | AERGOUSDT | LONG | ongoing | осторожно 63% |
| 297 | 03.07 | 09:34 | MRVLUSDT | SHORT | ongoing | осторожно 65% |
| 296 | 03.07 | 08:10 | LITUSDT | LONG | ongoing | осторожно 65% |
| 295 | 03.07 | 06:31 | ALLOUSDT | LONG | ongoing | осторожно 69% |
| 294 | 03.07 | 06:05 | MIRAUSDT | LONG | ongoing | осторожно 67% |
| 293 | 03.07 | 06:01 | CAPUSDT | SHORT | ongoing | осторожно 73% |
| 292 | 03.07 | 03:37 | AIGENSYNUSDT | SHORT | ongoing | осторожно 70% |
| 291 | 03.07 | 03:31 | RPLUSDT | LONG | ongoing | осторожно 61% |
| 290 | 02.07 | 23:35 | SOLUSDT | LONG | ongoing | осторожно 60% |
| 289 | 02.07 | 23:31 | BIRBUSDT | LONG | ongoing | входить 82% |
| 288 | 02.07 | 23:30 | LABUSDT | SHORT | ongoing | осторожно 68% |
| 287 | 02.07 | 22:09 | INJUSDT | LONG | ongoing | осторожно 60% |
| 286 | 02.07 | 20:33 | MORPHOUSDT | LONG | ongoing | осторожно 60% |
| 285 | 02.07 | 20:10 | TSMUSDT | SHORT | ongoing | осторожно 67% |
| 284 | 02.07 | 18:01 | AERGOUSDT | LONG | ongoing | осторожно 72% |
| 283 | 02.07 | 14:38 | SLXUSDT | SHORT | ongoing | осторожно 70% |
| 282 | 02.07 | 13:31 | REUSDT | SHORT | ongoing | осторожно 65% |
| 281 | 02.07 | 13:05 | TSMUSDT | SHORT | ongoing | осторожно 63% |
| 280 | 02.07 | 13:03 | AMATUSDT | SHORT | ongoing | осторожно 73% |
| 279 | 02.07 | 12:08 | WLDUSDT | SHORT | ongoing | осторожно 62% |
| 278 | 02.07 | 12:02 | EWYUSDT | SHORT | ongoing | осторожно 68% |
| 277 | 02.07 | 11:01 | BIRBUSDT | LONG | ongoing | осторожно 62% |
| 276 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 275 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 274 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 273 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 272 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 271 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 270 | 02.07 | 00:38 | HUSDT | SHORT | TP_clean | осторожно 73% |
| 269 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 268 | 01.07 | 23:31 | AIGENSYNUSDT | SHORT | TP_clean | осторожно 63% |
| 267 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 266 | 01.07 | 23:04 | 1000BONKUSDT | SHORT | Sideways | осторожно 62% |
| 265 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 264 | 01.07 | 21:34 | INJUSDT | LONG | SL_clean | осторожно 68% |
| 263 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 262 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 261 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 260 | 01.07 | 19:07 | PYTHUSDT | LONG | SL_clean | осторожно 61% |
| 259 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 258 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 257 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 256 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 255 | 01.07 | 15:08 | ALLOUSDT | SHORT | TP_clean | осторожно 62% |
| 254 | 01.07 | 14:36 | CHZUSDT | SHORT | SL_clean | осторожно 61% |
| 253 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-04 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-04 00:30 UTC
- mmscan-snapshot: next run 2026-07-04 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
