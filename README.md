# Global-Tourism-Travel-Trends-Analytics
This project explores patterns in a tourism-trip dataset using Python, Pandas, Matplotlib, and Seaborn. It examines travel purposes, destinations, trip spending, traveler groups, monthly patterns, ratings, and recorded carbon footprint.

## Dataset
The supplied CSV contains 10,000 trip records and 33 columns covering 2019–2024. One row represents one trip, which may include multiple travelers.

## What the notebook includes
- Dataset overview and data-quality checks
- Univariate, bivariate, and multivariate analysis
- 14 visualizations with explanations
- Six findings supported by calculations
- Summary, recommendations, and limitations
  
## Key findings
- Leisure/Tourism is the largest travel-purpose group, with 32.51% of records.
- Mean total trip spending is $11,549.69, while the median is $3,721.87. A small number of expensive trips raise the mean.
- Group tours have high total trip spending, but they also involve more travelers; total spending is not spending per person.
- Average total trip spending is highest in April and lowest in July.
- Air trips have a higher average recorded carbon footprint than rail trips in this dataset. The trips are not matched by distance or group size.
- 75.06% of trips received a rating of 4 or 5.

## Limitations
These results describe the supplied records, not all tourists worldwide. Group comparisons and correlations do not prove cause and effect. Trip totals may be affected by the number of travelers, and unusually high spending values affect averages.
