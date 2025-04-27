# DS4002-CS3
This repository contains the study, deliverables, data, and reference materials necessary to complete the case study.

# Important Information
To meet the case study requirements, follow the Hook and Rubric PDFs.

# Data
This repository contains the contents necessary to implement our sentiment analysis, which consists of two files:

DATA FOLDER: 
* **[DATA/DS4002P2_RawData.xlsx](DATA/DS4002P2_RawData.xlsx)**: The raw dataset with two sheets. The first sheet contains our monthly Consumer Price Index and Medical Consumer Price Index values. This sheet runs from 2000-12-01 to 2025-01-01. The second sheet contains our annual Health Expenditure Index values. This sheet runs from 2001-01-31 to 2021-01-31.
* **[DATA/established.csv](DATA/established.csv)**: The established dataset with columns CPI, MCPI, and HEI. The index is the observation date, forward filled to annually at the end of the month. This set runs from 2000-12-31 to 2025-01-31. HEI values were not available from 2021 onwards and are marked as missing.

# Materials
The analysis scripts and literature relevant to this project are in two folders:  

REFRENCE_MATERIAL FOLDER:
* **[SCRIPTS/holder.ipynb](SCRIPTS/holder.ipynb)**: This script uses the established dataset train a linear regression model to predit Medical Care CPI based on the Health Expenditures Price Index. The script then uses SARIMAX (Seasonal Autoregressive Integrated Moving Average with eXogenous regressors) Model for time series forecasting. It generates scatterplot visualizations.
* **[LITERATURE/holder.ipynb](LITERATURE/holder.ipynb)**: These two pieces of literature highlight the changes in national health expenditures and how BLS measures price change for medical care Services in the consumer price index. 
