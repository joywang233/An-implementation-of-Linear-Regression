# Predicting houseing price during Covid19 in Australia
Compare and predict house price fro AUS and USA between 2008 financial crisis and 2020 Covid19

### Scenario: 
USA and Australia are two popular counties for property investment on the global wide. As a property consultant(My part-time job), I would like to know, what are the correlations bettwen property market and the general socio-economic conditions for the two countries.

More importantly, since the world is been through covid-19 crisis, I would like to investigate how the housing market is affected by national crisis, for example, 2008 financial crisis. Based on the history, I could get some insights on how the property market will be infected by the current covid-19 crisis and give my customers some suggestion on the curret situation.
Data:

### Dataset
The datasets used in this question are described as follows:
- GDP:The general indicator of a country's socio-economic conditions.
- Norminated House Price: A direct indicator of a country's housing market.
- Long-term Interest Rate: A very important indicator for investers/buyers. Also, during crisis, interst rate can be an effective way for goverment to rescue the market.

All the datasets are sources from http://www.oecd.org/

### Libraries 
```
import pandas as pd               
import matplotlib.pyplot as plt  
import datetime
```


### Graphs
![graph1](/outputimg/graph1.png)
![graph2](/outputimg/graph2.png)
![graph3](/outputimg/graph3.png)
![graph4](/outputimg/graph4.png)
![graph5](/outputimg/graphy5.png)
![graph6](/outputimg/houseprice_compare.png)
![linear1](/outputimg/linear1.png)
![linear2](/outputimg/linear2.png)
![linear3](/outputimg/linear3.png)




### Analysis and discussion

To summarize, from the GDP, interest rate and house price data in the past 20 years we can see that there are linear correlations in between the variables, this can be used for predicting the future socio-economical conditions of a country.

From the comparison of USA and AUS we can see that, AUS were less affected by the global financial crisis, this may because the USA economics is much bigger than AUS. In other ways, We can say that AUS is safer for long term property investment.

Dring 2020 covid-19, the govenrment has took earlier actions to reduce the interest rate and provide financial assisstance. Based on the analysis from 2008 financial crisis, we predict that there is unlikely a huge drop of house price of AUS property market this time. This gives us more confidence when facing the current situation. Although the market will be, more or less, negatively affected by covid-19, we believe it will recover soon.

### Future Work

To improve the performance of our model and predict the future GDP trendency, other stronger indicators(maybe second industry data) can be added to enhence the result. This could be achieved through a decision tree model.




