# MM Scan Shadow Snapshot
Generated: 2026-09-23T00:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1004.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-22T22:34:11+0000 (#1237 1000PEPEUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-22T00:00:01Z → 2026-09-23T00:00:01Z)
- New signals: 17 (LONG 10 / SHORT 7)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1004.2h, restarts: 0
- Last closer: 2026-09-22T03:00:47Z
- Last backfill: 2026-09-22T23:30:02Z
- Anomalies: ongoing >24h без закрытия: 15

## Health 7d (window: 2026-09-16T00:00:01Z → 2026-09-23T00:00:01Z)
- New signals: 89 (~12.7/day)
- Closed: 57 (TP 29, SL 26, SL→rev 0, Sideways 2, N/A 0)
- Ongoing: 32
- TP rate 7d: 52.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1237
- Closed: 1205 (TP_clean 612, SL_clean 423, SL→reverse 0, Sideways 170, N/A 0)
- Ongoing (<24h): 32
- TP rate: 59.1% decided (TP/(TP+SL)) · 50.8% pointwise (excl N/A)

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
| 1237 | 23.09 | 01:34 | 1000PEPEUSDT | LONG | ongoing | осторожно 64% |
| 1236 | 22.09 | 23:38 | CHIPUSDT | LONG | ongoing | осторожно 62% |
| 1235 | 22.09 | 21:09 | UNIUSDT | LONG | ongoing | осторожно 60% |
| 1234 | 22.09 | 20:34 | ALLOUSDT | LONG | ongoing | осторожно 65% |
| 1233 | 22.09 | 20:07 | BABAUSDT | SHORT | ongoing | осторожно 86% |
| 1232 | 22.09 | 19:40 | ENSUSDT | LONG | ongoing | осторожно 64% |
| 1231 | 22.09 | 19:30 | WIFUSDT | LONG | ongoing | осторожно 70% |
| 1230 | 22.09 | 19:10 | SOXSUSDT | SHORT | ongoing | осторожно 62% |
| 1229 | 22.09 | 19:06 | PENDLEUSDT | SHORT | ongoing | осторожно 60% |
| 1228 | 22.09 | 16:36 | KORUUSDT | LONG | ongoing | осторожно 69% |
| 1227 | 22.09 | 15:14 | BNBUSDT | SHORT | ongoing | осторожно 64% |
| 1226 | 22.09 | 14:34 | AAOIUSDT | SHORT | ongoing | осторожно 67% |
| 1225 | 22.09 | 13:05 | WIFUSDT | LONG | ongoing | осторожно 60% |
| 1224 | 22.09 | 12:00 | SANDUSDT | LONG | ongoing | осторожно 61% |
| 1223 | 22.09 | 11:06 | ASTERUSDT | SHORT | ongoing | осторожно 65% |
| 1222 | 22.09 | 10:06 | AAOIUSDT | SHORT | ongoing | осторожно 74% |
| 1221 | 22.09 | 10:05 | KERNELUSDT | LONG | ongoing | осторожно 61% |
| 1220 | 22.09 | 02:35 | ASTERUSDT | SHORT | ongoing | осторожно 70% |
| 1219 | 22.09 | 02:34 | KERNELUSDT | LONG | ongoing | осторожно 61% |
| 1218 | 21.09 | 23:30 | PHAUSDT | LONG | ongoing | осторожно 61% |
| 1217 | 21.09 | 23:09 | MYXUSDT | LONG | ongoing | осторожно 68% |
| 1216 | 21.09 | 21:39 | HYPEUSDT | SHORT | ongoing | осторожно 66% |
| 1215 | 21.09 | 21:35 | LITUSDT | SHORT | ongoing | осторожно 62% |
| 1214 | 21.09 | 20:37 | CBRSUSDT | LONG | ongoing | осторожно 83% |
| 1213 | 21.09 | 18:03 | ZROUSDT | LONG | ongoing | осторожно 60% |
| 1212 | 21.09 | 16:00 | B2USDT | SHORT | ongoing | осторожно 62% |
| 1211 | 21.09 | 12:40 | LITUSDT | SHORT | ongoing | осторожно 63% |
| 1210 | 21.09 | 11:00 | EGLDUSDT | SHORT | ongoing | осторожно 72% |
| 1209 | 21.09 | 09:31 | XMRUSDT | SHORT | ongoing | осторожно 79% |
| 1208 | 21.09 | 09:07 | RENDERUSDT | LONG | ongoing | осторожно 60% |
| 1207 | 21.09 | 07:06 | CRVUSDT | SHORT | ongoing | осторожно 72% |
| 1206 | 21.09 | 06:37 | STGUSDT | SHORT | ongoing | входить 87% |
| 1205 | 21.09 | 02:33 | SOPHUSDT | LONG | TP_clean | осторожно 68% |
| 1204 | 20.09 | 23:01 | ARBUSDT | LONG | TP_clean | осторожно 67% |
| 1203 | 20.09 | 22:34 | VVVUSDT | SHORT | SL_clean | входить 90% |
| 1202 | 20.09 | 20:35 | CAPUSDT | SHORT | SL_clean | осторожно 66% |
| 1201 | 20.09 | 16:34 | HOMEUSDT | LONG | TP_clean | осторожно 71% |
| 1200 | 20.09 | 16:32 | EGLDUSDT | SHORT | SL_clean | осторожно 71% |
| 1199 | 20.09 | 15:35 | ATOMUSDT | SHORT | SL_clean | осторожно 62% |
| 1198 | 20.09 | 15:08 | ENAUSDT | LONG | SL_clean | осторожно 65% |
| 1197 | 20.09 | 13:31 | ZAMAUSDT | LONG | TP_clean | входить 83% |
| 1196 | 20.09 | 12:04 | TUSDT | LONG | TP_clean | осторожно 65% |
| 1195 | 20.09 | 10:05 | BANKUSDT | LONG | SL_clean | осторожно 71% |
| 1194 | 20.09 | 09:31 | ACEUSDT | LONG | SL_clean | осторожно 68% |
| 1193 | 19.09 | 23:31 | PENGUUSDT | LONG | SL_clean | осторожно 61% |
| 1192 | 19.09 | 23:09 | ZECUSDT | SHORT | TP_clean | осторожно 64% |
| 1191 | 19.09 | 23:08 | ASTERUSDT | LONG | SL_clean | осторожно 60% |
| 1190 | 19.09 | 22:05 | AAVEUSDT | LONG | SL_clean | осторожно 68% |
| 1189 | 19.09 | 22:05 | FUSDT | LONG | SL_clean | осторожно 75% |
| 1188 | 19.09 | 21:31 | ENAUSDT | LONG | TP_clean | осторожно 70% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-23 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-23 00:30 UTC
- mmscan-snapshot: next run 2026-09-23 06:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
