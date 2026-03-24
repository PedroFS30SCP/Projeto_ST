# ✈️ TSAF Project — Time Series Analysis and Forecasting

This project was developed as part of the **Time Series Analysis and Forecasting (ASTP)** course in the Master's in Data Science program.

The main objective is to apply **exploratory analysis, classical modeling, deep learning modeling**, and **causality analysis** techniques on time series related to the aviation sector, namely **flight delays and cancellations**, complemented with real weather data.

---

## 🗂️ Project Structure

```bash
📁 data/
├── flight-delay-dataset-2018-2022_Final.csv
├── weather-events-2018-2022_Final.csv
├── causality-dataset-2018-2022_Final.csv

📁 notebooks/
├── fligth-delay-cleaning.ipynb  
➡️ Cleaning and aggregation of flight delay and cancellation data, by date.

├── weather-events-cleaning.ipynb  
➡️ Processing and filtering of weather data, aggregating daily events by type.

├── fligth-delay-EDA.ipynb  
➡️ EDA of delay and cancellation series with normality and stationarity tests, etc.

├── weather-events-EDA.ipynb  
➡️ Full EDA of weather variables with visualizations, statistical tests, and correlations, etc.

├── modelacao-classica.ipynb  
➡️ Application of ETS models to forecast delays and cancellations, with in/out-of-sample evaluation.

├── modelacao-deep-learning.ipynb  
➡️ Training of an RNN for time series forecasting, with in/out-of-sample evaluation.

├── granger-causality.ipynb  
➡️ Granger causality test between weather events and flight operations, with visualizations and interpretation.
```
