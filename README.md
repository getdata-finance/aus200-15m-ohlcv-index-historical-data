# AUS200 15m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-377_188_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 15m OHLCV index historical data** — ultra high-quality 15m OHLCV for **S&P/ASX 200**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **S&P/ASX 200** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **377,188** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AUS200_15m.csv` (10,947 rows, `2026-03-26` -> `2026-09-25`, 715.98 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **377,188** `15m` rows (full `1m`: 5,046,226), **11 timeframes**, `2008-09-10` -> `2026-09-25`.

## Download sample

**[AUS200_15m.csv](https://github.com/getdata-finance/aus200-15m-ohlcv-index-historical-data/blob/main/AUS200_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-15m-ohlcv-index-historical-data/main/AUS200_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aus200-15m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aus200-15m-ohlcv-index-historical-data/](https://getdata-finance.github.io/aus200-15m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aus200](https://getdata.finance/datasets/aus200)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | S&P/ASX 200 · Index | S&P/ASX 200 · Index |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 10,947 | **377,188** |
| Size | 715.98 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Period | `2026-03-26` -> `2026-09-25` | `2008-09-10` -> `2026-09-25` |
| File | `AUS200_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/aus200) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 8517 | 8518 | 8496.98 | 8510.48 | 697 |
| 2026-03-26T02:45:00+00:00 | 8510.48 | 8520 | 8505.5 | 8508.5 | 563 |
| 2026-03-26T03:00:00+00:00 | 8508.5 | 8513 | 8502.49 | 8511.99 | 324 |
| 2026-03-26T03:15:00+00:00 | 8511.99 | 8514 | 8506.98 | 8514 | 288 |
| 2026-03-26T03:30:00+00:00 | 8514 | 8526 | 8512.98 | 8522.98 | 519 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T19:30:00+00:00 | 8656.06 | 8664.07 | 8655.05 | 8663.55 | 195 |
| 2026-09-25T19:45:00+00:00 | 8663.55 | 8673.07 | 8663.55 | 8669.05 | 296 |
| 2026-09-25T20:00:00+00:00 | 8669.05 | 8670.07 | 8667.55 | 8667.55 | 65 |
| 2026-09-25T20:15:00+00:00 | 8667.55 | 8668.07 | 8664.57 | 8664.57 | 30 |
| 2026-09-25T20:30:00+00:00 | 8664.57 | 8667.55 | 8663.06 | 8667.55 | 50 |

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

df = pd.read_csv('AUS200_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_15m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUS200_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[getdata.finance](https://getdata.finance/datasets/aus200)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **377,188** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**

---
*GetData · AUS200 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aus200)*
