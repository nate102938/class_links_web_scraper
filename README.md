# Class Links Web Scraper

This project relates to a blog post linked [here](https://nate23424533.wordpress.com/2023/01/23/web-scraping-tips/).  

The blog post discusses tips for web scraping.  I used the information I gathered in the blog post to web scrape the lesson names and links from the Flatiron School Data Science class site.  This information is freely available at another website [Flatiron Open Source](https://flatironopensource.ml/); however, I wanted to get the curriculum lesson names and links into a more concise format of my liking (and I wanted to practice web scraping).  

Therefore, I created a web scraper using Selenium that pythonically logs into Flatiron School, navigates into each phases' page, captures all of the lesson names and links for each phase, navigates into each lesson link, and captures all external github/vimeo links.  It then saves all of the lesson information to file and outputs it to a user-friendly collapsible HMTL file. 

The lesson information was captured in two steps and then put together:
- Version 01 - Captured all lesson information for phases 1 through 5, 
- Version 02 - Captured all lesson information for pre-work.  
- Version 03 - Combined information from Version 01 and Version 02

See the [blog post](https://nate23424533.wordpress.com/2022/12/05/building-a-crypto-trading-dashboard-the-first-steps/) or the related [Jupyter Notebook](notebook.ipynb) for further information.  

See the final product of the web scraping effort [here](https://htmlpreview.github.io/?https://github.com/nate102938/class_links_web_scraper/blob/main/Version%20-%2003%20-%20All/DS_Links.html).
