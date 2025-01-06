Our code is based on a python library to compute strength values at:
https://github.com/nicopotyka/Uncertainpy, and we added more functions to carry out our experiments.

Instructions:
1. Run AAE\examples\gradual\CFX_generate_QBAF_acyclic.ipynb to generate random acyclic QBAFs (named acyclic_0.bag).
2. Run AAE\examples\gradual\compute_gradient_AAE_acyclic.ipynb to generate AAEs for acyclic_0.bag.
3. Run AAE\examples\gradual\AAE_test_time.ipynb to get the runtime figures.