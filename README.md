# HousePrices
To run the code you must first download the dataset from https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads and then run the Database Creation.ipynb.

From our analysis, we can see that the capital clearly has the most expensive property prices. 
On closer inspection the further north the city the more likely it is to have lower property value. We can see this in the heat map generated on Power BI. Properties in the south are more expensive than the north and have a close proximity to London also seems to boost housing prices.

Furthermore, we can see huge dips in the sales of properties since 1995. 
There a 3 dips: 
- 1:1999 - 2001 
- 2:2007 - 2008 
- 3:2021 - present

Reason for the dips:
- 1999 - 2001 :  During the 90s there was a recession. During this period of economic downturn, interest rates were raised to 15% and left in place to control inflation. House prices fell by 20% from 89-93. The market started to recover during the late 90's, where we start seeing increase in property prices.

- 2007 - 2008 : This one is quite obvious, it has to be the infamous global financial crisis triggered by the collapse of the US housing market. The crisis was caused by a combination of factors, including reckless lending by banks and the widespread use of subprime mortgages. Many homeowners started to face negative equity where the value of their home is less than the outstanding mortgage.

- 2021 - present : Caused mainly by the increase in interest rates in the UK, with no real salary increases to keep up with inflation, meaning ordinary working class people cannot afford a loan to buy a house.

If I was to do this project again I would try to find a dataset with longitude and latitude data allowing me to use GeoPandas. I would not only be able to create a heatmap on Python instead of Power BI but would also be able to incorporate datasets from the Ordnance Survey, NaPTAN and Noise pollution data from UK Gov. This will provide data on roads, trains, planes, waterways (canals and rivers) and noise pollution data. Plugging this into a UK heat map would help us better understand the property price differences, furthermore also giving us a better understanding of price differences in city neighborhoods (ie: properties near rivers and canals may be more expensive than properties near motorways/highways).  
