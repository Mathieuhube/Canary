The Canary - Small Analysis

This repository combines automated data engineering with macro-economic analysis to monitor market health and portfolio performance. 
It uses a "Canary" model to detect shifts in market regimes based on the relationship between global equities and gold.

This module fetches and stores data for MSCI ACWI (Equities) and GC=F (Gold) to identify four specific economic states:

- Inflationary Growth: Both Equities and Gold rising.
- Liquidity Crisis: Both Equities and Gold falling.
- Economic Trust: Equities rising while Gold falls.
- Economic Distrust: Equities falling while Gold rises.
