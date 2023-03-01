# HTML Scraping and Parsing Project
By Kiana Navarre

**Programming Language Used: Splinter, Beautiful Soup, Python**

## Description
The goal of this project is to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.  The project consists of 2 technical products, submitting the following deliverables:
1. Scrape Titles and preview text from Mars News Articles
2. Scrape and analyze Mars weather data (existing in a table)

## Mars News Articles
The goals for this section were to:
- Use automated browsing to visit [Mars Planet Science/News](https://static.bc-edx.com/data/web/mars_news/index.html) and identify which elements to scrape
- create a Beautiful Soup object and use it to extract text elements from the website
- extract titles and preview text from the news articles listed
- store scraped resultes as title-and-preview pairs in a Python dictionary
  - each dictionary containing two keys: title and preview. 
- Store dictionaries in a Python list

## Mars Weather Data Analysis 
The goals for this section were to: 
- use automated browsing to visit [Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and identify which elements to scrape
- create a Beautiful Soup object and use it to scrape the data in the HTML table 
- Assemble the scraped data into a Pandas DataFrame
- Cast the data to the appropriate data types
- Analyze the dataset using Pandas functions
- Export the DataFrame to a CSV file
  
The data analysis performend on the created Pandas DataFrame answers the following questions: 
1. How many months exist on Mars? 
   - 12 months
2. How many Martion (not Earth) days worth of of data exist in the scraped dataset? 
   - 1,977 Martian days
3. What are the coldest and warmest months on Mars (at the given location)?
    ![alt text](https://github.com/knavarre/HTML-scraping-challenge/blob/main/outputs/AverageTemp_by_Month.png?raw=true)
    - The hottest month is month 8.
    - The coldest month is month 3.

4. Which months have the lowest and highest atmospheric pressure on Mars? 
   ![alt text](https://github.com/knavarre/HTML-scraping-challenge/blob/main/outputs/AveragePressure_by_Month.png?raw=true)
5. Approximately how many terrestrial (Earth) days exist in a Martian year? 
   - There are 687 terrestrial days in a Martian year.

The graphs and csv file outputs of this analysis can be found in the outputs folder.  