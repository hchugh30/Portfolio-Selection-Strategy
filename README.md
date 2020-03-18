# Portfolio Selection Strategy
The goal of optimization effort is to create a tool that allows the user to make regular decisions
about re-balancing their portfolio and compare different investment strategies. The user wants to
consider the total return, the risk and Sharpe ratio. They may want to minimize/maximize any of
these components, while limiting one or more of the other components. The basic building block is
a decision made at the first trading day of each 2-month holding period: given a current portfolio,
the market prices on that day, and the estimates of the mean and covariance of the daily returns,
make a decision about what to buy and sell according to a strategy. Tested four strategies:

1. \Buy and hold" strategy;
2. \Equally weighted" (also known as \1=n") portfolio strategy;
3. \Minimum variance" portfolio strategy;
4. \Maximum Sharpe ratio" portfolio strategy.
