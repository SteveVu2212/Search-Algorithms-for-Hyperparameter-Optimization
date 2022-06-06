# Introduction

The project compares 06 widely used search algorithms for hyperparameter optimization in machine learning in terms of convergence rate and running time. Those consist of
* Random search (random_search)
* Bayesian Optimization with Gaussian Process (gp_search)
* Bayesian Optimization with Random Forests (fm_search)
* Bayesian Optimization with Gradient Boosting (gbm_search)
* Annealing Search (anneal_search)
* Tree-structured Parzen Estimators Search (tpe_search)

The project employes GradientBoostingClassifier to identify patients in the breast cancer dataset from Sklearn. While 62.7% of patients are healthy, accuracy is used as a predictive performance metric

# Outcome

![](https://github.com/SteveVu2212/Search-Algorithms-for-Hyperparameter-Optimization/blob/main/Images/convergence_and_runtime.png)
