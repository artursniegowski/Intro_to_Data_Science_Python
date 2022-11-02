# Intro_to_Data_Science_Python
This is a repository of projects that will teach you the most important libraries and concepts used in data science with the help of Python. The programs below will demonstrate how easy and efficient Python is, and why it is one of the most popular and widely used language in data science. Have fun and enjoy the codding!


## 01_Analysing_Salaries_of_Graduates_by_Major
Basic operations using the Pandas library for data exploration. As an example, data from salaries_by_college_major.csv was
used and explored with Python Library Pandas. In order to have a better understanding and manipulation of data, the Jupyter Notebook was used, which is an interactive computing platform.
In this example, the salaries of post-university graduates by major are being analised.

## 02_Analyse_Popularity_of_Programming_Languages
Each post on Stack Overflow comes with a tag. And this tag can be the name of a programming language. Based on that, we will gather data from stackoverflow and generate a csv file containing information on various programming languages and
the number of times each language is tagged in a post. This will help us to determine which programming language is the most popular.
The analysis is carried out using the Python Library Pandas, and the results are plotted using the Python Library Matplotlib. 

## 03_Analysing_Dataset_LEGO_Pieces
The data for LEGO pieces was used from https://rebrickable.com/downloads/ (like colors.csv, sets.csv, and themes.csv).
The analysis is carried out using the Python Library Pandas, and the results are plotted using the Python Library Matplotlib. Some examples of how to use a relational database and merge columns were described in this analysis.
Some very interesting facts could be found thanks to this analysis, like the most enormous Lego set ever or how many pieces did it have? Or, when were the first LEGO sets released, and how many sets did the company sell when it first opened its doors? Or we can explore which LEGO theme is the most popular. By analysing the data, we can see when the company really took off based on its product offering. We can also answer questions like whether LEGO complexity has changed over time, or which sets tend to have more parts. 

## 04_Combine_Google_Trends_with_other_Data
This analysis shows how to combine Google trends with web searches from https://trends.google.com/trends in comparison to some other data. The popularity of search terms can tell us a lot about future trends. In this particular example, three main data sets were examined.</br>
1. Bitcoin search volume in comparison to Bitcoin prices</br>
2. The relationship between Tesla's stock price and Tesla search volume</br>
3. Unemployment Rate vs. Unemployment Benefits Search Volume</br>

For getting the bitcoin, the Tesla stock price, https://finance.yahoo.com/quote was used.</br>
For getting the unemployment rate,https://fred.stlouisfed.org/series/UNRATE/ was used.</br>
In order to match the data, resampling of dates and time series was necessary.</br>

## 05_Analysing_Google_Apps_Plotly
This analysis focuses on data about Google apps scraped from the Google Play Store by Lavanya Gupta in 2018. The original files are available [here] (https://www.kaggle.com/lava18/google-play-store-apps).
The main points were depicting interesting facts about Google Apps with the help of Python libry plotly, and
using diverse charts, like pie, bar, box, and many more.</br>
The data about Google apps was explored to find out interesting facts like:</br>
* how competitive various app categories (for example, games, lifestyle, and weather) are,</br>
* What are the most popular apps,</br>
* What was the most downloaded app's estimated revenue,</br>
* how the monetization of an app affects its download count,</br>
* What is a reasonable price for an app,</br>

## 06_NumPy_and_N_Dimensional_Arrays
In this project we will explore the NumPy (Numerical Python) Python library, which is
used in almost every field of science and engineering. It’s practically the standard for working with numerical data in Python. It is an introduction to get a better understanding of how to work with this library.</br>
Main points, including:</br>
* how to work with arrays</br>
* how to create nd.arrays</br>
* creating arrays with standard functions such as arange(), random(), or linespace()</br>
* What exactly is broadcasting and how does it work</br>
* How to do linear algebra with NumPy</br>
* Image manipulation with a NumPy arrays </br> 

## 07_Seaborn_and_Linear_Regression
This project will have a focus on analysing data about films. Data was scraped on May 1, 2018 from
https://www.the-numbers.com/movie/budgets .In this analysis, we will explore the different aspects of how the budget of a movie influences the revenue, and also how to predict future revenue based on the budget and year it was filmed.
Different Python libraries were used. like the visualisation library [Seaborn](https://seaborn.pydata.org/index.html), which is based on Matplotlib for generating different kinds of charts (bubble chart, scatter chart, regressions). as well as the open source data analysis library [scikit-learn](https://scikit-learn.org/stable/) (the gold standard for machine learning), which was used to calculate the data for linear regression, check how accurate our model is, and make predictions about future revenue.

## 08_Nobel_Prize_Analysis
In this project, we're going to analyse data (https://www.nobelprize.org/prizes/lists/all-nobel-prizes/) on the past winners of the Nobel Prize. Thanks to this analysis, we will find some interesting facts about the Nobel laureates, like:
The ratio of male to female winners, or who was the first to win a Nobel Prize, how many people got a Nobel Prize more than once, how many categories there are and how many prizes there are for each category, the number of Nobel Prizes awarded over time, which countries have the most Nobel Prizes, which cities make the most discoveries, where are the Nobel laureates born? What are the patterns or statistics in the laureates' age at the time of the award?
There were different Python libraries used in order to better visualise the results. 
[Seaborn](https://seaborn.pydata.org/index.html), which is based on Matplotlib for generating different kinds of charts (bubble chart, scatter chart, box charts, regressions).
[Plotly](https://plotly.com/python/), it's Python graphing library, makes interactive, publication-quality graphs (like sunbursts and choropleths).
[Matplotlib](https://matplotlib.org/) is a comprehensive library for creating static, animated, and interactive visualisations in Python. Matplotlib makes easy things easy and hard things possible.