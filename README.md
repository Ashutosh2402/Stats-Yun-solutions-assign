METHOD 
1. Copied and pasted the NIFTY's Straddle prices for different Dates and Expiry Dates from the website linked
2. Unnamed columns are the Index prices which we have ignored for predicting the straddle prices using time series.
3. Reason being the websites UI didn't allow to navigate to the right and the price at which the option is bought is not given   so the only information we could have gathered from the index prices would be the volatility of the stock
4. But since the graphs of premium straddle prices we plotted has an almost regular increasing trend for different expiry dates and since we have less data available we might get a good model for time series prediction using previous days price.
5. So the exact method would be - we will first predict the price of NIFTY on 12th March(i.e of dte=2) by using data from dte=3 to dte=8 on 14th March using SARIMA model.
6. We wanted to predict the price on the same day using the prices on dte=2 for different expiry dates. But the graph we got at different dte were non consistent(dte=6 graph has been plotted for reference here)
7. Hence we conclude the final straddle prices and then plot them accordingly for 12th March 2024
