# Web Scraping

Web scraping of a wikipedia page and video game publisher's Form 10-K Annual Report.

## Description

This mini-project uses the BeautifulSoup from the Python library bs4 to web scrape and Matplotlib to visualize a Wikipedia of the top-selling video games ever. Then the form 10-K of Two Take Interactive is scraped, and data such as sources of revenue and the balance sheet are visualized.

## Wikipedia Webscrape 

wiki_videogames_scrape.ipynb turns the data from the [Wikipedia](https://en.wikipedia.org/wiki/List_of_best-selling_video_games) page of best-selling video games into a Pandas dataframe. The data such as release date versus copies sold or the count of game publishers is visualized.

## Form 10-K

take_two_10k_scrape.ipynb analyzes the annual report of [Take Two Interactive](https://www.sec.gov/Archives/edgar/data/946581/000162828023019851/ttwo-20230331.htm) which is the parent company of Rockstar, a publisher that appears on the best-selling video games often. Plots are made of sources of revenue and the balance sheet.

## Author
 
Mark Pham  
