# econ3916-lab03-visualization
Honest vs. Misleading Visualizations
Objective
Evaluate how visualization choices can clarify or distort economic evidence and apply systematic exploratory data analysis to produce accurate, transparent conclusions.
Methodology
- Recreated Anscombe’s Quartet to demonstrate how datasets with nearly identical summary statistics can have fundamentally different visual patterns.
- Calculated a Lie Factor of 49.0 for a truncated-axis revenue chart and redesigned it using an honest scale and direct labels.
- Adjusted FRED average hourly earnings for inflation using the Consumer Price Index, expressing wages in constant 2020 dollars.
- Compared four presentations of the same wage series using full, truncated, cherry-picked, and logarithmic scales.
- Applied a four-step EDA framework—structure, distributions, relationships, and anomalies—to World Bank GDP data covering 262 country and regional economy codes across 64 years (1960–2023).
- Built an interactive chart toggler that displays how axis choices affect the chart’s live Lie Factor.
Key Findings
Anscombe’s Quartet showed that similar means, variances, correlations, and regression lines can conceal dramatically different data structures. The truncated revenue chart transformed an actual 4.1% increase into an apparent 200% visual increase, producing a Lie Factor of 49.0. The wage analysis demonstrated that time windows, axis limits, and scale transformations can create different narratives from identical data. Finally, the GDP analysis revealed substantial right-skewness, making a logarithmic transformation necessary to compare economies and identify patterns more clearly.
