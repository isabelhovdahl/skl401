# FRED data

This folder contains monthly and quarterly US macroeconomic time series sourced from FRED, maintained by the Federal Reserve Bank of St. Louis.

## Files

### `FRED_monthly_<decade>.csv`

Monthly data split into one file per decade (`FRED_monthly_1950.csv` through `FRED_monthly_2010.csv`, covering 1950–2019). Each file contains the same five columns:

| Column     | Description                                                                 |
|------------|-------------------------------------------------------------------------------|
| `DATE`     | First day of the month                                                       |
| `CPI`      | Consumer Price Index for All Urban Consumers: All Items in U.S. City Average (Index, 1982–84 = 100) |
| `UNRATE`   | Unemployment rate (percent) |
| `FEDFUNDS` | Effective federal funds rate (percent) |
| `REALRATE` | 1-year real interest rate, (percent) |
| `LFPART`   | Labor force participation rate (percent) |

### `GDP.csv`

Quarterly US real gross domestic product, in billions of chained 2017 dollars, covering 1947–2024. Contains two columns: `DATE` (first day of the quarter) and `GDP`.

## Source and acknowledgment

This data was obtained from the course materials for [TECH2](https://github.com/richardfoltyn/TECH2-H25/tree/main/data/FRED), taught by Richard Foltyn at the Norwegian School of Economics (NHH), and is used here with thanks for teaching in SKL401. The original data was in turn sourced from FRED. Please refer to the [FRED website](https://fred.stlouisfed.org/) for the most current values, full methodology, and terms of use for these series.