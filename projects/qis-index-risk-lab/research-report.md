# Computed synthetic research report

Software evidence only; no empirical investment evidence.

All scenarios use common evaluation dates. Figures below include inception costs and pre-inception capital anchor 100.

|Scenario|CAGR|Volatility|Sharpe|Max drawdown|Total turnover|Costs (index points)|
|---|---:|---:|---:|---:|---:|---:|
|baseline_gross|2.05%|5.39%|0.027|-13.85%|38.32|0.0000|
|baseline_net|1.96%|5.39%|0.010|-13.89%|38.32|2.1838|
|cash|2.05%|0.08%|N/A|0.00%|0.00|0.0000|
|cost_10bps|1.86%|5.39%|-0.007|-13.93%|38.32|4.3222|
|cost_20bps|1.68%|5.39%|-0.041|-14.00%|38.31|8.4664|
|equal_gross|0.10%|14.23%|-0.065|-43.21%|7.99|0.0000|
|equal_net|0.08%|14.23%|-0.066|-43.23%|7.99|0.3716|
|lookback_126|2.92%|5.25%|0.188|-11.75%|43.00|2.8400|
|reference_14pct|1.80%|6.59%|-0.004|-16.48%|40.93|2.2440|
|reference_6pct|2.15%|4.13%|0.045|-13.41%|36.29|2.1643|
|trend_gross|1.06%|8.05%|-0.081|-29.64%|31.97|0.0000|
|trend_net|0.98%|8.05%|-0.090|-29.88%|31.97|1.6292|
|vol_window_126|1.43%|5.82%|-0.075|-16.21%|38.96|2.0875|

The sensitivity set is exploratory; no winning parameter is selected. Designed regimes and a chosen universe cannot establish historical profitability.

Retrospective synthetic evaluation; inspected in this delivery; no tuning. No historical holdout inspected.

Daily asset P&L, cash interest, and negative costs are additive index-point attribution. Summing these explains final index minus 100; daily percentages are not presented as compounded attribution.

Historical stress-window results: unavailable because no historical dataset is licensed or loaded. Frozen-holdings shocks in results.json are hypothetical.
