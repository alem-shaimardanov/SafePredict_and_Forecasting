Description:
The Vector Autoregression (VAR) method models the next step in each time series using an AR model. It is the generalization of AR to multiple parallel time series.

Like the autoregressive model, each variable has an equation modelling its evolution over time. This equation includes the variable's lagged (past) values, the
lagged values of the other variables in the model, and an error term.  The only prior knowledge required is a list of variables which can be hypothesized to affect 
each other over time.

Parameters and equations:
A VAR model describes the evolution of a set of k variables, called endogenous variables, over time. Each period of time is numbered, t = 1, ..., T. The variables are collected in a vector, yt, which is of length k. 
The vector is modelled as a linear function of its previous value. The vector's components are referred to as y(i,t), meaning the observation at time t of the i-th variable. For example, if the first variable in the model measures the price of wheat over time, then y(1,1998) would indicate the price of wheat in the year 1998.
The past values of the series are used to forecast the current and future.



GitHub / Code snippet
Python API: https://www.statsmodels.org/dev/generated/statsmodels.tsa.vector_ar.var_model.VAR.html 
