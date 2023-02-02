# Machine_Learning_Trading_Bot (README.md)

This is a Jupyter Lab notebook file. This `.ipynb` file utilizes Python to read a `.csv` file and then uses a machine learning algorithm, through scikit-learn, to . These models attempt to get as close to 1.0 accuracy in predicting future outcomes. A data analyst could use these models to test specific target data in an attempt to determine future outcomes and thereby to create company policies in order to promote desirable outcomes. A data analyst would have to use these models and make lots of trial-and-error type changes to the code in order to get as close to 1.0 accuracy as their company is comfortable with. 

---

## REPORT



--

## Technologies

Please be sure you have Jupyter Lab installed:

* [JupyterLab](https://jupyter.org/)

This application was written in Python 3.9.12. This application is dependent on the following libraries:

* [pandas](https://pandas.pydata.org/)
* [numpy](https://numpy.org/)
* [pathlib](https://docs.python.org/3/library/pathlib.html)
* [hvplot](https://hvplot.holoviz.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn svm](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
* [sklearn preprocessing standard scaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
* [pandas tseries offsets date offset](https://pandas.pydata.org/docs/reference/api/pandas.tseries.offsets.DateOffset.html)
* [sklearn metrics classification report](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
* [sklearn linear model logistic regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

---

## Installation Guide

If you have [Anaconda](https://www.anaconda.com/products/distribution) downloaded, then pandas and matplotlib will be part of your package. You can check that they're ready to use by typing the following in your CLI terminal:

```python
conda list pandas
conda list numpy
conda list pathlib
conda list hvplot
conda list matplotlib

```

You can download the following local machine using this code:
```python
pip install -U scikit-learn
```

And check that they've been installed with this code:
```python
conda list scikit-learn
```

---

## Usage

Open your CLI terminal and type
```python
jupyter lab
```
then JupyterLab will automatically open in your browswer. Use the left side menu bar to search for the `machine_learning_trading_bot.ipynb` file. Open this file. Then you can use the formaulas in the `.ipynb` file to analyze the data your `.csv` file(s) and optimize the algorithm to make preditions based on your data. You can change the rolling windows and the amount of months in the algorithim to try to get the most accurate predictions possible.

---

## Contributors

[Rachel Ann Hodson](https://www.linkedin.com/in/rachelannhodson/)
rachelannhodson@gmail.com

---

## License

MIT