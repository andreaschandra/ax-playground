# ax-playground
Adaptive Experimentation Platform - Playground

Ax is a platform for optimizing any kind of experiment, including machine learning experiments, A/B tests, and simulations. Ax can optimize discrete configurations (e.g., variants of an A/B test) using multi-armed bandit optimization, and continuous (e.g., integer or floating point)-valued configurations using Bayesian optimization. This makes it suitable for a wide range of applications.

Ax has been successfully applied to a variety of product, infrastructure, ML, and research applications at Facebook.

_https://ax.dev/docs/why-ax.html_

## Installation
The library strongly encourage you to install via pip and conda for OSX

```
conda install pytorch torchvision -c pytorch  # OSX only (details below)
pip3 install ax-platform
```

## Highlights

Tutorial References:
- https://ax.dev/tutorials/tune_cnn.html
- https://towardsdatascience.com/quick-tutorial-using-bayesian-optimization-to-tune-your-hyperparameters-in-pytorch-e9f74fc133c2
- https://www.justintodata.com/hyperparameter-tuning-with-python-keras-guide/

Key points:
- Well documented (better) than BoTorch
- There are 3 types of usage in order to tune your parameters: Loop API, Service API, Developer API.
- There are 2 Algorithms: Bayesian and Bandit Optimization
- built-in feature that enables saving results to a JSON file or a MySQL database.
- able to create such as complext dependent parameter constraints.
- Integrate visualization using plotly and stunning visualization.