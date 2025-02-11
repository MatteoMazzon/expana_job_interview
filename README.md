# expana_job_interview

I've analyzed the time series in the following file: assignment_expana_01.ipynb

In this assignment, I analyzed the time series, identified potential patterns, and aimed to build a model capable of performing well on unseen data and reliably predicting the time series development for 2023. Specifically:

In the first part, I analyzed the time series. Due to the difficulty in determining the appropriate order for the ARIMA model and the lack of meaningful insights from the ACF and PACF plots, I adjusted the frequency of the time series to a monthly interval and attempted to forecast future values using a SARIMA model. Unfortunately, the results were unsatisfactory, and the predicted values had a different frequency than the original series. I've also attempted to forecast the test set using an ARIMA model. However, the correlation and partial correlation plots provided unclear insights, making it difficult to determine an optimal order for the model that could effectively capture price fluctuations in the test set. Additionally, the predictions using monthly frequency data yielded unsatisfactory results. Due to these challenges, I opted to proceed with a classical machine learning approach instead.

In the second part, I shifted to using supervised machine learning techniques to build a model. I implemented feature engineering (detailed below) and experimented with a set of variables to enhance prediction accuracy. Based on the patterns identified in the analysis and the results obtained, the machine learning model emerged as the most suitable approach for forecasting the time series in 2023. However, there is still potential for further improvements.
