# EURUSD 30m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_392_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full EURUSD dataset on ork.ad**](https://ork.ad/)

**EURUSD 30m OHLCV Forex historical data** — ultra high-quality 30m OHLCV for **Euro / US Dollar**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 30m OHLCV** for **Euro / US Dollar** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **9,392** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `EURUSD_30m.csv` (9,220 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **9,392** `30m` rows (~0.57 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-29` → `2026-07-02`.

## Download sample

**[EURUSD_30m.csv](https://github.com/ork-ad/eurusd-30m-ohlcv-forex-historical-data/blob/main/EURUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/eurusd-30m-ohlcv-forex-historical-data/main/EURUSD_30m.csv)) · [GitHub Releases](https://github.com/ork-ad/eurusd-30m-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/eurusd-30m-ohlcv-forex-historical-data/](https://ork-ad.github.io/eurusd-30m-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `30m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 30m rows | 9,220 | **9,392** |
| Size | 0.56 MB | ~0.57 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-29` → `2026-07-02` |
| File | `EURUSD_30m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`30m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `30m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_30m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T22:00:00Z | 1.17171 | 1.172112 | 1.171612 | 1.171832 | 657.0 |
| 2025-10-02T22:30:00Z | 1.171832 | 1.172062 | 1.171802 | 1.171902 | 543.0 |
| 2025-10-02T23:00:00Z | 1.171902 | 1.17231 | 1.171862 | 1.172242 | 988.0 |
| 2025-10-02T23:30:00Z | 1.172242 | 1.172602 | 1.172242 | 1.172492 | 1027.0 |
| 2025-10-03T00:00:00Z | 1.172492 | 1.172492 | 1.172082 | 1.172362 | 2412.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T20:00:00Z | 1.14302 | 1.14349 | 1.14288 | 1.14343 | 1183.0 |
| 2026-07-02T20:30:00Z | 1.14343 | 1.14348 | 1.1431 | 1.1431 | 932.0 |
| 2026-07-02T21:00:00Z | 1.1431 | 1.14337 | 1.14275 | 1.14327 | 723.0 |
| 2026-07-02T21:30:00Z | 1.14327 | 1.14328 | 1.14296 | 1.14327 | 589.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **9,392** rows at `30m`, plus all other timeframes in the same ZIP.

**[→ Get the full EURUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · EURUSD 30m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*