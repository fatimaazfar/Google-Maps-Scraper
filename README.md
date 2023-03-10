# Google-Maps-Scraper
This is selenium crawler for scraping data from google maps. 

The crawler works in the following manner:

Step 1: Access the URL and wait for the page to load.
Step 2: Find the search box, take query input from user and input this query into the search box and press enter.
Step 3: Wait for the results to load.
Step 4: Click on each result one by one.
Step 5: Wait till the results are loaded.
Step 6: Extract the current URL (used to extract lat, longs and place name)
Step 7: Extra address, status etc from the opened page and once its done go back and click next place.

Some weaknesses which I'll work on sometime:
1. It is slow as it is not headless.
2. It doesn't scroll down properly and thus it has to be done manually.
