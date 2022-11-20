# Module_11_Challenge

## Mission to Mars Overview:
This is a full web-scraping and data analysis for the mission to Mars. I have identify HTML elements on the [Mars News](https://redplanetscience.com/) and [Mars Temperature Data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) webpages,  to identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.  These include HTML tables and recurring elements, like multiple news articles. I have  scrape, organize, analyze, and visualize the data for this Challenge..

## Results:
### Deliverable 1: 
Jupyter [Mars Data Part 1](https://github.com/JaredTMurray/Mission-to-Mars/blob/main/mars_data_challenge_part_1.ipynb) notebook contains the code that scrapes the Mars news titles and preview text.
-	Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
In[7], Import Splinter and BeautifulSoup, In[8] set the executable path and In[16] are code used to visit the Mars NASA news site
-	The titles and preview text of the news articles were scraped and extracted. To set up the HTML parser and to scrape an article title and it's summary text, the code in In [54], [55] and [77]  use the ,div tag  and the class "content_title" to located the the title and the summary text.
-	The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. The variable news_p were used to stored the summary of the articles. I then used a for loop to go throught the the iteriation loop, then I created an empty dictionary all_news to store the results of the news summary. See In [58], [59],[80] and was wellas the Out[80]. 


### Deliverable 2: 
A Jupyter [Mars temperture Data Part 2](https://github.com/JaredTMurray/Mission-to-Mars/blob/main/mars_data_challenge_part_2.ipynb) notebook containing code that scrapes the [Mars weather data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) and that cleans, visualizes, and analyzes that data.
-	From the code In [2],[3] and [4], used the Beautiful Soap and two for loops to go through the HTML table were used, to find the row and header data in In [4]. the data from the HTM: table was extracted into mars_df dataframe. In [7] code was  used astpe to set the columns headers to the correct headings and data types. See Out [7].

 1. id                           int32
 2.  terrestrial_date    datetime64[ns]
 3. sol                          int32
 4. ls                           int32
 5. month                        int32
 6. min_temp                   float64
 7. pressure                   float64
 8. dtype: object
###	Data analysis 
 -	How many months exist on Mars?
 - 	Which month, on average, has the lowest temperature? The highest?
 -	Which month, on average, has the lowest atmospheric pressure? The highest?
 -	How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
-	The DataFrame was exported into a CSV file. (5 points)


## Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)
Submission

