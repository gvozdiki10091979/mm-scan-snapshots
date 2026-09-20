# MM Scan Shadow Snapshot
Generated: 2026-09-20T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 950.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-09-20T17:35:05+0000 (#1202 CAPUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-09-19T18:00:02Z → 2026-09-20T18:00:02Z)
- New signals: 15 (LONG 11 / SHORT 4)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 15
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 950.2h, restarts: 0
- Last closer: 2026-09-20T03:00:16Z
- Last backfill: 2026-09-20T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 6

## Health 7d (window: 2026-09-13T18:00:02Z → 2026-09-20T18:00:02Z)
- New signals: 83 (~11.9/day)
- Closed: 62 (TP 30, SL 26, SL→rev 0, Sideways 6, N/A 0)
- Ongoing: 21
- TP rate 7d: 53.6%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1202
- Closed: 1181 (TP_clean 602, SL_clean 409, SL→reverse 0, Sideways 170, N/A 0)
- Ongoing (<24h): 21
- TP rate: 59.5% decided (TP/(TP+SL)) · 51.0% pointwise (excl N/A)

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
| 1202 | 20.09 | 20:35 | CAPUSDT | SHORT | ongoing | осторожно 66% |
| 1201 | 20.09 | 16:34 | HOMEUSDT | LONG | ongoing | осторожно 71% |
| 1200 | 20.09 | 16:32 | EGLDUSDT | SHORT | ongoing | осторожно 71% |
| 1199 | 20.09 | 15:35 | ATOMUSDT | SHORT | ongoing | осторожно 62% |
| 1198 | 20.09 | 15:08 | ENAUSDT | LONG | ongoing | осторожно 65% |
| 1197 | 20.09 | 13:31 | ZAMAUSDT | LONG | ongoing | входить 83% |
| 1196 | 20.09 | 12:04 | TUSDT | LONG | ongoing | осторожно 65% |
| 1195 | 20.09 | 10:05 | BANKUSDT | LONG | ongoing | осторожно 71% |
| 1194 | 20.09 | 09:31 | ACEUSDT | LONG | ongoing | осторожно 68% |
| 1193 | 19.09 | 23:31 | PENGUUSDT | LONG | ongoing | осторожно 61% |
| 1192 | 19.09 | 23:09 | ZECUSDT | SHORT | ongoing | осторожно 64% |
| 1191 | 19.09 | 23:08 | ASTERUSDT | LONG | ongoing | осторожно 60% |
| 1190 | 19.09 | 22:05 | AAVEUSDT | LONG | ongoing | осторожно 68% |
| 1189 | 19.09 | 22:05 | FUSDT | LONG | ongoing | осторожно 75% |
| 1188 | 19.09 | 21:31 | ENAUSDT | LONG | ongoing | осторожно 70% |
| 1187 | 19.09 | 14:33 | ASTERUSDT | LONG | ongoing | осторожно 60% |
| 1186 | 19.09 | 14:32 | FUSDT | LONG | ongoing | осторожно 63% |
| 1185 | 19.09 | 11:37 | ACEUSDT | LONG | ongoing | осторожно 65% |
| 1184 | 19.09 | 11:34 | BOMEUSDT | LONG | ongoing | осторожно 68% |
| 1183 | 19.09 | 07:04 | SUSHIUSDT | LONG | ongoing | осторожно 62% |
| 1182 | 19.09 | 06:07 | SPXUSDT | LONG | ongoing | осторожно 85% |
| 1181 | 19.09 | 05:36 | FLOCKUSDT | LONG | TP_clean | осторожно 65% |
| 1180 | 19.09 | 00:38 | MAGMAUSDT | SHORT | TP_clean | осторожно 62% |
| 1179 | 18.09 | 22:36 | CAKEUSDT | LONG | SL_clean | осторожно 64% |
| 1178 | 18.09 | 19:34 | MRVLUSDT | SHORT | Sideways | осторожно 75% |
| 1177 | 18.09 | 17:35 | VVVUSDT | LONG | TP_clean | осторожно 62% |
| 1176 | 18.09 | 11:04 | AVAUSDT | LONG | TP_clean | осторожно 61% |
| 1175 | 18.09 | 04:01 | AEROUSDT | LONG | TP_clean | осторожно 64% |
| 1174 | 18.09 | 01:31 | DASHUSDT | LONG | TP_clean | осторожно 63% |
| 1173 | 18.09 | 01:00 | TUTUSDT | LONG | TP_clean | осторожно 60% |
| 1172 | 17.09 | 22:02 | POWERUSDT | SHORT | TP_clean | осторожно 61% |
| 1171 | 17.09 | 17:37 | POWERUSDT | SHORT | TP_clean | осторожно 77% |
| 1170 | 17.09 | 14:08 | COINUSDT | SHORT | SL_clean | осторожно 66% |
| 1169 | 17.09 | 14:03 | KORUUSDT | LONG | TP_clean | осторожно 62% |
| 1168 | 17.09 | 06:08 | KORUUSDT | SHORT | SL_clean | осторожно 62% |
| 1167 | 17.09 | 04:02 | LAUSDT | LONG | SL_clean | осторожно 61% |
| 1166 | 17.09 | 04:00 | BRUSDT | LONG | TP_clean | осторожно 67% |
| 1165 | 17.09 | 01:31 | CRVUSDT | SHORT | SL_clean | осторожно 72% |
| 1164 | 17.09 | 01:04 | KORUUSDT | SHORT | SL_clean | осторожно 62% |
| 1163 | 16.09 | 21:36 | LITUSDT | SHORT | TP_clean | осторожно 74% |
| 1162 | 16.09 | 21:08 | CRCLUSDT | SHORT | TP_clean | осторожно 70% |
| 1161 | 16.09 | 20:41 | SOLUSDT | SHORT | SL_clean | осторожно 70% |
| 1160 | 16.09 | 20:40 | ORDIUSDT | SHORT | SL_clean | осторожно 63% |
| 1159 | 16.09 | 20:04 | ATOMUSDT | SHORT | SL_clean | осторожно 68% |
| 1158 | 16.09 | 16:37 | ONUSDT | SHORT | SL_clean | осторожно 89% |
| 1157 | 16.09 | 16:05 | XMRUSDT | SHORT | TP_clean | осторожно 61% |
| 1156 | 16.09 | 14:07 | SOLUSDT | SHORT | SL_clean | осторожно 69% |
| 1155 | 16.09 | 13:38 | KAITOUSDT | SHORT | SL_clean | осторожно 65% |
| 1154 | 16.09 | 12:06 | AKEUSDT | LONG | TP_clean | осторожно 66% |
| 1153 | 16.09 | 10:38 | 1000BONKUSDT | SHORT | TP_clean | осторожно 61% |

## Cron jobs
- mmscan-daily-closer: next run 2026-09-21 03:00 UTC
- mmscan-hourly-backfill: next run 2026-09-20 18:30 UTC
- mmscan-snapshot: next run 2026-09-21 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
