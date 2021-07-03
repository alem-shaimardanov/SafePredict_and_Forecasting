Description:
The Vector Autoregression Moving-Average with Exogenous Regressors (VARMAX) is an extension of the VARMA model that also includes the modeling of exogenous 
variables.

Exogenous variables are also called covariates and can be thought of as parallel input sequences that have observations at the same time steps as the original 
series. The primary series are referred to as endogenous data to contrast it from the exogenous sequence(s). 
The observations for exogenous variables are included in the model directly at each time step and are not modeled in the same way as the primary endogenous 
sequence (e.g. as an AR, MA, etc. process).

The method is suitable for multivariate time series without trend and seasonal components with exogenous variables.

GitHub / Code snippet
Documentation of a VARMAX Python library: https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.varmax.VARMAX.html 
