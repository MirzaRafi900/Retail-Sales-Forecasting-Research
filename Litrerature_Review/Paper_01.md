# Literature Review Paper 01

## Paper Information

Title:
Comparative Analysis of Modern Machine Learning Models for Retail Sales Forecasting

Authors:
Luka Hobor
Mario Brčić
Lidija Polutnik
Ante Kapetanović

Year:
2025/2026 (arXiv Version)

Source:
arXiv

---

## Research Problem

Accurate sales forecasting is essential for retail businesses
to optimize inventory management, resource allocation,
and profitability.

The study investigates which forecasting approach performs best
under real-world brick-and-mortar retail conditions characterized by:

- Missing values
- Intermittent demand
- Product turnover
- Store-level variability

---

## Dataset

Retail sales data collected from a major retailer in
Southeast Europe.

Characteristics:

- 46,841 SKU time series
- 446 stores
- Hygiene products category
- 20.93% missingness
- 99.98% of series contain zero-sale days

These properties make forecasting challenging.

## Methodology

The researchers compared:

Statistical Models:
- Theta
- ETS
- Croston SBA

Machine Learning:
- XGBoost
- LightGBM

Deep Learning:
- N-BEATS
- N-HiTS
- Temporal Fusion Transformer (TFT)

Four experimental settings were tested:

1. Individual groups
2. Whole category
3. Individual groups with imputation
4. Whole category with imputation

## Evaluation Metrics

- RMSE
- MAE
- RMSSE
- MASE
- Demand Error
- Demand Bias

## Key Findings

1. XGBoost achieved the highest forecasting accuracy.

2. LightGBM achieved competitive results.

3. Tree-based ensemble methods consistently outperformed
deep learning architectures.

4. Data quality significantly influenced forecasting performance.

5. Model complexity does not necessarily lead to
better forecasting accuracy.

## Limitations

1. The research focused on one retail category.

2. The dataset originated from a specific geographical region.

3. Only selected machine learning and deep learning
models were evaluated.

4. The study focused primarily on forecasting accuracy
rather than explainability.

## Research Gap

The study demonstrated the superiority of tree-based
models such as XGBoost and LightGBM.

However:

1. Explainable AI techniques were not explored.

2. Model interpretability was not studied in depth.

3. Human-AI decision support capabilities were not evaluated.

4. Research assistants capable of helping retailers
understand forecasting outcomes were not investigated.

## Relevance To My Research

This paper provides strong evidence that machine learning
models, particularly XGBoost and LightGBM, are highly
effective for retail sales forecasting.

The findings support the inclusion of tree-based models
within my future forecasting experiments.

The identified limitations also suggest opportunities
for future research in explainable AI and intelligent
decision support systems.

## Personal Reflection

This paper taught me that more advanced deep learning
architectures do not always outperform well-tuned
machine learning models.

I learned that understanding the dataset and business
problem is often more important than selecting the
most complex model.

This insight will influence both my retail forecasting
research and future work on intelligent AI systems.
