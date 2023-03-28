# SHAAL
# **Group SHAAL Project 1**

##Background: Mudit & Associates, the number one professional service training provider in the U.S., are planning to expand their training program.  SHAAL Incorporated was hired to analyze the current non-farmer U.S job market in order to identify what  jobs will be in demand in the next 8 years and the best time for them to expand their business.

Analysis review:
- Inflation and interest rate data to assess when to invest in providing training for a new industry 
- Correlations between interest rate, inflation, and unemployment 
- Job market on employment/unemployment dynamics between 2010-2022
- Unemployment demographics
- Jobs that are in demand for the next 8 years

Data Sources:
https://www.bls.gov
https://fred.stlouisfed.org 
https://data.imf.org

#**Economic Analysis**

In order to expand its business there are a few considerations that a business needs to make. Starting with creating a business plan, considering forms of financing, and making hiring decisions are a few factors to explore. SHAAL looked at the current U.S. economic situation to assess if the current economy is a favorable one. To do so, we looked at current unemployment levels, inflation rate, and interest rates.

Why are these factors relevant?
- Inflation helps to determine with business cycle the U.S is experiencing (expansion or contraction)
- Lower unemployment rate leads to business computing in the market to attract and retain qualified employees
- Interest rate will influence how much and how companies will raise capital

#Inflation: The Federal Reserve looks at the Consumer Price Index to determine current inflation rates. In a simplest way to explain, the FED looks at current prices of goods and services, excluding food and energy prices due to its volatility, and compares them to prior prices. In the short term, high inflation leads to lower unemployment rates as business expands in order to keep up with the high demand. This causes prices and employment costs to rise.

Why does the FED try to lower inflation if it helps with employment and causes expansion? Because in the long term, inflation causes money to lose value. So, this is a classic example that too much of a good thing can be a bad thing.

In order to lower inflation the FED try to reduce the money circulation by increasing interest rate. High interest rate leads to high cost of borrowing, high cost of borrowing causes companies to reduce expantionary projects. It also leads to more individuals and companies choosing to invest instead expanding.

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Economic%20Analysis%20Slides/Project1.jpg)
![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Economic%20Analysis%20Slides/Project1%20(1).jpg)
![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Economic%20Analysis%20Slides/Project1%20(2).jpg)
![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Economic%20Analysis%20Slides/Project1%20(12).jpg)

## Statistical Analysis

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Statistical%20Analysis%20Slides/Project1%20(3).jpg)

To provide information on the relationships between inflation, real interest rate, and national employment, a statistical analysis concerning correlations between these three indicators was conducted. 
The correlation coefficient for inflation and national employment was 0.82, showing a strong positive correlation. This is explained by the fact that as employment increases, more people are earning money and therefore more money is also being spent. With more money circulating, purchasing power is lowered and inflation increases. 

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Statistical%20Analysis%20Slides/Project1%20(4).jpg)

When looking at inflation and real interest rate, there seems to be no correlation at first glance, as the correlation coefficient for data from the past 13 years is 0.21. However, we are looking at a timeframe from 2010 to 2023 and interest rates were heavily impacted by the pandemic during the years of 2020 and 2021. As a response to Covid, interest rates were lowered by almost 1% in total as an incentive to increase spending to support the suddenly slowed economy. When looking at the relationship between CPI and real interest rate without taking the “Covid years” of 2020 and 2021 into account, we can see a much clearer positive correlation with a correlation coefficient of 0.6. This is explained by the fact that as inflation increases, interest rates are raised to disincentivize spending and encourage saving, with the goal to reduce the money circulating in the market and therefore bringing inflation back down. 

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Statistical%20Analysis%20Slides/Project1%20(5).jpg)

Similar to CPI and real interest rate, national employment and real interest rate do not seem to be correlated at first with a correlation coefficient of -0.1. However, we are looking at the 2010 – 2023 timeframe, which was heavily impacted by Covid. When not taking 2020 and 2021 into account due to the effect Covid had as explained above, we can see that national employment and real interest rate actually have a correlation coefficient of -0.58, displaying a negative correlation. As the real interest rate is increased with the goal to disincentivize spending and ultimately reduce inflation, less money will be circulating in the market, and employment will ultimately drop with money becoming more “valuable” again. 

## Business Employment Dynamics

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(6).jpg)

Based on the the BLS series of gross job gains and gross job losses statistics indicate that the US economy has experienced an average job gain of 28,846.62 per period between 2010 and 2022. The lower quartile of job gains is 28,122.0, which means that 25% of the job gains are below this figure. Similarly, the upper quartile of job gains is 30,346.0, indicating that 25% of the job gains are above this figure.
Furthermore, the data suggests that job gains below 24,786 could be outliers and values of job gains above 33,682 could also be outliers. This implies that such gains are not common and may indicate significant changes in the economy, such as large-scale layoffs or the creation of many new jobs due to an industry-wide expansion.
Between 2010 and 2022, the US experienced an average job loss of 27,316. The lower quartile of job losses is 25,859, indicating that 25% of job losses were below this figure. Similarly, the upper quartile of job losses is 28,145, indicating that 25% of job losses were above this figure.
Additionally, the information suggests that job losses below 22,430 could be outliers, while job losses above 31,574 could also be outliers. This implies that job losses falling outside of these ranges are not typical and may not be representative of the overall trend in the job market.

Note
The accuracy of projections for individual occupations is subject to error because of the many unknown factors that may affect the economy over the projection period. Furthermore, while occupational employment projections and related job outlook information can provide valuable inputs to the career decision-making process, 
they should not be the sole basis for a choice of career.

## Unemployment Rate by industry and by age group

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(7).jpg)

The first plot shows us the unemployment rate over time 2010-2023 for six industries such as retail trade, information, health care, real estate, leisure and manufacturing. It can be seen that the retail trade had the highest unemployment rate during the Covid-19 pandemic , reaching a peak of 16.2% in April 2020. And the plot also  suggests that the information industry had a lower impact during the COVID-19 pandemic and pre-pandemic periods compared to other industries and occupations
Second plot suggests that the unemployment rate for all age groups generally decreased from 2010-2020, with a few spikes during economic downturns. Plot also suggests that unemployment rates tend to be higher for younger age groups. And 35-65 was relatively lower than 16-19. It’s also worth noting that the unemployment rate for the age group 65 and over was the lowest among all age groups both before and during the pandemic. It’s possible that 65+ individuals have more experience and skills in their field, which make them more competitive in the job market. Also they may have more stable employment histories and established networks that can help them find a new job opportunities. 
Top 10 jobs that will be on Demand by 2031 -based on employment changes

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(9).jpg)

By 2031, there will be a high demand for software developers, with an employment change of 370.6% and % change of 26. Median salary in 2021 was $120,730. From this information, we can say that demand for software developers is expected to increase significantly over the next decade and that individuals with bachelor degree in software development or related field will be well positioned to take advantage of this trend. Additionally, the high median annual wage for software developers suggests that this is a lucrative career path for those with necessary skills and qualifications. 


![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(10).jpg)

By 2031, there is expected to be a 40.5% increase in employment for data scientist, with percentage % of 35.8. The median annual wage for data scientists in 2021 was $100,910 and bachelor degree is typically required to enter this field. This data suggests that data science is rapidly growing field with promising job prospects and a competitive salary. Individuals with bachelor degree in data science or related field may be well positioned to take advantage of this trend as well. 

![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(8).jpg)

We recommend marketing in the states with higher unemployment rates such as Nevada 5.5% and Oregon 4.8%. It can be a good strategy for businesses because with higher unemployment there may be a larger pool of jobs seekers looking to work, which increase the likelihood of finding the qualified employees for open positions. 

##Limitations and Conclusions
![Alt Text](https://github.com/aumekubo2/SHAAL/blob/main/Job%20Market%20Analysis%20and%20Conclusion%20Slides/Project1%20(11).jpg)







