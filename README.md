# DS4002-CS3
This repository contains the study, deliverables, data, and reference materials necessary to complete the case study.

## (1) Important Information
To meet the case study requirements, follow the Hook and Rubric PDFs.

## (2) Data
This repository contains the contents necessary to implement our sentiment analysis, which consists of two files:

DATA FOLDER: 
* **[DATA/DS4002P2_RawData.xlsx](DATA/DS4002P2_RawData.xlsx)**: The raw dataset with two sheets. The first sheet contains our monthly Consumer Price Index and Medical Consumer Price Index values. This sheet runs from 2000-12-01 to 2025-01-01. The second sheet contains our annual Health Expenditure Index values. This sheet runs from 2001-01-31 to 2021-01-31.
* **[DATA/established.csv](DATA/established.csv)**: The established dataset with columns CPI, MCPI, and HEI. The index is the observation date, forward filled to annually at the end of the month. This set runs from 2000-12-31 to 2025-01-31. HEI values were not available from 2021 onwards and are marked as missing.

## (3) Materials
The analysis scripts and literature relevant to this project are in two folders:  

REFRENCE_MATERIAL FOLDER:
* **[SCRIPTS/eda.ipynb](SCRIPTS/eda.ipynb)**: This script uses raw data to perform exploratory data analysis and generate visualizations.
* **[SCRIPTS/make_data.ipynb](SCRIPTS/make_data.ipynb)**: This script uses raw data to create the established dataset found at [DATA/established.csv](DATA/established.csv).
* **[SCRIPTS/analysis.ipynb](SCRIPTS/analysis.ipynb)**: This script uses the established dataset train a linear regression model to predit Medical Care CPI based on the Health Expenditures Price Index. The script then uses SARIMAX (Seasonal Autoregressive Integrated Moving Average with eXogenous regressors) Model for time series forecasting. It generates scatterplot visualizations.
* **[LITERATURE/Article - National Health Expenditures.pdf](REFERENCE_MATERIAL/LITERATURE)**
* **[LITERATURE/Blog - Consumer Price Index (Medical Care).pdf](REFERENCE_MATERIAL/LITERATURE)**

 ## (4) References
[1] A. B. Martin, M. Hartman, B. Washington, A. Catlin, and The National Health Expenditure Accounts Team, “National Health Expenditures In 2023: Faster Growth As Insurance Coverage And Utilization Increased: Article examines National Health Expenditures in 2023,” Health Affairs, vol. 44, no. 1, pp. 12–22, Jan. 2025, doi: 10.1377/hlthaff.2024.01375.

[2] C. Cox, J. Ortaliza, E. Wager, and K. Amin, “How Has U.S. Health Care Spending Changed Over Time? - Health Care Costs and Affordability | KFF.” [Online]. Available: https://www.kff.org/health-policy-101-health-care-costs-and-affordability/?entry=table-of-contents-how-has-u-s-health-care-spending-changed-over-time

[3] U.S. Bureau of Labor Statistics, “How BLS Measures Price Change for Medical Care Services in the Consumer Price Index,” Bureau of Labor Statistics. [Online]. Available: https://www.bls.gov/cpi/factsheets/medical-care.htm

[4] U.S. Bureau of Economic Analysis, “Picking the Right Health Care Price Index | U.S. Bureau of Economic Analysis (BEA).” [Online]. Available: https://www.bea.gov/news/blog/2017-05-19/picking-right-health-care-price-index

[5] D. Wiczer, “Healthy inflation? | FRED Blog.” [Online]. Available: https://fredblog.stlouisfed.org/2017/07/healthy-inflation/

[6] J. Brownlee, “How to Create an ARIMA Model for Time Series Forecasting in Python - MachineLearningMastery.com.” [Online]. Available: https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/  
