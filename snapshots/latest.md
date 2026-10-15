# MM Scan Shadow Snapshot
Generated: 2026-10-15T06:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1538.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-15T05:35:50+0000 (#1523 XPLUSDT SHORT, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-14T06:00:02Z → 2026-10-15T06:00:02Z)
- New signals: 16 (LONG 2 / SHORT 14)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 16
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1538.2h, restarts: 0
- Last closer: 2026-10-15T03:00:32Z
- Last backfill: 2026-10-15T05:30:02Z
- Anomalies: ongoing >24h без закрытия: 2

## Health 7d (window: 2026-10-08T06:00:02Z → 2026-10-15T06:00:02Z)
- New signals: 96 (~13.7/day)
- Closed: 78 (TP 37, SL 26, SL→rev 0, Sideways 15, N/A 0)
- Ongoing: 18
- TP rate 7d: 58.7%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1523
- Closed: 1505 (TP_clean 761, SL_clean 530, SL→reverse 0, Sideways 214, N/A 0)
- Ongoing (<24h): 18
- TP rate: 58.9% decided (TP/(TP+SL)) · 50.6% pointwise (excl N/A)

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
| 1523 | 15.10 | 08:35 | XPLUSDT | SHORT | ongoing | осторожно 62% |
| 1522 | 15.10 | 08:03 | 1000BONKUSDT | SHORT | ongoing | осторожно 60% |
| 1521 | 15.10 | 08:02 | SUIUSDT | SHORT | ongoing | осторожно 61% |
| 1520 | 15.10 | 08:01 | DUSKUSDT | LONG | ongoing | осторожно 60% |
| 1519 | 15.10 | 02:10 | DOGEUSDT | SHORT | ongoing | осторожно 61% |
| 1518 | 15.10 | 02:10 | ADAUSDT | SHORT | ongoing | осторожно 60% |
| 1517 | 15.10 | 02:09 | SOLUSDT | SHORT | ongoing | осторожно 62% |
| 1516 | 15.10 | 01:38 | BTCUSDT | SHORT | ongoing | осторожно 60% |
| 1515 | 14.10 | 23:07 | SUIUSDT | SHORT | ongoing | осторожно 62% |
| 1514 | 14.10 | 22:42 | SKHYUSDT | SHORT | ongoing | осторожно 61% |
| 1513 | 14.10 | 21:41 | SOLUSDT | SHORT | ongoing | осторожно 62% |
| 1512 | 14.10 | 21:40 | POLUSDT | SHORT | ongoing | осторожно 66% |
| 1511 | 14.10 | 21:38 | DASHUSDT | SHORT | ongoing | осторожно 68% |
| 1510 | 14.10 | 21:34 | BLURUSDT | SHORT | ongoing | осторожно 67% |
| 1509 | 14.10 | 14:34 | ZECUSDT | SHORT | ongoing | осторожно 60% |
| 1508 | 14.10 | 11:10 | FILUSDT | LONG | ongoing | осторожно 63% |
| 1507 | 14.10 | 07:00 | BRUSDT | SHORT | ongoing | осторожно 69% |
| 1506 | 14.10 | 06:01 | ARCUSDT | SHORT | ongoing | входить 87% |
| 1505 | 14.10 | 04:02 | SKLUSDT | LONG | SL_clean | осторожно 67% |
| 1504 | 14.10 | 02:05 | GRASSUSDT | SHORT | SL_clean | осторожно 63% |
| 1503 | 14.10 | 00:32 | BLURUSDT | SHORT | SL_clean | осторожно 69% |
| 1502 | 14.10 | 00:08 | BATUSDT | LONG | TP_clean | осторожно 61% |
| 1501 | 13.10 | 23:35 | CYBERUSDT | LONG | SL_clean | осторожно 72% |
| 1500 | 13.10 | 17:36 | ERAUSDT | SHORT | TP_clean | осторожно 60% |
| 1499 | 13.10 | 14:34 | BLURUSDT | SHORT | TP_clean | входить 83% |
| 1498 | 13.10 | 14:32 | CSOPSKHYNIX2LUSDT | SHORT | SL_clean | входить 84% |
| 1497 | 13.10 | 14:01 | IOUSDT | SHORT | Sideways | осторожно 63% |
| 1496 | 13.10 | 12:07 | APTUSDT | SHORT | TP_clean | осторожно 60% |
| 1495 | 13.10 | 12:04 | ORCAUSDT | SHORT | TP_clean | входить 87% |
| 1494 | 13.10 | 11:32 | DOTUSDT | SHORT | TP_clean | осторожно 62% |
| 1493 | 13.10 | 06:01 | BLURUSDT | SHORT | SL_clean | осторожно 62% |
| 1492 | 13.10 | 04:34 | UNITREEUSDT | LONG | TP_clean | осторожно 63% |
| 1491 | 13.10 | 04:33 | NMRUSDT | SHORT | Sideways | осторожно 62% |
| 1490 | 13.10 | 03:34 | CKBUSDT | LONG | TP_clean | осторожно 75% |
| 1489 | 12.10 | 22:40 | ARUSDT | LONG | SL_clean | осторожно 63% |
| 1488 | 12.10 | 22:09 | 1000PEPEUSDT | SHORT | TP_clean | осторожно 62% |
| 1487 | 12.10 | 22:01 | JCTUSDT | LONG | TP_clean | осторожно 61% |
| 1486 | 12.10 | 20:12 | CAKEUSDT | SHORT | TP_clean | осторожно 69% |
| 1485 | 12.10 | 16:06 | WIFUSDT | SHORT | TP_clean | осторожно 72% |
| 1484 | 12.10 | 14:07 | MUUUSDT | SHORT | TP_clean | осторожно 61% |
| 1483 | 12.10 | 13:05 | MINAUSDT | LONG | SL_clean | осторожно 61% |
| 1482 | 12.10 | 12:37 | USUSDT | SHORT | SL_clean | осторожно 65% |
| 1481 | 12.10 | 07:35 | KORUUSDT | LONG | SL_clean | осторожно 64% |
| 1480 | 12.10 | 03:04 | INJUSDT | LONG | TP_clean | осторожно 61% |
| 1479 | 12.10 | 02:34 | WALUSDT | LONG | SL_clean | осторожно 76% |
| 1478 | 11.10 | 22:40 | LAUSDT | LONG | TP_clean | осторожно 60% |
| 1477 | 11.10 | 22:36 | ZROUSDT | LONG | TP_clean | осторожно 61% |
| 1476 | 11.10 | 22:00 | STRKUSDT | LONG | SL_clean | осторожно 60% |
| 1475 | 11.10 | 20:31 | ZKUSDT | LONG | SL_clean | осторожно 65% |
| 1474 | 11.10 | 20:30 | CHIPUSDT | LONG | SL_clean | осторожно 77% |

## Cron jobs
- mmscan-daily-closer: next run 2026-10-16 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-15 06:30 UTC
- mmscan-snapshot: next run 2026-10-15 12:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
