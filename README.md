# Volatility-Maximization

### ** This is a previous project developed as a submission for CFM101's final term project **

![img](https://images.unsplash.com/photo-1591696205602-2f950c417cb9?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

Our group was tasked with developing a program that follows certain guidelines and develops a hyper-volatile 
portfolio based on unknown tickers provided in a CSV file. Not all tickers in said file could be invested in, and it was our responsibility to use the following guideline to filter through the list during portfolio development:

- Denominated in CAD/USD
- Valid ticker in yFinance API
- Average monthly trading volume of 150000
   - Only months with a minimum of 18 trading days are to be included in the mean calculation
- The final portfolio must include a minimum of 10 stocks and a maximum of 22

Both the implementation & an example .csv file with tickers are included in the repository.

