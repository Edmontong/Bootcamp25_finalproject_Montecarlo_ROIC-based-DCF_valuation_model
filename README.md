# Bootcamp25_finalproject_Montecarlo_ROIC-based-DCF_valuation_model

Montecarlo_ROIC-based-DCF_valuation_model for PEPSICO(Ticker: PEP)

In this project, we intend to create a dcf model for valuation of PEPSICO in a 10 year horizon, using MOnte carlo simulations and ROIC_based dcf.
We extract PEPSICO's past 75 years of financial data, 1950-2024 and insert to a Monte Carlo layer for simulation. These data all come from WRDS, compustat database.
We then take the monte carlo layer simulated financials and plug in ROIC based dcf model which uses ROIC*Reinvestment Rate for revenue growth rate.
As we simulate 5000 times, we obtain 5000 distinct valuations simulating the company undergoing different circumstances for the following 10 years, and their potential equity value under such circumstances
We desire to obtain a PEPSICO valuation that is more accurate and accounts for various scenarios comparing to a traditional, simple DCF
For our conclusion, we present the mean&median equity value, mean&median per share price, and a 90% confidence interval valuation. We also compare our findings to a simple dcf's valuation, as well as current equity value and per share price; 
