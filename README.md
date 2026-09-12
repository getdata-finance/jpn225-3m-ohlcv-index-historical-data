# JPN225 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_832_392_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 3m OHLCV index historical data** — ultra high-quality 3m OHLCV for **Nikkei 225**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **1,832,392** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `JPN225_3m.csv` (60,236 rows, `2026-03-12` -> `2026-09-11`, 4.00 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **1,832,392** `3m` rows (full `1m`: 4,718,919), **11 timeframes**, `2008-09-01` -> `2026-09-11`.

## Download sample

**[JPN225_3m.csv](https://github.com/getdata-finance/jpn225-3m-ohlcv-index-historical-data/blob/main/JPN225_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-3m-ohlcv-index-historical-data/main/JPN225_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/jpn225-3m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/jpn225-3m-ohlcv-index-historical-data/](https://getdata-finance.github.io/jpn225-3m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/jpn225](https://getdata.finance/datasets/jpn225)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 60,236 | **1,832,392** |
| Size | 4.00 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2026-03-12` -> `2026-09-11` | `2008-09-01` -> `2026-09-11` |
| File | `JPN225_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/jpn225) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T02:30:00+00:00 | 54135.49 | 54174.99 | 54100.51 | 54117.51 | 205 |
| 2026-03-12T02:33:00+00:00 | 54117.51 | 54117.51 | 53980.49 | 53984.99 | 273 |
| 2026-03-12T02:36:00+00:00 | 53984.99 | 53984.99 | 53880.49 | 53889.99 | 264 |
| 2026-03-12T02:39:00+00:00 | 53889.99 | 53960.01 | 53840.5 | 53940.51 | 294 |
| 2026-03-12T02:42:00+00:00 | 53940.51 | 53950.01 | 53900.49 | 53900.5 | 175 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T20:30:00+00:00 | 64667.99 | 64697.49 | 64667.99 | 64697.49 | 14 |
| 2026-09-11T20:33:00+00:00 | 64697.49 | 64697.49 | 64663 | 64663 | 15 |
| 2026-09-11T20:36:00+00:00 | 64663 | 64677.49 | 64662.99 | 64672.49 | 17 |
| 2026-09-11T20:39:00+00:00 | 64672.49 | 64677.5 | 64663 | 64677.5 | 17 |
| 2026-09-11T20:42:00+00:00 | 64677.5 | 64677.51 | 64658 | 64662.99 | 31 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('JPN225_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,832,392** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
