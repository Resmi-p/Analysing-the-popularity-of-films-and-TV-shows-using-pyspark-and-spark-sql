# Analysing-the-popularity-of-films-and-TV-shows-using-pyspark-and-spark-sql
**Data Handling and Processing with PySpark**

Analysing the popularity of films and TV shows on the streaming platform, Netflix. Using your knowledge of PySpark DataFrames and Spark SQL, you will produce a number of "downstream" data products to analyse trends in global streaming habits.

Downloaded the dataset from this Kaggle "all_weeks_countries.csv" file.
1.Create two separate DataFrames for Films and TV.

2.For the Films data, drop the column containing the season names.

3.For the TV data, replace any null values in the season name column with the show name.

4.Making use of the "groupBy" and "where" methods, find the number of weeks the show "Stranger Things" was in the Top 10 for the United Kingdom across all seasons. Store your result in a variable named "STWeeks".

5.Produce a dataframe containing only the Top 25 TV seasons in the UK, based on the number of weeks they spent in the Top 10.

6.For the show "Young Sheldon", find the country where each season spent the most time in the Top 10.

7.For each country, find the film that spent the most time in the Top 10.

8.Calculate the number of weeks each film spent at the number 1 spot of each country's Top 10 list. Then find the films that spent the most time in the number 1 spot for each country.
