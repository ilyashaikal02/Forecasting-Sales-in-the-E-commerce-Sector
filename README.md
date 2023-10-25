# Forecasting-Sales-in-the-E-commerce-Sector

In this project, various sales forecasting approaches including SARIMAX, Facebook's Prophet, LSTM, and XG Boost Regression were explored and optimized to find the most suitable model for forecasting sales on the Olist platform, given its limited historical data. Extensive data processing was carried out to create a master table, clean the data, and add relevant features such as holidays obtained from a Brazilian national holiday website.

Key insights regarding the volume of orders, customer retention, product diversity, and revenue generation were derived from the data. A notable insight was the significant revenue increase observed annually and during special events like Black Friday.

The sales data was pre-processed into a time series format, and a thorough time series analysis was performed to observe trends and seasonality, which revealed a positive revenue trend and a substantial revenue increase over the years.

Several forecasting models were applied and fine-tuned, with a focus on including the impact of holidays on sales. Among the models, the Facebook Prophet model was chosen for final sales forecasting due to its ability to capture seasonality, trend, and weekly variations, yielding a Mean Absolute Percentage Error (MAPE) of 51.45%.

