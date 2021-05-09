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

We have looked at the Covid-19 vaccination trends in these 5 countries and conducted an analysis of people getting vaccinated. Extracting the data from [Our World in Data](https://ourworldindata.org/covid-vaccinations), we were able to analyze the current trends of vaccinations. Using groupby tool on python, we were able to look at the number of total cases and total vaccinations for the selected five countries. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Python%20Data.png)

In this line chart, it shows the number of people getting vaccinated for different countries. This shows that number of people getting vaccinated fluctuates daily, but it is clearly shown that significantly higher number of people in China and India are getting vaccinated compared to other three countries. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccination%20Trend.png)

From this table and line graph, it is shown that China and India had the most vaccinations, but they also have a significantly high population, so we decided to look at total vaccinations per hundred in order to compare the percent of people getting vaccinated from their countries. 

In order to compare the percent of people getting vaccinated for different countries, we have decided to make a bar graph using plotly as it provides effective comparison.

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccinations%20per%20Population.png)

From this graph, we learned that Canada has the highest proportion of people who got vaccinated, followed by Turkey, China, India, and South Korea. 


![alt text](https://github.com/justinjiholee/covid-vaccinations/blob/main/vaccinatedpeople.png)

## How fast are countries vaccinating?
Among countries with more than 1 million people, Mongolia is currently vaccinating faster than any other, administering a daily average of 2,289 doses per 100,000 people in the past seven days. Their fastest was about 2,289 doses per 100,000 people per day.

## Do some countries have an advantage?
Yes, generally richer and more developed countries have better health care infrastructure to manufacture, acquire and administer doses.

About 55% of people who have received at least one dose of a coronavirus vaccine were from high income countries, and at least 53% were from Europe and North America (that only includes data from countries that report these figures).

## Who is getting vaccinated?
Because of the limited availability of vaccines, most countries are prioritizing certain groups of people to receive their shots before others. People who are older or more likely to become very ill or die from COVID-19 are usually prioritized over those who are young and healthy. Some groups are prioritized because they are more likely to come into contact with an infected person based on what they do or where they live and, in turn, infect others.

## Conclusion
In this project, we have decided to look at vaccination trends as the vaccines are not accessible to everyone yet and we wanted to think about how the vaccines should be distributed. We believe that students who are from countries with low accessibility to vaccines should be prioritized. We were able to look at the data of vaccinations for China, India, South Korea, Canana, and Turkey, as we have a lot of students from these countries at Johns Hopkins. 

Using various python tools, we were able to look at the number of total vaccinations and the proportion of people who got vaccinated. Using scatter, we were able to look at the general trends of number of people getting vaccinated for the selected countries by making a line chart. While the graph shows China and India has comparatively higher number of people getting vaccinated, we didn't take the number of population into account. Therefore, we created a bar graph of proportion of people who got vaccinated using scatter, which suggested that Canada and Turkey have the highest percentage.

Thus, in order to analyze the accessibility of vaccines, I believe that we have to consider the population of a country when looking at the number of people who got vaccinated. From this analysis, we were able to show that South Korea has the least accessibility to the vaccines. In our future research, it would be interesting to find and analyze methods of increasing accessibility to the vaccines. As a student from South Korea, I hope that more people from my country would get vaccinated in the near future.
