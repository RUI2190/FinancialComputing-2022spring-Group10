# A Robust Weight Estimator of Portfolio Theory and Optimization Methods Stability Comparison

**There is something that should really pay attention.**

All implementation in this project based on the python package ``mcos``. However, based on the experience, the package is not available for computers under Mac Operation system. It is strongly recommended to run this code by installing the package mcos in computers under Windows Operation system.

For Windows Operation system, in order to get the result of comparison among **NCO** and other three numerical optimization methods, only need to run the codes in ``MCOSDemo.ipynb``. However, before running the code there are two bugs in the source code that needed to be corrected.

1. Depend on your installing path, find mcos source code file folder, and open ``optimizer.py`` file. Find the function ``_cluster_k_means_base``, deleting ``n_job=1``. After the modification, the function should be the same as the screenshot.
![image](https://github.com/RUI2190/FinancialComputing-2022spring-Group10/blob/main/bug1.png)

2. Depend on your installing path, find mcos source code file folder, and open ``error_estimator.py`` file. Find the function ``_mean_difference_variance``, modify according to the screenshot.
![image](https://github.com/RUI2190/FinancialComputing-2022spring-Group10/blob/main/bug2.png)

After fixing these two bugs, code should run without errors.

For Mac Operation system, although it is probably that fail to run ``MCOSDemo.ipynb``, source code of mcos are available。
