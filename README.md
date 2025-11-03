## Summary

The main functionality of this tool is to calculate the both Equity and Enterprise value of a selected company with the DCF method. 
The forcasting of the future FCF and stocks are conducted through a Monte Carlo simulation This project, in order to be properly executed, 
requires to have full access to APIs via FMP, on that account the structure and approach for the valuation are designed this way.
Furthemore, it relies on the following significant **assumptions** :

1) the application of the tool cannot be global due to the different countries regulations,
2) the source of information (APIs) is Financial Modeling Prep. The access there is limited and refers to US market,
3) the project it doesn't take into account the various indexes, yet.
4) some data are default and not a dynamic solution.

It is evolving and currently in its early stage.

Sources :
-

- Aswath Damodaran for premiums, rf etc
- FMP for APIs (limited access)
