# TreasuryYieldCurve

Team Name and Names of the Contributors (sub-task-1)
Team Name: Yield Curve
Contributors: Jefferson Feaganes

Objective and Motivation: (sub-task-2)

Objective: Analyze U.S. Treasury yield curve behavior using Python and statistical methods to investigate volatility, inversions, predictability
Dataset: Department of the Treasury - Interest Rate Statistics - Daily Treasury Yield Curve Rates - https://catalog.data.gov/dataset/interest-rate-statistics-daily-treasury-yield-curve-rates?from_hint=eyJxIjoiIiwic29ydCI6InJlbGV2YW5jZSJ9
Daily Treasury Rates | U.S. Department of the Treasury - https://home.treasury.gov/resource-center/data-chart-center/interest-rates/TextView?type=daily_treasury_yield_curve&field_tdr_date_value=2026
Variables: Date and Treasury yields from 3-month to 30-year maturities.

Research Questions:

How does yield volatility vary by maturity?

How frequent / long were yield curve inversions from 2020 – 2025?

Can the 10Year – 2Year spread predict future spread changes?

Motivation: Apply computational and statistical methods to financial data to better understand interest rate behavior.

Introduction/Context of project: 

The Treasury yield curve represents interest rates across different maturities. An inversion occurs when short-term yields exceed long-term yields. This project uses the 10Year – 2Year spread to identify inversions and examine changes in interest rates.

Implementation Details: (sub-task-3 and sub-task-4)

Question 1: Volatility vs. Maturity: Calculate daily yield changes and standard deviations using pandas and NumPy. Use SciPy regression to compare volatility across maturities. Plot results with a bar chart and trendline.

Question 2: Spread Predictability: Calculate the 10Year – 2Year spread and daily changes using pandas. Use SciPy regression to find R^2 and p-values. Plot results with a scatterplot and regression line.

Question 3: Yield Curve Inversions: Calculate the 10Year – 2Year spread using pandas and identify negative periods. Measure inversion frequency and duration. Plot results with a time-series graph highlighting inversions.

Results (Answers to the Questions): (sub-task-6)


Conclusions: (sub-task-7)

Actions that need to be completed:

[ ] Download and clean Treasury data.

[ ] Perform statistical calculations and tests.

[ ] Generate graphs and analyze results.

References/Source files:

https://catalog.data.gov/dataset/interest-rate-statistics-daily-treasury-yield-curve-rates?from_hint=eyJxIjoiIiwic29ydCI6InJlbGV2YW5jZSJ9

https://home.treasury.gov/resource-center/data-chart-center/interest-rates/TextView?type=daily_treasury_yield_curve&field_tdr_date_value=2026
