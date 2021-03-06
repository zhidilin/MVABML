# _Bayesian Machine Learning_

This code is for the project for the master MVA course [_Bayesian Machine Learning_](https://github.com/rbardenet/bml-course), about variational approaches for Gaussian Process learning and inference [1].

![Boston dataset (RBF kernel)](figures/Titsias_Boston_inducingPtNumInfluence.png)

## Data layout

### Toy data

```
data/1D_toy_data
    - Simple_test.csv
    - Simple_train.csv
```

### New York Taxi

Get the dataset [here](https://www.kaggle.com/c/nyc-taxi-trip-duration/data). The folders should look like this:
```
data/taxi-data
    - test.csv
    - train.csv
```

## Experiments

We provide notebooks to run experiments:
* [Hand-coded GP regression using Numpy/Scipy](GPRegression_Handcoded.ipynb)
* [A comparison of approximate GP regression schemes](sparse_gp_comparison.ipynb)
* [GP regression on the (massive) NYC Taxi dataset](taxi.ipynb)

## References

[1] Titsias, M.. (2009). Variational Learning of Inducing Variables in Sparse Gaussian Processes. Proceedings of the Twelth International Conference on Artificial Intelligence and Statistics, in PMLR 5:567-574

