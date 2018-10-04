# stock-reinforcement-learning
**Computer Project – Reinforcement Learning in Stock Trading Systems**  
**Overview**

* Three reinforcement learning relative algorithms which provide daily-trade strategy to a single stock.
  * Q-Learning, which is relatively simple and intuitive, we compare its result with the other two algorithms.
  * Approximate Q-Learning
    * Solution to the precision problem of Q-Learning
    * Our training-trading flow, trading action level, reward function definition.
    * Effects of each parameters.
    * Design 8 features based on supposed price, popular technical indicators, etc.
  * Continuous Rise-Fall Algorithm
    * The idea came from Q-Learning. We defined states by the number of days in a row which stock price rise/fall.
    * Simple and very explainable.

* Testing methods
  * Comparing with the algorithms corresponding to the technical indicators such as KD, PSY, RSI.
  * All algorithms in this project trade with daily close prices, without considering the trade cost.
  * Different from several relative papers which only show the trading results of few numbers of stock, we observe the result of nearly a thousand of stocks.
    * Each algorithms and indicators only consider technical information such as stock price. It’s difficult to have steady results among different stocks.
    * Testing by lots of stocks and observe the overall result, we can tuning parameters more effectively and providing more persuasive results.

* Results
  * Observe the trading result of all random selected stocks, raising-trend stocks and falling-trend stocks.
  * Approximated Q-Learning and continuous rise-fall algorithm perform better than Q-Learning and the indicators.
