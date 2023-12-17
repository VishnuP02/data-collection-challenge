Task: Throughout this challenge, I put to use my knowledge of learning to identify HTML elements on a webpage, identifying their id and class attributes, and extracting information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. I also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage. This challenge was broken up into two parts:

Part 1: Scrape Titles and Preview Text from Mars News
  1. Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
  2. The titles and preview text of the news articles were scraped and extracted. 
  3. The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

Part 2: Scrape and Analyze Mars Weather Data (60 points)
  1. The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. 
  2. The data was analyzed to answer the following questions: 
       - nHow many months exist on Mars? 
       - How many Martian days' worth of data are there? 
  3. The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 
       - Which month, on average, has the lowest temperature? The highest? 
       - Which month, on average, has the lowest atmospheric pressure? The highest? 
       - How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
  4. The DataFrame was exported into a CSV file.

Resources used to complete activity:
  - Lecture slides, class recordings, AskBCS session with LA Shreha Mittal, LA Robert Perron, and LA Dinh Chau
