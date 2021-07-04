# Predicting-Stock-Prices-Using-Facebook-s-Prophet-Model
In this notebook, I  have experimented with using Prophet to forecast stock prices. Prophet uses a decomposable time series model with three main model components: growth, seasonality and holidays. They are combined using the equation
y(t) = g(t) + s(t) + h(t) + e(t),
where g(t) represents the growth function which models non-periodic changes, s(t) represents periodic changes due to weekly or yearly seasonality, h(t) represents the effects of holidays, and e(t) represents the error term. Such decomposable time series are very common in forecasting and later in the article we will see how to tune each component of the above equation.
