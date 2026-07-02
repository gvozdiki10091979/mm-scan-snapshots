# MM Scan Shadow Snapshot
Generated: 2026-07-02T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 1505324
- Uptime: 185.3h (active since Thu 2026-06-25 00:39:12 UTC)
- Last signal: 2026-07-02T17:33:12+0000 (#286 MORPHOUSDT LONG, ongoing)
- Auto-restarts (since unit start): 143

## Health 24h (window: 2026-07-01T18:00:01Z → 2026-07-02T18:00:01Z)
- New signals: 14 (LONG 4 / SHORT 10)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 14
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 185.3h, restarts: 143
- Last closer: 2026-07-02T03:00:32Z
- Last backfill: 2026-07-02T17:30:02Z
- Anomalies: listener рестартов: 143; ongoing >24h без закрытия: 29

## Health 7d (window: 2026-06-25T18:00:01Z → 2026-07-02T18:00:01Z)
- New signals: 108 (~15.4/day)
- Closed: 65 (TP 31, SL 22, SL→rev 0, Sideways 12, N/A 0)
- Ongoing: 43
- TP rate 7d: 58.5%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 286
- Closed: 243 (TP_clean 130, SL_clean 87, SL→reverse 0, Sideways 26, N/A 0)
- Ongoing (<24h): 43
- TP rate: 59.9% decided (TP/(TP+SL)) · 53.5% pointwise (excl N/A)

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
| 276 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 275 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 274 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 273 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 272 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 271 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 270 | 02.07 | 00:38 | HUSDT | SHORT | ongoing | осторожно 73% |
| 269 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 268 | 01.07 | 23:31 | AIGENSYNUSDT | SHORT | ongoing | осторожно 63% |
| 267 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 266 | 01.07 | 23:04 | 1000BONKUSDT | SHORT | ongoing | осторожно 62% |
| 265 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 264 | 01.07 | 21:34 | INJUSDT | LONG | ongoing | осторожно 68% |
| 263 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 262 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 261 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 260 | 01.07 | 19:07 | PYTHUSDT | LONG | ongoing | осторожно 61% |
| 259 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 258 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 257 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 256 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 255 | 01.07 | 15:08 | ALLOUSDT | SHORT | ongoing | осторожно 62% |
| 254 | 01.07 | 14:36 | CHZUSDT | SHORT | ongoing | осторожно 61% |
| 253 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 252 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 251 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 250 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 249 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 248 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 247 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 246 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 245 | 01.07 | 07:01 | FLNCUSDT | SHORT | ongoing | осторожно 60% |
| 244 | 01.07 | 06:06 | AAOIUSDT | LONG | ongoing | осторожно 62% |
| 243 | 01.07 | 05:03 | AIGENSYNUSDT | LONG | SL_clean | осторожно 71% |
| 242 | 01.07 | 03:10 | 1000BONKUSDT | SHORT | SL_clean | осторожно 63% |
| 241 | 01.07 | 00:01 | SLXUSDT | SHORT | TP_clean | осторожно 60% |
| 240 | 30.06 | 22:33 | FLNCUSDT | SHORT | TP_clean | осторожно 63% |
| 239 | 30.06 | 19:31 | CBRSUSDT | LONG | TP_clean | осторожно 66% |
| 238 | 30.06 | 18:32 | ALGOUSDT | SHORT | SL_clean | осторожно 62% |
| 237 | 30.06 | 18:10 | 1000BONKUSDT | SHORT | SL_clean | осторожно 65% |

## Cron jobs
- mmscan-daily-closer: next run 2026-07-03 03:00 UTC
- mmscan-hourly-backfill: next run 2026-07-02 18:30 UTC
- mmscan-snapshot: next run 2026-07-03 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
