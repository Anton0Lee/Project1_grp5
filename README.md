Project1_grp5

# Melbourne Housing Market
In this repository, we have created this project which aims to analyse data and answer the following questions.  
The powerpint is included for our presentation.  
The VSCodes for each question are separated in 3 different files labeled Q1, Q2,and Q3.  
A resources folder is included which contains our dataset.  
A 'Graph' folder is included which contains all our graphs form the analysis.  

## Question 1: How does the changes of interest rate impact the housing market? 
After analysis, it is observed that most houses are sold when the interest rate is low and the least houses are sold when the interest rate is high.  
Additionally, the housing price increases as the interest rate drops. 
    
## Question 2: Optimal Location for Real Estate Investment

## Question 3:What are the most expensive suburbs in Melbourn and what factors affect the prices in these suburbs?
Melbourne's most expensive suburbs and analyze factors influencing property prices. Examine how these factors impact real estate dynamics in these areas.
providing insights into Melbourne's high-end property market trends.

# Dataset
- melb_housing_data.csv
- F5_Indicator_Lending_Rates.csv

## Melbourne Housing Dataset
https://www.kaggle.com/datasets/ronikmalhotra/melbourne-housing-dataset?resource=download 

This housing dataset provides a thorough analysis for 2016 to 1st Quarter 2018 of the housing market. It includes information on housing prices, availability, and key trends, allowing you to gain a better understanding of the market and make informed decisions. Whether you're a homebuyer, investor, or simply interested    in the state of the housing market, this dataset has valuable insights to offer.
  
## Interest Rate
https://www.rba.gov.au/statistics/tables/#interest-rates 

This page lists statistical tables for a range of economic and financial data produced by the Reserve Bank of Australia and other organisations.

# Visualizations

## Graph 1  
![q1_sales_overtime](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/da2efa5c-11a7-422b-abe1-9e410075f92f)

Our focus on the number of houses sold over the 24-month period revealed a noteworthy increase in 2017 compared to 2016. While we assumed no external factors changed during this time, we hypothesized that higher interest rates in 2016 might have influenced the observed difference. However, we emphasized the necessity for further analysis to confirm this hypothesis and explore additional factors influencing house sales.

## Graph 2
![q1_sales_irates](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/458d1f76-88b6-492a-879a-df3ff6d10bbc)

Examining the relationship between houses sold and interest rates revealed a significant trend. The majority of houses were sold when interest rates were 5.26% and below, suggesting a positive correlation between lower interest rates and increased house sales. However, we acknowledged that this observation, based on a barplot, requires more in-depth analysis to understand the nuanced dynamics at play. Additional investigations are essential to establish a comprehensive understanding of the relationship between interest rates and houses sold.

## Graph 3
![q1_sales_irates_overtime](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/bd964623-07cd-47b2-9bb0-93f735949212)
Looking at the housing counts compared to the interest rate over the 2 years, we can see that the interest rates have dropped by 0.41% over 2 years. On the other hand, the housing sale counts is fluctuating between 2 to 1536 houses but showing a weak increasing trend over the 2 years. Putting two graphs together we can see that the housing sale counts increases as the interest rates decreases. 

## Graph 4
![q1_price_irates_overtime](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/a8082418-b2ed-4c31-b7b4-36958eeec018)
Looking at the housing price compared to the interest rate over the 2 years, we can see that the housing price is fluctuating between 0.89Million to 1.2Million but showing a moderate increasing tread over the 2 years. Putting two graphs together, we can see that the housing price is increasing as the interest rate is decreasing overtime. 

## Graph 5
![q2_price_landsize](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/33c58d59-afcd-4ebc-ad3d-cff331fba75e)
This plot shows the relationship between property prices and land size, differentiated by property type.
Inference: Larger land sizes usually command higher prices, with variations across different property types.
For example houses in remote areas will be higher in land value and lower in Price

## Graph 6
![q2_price_buildingarea](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/7e6b0a3d-9c8c-429b-9089-b22268929b11)
This visualization depicts the correlation between property prices and building area, distinguished by property type.
Inference: Generally, larger building areas are associated with higher property prices, though this varies by type.

Interpretation
Correlation between Price and Landside  0.2171432770316884
Correlation between Price and BuildingArea  0.5578617577181919

There is a moderate positive correlation between Price and Building area (Higher the Building area higher the Price) In comparison to  Price and Building area correlation  of  0.21  The building area to price relationship appears to be moderately strong .
When  determining optimal investment It is important not to only rely on Correlation But also consider Causation which identify the cause and effect.

## Graph 7
![q2_top_suburbs_score](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/6d2a570f-e71f-4932-9187-40adcd6303ad)
This bar graph ranks the top 5 suburbs in Melbourne based on a composite score from various property features.
Inference: Suburbs like Seaholme rank highest, indicating favourable property features. (Based on Higher average score)

## Graph 8
![q2_bottom_suburbs_score](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/0978208c-6f37-4daf-9bfd-1716669ebb4f)

This graph shows the suburbs with the lowest scores, reflecting less favorable property characteristics.
Inference: Suburbs such as Emerald and Carrum have lower scores, suggesting less desirable aspects.
(Based on Lower average score)

## Conclusion on Q2.
The average score is grouped by suburb based on factors such as ‘Price,Distance', 'Rooms', 'Bedroom', 'Bathroom', 'Car', 'Land size. 

Based on average score ( adjusted for outliers ) Seaholme Ranks 1st in relation to Optimal location for real estate investment.

The suburbs are ranked based on their average scores, and the top 5 suburbs with the highest scores are identified as the best for investment. Conversely, the suburbs with the lowest scores are identified as the worst for investment.
The analysis provides a data-driven approach to identify attractive and unattractive suburbs for real estate investment in Melbourne. This methodological approach can be enhanced further by integrating more direct measures such as crime rates, school ratings, and amenities when such data becomes available.

## Graph 9
![q3_most_expensive_suburbs](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/e32884b4-c089-4b03-a2ec-10514a349f93)

This shows top 10 suburbs based on their average housing prices. The x-axis represents the suburbs, while the y-axis represents the average price. 
The graph is a bar plot, where each bar represents a suburb and its corresponding average price. The height of each bar indicates the average price of the suburb.

![image](https://github.com/Anton0Lee/Project1_grp5/assets/151039901/43141b18-cc47-4317-9d16-4fe89d9a0e7d)


## Graph 10
![q3_price_distance](https://github.com/Anton0Lee/Project1_grp5/assets/152049332/27f1d813-6cb4-4485-9fc2-1f1b0c2134da)

The code is performing a linear regression analysis between 'Average Distance from CBD' and 'Average Price'. This is to understand the relationship between these two variables.
The slope and intercept obtained from the linear regression can give us an idea about the nature of the relationship. The slope is negative, it means that as the average distance from CBD increases, the average price decreases
The R-value (or correlation coefficient) indicates the strength and direction of the relationship between the two variables. A value close to 1 indicates a strong positive relationship, a value close to -1 indicates a strong negative relationship, and a value close to 0 indicates no relationship. In this case the r value is -0.47, which means there is a negative correlation between the average distance from CBD and the average price of housing. When the average distance from CBD increases, the average price of housing decreases and vis-Versa.
The scatter plot visualizes the data points and the linear regression line, which can help us visually understand the relationship between the two variables.


# Conclusion
We've explored the impact of interest rates on house sales, identified optimal locations for investment, and delved into factors influencing prices in high-end suburbs.
While our analysis provides valuable insights into the trends of the Melbourne real estate market during the 2016-2017 period, it's crucial to acknowledge the dynamic nature of the real estate landscape. Market conditions, economic factors, and external influences can evolve, impacting the relevance of this historical data to the current scenario. Therefore, our findings should be considered within the context of the specific time frame studied, and we recommend continuous monitoring and periodic updates to account for changing market dynamics.

# Contributors (in alphabetic order)
Anton

Karunadhipathi Abeyakoon

Malini Sintre

Masih Qadir



