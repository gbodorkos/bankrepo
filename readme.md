Logistic regression - bank

In this project we were trying to identify correlations in the earlier discussed czech bank database and applying a logistic regression model to detect correlation between the selected data fields after filtering and cleaning the original dataset. The tables represent customer data, and by selecting the relevant tables and joining them we could make a logical conclusion following an exploration of the available data.

Using techniques from SQL database administration, python dataframe and visualisation we can see the correlation values and visualize the results in easy to grasp graphs. The assumptions were not based by earlier experiments or ideas, it's much more discovery of possible causes following common sense and possible connections between values accumulated over years. 

The data fields observed and later used for statistical prediction were loan id, status, number of accounts per client, age of accounts, unemployment rates per year, loan amounts, age of client, criminal rate and the amounts paid back. Multicollinearity has been checked and mapped that led to the assumption of potentially dependent variables. A logistic regression model has been applied to the data, which turned out to be highly inbalanced due to sampling differences that was not methodologically based to begin with - which directly influenced the predictive value of the assumed statistics

We could outline the following best ideas and refinement of our dataset if needed using synthetic minority oversampling technique or Tomek links 