# Stocastic-Volatility-with-PyMC-and-OANDA
Using Monte Carlo Markov Chains for Time Series Forecasting 

This is my version of the SVL model from the book https://github.com/mfrdixon/ML_Finance_Codes/blob/master/Chapter7-Probabilistic-Sequence-Modeling/ML_in_Finance-Kalman_Filters.ipynb

It is with OANDA broker and uses the package PyMC to calculate the MCMC - Monte Carlo Markov Chain. 

The prediction is done by putting other values for the length of the trace. After the inference was done the new estimated value can be compared to the old one.  

The same approach is applied for the second model as well. It is my adoption of the stochastic volatility example from PyMC3 https://docs.pymc.io/en/v3/pymc-examples/examples/case_studies/stochastic_volatility.html. The predictons are done, but more samples should be drawn to improve the prediction. 

If you have ideas to improve the current work do not hesitate to contact me :-D

Cheers and thank you!
