# 04_Combine_Google_Trends_with_other_Data

This analysis shows how to combine Google trends with web searches from https://trends.google.com/trends in comparison to some other data. The popularity of search terms can tell us a lot about future trends. In this particular example, three main data sets were examined.</br>
1. Bitcoin search volume in comparison to Bitcoin prices</br>
2. The relationship between Tesla's stock price and Tesla search volume</br>
3. Unemployment Rate vs. Unemployment Benefits Search Volume</br>
For getting the bitcoin, the Tesla stock price, https://finance.yahoo.com/quote was used.
For getting the unemployment rate,https://fred.stlouisfed.org/series/UNRATE/ was used.
In order to match the data, resampling of dates and time series was necessary.


---

Useful Links:

Pandas </br>
https://pandas.pydata.org/pandas-docs/stable/index.html </br>

Jupyter Notebook</br>
https://jupyter.org/</br>


---

The necessary steps to make the program work:</br>
1. Install the required libraries from the requirements.txt using the following command: </br>
*pip install -r requirements.txt*</br>
2. Explore data in the main.ipynb where Python code can be run in blocks.</br>
3. Using Colab from google https://research.google.com/colaboratory/faq.html explore data from main.ipynb.</br>


---

**Example view:**</br>


<a href="main.ipynb - Colaboratory.pdf">see the pdf main.ipynb - Colaboratory.pdf</a>

</br>
</br>

***Some examples from the analysis:*** 
</br>

![Screenshot](docs/img/01_chart.png)</br>

![Screenshot](docs/img/02_chart.png)</br>

![Screenshot](docs/img/03_chart.png)</br>

![Screenshot](docs/img/04_chart.png)</br>


---

**The program was developed using python 3.11.0, Pandas 1.5.1, Matplotlib, Jupyter-Notebook**

In order to run the program, open main.ipynb and install the required add-ons.
