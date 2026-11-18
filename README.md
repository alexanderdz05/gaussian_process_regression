# Gaussian Process Regression

Plan so far:
1) In `src/gpr.py`, code up the GPR algo and the metric evaluation methods
2) [Optional], but I was thinking to have `tests/test_gpr.py` to test the implementation of the model. Obviously, in the notebooks, we'll test how well the model performs on the datasets. `tests/test_gpr.py` will test whether our algo is mathematically correct. Use assert keywords.
3) In `notebooks/dataset(n).ipynb`, load CSV --> Clean data --> Train model --> Evaluate & plot results. Everything done here will be called using implementations in `src/gpr.py` for the model and evaluation functions. Also, we should compare our model against Linear Regression and CART using metrics and see if our model beats the baselines.