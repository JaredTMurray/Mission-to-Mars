# Module_11_Challenge

## Mission to Mars Overview:
This is a full web-scraping and data analysis for the mission to Mars. I have identify HTML elements on the [Mars News](https://redplanetscience.com/) and [Mars Temperature Data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) webpages,  to identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.  These include HTML tables and recurring elements, like multiple news articles. I have  scrape, organize, analyze, and visualize the data for this Challenge..

## Results:
### Deliverable 1: 
Jupyter [Mars Data Part 1](#) notebook contains the code that scrapes the Mars news titles and preview text.
-	Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
-	The titles and preview text of the news articles were scraped and extracted. (20 points)
-	The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)


### Deliverable 2: 
A Jupyter [Mars temperture Data Part 2](#) notebook containing code that scrapes the [Mars weather data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) and that cleans, visualizes, and analyzes that data.
-	From the code In [2],[3] and [4], used the Beautiful Soap and two for loops to go through the HTML table were used, to find the row and header data in In [4]. It was extracted into mars_df dataframe. The Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)
-	The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (40 points)
 -	How many months exist on Mars?
 - 	Which month, on average, has the lowest temperature? The highest?
 -	Which month, on average, has the lowest atmospheric pressure? The highest?
 -	How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
-	The DataFrame was exported into a CSV file. (5 points)


## Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)
Submission

