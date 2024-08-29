### Mean Reversion Alpha Factor Research:

In this work, we will build a 3-Day Mean Reversion alpha factor on a portfolio of 20 stocks using 10 years historical data, and evaluate its performance on different forward hodling periods. Evaluation metrics include, expected forward returns, annualized Sharpe Ratio, information coefficient, Turnover, etc.

### Regression-base Momentum Alpha Factor Research:

In this work we  build a regression-based momentum alpha factor.

The term regression-based momentum alpha factor refers to a kind of alpha factor that combine linear regressions and simple returns. That means, a first alpha factor is constructed as a simple stock returns within a considered time window; the main time winow. In addition to that alpha factor, a second alpha factor is systematically constructed as the slop of a linear regression model built from a smaller sub time window of the main time window.

The smaller time window covers periods ranging from a certain time point inside the main time window until the upper bound of the main window. In this way, we believe that combining the slop and the returns yield strong information on stock price's futur direction. For instance, if the slop is strongly positive and the return is strongly positive, then we hope to see a strong upward trend for future returns  and vice versa. Thus we are dealing with a momentum type strategy.  Hence, long and short positions will be taken accordingly. 

The trading strategy will be evaluated using metrics that include, expected forward returns, annualized Sharpe Ratio, information coefficient, Turnover, etc.


### accelerated gain and decelerated loss momentum alpha factor

In this work, we are going to build joint alpha factors from the research paper **"The Formation Process of Winners and Losers in Momentum Investing".** 

The paper develops a model showing that past returns and the formation process of past returns have joint effect on future expected returns. That means, the past behavior of a stock that has become a winner (bullish) or a looser (bearish) plays an important role in momentum investing. 


### Market and stock regime features 

We calculate stock and market features which we hope will enhance the prediction potential of underlying alpha factors. 

Features serve as additional inputs that provide our  alpha model more context about market conditions.  Therefore, considered alpha models may be able to  learn to adjust their predictions accordingly. 
