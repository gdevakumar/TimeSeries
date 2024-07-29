# Time Series

Time Series is an important and often neglected topic in Machine Learning. It has 4 components:

1. **Level**: Baseline value for the data.
2. **Trend**: Describes the overall trend of the data, like linearly increasing, exponentially decreasing, etc. (*optional*).
3. **Seasonality**: A pattern or cycle repeating continuously over a time period (*optional*).
4. **Noise**: Random fluctuations in the data that can't be explained by the model.

## Types of Time Series Datasets

- **Univariate**: Dataset having only one variable recorded over time.
- **Multivariate**: Dataset having more than one variable recorded over time.

---

## Important Libraries

Some of the important libraries used in Python for Time Series forecasting are:

- `SciPy`
- `Pandas`
- `NumPy`
- `Matplotlib`
- `statsmodels`
- `Scikit-learn`

To install them & other required libraries, run:
```bash
pip install -r requirements.txt
```

- One class of models to do Time Series Forecasting based on Error, Trend and Seasonality are ETS Models. [Here](./ETS-models.ipynb)'s how to code them in Python using `statsmodels`.

