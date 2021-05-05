# COVID- 19 Vaccinations for international students at JHU

## Background

Earlier this semester Johns Hopkins University announced its plans for the staged return of activity back to its campuses, with the hope and expectation that the university will be substantially back to normal this fall. A fundamental part of this plan is that they will require all students coming or returning to campuses this fall, and who do not require religious or health exemptions, to be vaccinated. As Hopkins has indicated, they strongly urge, and may soon require, all faculty and staff to be vaccinated as well.

Multiple vaccines (from Moderna, Pfizer-BioNTech, and Johnson & Johnson) have been demonstrated to provide high levels of protection against the COVID virus with reports of only minimal and brief side effects following administration. However, not all countries have had the same access to vaccinations. As a global university with students from all over the world, it is important for Hopkins to consider the global vaccination accessibility. Therefore, this report is analysis of vaccination trends for five countries from where the largest percentage of international students at Hopkins come from.

Source: https://ourworldindata.org/covid-vaccinations https://www.collegefactual.com/colleges/johns-hopkins-university/student-life/international/chart-international.html

## Business Question

_What does mandating a vaccination mean for JHU and how Hopkins should think about getting students vaccinated?_

## Data Anlysis and Visualizations

First we perform geospatial analysis on JHU and its popularity is globally. We analyse international student trends at Johns Hopkins University to discover how Johns Hopkins stacks up to the competition when it comes to serving students from outside the United States.

Following maps show Popularity ranking of JHU by country and Value ranking of JHU by country:

![alt text](https://github.com/justinjiholee/covid-vaccinations/blob/main/PopularityRankingJHU.png)

![alt text](https://github.com/justinjiholee/covid-vaccinations/blob/main/ValueRanking.png)

Then, from https://www.collegefactual.com/colleges/johns-hopkins-university/student-life/international/chart-international.html we can extract 5 countries with the highest percentage of Hopkins students:

 China 3,260
 
 India 429
 
 South Korea 331
 
 Canada 219
 
 Turkey 41

![alt text](https://github.com/justinjiholee/covid-vaccinations/blob/main/international%20student%20countries.png)

Next, we look at the Covid-19 vaccination trends in these countries and do analysis on them. Extracting the data from [Our World in Data](https://ourworldindata.org/covid-vaccinations), we were able to analyze the current trends of vaccinations. Using groupby tool on python, we were able to look at the number of total cases and total vaccinations for the selected five countires. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Python%20Data.png)

In this line chart, it shows the number of people getting vaccinated for different countries. This shows that number of people getting vaccinated fluctuates daily, but it is clearly shown that significantly higher number of people in China and India are getting vaccinated compared to other three countries. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccination%20Trend.png)

From this table and line graph, it is shown that China and India had the most amount of vaccinations, but they also have a significantly high population, so we decided to look at total vaccinations per hundred in order to compare the percent of people getting vaccinated from their countries. 

In order to compare the percent of people getting vaccinated for different countries, we have decided to make a bar graph using plotly as it provides effective comparison.

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccinations%20per%20Population.png)

From this graph, we learned that Canada has the highest proportion of people who got vaccinated, followed by Turkey, China, India, and South Korea. In addition to the bar chart of the percentage of people who got vaccinated, we have also created a line graph of vaccination trends using scatter tool. 


![alt text](
