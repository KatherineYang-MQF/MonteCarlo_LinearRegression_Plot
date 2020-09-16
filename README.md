Industry_Portfolios.xlsx contains monthly returns for a portfolio of 10 industries. First, calculate mean, standard deviation and covariance matrix for the portfolio. Second, plot 2 minimum-variance frontiers without riskless asset and with riskless asset respectively. The 2 frontiers intersect at a single point which leads to the tangency portfolio with the highest Sharpe ratio.
Market_Portfolio.xlsx contains monthly returns for the market portfolio. This part mainly applies linear regression method. First, regress monthly returns for each industry on monthly return for the market portfolio, and generate intercept and slope coefficients for each industry. Second, regress mean returns for each industry on slopes for each industry, in order to obtain intercept and slope coefficient for SML (Security Market Line). Third, plot SML and mean returns for 10 industries. The points above SML are underpriced, while the points below SML are overpriced.

First, generate performance metrics of Sharpe ratio, Sortino ratio, Jensen's alpha, and Three-Factor alpha. Among those, Jensen's alpha and Three-Factor alpha are generated by applying simple and multiple linear regression respectively. Second, generate 10 numbers from uniform distribution and divide each number by the sum of the 10 numbers, in order to obtain weights of each industry which ensures total weight to be 1. Calculate mean and standard deviation of the portfolio. By applying Monte Carlo simulation, repeat this process for 10,000 times and plot scattered points.