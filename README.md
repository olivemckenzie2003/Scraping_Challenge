# Scraping_Challenge
Assignment 11


Files
    part_1_mars_news.ipynb 
    part_2_mars_weather.ipynb
    out.csv

contain information to meet the requirements of challenge 11

part_1_mars_news.ipynb and part_2_mars_weather.ipynb both contain code for retreiving or the term is srcaping information from HTML files 
on which analysis can be made. Analysis in the form of Visual presentaion of barcharts and a line chart are also produced, and the general functions are used such as count, max, min, average, and groupby and used to derive information from ther data on which the analysis is based.

part_1_mars_news.ipynb contains mainly data scraping from https://static.bc-edx.com/data/web/mars_news/index.html which is a Mars news website.
The Titles of the news and its content are scraped from the website matched together and printed, using BeautfifulSoap.

part_2_mars_weather.ipynb contains mainly analysis information based on the table scraped from 'https://static.bc-edx.com/data/web/mars_facts/temperature.html' using BeautfifulSoap. The information in the tabe appears to be otained from the robot Rover while travelling around mars and then transnitting information back to earth.

in the form of a table which contain the rows :
  
* `id`: the identification number of a single transmission from the Curiosity rover
* `terrestrial_date`: the date on Earth
* `sol`: the number of elapsed sols (Martian days) since Curiosity landed on Mars
* `ls`: the solar longitude
* `month`: the Martian month
* `min_temp`: the minimum temperature, in Celsius, of a single Martian day (sol)
* `pressure`: The atmospheric pressure at Curiosity's location



out.csv

The out.csv file contains the information that was in the table pull of the mars web page. The table was converted into a pandas dataframe and then converted into a CSV file and exported to the out.csv
