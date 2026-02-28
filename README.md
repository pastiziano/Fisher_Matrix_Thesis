# Fisher_Matrix_Thesis
Python code for Fisher matrix forecasts used in the Msc thesis “Testing Primordial Non-Gaussianity with Gravitational Wave Surveys".

Author: Pasquale Tiziano Ursino  
University: Università degli Studi di Padova  
Year: 2025

## Requirements
- Python = 2.7
-  class
- numpy
- scipy
- matplotlib
- jupyter


  ## External codes

The angular power spectra \(C_\ell\) used in this analysis were computed
using Multi_CLASS, a modification of the Boltzmann code CLASS that allows
for the computation of cross-tracer angular power spectra of number counts.

Multi_CLASS was used as an external code to generate the input \(C_\ell\)'s,
while all Fisher matrix calculations and forecasts are implemented in this repository.

For installation instructions and detailed documentation, see the official
Multi_CLASS repository:
https://github.com/nbellomo/Multi_CLASS.git

==================================================================================================
You can use Multi_CLASS freely, provided that in your publications you cite the presenting papers of Multi_CLASS (where you can find more details about the code):

Beware of commonly used approximations I: errors in forecasts, Bellomo, Bernal, Scelfo, Raccanelli and Verde; JCAP 10 (2020) 016.
Beware of commonly used approximations II: estimating systematic biases in the best-fit parameters, Bernal, Bellomo, Raccanelli and Verde; JCAP 10 (2020) 017.
And, of course, cite the original CLASS papers, at least:

The Cosmic Linear Anisotropy Solving System (CLASS) II: Approximation schemes, Blas, Lesgourgues and Tram (2011).

