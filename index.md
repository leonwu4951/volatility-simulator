# Volatility Surface Simulator (Internal Tool)
The volatility surface simulator is an internal backtesting tool I created to **backtest and benchmark my own improvements to the production volatilty model.**

## Video Examples

These examples show how my model improved the stability and accuracy of the volatility smile during times of extremely low liquidity.

### Surface Shock Recovery
<iframe width="938" height="500" src="https://www.youtube.com/embed/Gh7tK0he-Gg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Option Nearing Expiry
<iframe width="938" height="500" src="https://www.youtube.com/embed/W0GgPyomxOw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## My Improvements:
- New weight functions
- New penalty functions
- No-arbitrage constraints
- Robust regression methods
- L1 norm methodologies to handle outliers more effectively
- New liquidity model
- Smoothing functions
- Constrained optimization methods


---
---
# Volatility Surface Explorer > >[(Webapp Link)](http://vol-app-prod.us-east-2.elasticbeanstalk.com/)< < 

![Image](/assets/2D.png)
![Image](/assets/3D.png)

This volatility surface explorer is an options trading and pricing tool I built, enabling market makers and traders to visualise real-time and historical simulations of volatility surfaces, market quotes, and trades.

Using the tool, you can **view proprietary implied volatility surface marks generated from my own model**, and explore live or historical volatility surfaces in 2D or 3D through simulations.

Created in Plotly Dash (Python), CSS and HTML.
