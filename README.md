# Live_text_summerizer

Worked on transformer model BARD to make an application that summerizes an input text. The summerizer was test tested on a a webpage taken from 'https://www.washingtonpost.com/world/2022/04/29/russia-ukraine-war-news-putin-live-updates/' website.

The webpage was at that time, covering the ukraine war and the summerizer code scrapped the website, got the text and gave a brief summery of what the news was on that date. 

*** 
### Tools used for the task
* Beaeutiful soup: Web scrapping. 
* request library: To the url to gain permission to scrape.
* Pipeline library from transformers: The real summarization ML model.
