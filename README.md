# Pairs-Trade
A pairs trade or pair trading is a market neutral trading strategy enabling traders to profit from virtually any market conditions: uptrend, downtrend, or sideways movement. This strategy is categorized as a statistical arbitrage and convergence trading strategy.<br>
<br>
1) To explain what our strategy exactly does and how is it working, we have taken the example of the Indian Market, we have taken a few securities over a specified time interval. Then we have found all the cointegrated pairs of stocks from all the possible pairs of securities by considering all the stocks having p-value less than a certain cut-off. For further analysis, we have identified the security pair with minimum p-value for further analysis.<br>
2) Next we have calculated the spread of the two series. In order to actually calculate the spread, we use a linear regression to get the coefficient for the linear combination to construct between our two securities.
