# DataCollection-Challenge
# HTML and CSS scraping and data analysis

This challenge consists of two technical products:
## Part# 1: Scrape titles and preview text from Mars news articles.
## Part# 2: Scrape and analyse Mars weather data, which exists in a table.
# Part 1: Scrape Titles and Preview Text from Mars News
Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb was provided. Then I have followed the following steps to scrap the Mars News website.
1.	Used automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
2.	Created a Beautiful Soup object and used it to extract text elements from the website.
3.	Extracted the titles and preview text of the news articles that i scraped. Stored the scraping results in Python data structures as follows:
  a.	Stored each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview. 
  b.	Store all the dictionaries in a Python list.
  c.	Print the list in your notebook.
4.	Finaly I have stored the scraped data in a JSON file (“article.json” Output folder)
# Part 2: Scrape and Analyse Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. I have written the steps below to scrape and analyse Mars weather data.
1.	Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspected the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
2.	Created a Beautiful Soup object and used it to scrape the data in the HTML table. 
3.	Assembled the scraped data into a Pandas DataFrame. Made sure the columns  has the same headings as the table on the website. 
4.	Examined the data types then convert the data to the appropriate datetime, int, or float data types.
5.	Analysed the dataset by using Pandas functions to answer the following questions:
    1.	How many months exist on Mars?
    2.	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    3 .	What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        1.	Find the average minimum daily temperature for all of the months.
        2.	Plot the results as a bar chart.
    4.	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        1.	Find the average daily atmospheric pressure of all the months.
        2.	Plot the results as a bar chart.
    5.	About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        1.	Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        2.	Visually estimate the result by plotting the daily minimum temperature.
6.	Finaly exported the DataFrame to a Mars_tempdata.csv file in output folder.


