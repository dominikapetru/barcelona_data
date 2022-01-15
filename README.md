# Barcelona accumulated precipitations
Analysis of historic data of accumulated precipitations in Barcelona. The aim of the project is to analyze and possibly predict future values with machine learning algorithms.

## Content

#### 1. Data
- Dataset downloaded from OpenData Barcelona site.https://opendata-ajuntament.barcelona.cat/data/ca/dataset/precipitacio-hist-bcn/resource/6f1fb778-0767-478b-b332-c64a833d26d2
- Data are structured in time from 1786 to 2020.
#### 2. PosgreSQL database
- Tables year and month relate to the table precipitation.
#### 3. SQL query
- Get values of accumulated precipitation with corresponding year and month.
#### 4. Exploratory analysis
- What is the distribution of precipitation values?
- What can be observed from the evolution by years and by months?
- Is there a trend or seasonality in the observed values?
#### 5. Times series
- Stationarity, Dickey-Fuller test
- Observe trend, seasonality
- Autocorrelation and Partial autocorrelation to get parameters p,d,q
- Arima, autoregressive integrated moving average model
- Evaluation
- Forecast
#### 6. Supervised ML: Regression model
- Add more data - average temperature values
- Train and test
- Standardization of values with StandardScaler method
- Regression algorithms
- Cross Validation
- Evaluation
- Forecast
#### 7. Unsupervised ML: K-Means method to observe commen patterns
- Standardization of values with StandardScaler method
- PCA reduction to 2 main components
- Define the best number of clusters
- Evaluate the model
- Observe the final clustres and their common patterns
