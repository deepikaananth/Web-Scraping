# Web-Scraping

This repository is a collection of small time scripts and notebooks written by me for my own reference (and anyone else that might find it even a tiny bit useful!) as I ride my inexperienced little row boat into the greater sea of data engineering, stopping on my way to explore web scraping.

Here's a brief rundown of the inventory so far (updated as I add more stuff):


1. scraping_recipy.ipynb
> This was my first self-written web scraping script after a day's worth of focused reading of <a href="https://www.commoncrowbooks.com/pages/books/B61081/dimitrios-kouzis-loukas/learning-scrapy-learn-the-art-of-efficient-web-scraping-and-crawling-with-python">*Learning Scrapy - Learn the art of efficient web scraping and crawling using Python*</a> by Dimitrios Kouzis-Loukas, and following the guided explanations in <a href="https://www.coursera.org/projects/rudi-hinds-ai-web-scraping-with-gpt-translating-foreign-news-headlines">*Web Scraping With GPT: Translate Foreign News Headlines*</a>. It contains a simple <a href="https://beautiful-soup-4.readthedocs.io/en/latest/">**BeautifulSoup**</a> based parsing of <a href="https://requests.readthedocs.io/en/latest/">**Requests**</a> retrieved html content of an Italian recipe blog, whose response I then translate into English using the GPT 3.5-turbo API.


2. web_scraping_with_GPT.ipynb
> This is much the same. I retrieve the contents of Chinese and Arabic news websites and translate them into English, familiarizing myself with how BeautifulSoup and Requests work while very importantly learning how to manually inspect the DOM of a website and utilize a short and efficient version of an element's CSSpath selector to instruct BeautifulSoup to retrieve exactly what we want. No more, no less.


3. scraping_for_a_mockDataset.ipynb
> scraping_for_a_mockDataset is a much more comprehensive (with comments) and fleshed out notebook containing three nested functions I use to scrape all of the 142 Pages (at the time) of works hosted under the <a href="">*Halo (Video Games) & Related Fandoms*</a> sub-category of popular fanfiction hosting website AO3.
