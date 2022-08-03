# Time-Series-Analysis---currency-exchange-rate
We have the daily exchange rate of USD/EUR from January 1999 through December 31st 2020. We will aggregate the data on a weekly basis, by taking the average rate within each week. The time series of interest is the weekly currency exchange. We will analyze this time series and its first order difference.
Question 1a: Exploratory Data Analysis 

Before exploring the data, can you infer the data features from what you know about the USD-EUR currency exchange? Next plot the Time Series and ACF plots of the weekly data. Comment on the main features, and identify what (if any) assumptions of stationarity are violated.

Which type of model do you think will fit the data better: the trend or seasonality fitting model? Provide details for your response.

Question 1b: Trend Estimation

Fit the following trend estimation models:

Moving average
Parametric quadratic polynomial
Local Polynomial
Splines
Overlay the fitted values on the original time series.  Plot the residuals with respect to time for each model. Plot the ACF of the residuals for each model also. Comment on the four models fit and on the appropriateness of the stationarity assumption of the residuals.

Question 1c: Differenced Data Modeling

Now plot the difference time series and its ACF plot. Apply the four trend models in Question 1b to the differenced time series. What can you conclude about the difference data in terms of stationarity? Which model would you recommend to apply (trend removal via fitting trend vs differencing) such that to obtain a stationary process?

Hint: When TS data are differenced, the resulting dataset will have an NA in the first data element due to the differencing.

Temperature Analysis (40 Points)

In this problem, we will analyze aggregated temperature data.

 

Data file LA Temp Monthly.csv  Download LA Temp Monthly.csv contains the monthly average temperature of Los Angeles from January 1950 through December 2018. Run the following code to prepare the data for analysis:


You will perform the analysis and modelling on the 'temp' data column.

Question 2a: Exploratory Data Analysis 

Plot both the Time Series and ACF plots. Comment on the main features, and identify what (if any) assumptions of stationarity are violated. Additionally, comment if you believe the differenced data is more appropriate for use in fitting the data. Support your response with a graphical analysis.
Question 2b: Seasonality Estimation

Separately fit a seasonality harmonic model and the ANOVA seasonality model to the temperature data. Evaluate the quality of each fit with residual analysis. Does one model perform better than the other? Which model would you select to fit the seasonality in the data?

Question 2c: Trend-Seasonality Estimation

Using the time series data, fit the following models to estimate the trend with seasonality fitted using ANOVA:

Parametric Polynomial Regression
Non-parametric model
Overlay the fitted values on the original time series. Plot the residuals with respect to time. Plot the ACF of the residuals. Comment on how the two models fit and on the appropriateness of the stationarity assumption of the residuals.

What form of modelling seems most appropriate and what implications might this have for how one might expect long term temperature data to behave? Provide explicit conclusions based on the data analysis.

