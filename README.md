# Final_Project

James Goyette, Jhumi Parimal, Elizabeth Sun<br>

3 files. Deck, main jupyter notebook and the SQL file. The SQL portion was completely seperated from the main file but goes in #5 on the main file for continuity purposes. <br>

U.S. Personal Savings Rate Analysis: Post-COVID Macro Study<br>

Overview<br>
This project analyzes how U.S. personal savings rates have shifted since the COVID-19 pandemic and identifies which macroeconomic conditions are most associated with Americans saving more or less. The analysis is designed for everyday consumers and personal finance advisors, no economics background required.<br>

Research Question<br>
How have U.S. personal savings rates shifted since the COVID-19 pandemic, and which macroeconomic conditions (including unemployment, inflation, consumer sentiment, and income) are most associated with Americans saving more or less?<br>

Data<br>
Source: FRED (Federal Reserve Economic Data), Federal Reserve Bank of St. Louis<br>
Coverage: 12 monthly macroeconomic series, January 2015 – December 2024<br>
Observations: 120 rows, zero missing values<br>
Eras: Pre-COVID (2015–2019) · COVID (2020–2021) · Post-COVID (2022–2024)<br>

Tools & Methods

Python: data ingestion, EDA, feature engineering, and modeling<br>
SQLite: structured querying and storage of FRED series data<br>
Methods: Correlation analysis, era-based comparisons, engineered ratios (savings-to-income, credit-to-income), MinMaxScaler normalization, linear regression, and logistic regression<br>

Key Findings

The U.S. savings rate spiked to 31.8% in April 2020 (CARES Act stimulus + lockdown spending suppression) before collapsing to a historic low of ~3% in 2022<br>
Post-COVID is the worst savings era on record despite income being at its highest; inflation, housing costs, and revolving credit are absorbing income gains<br>
The strongest macro signals associated with lower savings: rising retail spending, growing revolving credit balances, and an elevated federal funds rate<br>
Falling consumer sentiment is a counter-intuitive leading indicator of increased precautionary saving<br>

Recommendations

Treat 3–5% as the realistic post-COVID savings baseline, not the pre-pandemic 6–8%<br>
Monitor CPI/PCE, revolving credit growth, and consumer sentiment as early-warning indicators<br>
Advisors should initiate savings conversations when sentiment drops, that's when clients are most receptive<br>

We used GenAI (specifically ChatGPT) to do a lot of our heavy lifting for coding. The primary use was to provide functions or outputs that we wanted and to return code that could be directly used in our file. Secondary uses included helping us interpret error messages, debugging those errors, and suggesting alternative functions or approaches that might improve our EDA. Finally, in some cases where we were unsure how to interpret the data (we are not economists), ChatGPT was used to provide a brief explanation of how to understand certain data points and their economic meaning.
