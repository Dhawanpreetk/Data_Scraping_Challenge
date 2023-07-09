# Data_Scraping_Challenge
This Challenge, core skills required were : collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.
This assignment consists of two technical products.
Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
##Part 1: Scrape Titles and Preview Text from Mars News
<img width="416" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/23b32d99-fb71-4a4f-bcf1-03a5984b5932">

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 

An example is the following:
{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
Store all the dictionaries in a Python list.

Print the list in your notebook.

<img width="758" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/dda3ad96-b54a-4b50-8bd9-748214a0c4a2">


**##Part 2: Scrape and Analyze Mars Weather Data**
Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

<img width="365" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/53e3c154-ce75-4aaa-a8a3-fa9991f94114">


Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
<img width="712" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/81cbcb6e-dd3b-4185-b56c-8a23bd023ac7">


How many Martian (and not Earth) days worth of data exist in the scraped dataset?

<img width="524" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/0c73a375-1b83-4185-be2f-67047cbb6d1f">


What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.

<img width="476" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/06a2ea80-5ce4-4bd7-8136-6f9e2be0d2a9">


Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.

<img width="492" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/403faf69-093c-4430-bff3-94cc8542bbee">


About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.

<img width="443" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/5b6668f2-bde8-42eb-a966-1ae0687b4a12">

Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.

<img width="413" alt="image" src="https://github.com/Dhawanpreetk/Data_Scraping_Challenge/assets/130263833/ffbfc3bc-d1b5-462e-9d7e-c306a4a9ae1a">
