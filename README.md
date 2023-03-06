# Data-Science-in-finance-Robinhood-data

This project is used to explore the retail trading behavior by looking at daily holdings and matching them with stock prices and returns from RobinHood dataset.
Through analysis of the data, we could answer below questions.
1. Which stock had the highest average weekly return and which stock had the lowest?
2. Which stock had the largest return and when? What about the smallest? 
3. Which stock experienced the largest weekly increase in holdings (and when)? what about the smallest?
4. What is the relation between lagged stock returns and holdings? 

Intuitive way: 

According to the plot, it seems that the lagged stock return has no relations to the holdings, the holdings keep growing up regardless stock return change")

![asg3_plot1](https://user-images.githubusercontent.com/102770592/223016995-1c5233cc-5715-41a7-a3aa-653ae0f8397a.png)

Using Regression:

The coefficient of the lagged stock returns is 1.449e+07, meaning that a 1% change in lagged stock return is
associated with a 1.449e+07 increase in the holdings.While since the R^2 only equals to 11.3%, this model does not predict quite well.

![asg3_plot2](https://user-images.githubusercontent.com/102770592/223016996-5ef3ed46-cf9b-4fd0-9f0f-30219185c991.png)
