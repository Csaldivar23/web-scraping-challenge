# web-scraping-challenge
Module_11_Challenge_HTML

## In this assignment, I will use my newfound web scraping skills to tackle this challenge.

This new assignment consists of two technical products. You will submit the following deliverables:

### Deliverable 1: Scrape titles and preview text from Mars news articles.

https://static.bc-edx.com/data/web/mars_news/index.html

On the first deliverable I created a Beautiful Soup object to extract the text elements from the website. I then stored them into a list seperating the title and preview into dictionaries. I then printed the list I created.

### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

https://static.bc-edx.com/data/web/mars_facts/temperature.html

On the second deliverable I created a Beautiful Soup object to extract the data in each of the rows on the 'Mars Temperature Data' table. I then assembled that data into a Pandas DataFrame with the appropriate data types. I then analyzed the data and created visualiztions using the matplotlib library. I concluded by answering the following questions:

    How many months are there on Mars?
    How many sols (Martian days) worth of data are there?
    What is the average minimum temperature by month?
    What is the average pressure by month?
    How many terrestrial (Earth) days are there in a Martian year?

 and then exporting the DataFrame to a CSV file.