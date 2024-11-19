# time-series-forecast
A comparison of time-series forecasting methods (ARIMA, LSTM, LLM). 

---

# Project Stages Overview: 

**1. Data Collection**  
The project adopted comprehensive datasets from Statistics Canada, covering unemployment rate and wage data from 1997 to 2023. The data included variables such as province, industry classification, sex, and age group. This ensured that the analysis captured diverse aspects of the Canadian labor market.


**2. Data Preprocessing**  
To prepare the data for modeling, several preprocessing steps were implemented:
- **Data Cleaning**: Removal of data format inconsistencies.
- **Transformation**: Standardization of numeric variables using log transformation.
- **Handling Missing Values**: Linear interpolation was applied to manage missing data.
- **Feature Engineering**: Creatation of new features to optimize data for model use.


**3. Model Selection and Development**  
The study focuses on applying a combination of advanced time-series modeling approaches:
- **Traditional Models**: ARIMA, SARIMA, and Facebook Prophet were used for capturing linear and seasonal relationships.
- **Deep Learning Models**: Long Short-Term Memory (LSTM) and Large Language Model (LLM) networks were used for capturing non-linear dynamics and long-term dependencies.


**4. Model Training and Testing**  
The data was split into training (1997-2020) and testing (2021-2023) sets to evaluate model performance. This ensured robust validation, allowing the models to be assessed based on their ability to generalize to new, unseen data.


**5. Model Implementation**  
Each model was implemented using the most suitable programming frameworks:
- **ARIMA and SARIMA**: Deployed via the Statsmodels library for statistical modeling.
- **LSTM**: Constructed using TensorFlow and Keras to build a recurrent neural network that can effectively learn temporal dependencies.
- **TimesFM**: Implemented using the dedicated TimesFM package.


**6. Analysis and Interpretation**  
Model performance was assessed based on predictive accuracy, with comparisons made across:
- **Model Accuracy Metrics**: The MSE, RMSE, MAE, and MAPE were used to evaluate individual model performance.
- **Outcome Comparisons**: The Mean Absolute Percentage Error (MAPE) was used to evaluate performance across models.
- **Visualization**: Graphs were developed to enhance understanding of the forecast trends and the relative model performance.


**7. Results Presentation and Policy Recommendations**  
The final step involved synthesizing the findings to inform public policy:
- **Insights Derived**: The outcomes aim to provide a clear understanding of potential future employment and wage trends across various industries in Canada.
- **Policy Implications**: Recommendations for policymakers, based on model results. 

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
- eda_report_original ***.html***
-     *merged raw dataset*
- eda_report_interpolated ***.html***
-     *dataset after linear interpolation*
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
*FB Prophet*
- FB Prophet (unemployment) ***.ipynb***
- FB Prophet (wage) ***.ipynb***




