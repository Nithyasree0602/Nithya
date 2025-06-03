🚌 Public Transport Passenger Journey Forecasting (Kovai.co Task)
📌 Task Overview
As part of the Kovai.co Data Science Interview Challenge, we were tasked with:

📊 Analyzing the public transport dataset and deriving 4–5 key insights.

🔮 Forecasting passenger journeys for the next 7 days across the following service types:

Local Route

Light Rail

Peak Service

Rapid Route

School

✅ Solution Highlights
📈 Prophet was used for forecasting due to its suitability for seasonal time series data.

🧹 Cleaned, sorted, and forward-filled the dataset.

📊 Performed exploratory analysis and generated detailed trend and correlation plots.

🧠 Identified seasonality, dips, spikes, and strong correlations between routes.

📉 Time series decomposition was applied to analyze trend/seasonality per service.

📦 Generated 7-day forecasts for each transport service, including confidence intervals.

📋 Summarized forecasts in a tabular view for quick interpretation.

🧪 Used cross-validation to compute MAPE and RMSE for each model.

🧠 (Optional) Added a School reopening scenario simulating a 25% increase in usage.

🔍 Key Insights
Rapid Route and Local Route share strong correlation (~0.96), suggesting similar usage patterns.

School service is inactive during long stretches — clearly dependent on academic schedules.

Peak Service dips appear around holiday periods.

Light Rail shows a steady growth pattern over time.

All services display clear seasonal components, validating the use of time-series models.

📊 Tools & Libraries
Python 3.x

pandas, matplotlib, seaborn

prophet (Facebook's time series forecasting model)

statsmodels (seasonal decomposition)

🧠 Why Prophet?
Automatically detects seasonality and trend changes

Offers interpretable components (trend, seasonality)

Quick to implement, ideal for short-term operational forecasting

Built-in support for cross-validation and uncertainty intervals
