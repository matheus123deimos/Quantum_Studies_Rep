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
* The first eleven Hermite Polynomials are:
  $$H_{0}(x) = 1$$
  $$H_{1}(x) = 2x$$
  $$H_{2}(x) = 4x^2 - 2$$ 
  $$H_{3}(x) = 8x^3 - 12x$$
  $$H_{4}(x) = 16x^4 - 48x^2 + 12$$
  $$H_{5}(x) = 32x^5 - 160x^3 + 120x$$
  $$H_{6}(x) = 64x^6 - 480x^4 + 720x^2 - 120$$
  $$H_{7}(x) = 128x^7 - 1344x^5 + 3360x^3 - 1680x$$
  $$H_{8}(x) = 256x^8 - 3584x^6 + 13440x^4 - 13440x^2 + 1680$$
  $$H_{9}(x) = 512x^9 - 9216x^7 + 48384x^5 - 80640x^3 + 30240x$$
  $$H_{10}(x) = 1024x^{10} - 23040x^8 + 161280x^6 - 403200x^4 + 302400x^2 - 30240$$
