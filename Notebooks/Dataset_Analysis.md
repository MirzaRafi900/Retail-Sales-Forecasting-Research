# Dataset Analysis

## Dataset Overview

The Rossmann Store Sales Dataset contains
1,017,209 observations and 18 features.

The target variable is Sales, representing
daily store sales across multiple Rossmann stores.

The dataset includes operational, customer,
promotional, temporal, and store-specific
characteristics that can potentially influence
sales performance.

## Data Quality Assessment

Missing values were identified primarily within:

- CompetitionDistance (2,642)
- CompetitionOpenSinceMonth (323,348)
- CompetitionOpenSinceYear (323,348)
- Promo2SinceWeek (508,031)
- Promo2SinceYear (508,031)
- PromoInterval (508,031)

No duplicate records were detected within the dataset.

## Initial Findings

Exploratory data analysis revealed that:

1. Sales distributions are positively skewed.

2. Different store types exhibit different sales patterns.

3. Promotional activities significantly increase sales.

4. Sales vary across different days of the week.

5. Store operational status directly influences sales.

6. Customer count shows a strong positive relationship
   with sales performance.

These observations indicate that retail sales are
affected by multiple business and operational factors,
which should be incorporated into forecasting models.