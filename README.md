# The geometry of forecast reconciliation

## Abstract:

It is common to forecast at different levels of aggregation. For example, a retail company will want national forecasts, state forecasts, and store-level forecasts. And they will want them for all products, for groups of products, and for individual products. Forecast reconciliation methods allow for the forecasts at all levels of aggregation to be adjusted so they are consistent with each other.

I will describe a geometric interpretation for reconciliation methods used to forecast time series that adhere to known linear constraints. In particular, a general framework is established nesting many existing popular reconciliation methods within the class of projections. This interpretation facilitates the derivation of novel results that explain why and how reconciliation via projection is guaranteed to improve forecast accuracy with respect to a specific class of loss functions. The result is also demonstrated empirically using Australian tourism flows. I will also discuss how this geometric interpretation naturally extends to probabilistic forecasting.

Finally, I will show how these ideas can be easily implemented using the [fable package](http://fable.tidyverts.org) in R.

