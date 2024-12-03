# time-series-forecast
A comparison of time-series forecasting methods (ARIMA, SARIMA, FB Prophet, LSTM). 

---
# Overview
This repository contains the project "Forecasting the Future of Work: 
Advanced Predictive Analytics for Understanding Canadian Employment Trends." 

The project aims to predict Canadian employment trends by leveraging advanced predictive analytics and big data methodologies. The study employs ARIMA, SARIMA, FB Proohet, and LSTM to forecast unemployment rates and employment wages.

# Project Stages: 

**1. Data Collection**  
The project adopted comprehensive datasets from Statistics Canada, covering unemployment rate and wage data from 1997 to 2023. The data included variables such as province, industry classification, sex, and age group. This ensured that the analysis captured diverse aspects of the Canadian labor market.


**2. Data Preprocessing**  
- *Data Cleaning*: Removal of data format inconsistencies.
- *Transformation*: Standardization of numeric variables using log transformation.
- *Handling Missing Values*: Linear interpolation was applied to manage missing data.
- *Feature Engineering*: Creatation of new features to optimize data for model use.


**3. Model Selection and Development**  
- *Traditional Models*: ARIMA, SARIMA, and Facebook Prophet were used for capturing linear and seasonal relationships.
- *Deep Learning Models*: Long Short-Term Memory (LSTM) was used for capturing non-linear dynamics and long-term dependencies.


**4. Model Training and Testing**  
- *Training*: 1997 - 2020
-  *Testing*: 2021 - 2023

**5. Model Implementation**  
- *ARIMA and SARIMA*: Statsmodels library 
- *FB Prophet*: prophet library
- *LSTM*: TensorFlow and Keras 


**6. Analysis and Interpretation**  
Model performance was assessed based on predictive accuracy, with comparisons made across:
- *Model Accuracy Metrics*: The MSE was used to evaluate individual model performance.
- *Outcome Comparisons*: The Mean Absolute Percentage Error (MAPE) was used to evaluate performance across models.
- *Visualization*: Graphs were developed to enhance understanding of the forecast trends and the relative model performance.


**7. Results Presentation and Policy Recommendations**  
- *Results*: All model results are documented in ***.html*** format

---

# Important Considerations
## Datasets
All analysis ***.ipynb*** files are coded to automatically retrieve the appropriate working datasets; however, the codes to download all of them separately for additional inspection are found in the **datasets** folder.

# Repository Structure
**datasets**
- unemployment rate (csv download) ***.ipynb***
- wage rate (csv download) ***.ipynb***
- cleaned data (csv download) ***.ipynb***

**exploratory analysis**
- eda_report_original  *merged raw dataset* ***.html***
- eda_report_interpolated *dataset after linear interpolation* ***.html***
- exploratory analysis (unemployment & wage) ***.ipynb***
- exploratory analysis (unemployment & wage) ***.html***

**statistical analysis**

*ARIMA*
- ARIMA (unemployment) ***.ipynb***
- ARIMA (unemployment) ***.html***
- ARIMA (wage) ***.ipynb***
- ARIMA (wage) ***.html***

*SARIMA*
- SARIMA (unemployment) ***.ipynb***
- SARIMA (unemployment) ***.html***
- SARIMA (wage) ***.ipynb***
- SARIMA (wage) ***.html***
- Additional Models (less effective model parameters) ***folder***

*FB Prophet*
- FB Prophet (unemployment) ***.ipynb***
- FB Prophet (unemployment) ***.html***
- FB Prophet forecast plots (unemployment) ***.html***
- FB Prophet (wage) ***.ipynb***
- FB Prophet (wage) ***.html***
- FB Prophet forecast plots (wage) ***.html***

*LSTM*
- LSTM (unemployment) ***.ipynb***
- LSTM (unemployment) ***.html***
- LSTM (wage) ***.ipynb***
- LSTM (wage) ***.html***
- Additional Models (less effective model parameters) ***folder***
