# numerai-sandbox
A Repo to Share Scripts for Numerai

So far there are just 2 files showing 2 simple ways to add noise to our training data. In the first notebook, we and Gaussian noise to the input data, and investigate the performance using cross validation metrics. There are 3 scenarios tested: the baseline (no noise), then we test only using data with noise added in training and finally we test the case where using all the original data and a copy of the data with noise.

A similar experiment is done where instead of adding Gaussian noise we use pairwise averages of data points to produce our "noisy" data. Again we test with the original data, noisy data, and both.

For consistency we use a the same model across runs.
