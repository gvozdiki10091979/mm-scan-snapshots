# MM Scan Shadow Snapshot
Generated: 2026-10-15T18:00:01Z

## Listener Health
- systemd status: **active**
- MainPID: 862
- Uptime: 1550.2h (active since Wed 2026-08-12 03:48:33 UTC)
- Last signal: 2026-10-15T17:32:29+0000 (#1534 NILUSDT LONG, ongoing)
- Auto-restarts (since unit start): 0

## Health 24h (window: 2026-10-14T18:00:01Z → 2026-10-15T18:00:01Z)
- New signals: 25 (LONG 3 / SHORT 22)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 25
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 1550.2h, restarts: 0
- Last closer: 2026-10-15T03:00:32Z
- Last backfill: 2026-10-15T17:30:02Z
- Anomalies: ongoing >24h без закрытия: 4

## Health 7d (window: 2026-10-08T18:00:01Z → 2026-10-15T18:00:01Z)
- New signals: 101 (~14.4/day)
- Closed: 72 (TP 31, SL 26, SL→rev 0, Sideways 15, N/A 0)
- Ongoing: 29
- TP rate 7d: 54.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1534
- Closed: 1505 (TP_clean 761, SL_clean 530, SL→reverse 0, Sideways 214, N/A 0)
- Ongoing (<24h): 29
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
| 1534 | 15.10 | 20:32 | NILUSDT | LONG | ongoing | осторожно 60% |
| 1533 | 15.10 | 19:08 | AAOIUSDT | SHORT | ongoing | осторожно 77% |
| 1532 | 15.10 | 19:07 | COHRUSDT | SHORT | ongoing | осторожно 63% |
| 1531 | 15.10 | 17:36 | KORUUSDT | SHORT | ongoing | осторожно 61% |
| 1530 | 15.10 | 16:34 | RKLBUSDT | SHORT | ongoing | осторожно 71% |
| 1529 | 15.10 | 16:04 | USUSDT | SHORT | ongoing | осторожно 77% |
| 1528 | 15.10 | 15:02 | BSPUSDT | LONG | ongoing | осторожно 61% |
| 1527 | 15.10 | 14:06 | SNDKUSDT | SHORT | ongoing | осторожно 64% |
| 1526 | 15.10 | 13:06 | ARBUSDT | SHORT | ongoing | осторожно 62% |
| 1525 | 15.10 | 11:33 | ICPUSDT | SHORT | ongoing | осторожно 60% |
| 1524 | 15.10 | 11:10 | ZHONGJIUSDT | SHORT | ongoing | осторожно 70% |
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

## Cron jobs
- mmscan-daily-closer: next run 2026-10-16 03:00 UTC
- mmscan-hourly-backfill: next run 2026-10-15 18:30 UTC
- mmscan-snapshot: next run 2026-10-16 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
