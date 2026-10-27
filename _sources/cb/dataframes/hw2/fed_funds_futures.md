# Dataframe: `hw2:fed_funds_futures` - Fed Funds Futures

Daily bars from GLBX.MDP3 using parent symbol ZQ.FUT and schema ohlcv-1d. Includes outright contracts and calendar spreads; filter spreads before calculating implied rates.


## DataFrame Glimpse

```
Rows: 11751
Columns: 7
$ date   <datetime[ns]> 2026-10-25 00:00:00
$ symbol          <str> 'ZQF7'
$ open            <f64> 95.895
$ high            <f64> 95.895
$ low             <f64> 95.89
$ close           <f64> 95.895
$ volume          <u64> 396


```

## Dataframe Manifest

| Dataframe Name                 | Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           |                                              |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API                                                   |
| Data available up to (min)     | 2026-10-25 00:00:00                                                             |
| Data available up to (max)     | 2026-10-25 00:00:00                                                             |
| Dataframe Path                 | /Users/marco/Projects/finm-32800/hw2/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///Users/marco/Projects/finm-32800/hw2/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-26 23:44:14           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

