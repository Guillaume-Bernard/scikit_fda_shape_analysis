The objective of this package is to implement some shape feature extraction for functional data analysis (FDA).

Documentation
=============

FDA aims at analyzing a dataset where each sample **x_i** is a realisation of an unknown function **f** which depends on a continuous variable **t**. 

As we work with multivariate data, each  **x_i** is a vector containing samples of **f** along **t**, where **f** may be scalar- or vector-valued.
In FDA, **x_i** is approximated by a functional variable written as the linear combination spaned by an orthogonal functional basis (e.g B-splines, Fourier, wavelets).
In our context, we use such an approximation as a building block to ease the computation of (functional) shaped-based features (e.g curvature, velocity, arc length) that require accurate estimates of derivatives and integrals.

This package is based on Scikit-fda, see notebooks for examples.

Installation
============
You only need to install the library scikit-fda https://fda.readthedocs.io/en/stable/ and its dependencies to use this package
Note: scikit-fda requires Visual studio Build tools as C++ compiler.

Installation 
------------------------

.. code:: bash

    git clone https://github.com/Guillaume-Bernard/curve_shape_analysis.git
    pip install ./curve_shape_analysis

References
============
- https://www.sciencedirect.com/science/article/abs/pii/S0950705120302835 : Clément Lejeune, Josiane Mothe, Adil Soubki, Olivier Teste. Shape-based outlier detection in multivariate functional data. Knowledge-based Systems. 2020.
- https://openproceedings.org/2020/conf/edbt/paper_236.pdf : Clément Lejeune, Josiane Mothe, Olivier Teste. Outlier detection in multivariate functional data based on a geometric aggregation. Proceedings of EDBT conference 2020.
- Functional Data Analysis with R and MATLAB 2009 Authors: Ramsay, James O., Hooker, Giles, Graves, Spencer
- Scikit-fda: https://fda.readthedocs.io/en/stable/

Contributors
=============
The people involved in the development are Guillaume Bernard, Clément Lejeune, Sandra Ferrieres and Olivier Teste.
