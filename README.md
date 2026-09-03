# XAUUSD 1w OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_754_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 1w OHLCV metals historical data** — ultra high-quality 1w OHLCV for **Gold / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Gold / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **2,754** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `XAUUSD_1w.csv` (8 rows, `2026-07-09` -> `2026-08-27`, 0.56 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **2,754** `1w` rows (full `1m`: 6,032,490), **11 timeframes**, `1970-02-26` -> `2026-08-27`.

## Download sample

**[XAUUSD_1w.csv](https://github.com/getdata-finance/xauusd-1w-ohlcv-metals-historical-data/blob/main/XAUUSD_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-1w-ohlcv-metals-historical-data/main/XAUUSD_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-1w-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-1w-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-1w-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 8 | **2,754** |
| Size | 0.56 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Period | `2026-07-09` -> `2026-08-27` | `1970-02-26` -> `2026-08-27` |
| File | `XAUUSD_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T00:00:00+00:00 | 4123.35 | 4134.83 | 3969.11 | 3975.77 | 6507414 |
| 2026-07-16T00:00:00+00:00 | 3975.77 | 4165.97 | 3959.49 | 4048.86 | 6819720 |
| 2026-07-23T00:00:00+00:00 | 4048.86 | 4120 | 3995.83 | 4102.92 | 6537198 |
| 2026-07-30T00:00:00+00:00 | 4102.92 | 4304.06 | 4018.99 | 4239.43 | 3958897 |
| 2026-08-06T00:00:00+00:00 | 4239.43 | 4449.69 | 4229.6 | 4349.95 | 4967523 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-30T00:00:00+00:00 | 4102.92 | 4304.06 | 4018.99 | 4239.43 | 3958897 |
| 2026-08-06T00:00:00+00:00 | 4239.43 | 4449.69 | 4229.6 | 4349.95 | 4967523 |
| 2026-08-13T00:00:00+00:00 | 4349.95 | 4540.88 | 4310.72 | 4518.53 | 4213195 |
| 2026-08-20T00:00:00+00:00 | 4518.53 | 4696.62 | 4508.71 | 4596.5 | 3420719 |
| 2026-08-27T00:00:00+00:00 | 4596.5 | 4626.71 | 4288.45 | 4289.48 | 3552634 |

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

df = pd.read_csv('XAUUSD_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAUUSD_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,754** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd)*
