# JungleBoogie
Project Luther: Linear Regression Metis

*Project 2 of Metis Data Science Bootcamp.* Problem statement below:  

Using information we scrape from the web, can we build linear regression models from which we can learn about the movie industry.
___

I chose to focus on 100 top rated movies over the last 21 yers to determine which features predict success, as measured by Worldwide Gross. More specifically, I was trying to determine the impact of movies' soundtrack and the identity of the composer on the Worlwide gross. Using BeautifulSoup & Selenium, I scraped movie data from IMDB.com, Boxofficemojo.com, and Thenumbers.com on the following features:


1) Worldwide Gross  
2) Domestic Gross 
3) Foreign Gross  
4) Budget  
5) Runtime  
6) Composer  
7) Genre  
8) Year  
9) IMDB Metascore  
10) Rating
11) Oscar Wins
12) Winning Awards

I performed OLS Regression using StatsModels and eliminated features that had an insignificant effect on the response variable by evaluating the p-values and R^2 value of the model.

---

###Files

1) `final_movie.csv` contains the data scraped from the web  
2) `data_scraping.ipynb` is the code used to scrape the data from Box Office Mojo & IMDB  
3) `merge_budget.ipynb` & `merge_all.ipynb` sets up the scraped data for analysis
4) `movies_lin_reg.ipynb` is the code that actually analyzed the data

The project **blog post** can be found [here](). The project presentation can be found [here] (https://www.slideshare.net/MarineVeits/metis-project-2-predicting-worldwide-gross-jungleboogie).



