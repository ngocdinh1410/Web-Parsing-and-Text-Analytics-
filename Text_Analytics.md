# Web Parsing and Text Analytics

## Introduction
In this repository, I will go through the process of scraping rotten tomato reviews and analyze those text reviews
For this project, we utilized a web parser in order to scrape data from 11 movies from the website Rotten Tomatoes. 
From there, we used this data to build a classifier which we then evaluated. 
Lastly, we performed exploratory data analysis on our data.
For each of the 11 movies we scraped a total of ten pages of reviews from each movie. From this we gathered information on a total of 2,089 reviews. Our data frame consisted of the following columns: Reviewers' Name, Rating (fresh or rotten), Review and Date. 
## Web parsing
For how to scrape the reviews with BeautifulSoup, please refer to [BaoNgoc_Dinh_parser.py](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-/blob/master/BaoNgoc_Dinh_parser.py)
## Text Analytics & fresh/rotten classifier
For the classifier created through TFDIF vectorizer and sentiment analysis, please refer to [Text Analytics Rotten Tomato.ipynb](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-/blob/master/Text%20Analytics%20Rotten%20Tomato.ipynb)
## Misc:
* Text file consisting reviews of 11 movies: [Homework3.txt](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-/blob/master/Homework3.txt)
* Written report with some basic analysis from the 11 movies: [Homework 3 Written Report.pdf](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-/blob/master/Homework%203%20Written%20Report.pdf)
