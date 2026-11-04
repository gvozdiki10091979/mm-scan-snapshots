# MM Scan Shadow Snapshot
Generated: 2026-11-04T18:00:02Z

## Listener Health
- systemd status: **active**
- MainPID: 1937138
- Uptime: 210.6h (active since Mon 2026-10-26 23:24:26 UTC)
- Last signal: 2026-11-04T17:10:34+0000 (#1851 SPCXUSDT LONG, ongoing)
- Auto-restarts (since unit start): 8

## Health 24h (window: 2026-11-03T18:00:02Z → 2026-11-04T18:00:02Z)
- New signals: 17 (LONG 5 / SHORT 12)
- Closed: 0 (TP 0, SL 0, SL→rev 0, Sideways 0, N/A 0)
- Ongoing: 17
- TP rate 24h: n/a (<6 closed)
- Listener uptime: 210.6h, restarts: 8
- Last closer: 2026-11-04T03:00:33Z
- Last backfill: 2026-11-04T17:30:03Z
- Anomalies: listener рестартов: 8; ongoing >24h без закрытия: 15

## Health 7d (window: 2026-10-28T18:00:02Z → 2026-11-04T18:00:02Z)
- New signals: 119 (~17.0/day)
- Closed: 87 (TP 50, SL 20, SL→rev 0, Sideways 17, N/A 0)
- Ongoing: 32
- TP rate 7d: 71.4%
- Listener uptime 7d: 100.0% (continuous since unit start)

## Shadow Journal Live
- Total signals: 1851
- Closed: 1819 (TP_clean 941, SL_clean 622, SL→reverse 0, Sideways 256, N/A 0)
- Ongoing (<24h): 32
- TP rate: 60.2% decided (TP/(TP+SL)) · 51.7% pointwise (excl N/A)

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
| 1851 | 04.11 | 20:10 | SPCXUSDT | LONG | ongoing | осторожно 66% |
| 1850 | 04.11 | 17:31 | BMTUSDT | LONG | ongoing | осторожно 61% |
| 1849 | 04.11 | 17:05 | WLFIUSDT | LONG | ongoing | осторожно 67% |
| 1848 | 04.11 | 15:07 | SPCXUSDT | SHORT | ongoing | осторожно 60% |
| 1847 | 04.11 | 15:00 | MUUUSDT | SHORT | ongoing | осторожно 66% |
| 1846 | 04.11 | 13:32 | BZUSDT | SHORT | ongoing | осторожно 65% |
| 1845 | 04.11 | 10:05 | TSLAUSDT | SHORT | ongoing | осторожно 69% |
| 1844 | 04.11 | 09:31 | SKDDUSDT | LONG | ongoing | осторожно 61% |
| 1843 | 04.11 | 09:01 | CXMTUSDT | SHORT | ongoing | входить 84% |
| 1842 | 04.11 | 07:09 | BZUSDT | SHORT | ongoing | осторожно 72% |
| 1841 | 04.11 | 06:35 | COINUSDT | SHORT | ongoing | осторожно 66% |
| 1840 | 04.11 | 06:06 | BOMEUSDT | SHORT | ongoing | осторожно 62% |
| 1839 | 04.11 | 03:31 | NILUSDT | LONG | ongoing | осторожно 67% |
| 1838 | 04.11 | 01:35 | BZUSDT | SHORT | ongoing | осторожно 60% |
| 1837 | 04.11 | 01:32 | HYPEUSDT | SHORT | ongoing | осторожно 69% |
| 1836 | 04.11 | 00:37 | NBISUSDT | SHORT | ongoing | осторожно 65% |
| 1835 | 03.11 | 23:32 | PYTHUSDT | SHORT | ongoing | осторожно 64% |
| 1834 | 03.11 | 16:02 | FLOCKUSDT | LONG | ongoing | осторожно 68% |
| 1833 | 03.11 | 14:01 | VVVUSDT | SHORT | ongoing | осторожно 66% |
| 1832 | 03.11 | 13:05 | BEATUSDT | LONG | ongoing | осторожно 64% |
| 1831 | 03.11 | 11:06 | NEARUSDT | SHORT | ongoing | осторожно 62% |
| 1830 | 03.11 | 11:05 | AVAXUSDT | SHORT | ongoing | осторожно 67% |
| 1829 | 03.11 | 09:06 | 1000BONKUSDT | SHORT | ongoing | осторожно 60% |
| 1828 | 03.11 | 09:05 | PENDLEUSDT | SHORT | ongoing | осторожно 62% |
| 1827 | 03.11 | 08:33 | BMTUSDT | SHORT | ongoing | осторожно 67% |
| 1826 | 03.11 | 08:31 | MARSCOINUSDT | SHORT | ongoing | осторожно 66% |
| 1825 | 03.11 | 08:10 | RENDERUSDT | SHORT | ongoing | осторожно 61% |
| 1824 | 03.11 | 08:10 | ARBUSDT | SHORT | ongoing | осторожно 68% |
| 1823 | 03.11 | 08:09 | ONDOUSDT | SHORT | ongoing | осторожно 60% |
| 1822 | 03.11 | 06:37 | SKHYUSDT | SHORT | ongoing | осторожно 65% |
| 1821 | 03.11 | 06:36 | SAMSUNGUSDT | SHORT | ongoing | осторожно 64% |
| 1820 | 03.11 | 06:04 | SKHYNIXUSDT | SHORT | ongoing | осторожно 69% |
| 1819 | 03.11 | 01:33 | ARBUSDT | SHORT | TP_clean | осторожно 72% |
| 1818 | 03.11 | 01:01 | AKEUSDT | SHORT | TP_clean | входить 90% |
| 1817 | 03.11 | 00:33 | SKHYNIXUSDT | LONG | TP_clean | осторожно 65% |
| 1816 | 03.11 | 00:00 | HAEDALUSDT | LONG | TP_clean | осторожно 77% |
| 1815 | 02.11 | 18:32 | HAEDALUSDT | LONG | TP_clean | осторожно 66% |
| 1814 | 02.11 | 15:09 | ETHFIUSDT | SHORT | TP_clean | осторожно 60% |
| 1813 | 02.11 | 15:06 | TAOUSDT | SHORT | TP_clean | осторожно 66% |
| 1812 | 02.11 | 10:03 | STXUSDT | LONG | Sideways | осторожно 60% |
| 1811 | 02.11 | 09:04 | LINKUSDT | SHORT | TP_clean | осторожно 62% |
| 1810 | 02.11 | 04:04 | POWRUSDT | SHORT | TP_clean | осторожно 66% |
| 1809 | 01.11 | 22:05 | UNIUSDT | SHORT | Sideways | осторожно 71% |
| 1808 | 01.11 | 22:03 | BLESSUSDT | LONG | TP_clean | осторожно 64% |
| 1807 | 01.11 | 21:10 | AVAXUSDT | SHORT | TP_clean | осторожно 85% |
| 1806 | 01.11 | 19:05 | USELESSUSDT | SHORT | TP_clean | осторожно 70% |
| 1805 | 01.11 | 17:30 | FLOCKUSDT | LONG | SL_clean | осторожно 61% |
| 1804 | 01.11 | 08:33 | REUSDT | SHORT | TP_clean | осторожно 76% |
| 1803 | 01.11 | 05:32 | ZECUSDT | SHORT | TP_clean | осторожно 85% |
| 1802 | 01.11 | 03:30 | POWRUSDT | LONG | TP_clean | осторожно 60% |

## Cron jobs
- mmscan-daily-closer: next run 2026-11-05 03:00 UTC
- mmscan-hourly-backfill: next run 2026-11-04 18:30 UTC
- mmscan-snapshot: next run 2026-11-05 00:00 UTC

## Pending items (для PM)
- 4 REAL FLAG: ETHFI #132, TIA #137, POL #271, KERNEL #361
- 19 NOT_FOUND_IN_v17_13 (lessons learned)
- File-lock на shadow_journal saves (Phase 3b, отложено)

_v17_13 frozen; shadow lineage: live с 09.06 + 12.05–09.06 через FULL backfill_
