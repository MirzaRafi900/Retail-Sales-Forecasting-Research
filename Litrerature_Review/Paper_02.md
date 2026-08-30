# Literature Review Paper 02

## Paper Information

### Title
Sales Forecasting for Retail Stores Using Hybrid Neural Networks and Sales-Affecting Variables

### Authors
Saad Mansur, Kashif Sattar, Seyed Ebrahim Hosseini,
Shahbaz Pervez, Iftikhar Ahmad,
Kashif Saleem, Ahmed Zohier Elhendi

### Year
2025

### Journal
PeerJ Computer Science

### DOI
10.7717/peerj-cs.3058

---

## Research Problem

Accurate sales forecasting remains a major challenge in retail
because customer demand is influenced by multiple factors such as:

- Historical sales trends
- Weather conditions
- Holidays
- Salary days
- Social events
- Consumer behaviour

Many previous studies focused only on historical sales data
and ignored important environmental and demographic variables,
leading to reduced forecasting accuracy. The authors aimed to
develop a forecasting model capable of capturing both temporal
and contextual influences on retail sales.

## Dataset

The study utilized a real-world retail sales dataset obtained
from Kaggle.

Dataset Characteristics:

- Daily retail sales records
- 6 months of historical sales data
- Retail store in Faisalabad, Pakistan

Additional Variables:

Environmental Factors:
- Rainfall
- Temperature

Demographic Factors:
- Holidays
- Salary days
- Promotions
- Protests
- Store status (open/closed)

The dataset was enriched with external information to improve
forecasting accuracy.

## Models Used

Baseline Models:

1. ANN (Artificial Neural Network)
2. CNN (Convolutional Neural Network)
3. LSTM (Long Short-Term Memory)

Proposed Model:

4. Hybrid CNN-LSTM Model

## Methodology

The researchers proposed a hybrid deep learning architecture
combining CNN and LSTM.

CNN Component:
- Captures short-term patterns
- Identifies local sales fluctuations
- Extracts feature representations

LSTM Component:
- Captures temporal dependencies
- Learns trends and seasonality
- Models long-term behaviour

Data Preprocessing Included:

- Data cleaning
- Normalization using Min-Max Scaling
- Feature engineering
- Conversion of qualitative variables
- Integration of weather and demographic factors

Performance Evaluation:

- MAE
- RMSE
- MAPE

## Key Findings

The hybrid CNN-LSTM model achieved the highest forecasting
performance among all evaluated models.

Performance:

MAPE = 4.16%
MAE = 11,165
RMSE = 26,200

Key Observations:

1. Hybrid CNN-LSTM significantly outperformed
   standalone ANN, CNN, and LSTM models.

2. Environmental factors improved forecasting accuracy.

3. Demographic variables had substantial impact
   on sales prediction.

4. Combining environmental and demographic variables
   produced the best results.

5. The model successfully captured sales spikes and
   seasonal fluctuations.

## Comparative Model Performance

ANN:
MAPE = 19.74%

CNN:
MAPE = 13.90%

LSTM:
MAPE = 10.39%

Hybrid CNN-LSTM:
MAPE = 4.16%

Finding:

Hybrid learning architectures can outperform
single deep learning models in retail forecasting.

## Limitations

1. The dataset included data from only one retail store.

2. Results may not generalize across different
   countries, industries, or store formats.

3. The research focused on deep learning models and
   did not compare against modern tree-based methods
   such as XGBoost and LightGBM.

4. Potential overfitting was observed due to sales spikes
   and limited data duration.

5. Only six months of historical data were used.

## Research Gap

Several important opportunities remain for future research:

1. Compare hybrid CNN-LSTM with XGBoost and LightGBM.

2. Evaluate forecasting performance on larger datasets.

3. Improve model explainability using Explainable AI (XAI).

4. Investigate hybrid systems that combine deep learning
   and machine learning approaches.

5. Develop intelligent forecasting assistants capable of
   explaining forecasting outcomes to decisionmakers.
