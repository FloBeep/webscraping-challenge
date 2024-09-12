# Challenge 11: Web Scraping

This assignement is a full web-scraping and data analysis project. It was necessary to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. Various types of information were scrapped, including HTML tables and recurring elements, like multiple news articles on a webpage.

This result of the assignment consists of two files with the following content:

* Part 1: Scraped titles and preview text from Mars news articles.
* Part 2: Scraped and analyzed Mars weather data, which exists in a table.

#### Description of Part 1 (part_1_mars_news file):

* Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
* The titles and preview text of the news articles were scraped and extracted.
* The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

#### Description of Part 2 (part_1_mars_news file):

* The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.
* The data was analyzed to answer the following questions:
  * How many months exist on Mars? **12**
  * How many Martian days' worth of data are there? **1977**
* The data was analyzed to answer the following questions, and a data visualization was created to support each answer:
  * Which month, on average, has the lowest temperature? The highest? **Lowest: 3rd month. Highest: 8th month.**
  * Which month, on average, has the lowest atmospheric pressure? The highest? **Lowest: 6th month. Highest: 9th month.**
  * How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. **Estimate: 675 days. Real life: 681 days.**
* The DataFrame was exported into a CSV file.
