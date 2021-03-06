# Walmart Sales Data-EDA
## Overview
Exploratory data analysis of sales pattern on 45 Walmart stores in geographically diverse locations.
The aim of this project is to:
* Appreciate the influence of multiple distribution factors and a better analysis of the sales trend.
* Understand and evaluate which store type improves the sale scale.




## Data description
The data collection includes historical data from 2010-02-05 to 2012-11-01 containing revenue information. An abstract of the original data is given in the picture below. 

![Screenshot (4)](https://user-images.githubusercontent.com/73240466/104918220-73694500-59ba-11eb-827a-66dfb356f428.png)



The dataset contained records on 421570 sale details of 45 stores .

## Methodology
The dataset was analysed using different visualisations and by using various statistical indexes. Based on the analysis, a set of features were found to be relevant. The analysis is being done primarily using pandas. Seaborn and matplotlib were used for creating data visualisations. 
Stores were categorized according to the size and type wise weekly sales per year graph was plotted. In addition, calculated median weekly sales per unit area by store type
Correlation matrices were plotted overall level and for each store types to find out the interdependence of parameters affecting sales

## Inference
It is found that the festive seasons show peak in sales and usually hit the lowest in the weeks following the year end peak season. The sale is healthier when temperature is ambient and fuel price stable. Among the factors that determine the weekly sales, size has proved to be a key factor.At the same time when sales per unit area is being analysed,medium size stores have effectively larger sales. So we can conclude that type B stores(medium sized) are more remunerative than larger stores.

![Screenshot (5)](https://user-images.githubusercontent.com/73240466/104918397-b1feff80-59ba-11eb-9222-300156de029b.png)
 
![Screenshot (7)](https://user-images.githubusercontent.com/73240466/104918887-70228900-59bb-11eb-9549-e6ce61660995.png)
