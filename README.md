# Web Scraping with Scrapy Library

**Before start scrap any Site, you should be sure of its "terms and policy".**\
**You should not use a site that is illegal to scrap.**

## Using Scrapy Library

for using this library you need to install it first:
````
pip install scrapy
````

for anaconda:
````
conda install -c conda-forge scrapy
````

You can then define your spider by subclassing the scrapy. Spider class and defining the following methods:

name: A string that identifies the spider.

start_urls: A list of URLs that the spider will start by visiting.

parse(): A method that defines how the spider should parse the response and extract the data it is interested in.

But Before that, Once Scrapy is installed, you need to create a new Scrapy project using the scrapy startproject command.\
This will create a new directory with the basic file structure and settings for your Scrapy project.

````
scrapy startproject myproject
````
After running this command, it will make a Spider folder on your PC like [This](https://github.com/kohandelramin/Web-Scraping-with-Scrapy-Library/tree/main/myproject)

**For more details take a look at [Amazon Reviews Scrapy](https://github.com/kohandelramin/Web-Scraping-with-Scrapy-Library/blob/main/Amazon%20Reviews%20Scraping%20with%20Scrapy.ipynb)**
