# Investment_Strategies_Using_Python
This project evaluates $10,000 investment strategies for the SPY ETF using Python. It compares buy-and-hold, intraday, overnight, and modified buy-and-hold strategies, analyzing daily data and discussing real-world limitations to determine the best approach.


### Project Description: Evaluating Investment Strategies for SPY ETF in a Taxable Brokerage Account Using Python

#### Objectives:
- Implemented and evaluated different investment strategies using Python.
- Considered real-world limitations of these strategies.

#### Strategies Evaluated:
1. **Buy-and-Hold SPY ETF:** Invested $10,000 and held the SPY ETF over the evaluation period.
2. **Intraday Trading:** Bought SPY at the market open and sold at the market close each day.
3. **Overnight Trading:** Bought SPY at the market close and sold at the market open the next day.
4. **Modified Buy-and-Hold:** Bought-and-held SPY excluding the worst and best n days each year (where \( n \in \{1, 2, 3\} \)).

#### Methodology:
1. **Data Collection:** 
   - Obtained daily SPY ETF price data for a significant historical period.
   
2. **Implementation in Python:**
   - Developed Python scripts to simulate each strategy using the collected daily price data.
   
3. **Performance Metrics:**
   - Calculated and compared the performance metrics for each strategy, including:
     - Total return
     - Annualized return
     - Volatility
     - Sharpe ratio
     - Maximum drawdown

4. **Comparison and Analysis:**
   - Compared the performance of each strategy using the calculated metrics.
   - Discussed real-world limitations such as transaction costs, tax implications, and market conditions.

5. **Visualizations:**
   - Created visualizations to illustrate the performance and risks associated with each strategy.

6. **Conclusion:**
   - Provided a recommendation on which strategy is the most suitable for a $10,000 investment in a taxable brokerage account.
   - Highlighted the potential trade-offs and considerations for each strategy.

#### Outcomes:
- A comprehensive comparison of different SPY ETF investment strategies.
- Insights into the performance and practical limitations of each strategy.
- A clear recommendation for the best investment approach based on historical data and real-world considerations.
