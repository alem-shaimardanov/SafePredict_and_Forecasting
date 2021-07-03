Description:
The Vector Autoregression Moving-Average (VARMA) method models the next step in each time series using an ARMA model. 
It is the generalization of ARMA to multiple parallel time series.

Given a time series of data Xt , the ARMA model is a tool for understanding and predicting future values in this series. 
The AR part involves regressing the variable on its own lagged (i.e., past) values. The MA part involves modeling the error term as a linear combination of error 
terms occurring contemporaneously and at various times in the past. 

Parameters and equations:
The general form of a VARMA(p,q) process with VAR order p and MA order q is
where  is a white noise process with nonsingular covariance matrix .
mu is the mean of the series.
Thetas are the parameters of the model.


GitHub / Code snippet:
Documentation of a VARMAX Python library: https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.varmax.VARMAX.html 
