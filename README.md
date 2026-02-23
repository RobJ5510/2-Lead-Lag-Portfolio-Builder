**2-Lead-Lag-Portfolio-Builder**

**Description:**
This is a python script built in Juypter Notebook that uses publically available data to quantify how one stock moves in relation to another

It tracks the movements of Stock A (i.e. if it goes up or down), then works out the probability of Stock B going up or down the following trading day, or two days after that ect.

Then it will take, given your input, the most correlative sets of stocks (for example Stock B goes up 58.1% of the time 1 day after Stock A goes down) and works out the Sharpe Ratio of your investment if you to invest every time that signal.

Finally, the Portfolio Builder takes the best few Sharpe Ratio stock pairs and turns it into a Investment Strategy, and plots the returns of that entire portfolio.

**Next Steps that will be executed in the Future:**
Ability to change certain constants, like Risk Free Rate or the dates of the Backtest, without just going in and editing the code
Make the UI better on Juypter or have it create a window of its own to run
Increase its efficiency of calculations, eliminate any wasted computational power from the 1st Draft
Diversify asset classes looked out, branching out potentially from US-based equities into FICC as well increase sample size and reduce risk
