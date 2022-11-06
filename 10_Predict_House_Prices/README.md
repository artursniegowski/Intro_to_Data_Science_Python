# 10_Predict_House_Prices

In this project, we will use data from the UCI ML housing dataset, https://archive.ics.uci.edu/ml/machine-learning-databases/housing/. This data set includes 14 characteristics describing the housing market in the Boston area in the 1970s.
We will analyse the data, and based on that, we will build a multivariable regression model to predict house prices in this area. We will divide the data set into two categories: one that will be used to train or find the parameters for our multivariable linear regression, and the other that will be used for testing.
The price will be the target value, and the rest of the characteristics (13 in total, like CRIM (crime rate), RM (number of rooms), and NOX (pollution)) will be used as factors to determine the price.
The features will be analysed and checked to see if they are sufficient for predicting house prices.
The main libraries used in this analysis were:</br>
[Seaborn](https://seaborn.pydata.org/index.html), which is based on Matplotlib for generating different kinds of charts.</br>
[Plotly](https://plotly.com/python/), it's Python graphing library, makes interactive, publication-quality graphs.</br>
[Matplotlib](https://matplotlib.org/) is a comprehensive library for creating static, animated, and interactive visualisations in Python.</br>
[SciPy](https://docs.scipy.org/doc/scipy/index.html) is an open-source software for mathematics, science, and engineering (for calculating the t-statistic and the p-value).</br>

---

Useful Links:

Pandas </br>
https://pandas.pydata.org/pandas-docs/stable/index.html </br>

Jupyter Notebook</br>
https://jupyter.org/</br>

NumPy
https://numpy.org/doc/stable/index.html</br>

scikit-learn</br>
https://scikit-learn.org/stable/index.html</br>

SciPy</br>
https://docs.scipy.org/doc/scipy/getting_started.html</br>


seaborn</br>
https://seaborn.pydata.org/index.html</br>

Plotly</br>
https://plotly.com/python/</br>

Matplotlib</br>
https://matplotlib.org/stable/</br>

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

***Overview:*** 
</br>

![Screenshot](docs/img/01_graph.png)</br>

![Screenshot](docs/img/02_graph.png)</br>

![Screenshot](docs/img/03_graph.png)</br>

![Screenshot](docs/img/04_graph.png)</br>

![Screenshot](docs/img/05_graph.png)</br>

![Screenshot](docs/img/06_graph.png)</br>

![Screenshot](docs/img/07_graph.png)</br>

![Screenshot](docs/img/08_graph.png)</br>

![Screenshot](docs/img/09_graph.png)</br>

---

**The program was developed using python 3.11.0, Pandas 1.5.1, NumPy, scipy, Matplotlib, scikit-learn, seaborn, plotly, Jupyter-Notebook**

In order to run the program, open main.ipynb and install the required add-ons.