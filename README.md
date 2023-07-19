# Project1-OpenClassrooms
Analyze data from education systems

## Business Case

The mission consists of an exploratory analysis to determine if the World Bank education dataset (https://datacatalog.worldbank.org/dataset/education-statistics) helps inform the expansion project of an on-line learning company. The database lists 4000 international indicators describing access to education, graduation and information related to teachers and education expenditure.

These indicators may not all be relevant, so it will be necessary to filter the data to retrieve and analyze the most important indicators. In addition, it will be necessary to clean the database of duplicates and/or missing values.

Finally, it will be necessary to develop a score to classify the countries according to their potential for commercial development.

## Main results

I carried out several filtering steps in order to select the data that could be useful for the commercial expansion project. In particular, these steps were:

-	filter on the year to have recent information and forecasts for 2030 (from 2012 to 2017 + 2030)
-	selection of potentially relevant indicators (percentage of young people in school, young population, total population, etc.)
-	filter on the size of the population (minimum 6.3 million, i.e. the median)
-	filter on GDP (minimum $5355, i.e. the median)
-	filter on the number of internet users
-	suppression of indicators with too many missing values (more than 25% of the total)
-	replacement of missing values with the median 

Once the dataset was cleaned, I calculated a score using the weighted average of the indicators.

The United States, Canada, and Australia are at the top of the ranking. These 3 countries also have positive population growth and the average number of years spent in school is expected to grow. This implies a growing number of potential customers.

Finally, for these countries, a market study should be carried out in order to identify the competitors or study the habits of the population and their interests in order to better adapt the offer, the courses and identify the best business model to adopt.

## Aquired skills

-	Set up a Python environment
-	Perform a graphical representation using a suitable Python library
-	Data manipulation with specialized Python libraries
-	Master the fundamental operations of the Python language for Data Science
-	Use a Jupyter notebook to facilitate code writing and collaboration



