# MM Scan Shadow Snapshot
Generated: 2026-07-05T12:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 251.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-05T07:31:02+0000 (#317 LABUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-04T12:00:01Z → 2026-07-05T12:00:01Z)
- New signals: 9 (LONG 7 / SHORT 2)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 9
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 251.3h, restarts: 143
- Last closer: 2026-07-05T03:00:23Z
- Last backfill: 2026-07-05T11:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 4

## Health 7d (window: 2026-06-28T12:00:01Z → 2026-07-05T12:00:01Z)
- New signals: 98 (~14.0/day)
- Closed: 85 (TP 52, SL 29, SL→rev 0, Sideways 4, N/A 0)
- Ongoing: 13
- TP rate 7d: 64.2%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 317
- Closed: 304 (TP_clean 170, SL_clean 106, SL→reverse 0, Sideways 28, N/A 0)
- Ongoing (<24h): 13
- TP rate: 61.6% decided (TP/(TP+SL)) · 55.9% pointwise (excl N/A)

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
| 317 | 05.07 | 10:31 | LABUSDT | LONG | ongoing | осторожно 68% |
| 316 | 05.07 | 07:34 | KITEUSDT | LONG | ongoing | осторожно 61% |
| 315 | 05.07 | 07:06 | ARXUSDT | LONG | ongoing | осторожно 64% |
| 314 | 05.07 | 07:03 | CAPUSDT | SHORT | ongoing | осторожно 61% |
| 313 | 05.07 | 04:30 | RPLUSDT | LONG | ongoing | осторожно 66% |
| 312 | 04.07 | 23:31 | AIGENSYNUSDT | SHORT | ongoing | осторожно 63% |
| 311 | 04.07 | 23:08 | XLMUSDT | LONG | ongoing | осторожно 61% |
| 310 | 04.07 | 21:33 | GUNUSDT | LONG | ongoing | осторожно 70% |
| 309 | 04.07 | 20:03 | BICOUSDT | LONG | ongoing | осторожно 65% |
| 308 | 04.07 | 13:08 | MEGAUSDT | LONG | ongoing | осторожно 61% |
| 307 | 04.07 | 10:04 | NEARUSDT | SHORT | ongoing | осторожно 60% |
| 306 | 04.07 | 07:02 | HEIUSDT | SHORT | ongoing | осторожно 60% |
| 305 | 04.07 | 07:02 | ESPORTSUSDT | SHORT | ongoing | осторожно 62% |
| 304 | 04.07 | 05:37 | LABUSDT | SHORT | SL_clean | входить 87% |
| 303 | 04.07 | 03:09 | BREVUSDT | SHORT | TP_clean | осторожно 75% |
| 302 | 03.07 | 16:01 | SLPUSDT | LONG | SL_clean | осторожно 61% |
| 301 | 03.07 | 14:31 | THEUSDT | LONG | TP_clean | осторожно 79% |
| 300 | 03.07 | 13:31 | REUSDT | SHORT | SL_clean | осторожно 66% |
| 299 | 03.07 | 11:32 | MUSDT | LONG | TP_clean | осторожно 63% |
| 298 | 03.07 | 10:03 | AERGOUSDT | LONG | SL_clean | осторожно 63% |
| 297 | 03.07 | 09:34 | MRVLUSDT | SHORT | SL_clean | осторожно 65% |
| 296 | 03.07 | 08:10 | LITUSDT | LONG | SL_clean | осторожно 65% |
| 295 | 03.07 | 06:31 | ALLOUSDT | LONG | SL_clean | осторожно 69% |
| 294 | 03.07 | 06:05 | MIRAUSDT | LONG | TP_clean | осторожно 67% |
| 293 | 03.07 | 06:01 | CAPUSDT | SHORT | TP_clean | осторожно 73% |
| 292 | 03.07 | 03:37 | AIGENSYNUSDT | SHORT | TP_clean | осторожно 70% |
| 291 | 03.07 | 03:31 | RPLUSDT | LONG | SL_clean | осторожно 61% |
| 290 | 02.07 | 23:35 | SOLUSDT | LONG | TP_clean | осторожно 60% |
| 289 | 02.07 | 23:31 | BIRBUSDT | LONG | SL_clean | входить 82% |
| 288 | 02.07 | 23:30 | LABUSDT | SHORT | SL_clean | осторожно 68% |
| 287 | 02.07 | 22:09 | INJUSDT | LONG | TP_clean | осторожно 60% |
| 286 | 02.07 | 20:33 | MORPHOUSDT | LONG | SL_clean | осторожно 60% |
| 285 | 02.07 | 20:10 | TSMUSDT | SHORT | Sideways | осторожно 67% |
| 284 | 02.07 | 18:01 | AERGOUSDT | LONG | TP_clean | осторожно 72% |
| 283 | 02.07 | 14:38 | SLXUSDT | SHORT | TP_clean | осторожно 70% |
| 282 | 02.07 | 13:31 | REUSDT | SHORT | SL_clean | осторожно 65% |
| 281 | 02.07 | 13:05 | TSMUSDT | SHORT | SL_clean | осторожно 63% |
| 280 | 02.07 | 13:03 | AMATUSDT | SHORT | SL_clean | осторожно 73% |
| 279 | 02.07 | 12:08 | WLDUSDT | SHORT | SL_clean | осторожно 62% |
| 278 | 02.07 | 12:02 | EWYUSDT | SHORT | TP_clean | осторожно 68% |
| 277 | 02.07 | 11:01 | BIRBUSDT | LONG | TP_clean | осторожно 62% |
| 276 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 275 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 274 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 273 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 272 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 271 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 270 | 02.07 | 00:38 | HUSDT | SHORT | TP_clean | осторожно 73% |
| 269 | 01.07 | 07:01 | FLNCUSDT | SHORT | TP_clean | осторожно 60% |
| 268 | 01.07 | 23:31 | AIGENSYNUSDT | SHORT | TP_clean | осторожно 63% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-06 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-05 12:30 UTC
- mmscan-snapshot: next run 2026-07-05 18:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
