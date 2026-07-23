# Sample Superstore — Exploratory Data Analysis

Exploratory data analysis of the Sample Superstore dataset (9,994 US retail orders), built for the DLBDSEDAV01 course (Exploratory Data Analysis and Visualization).

## What's in here

- **Data Set - Superstore.ipynb** — full analysis notebook: descriptive statistics (location, variance, distribution, correlation) and four rounds of iterative visualization
- **superstore.csv** — the dataset (Sales, Quantity, Discount, Profit, Category, Region, and more)
- **outputround1_baseline.png** — default histogram and scatter plot, no styling
- **outputround2_distributions.png** — log-transformed sales distribution and profit-by-category boxplot
- **outputround3_correlation_heatmap.png** — correlation matrix across all numeric variables
- **outputround4_subcategory_profit.png** — total profit by product sub-category

## Key finding

Discount level, not sales volume, is what separates profitable product lines from money-losers. **Tables** generate $207K in sales but still lose **-$17.7K** overall, driven by a 26% average discount. **Copiers** earn **+$55.6K** profit on a comparable sales scale, with a more disciplined 16% average discount.

## Tools

Python · pandas · matplotlib · seaborn · scipy

## Author

Aynur Rzayeva-Karabulut
