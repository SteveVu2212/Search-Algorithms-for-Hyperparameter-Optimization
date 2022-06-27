# Introduction

The project compared 06 search algorithms for hyperparameter optimization in machine learning in terms of convergence speed and running time. Those consist of
* Random search (random_search)
* Bayesian Optimization with Gaussian Process (gp_search)
* Bayesian Optimization with Random Forests (fm_search)
* Bayesian Optimization with Gradient Boosting (gbm_search)
* Annealing Search (anneal_search)
* Tree-structured Parzen Estimators Search (tpe_search)

The project applied those search algorithms to two classification models
* Convolutional Neural Network (CNN) - Functional API to classify handwritten digits
* Gradient Boosting to identify patients with breast cancer

Below is the outcome of the GradientBoostingClassifier. While 62.7% of patients were healthy, accuracy was used as a predictive performance metric.

# Outcome

![](https://github.com/SteveVu2212/Search-Algorithms-for-Hyperparameter-Optimization/blob/main/Images/convergence_and_runtime.png)
