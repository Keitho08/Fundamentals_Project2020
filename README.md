
# Fundamentals of Data Analysis - Project 2020

## Galway Mayo Intitute of Technology - HDip Data Analytics 2020-2021
***
### Keith Brazill - G00387845
***

**Project Brief:**

*Problem statement*

*In this project you must perform and explain simple linear regression using Python on the powerproduction dataset available on Moodle. The goal is to accurately predict wind turbine power output from wind speed values using the data set as a basis.*

*Your submission must be in the form of a git repository containing, at a minimum, the following items:*

1. upyter notebook that performs simple linear regression on the data set.
2. In that notebook, an explanation of your regression and an analysis of its accuracy.
3. Standard items in a git repository such as a README.

*To enhance your submission, you might consider comparing simple linear regression to other types of regression on this data set. Rest assured, all the above concepts will be explored in lecture videos and other materials in the coming semester.*

**Getting started**

In order to run the jupyter notebook in this repository the following is recommended to download and install Python using Anaconda. Anaconda is available at:
https://docs.anaconda.com/anaconda/install/

**Packages used in this project**

The following packages were used in this assignment to carry out the required tasks in the project brief:

* Python https://www.python.org/downloads/
* Numpy http://www.numpy.org/ - The fundamental package for scientific computing with Python.
* Jupyter Notebook https://jupyter.org/ - Project Jupyter exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages.
* matplotlib.pyplot https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html - matplotlib.pyplot is a state-based interface to matplotlib. It provides a MATLAB-like way of plotting. pyplot is mainly intended for interactive plots and simple cases of programmatic plot generation.
* seaborn https://seaborn.pydata.org/ - Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
* pandas https://pandas.pydata.org/ - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.
* scikit-learn https://scikit-learn.org/stable/ Simple and efficient tools for predictive data analysis, built on NumPy, SciPy, and matplotlib

**Importing Packages**

The above packages can be imported into Python. Use Import function in the notebook or in ipython to import:

* import numpy as np
* import seaborn as sns
* import matplotlib.pyplot as plt
* import pandas as pd
* use scikit-learn as sklearn

Jupyter notebook is already imported as standard in python when installed via Anaconda. It can be accessed by typing "jupyter notebook" in the command line which will open up the notebook in your browser.

**Summary of Repository**

The notebook Fundamentals_Project_2020.ipynb contained within this repository,  is prepared in response to the brief assigned for the project 2020 in the module of Fundamentals of Data Analysis 2020 as part of the postgraduate diploma in Computer Science with Data Analytics at Galway Mayo Institute of Technology.

The notebook is structured as follow's:

1. Introduction
2. The Project Brief
3. The Project Dataset
4. Simple Linear Regression Model
5. Simple Regression Model Analysis
6. Polynomial Regression
7. Conclusion
8. References

The approach to the project was to firstly to examine the provided dataset via some simple statistical tables and graphs and then carry out simple linear regression on this dataset. Following application of the simple linear regression the code was explained, analysed and the accuracy of the regression was determined. Finally other forms of regression were compared to our simple linear regression.

Throughout the notebook each of the above sections is cleary explained using a combination of code and markdown cells

**References** 

*A complete list of all references used in this repository is included below:*

1. Ponnusamy, Ramalingam & Venkatesan, R & Sing, A. (2014). Wind energy location prediction between meteorological stations using ANN. 1135-1144. 
2.Hydroquebec.com. 2021. Wind Turbines | How They Work | Hydro-QueBec. [online] Available at: <http://www.hydroquebec.com/learning/eolienne/#:~:text=Wind%20turbines%20require%3A,be%20stopped%20to%20avoid%20damage> [Accessed 7 January 2021].
3. Seaborn.pydata.org. 2021. Visualizing Distributions Of Data — Seaborn 0.11.1 Documentation. [online] Available at: <https://seaborn.pydata.org/tutorial/distributions.html> [Accessed 7 January 2021].
4. Codecademy. 2021. Seaborn Styling, Part 1: Figure Style And Scale | Codecademy. [online] Available at: <https://www.codecademy.com/articles/seaborn-design-i#:~:text=Seaborn%20has%20five%20built%2Din,name%20of%20it%20to%20sns.> [Accessed 7 January 2021].
5. Medium. 2021. Layman’S Introduction To Linear Regression. [online] Available at: <https://towardsdatascience.com/laymans-introduction-to-linear-regression-8b334a3dab09#:~:text=Linear%20regression%20attempts%20to%20model,variable%20(e.g.%20your%20expenses).> [Accessed 7 January 2021].
6. Mathcentre.ac.uk. 2021. Equations Of Straight Lines. [online] Available at: <https://www.mathcentre.ac.uk/resources/uploaded/mc-ty-strtlines-2009-1.pdf> [Accessed 7 January 2021].
7. Varsitytutors.com. 2021. Line Of Best Fit (Least Square Method). [online] Available at: <https://www.varsitytutors.com/hotmath/hotmath_help/topics/line-of-best-fit#:~:text=Step%201%3A%20Calculate%20the%20mean,mean%20of%20the%20y%20%2Dvalues.&text=Step%204%3A%20Use%20the%20slope,best%20fit%20for%20the%20data.> [Accessed 7 January 2021].
8. Medium. 2021. Mathematics For Machine Learning : Linear Regression & Least Square Regression. [online] Available at: <https://towardsdatascience.com/mathematics-for-machine-learning-linear-regression-least-square-regression-de09cf53757c> [Accessed 7 January 2021].
9. Numpy.org. 2021. Numpy Polyfit. [online] Available at: <https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html https://rstudio-pubs-> [Accessed 7 January 2021].
10. Github. 2021. Writing Mathematic Fomulas In Markdown. [online] Available at: <https://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/> [Accessed 7 January 2021].
11. Scikit-learn.org. 2021. 1.1. Linear Models — Scikit-Learn 0.24.0 Documentation. [online] Available at: <https://scikit-learn.org/stable/modules/linear_model.html> [Accessed 7 January 2021].
12. Seaborn.pydata.org. 2021. Seaborn.Lmplot — Seaborn 0.11.1 Documentation. [online] Available at: <https://seaborn.pydata.org/generated/seaborn.lmplot.html> [Accessed 7 January 2021].
13. Numpy.org. 2021. Numpy.Corrcoef — Numpy V1.19 Manual. [online] Available at: <https://numpy.org/doc/stable/reference/generated/numpy.corrcoef.html> [Accessed 7 January 2021].
14. Frost, J., 2021. How To Interpret R-Squared In Regression Analysis - Statistics By Jim. [online] Statistics By Jim. Available at: <https://statisticsbyjim.com/regression/interpret-r-squared-regression/#:~:text=R%2Dsquared%20is%20a%20goodness,the%20independent%20variables%20explain%20collectively.&text=For%20instance%2C%20small%20R%2Dsquared,values%20are%20not%20necessarily%20good!> [Accessed 7 January 2021].
15. Frost, J., 2021. How High Does R-Squared Need To Be? - Statistics By Jim. [online] Statistics By Jim. Available at: <https://statisticsbyjim.com/regression/how-high-r-squared/#:~:text=R%2Dsquared%20should%20accurately%20reflect,or%20lower%20than%20this%20value.&text=However%2C%20if%20you%20analyze%20a,%2Dsquared%20values%20over%2090%25.> [Accessed 7 January 2021].
16. Medium. 2021. Understanding And Calculating The Cost Function For Linear Regression. [online] Available at: <https://medium.com/@lachlanmiller_52885/understanding-and-calculating-the-cost-function-for-linear-regression-39b8a3519fcb> [Accessed 7 January 2021].
17. Medium. 2021. Mathematics For Machine Learning : Linear Regression & Least Square Regression. [online] Available at: <https://towardsdatascience.com/mathematics-for-machine-learning-linear-regression-least-square-regression-de09cf53757c> [Accessed 7 January 2021].
18. Medium. 2021. Layman’S Introduction To Linear Regression. [online] Available at: <https://towardsdatascience.com/laymans-introduction-to-linear-regression-8b334a3dab09#:~:text=Linear%20regression%20attempts%20to%20model,variable%20(e.g.%20your%20expenses).> [Accessed 7 January 2021].
19. Medium. 2021. Introduction To Linear Regression In Python. [online] Available at: <https://towardsdatascience.com/introduction-to-linear-regression-in-python-c12a072bedf0> [Accessed 7 January 2021].
20. Pandas.pydata.org. 2021. Pandas.Dataframe.Iloc — Pandas 1.2.0 Documentation. [online] Available at: <https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.iloc.html> [Accessed 7 January 2021].
21. Scikit-learn.org. 2021. Sklearn.Preprocessing.Polynomialfeatures — Scikit-Learn 0.24.0 Documentation. [online] Available at: <https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html> [Accessed 7 January 2021].
22. GeeksforGeeks. 2021. Python | Implementation Of Polynomial Regression - Geeksforgeeks. [online] Available at: <https://www.geeksforgeeks.org/python-implementation-of-polynomial-regression/> [Accessed 7 January 2021].
23. En.wikipedia.org. 2021. Degree Of A Polynomial. [online] Available at: <https://en.wikipedia.org/wiki/Degree_of_a_polynomial#:~:text=In%20mathematics%2C%20the%20degree%20of,is%20a%20non%2Dnegative%20integer.> [Accessed 7 January 2021].
24. En.wikipedia.org. 2021. Quartic Function. [online] Available at: <https://en.wikipedia.org/wiki/Quartic_function> [Accessed 7 January 2021].
25. Medium. 2021. Machine Learning: Polynomial Regression With Python. [online] Available at: <https://towardsdatascience.com/machine-learning-polynomial-regression-with-python-5328e4e8a386> [Accessed 7 January 2021].
26. En.wikipedia.org. 2021. Polynomial Regression. [online] Available at: <https://en.wikipedia.org/wiki/Polynomial_regression#:~:text=In%20statistics%2C%20polynomial%20regression%20is,nth%20degree%20polynomial%20in%20x.&text=Such%20variables%20are%20also%20used%20in%20classification%20settings.> [Accessed 7 January 2021].
27. Python, R., 2021. Linear Regression In Python – Real Python. [online] Realpython.com. Available at: <https://realpython.com/linear-regression-in-python/> [Accessed 7 January 2021].
28. Medium. 2021. 5 Types Of Regression And Their Properties. [online] Available at: <https://towardsdatascience.com/5-types-of-regression-and-their-properties-c5e1fa12d55e> [Accessed 7 January 2021].
29. VanderPlas, J., 2021. In Depth: Linear Regression | Python Data Science Handbook. [online] Jakevdp.github.io. Available at: <https://jakevdp.github.io/PythonDataScienceHandbook/05.06-linear-regression.html> [Accessed 7 January 2021].
30. GitHub. 2021. Ianmcloughlin/Jupyter-Teaching-Notebooks. [online] Available at: Mcloughlin, Ian., 2021. <https://github.com/ianmcloughlin/jupyter-teaching-notebooks/blob/master/fitting-lines.ipynb> [Accessed 7 January 2021].
31.  GitHub. 2021. Ianmcloughlin/Jupyter-Teaching-Notebooks. [online] Available at: Mcloughlin, Ian., 2021. <https://github.com/ianmcloughlin/jupyter-teaching-notebooks/blob/master/regression.ipynb> [Accessed 7 January 2021].

***
# End