## Reposytory 

* This is a repository focused in to study a way to use the CUDA parallel computing platform of NVIDIA in the Hermite Polynomial calculation to make it faster.
* The first code is a Python code, in the future this code will be translate to a Wolfram Mathematica code.

## Hermite Polynomials

* Definition:
  $$H_{n}(x) = (-1)^{n}e^{x^{2}}\frac{d^{n}}{dx^{n}}e^{-x^{2}}$$
* Recurrence Definition:
  $$H_{0}(x) = 1$$
  $$H_{1}(x) = 2x$$
  $$H_{n}(x) = 2xH_{n-1}(x) - 2(n-1)H_{n-2}(x)$$
