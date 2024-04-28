This repository contains Supplementary Material (data and source code) to support the paper "Moment-based Density Elicitation with Applications in ProbabilisticLoops" by Andrey Kofnov, Ezio Bartocci and Efstathia Bura. https://www.researchgate.net/publication/370103461_Moment-based_Density_Elicitation_with_Applications_in_Probabilistic_Loops.

We propose the K-series estimation approach for the recovery of unknown univariate and multivariate distributions given knowledge of a finite number of their moments. Our method is directly applicable to the probabilistic analysis of systems that can be represented as probabilistic loops; i.e., algorithms that express and implement non-deterministic processes ranging from robotics to macroeconomics and biology to software and cyber-physical systems. K-series statically approximates the joint and marginal distributions of a vector of continuous random variables updated in a probabilistic non-nested loop with nonlinear assignments given a finite number of moments of the unknown density. Moreover, K-series automatically derives the distribution of the systems’ random variables symbolically as a function of the loop iteration. K-series density estimates are accurate, easy and fast to compute. We demonstrate the feasibility and performance of our approach on multiple benchmark examples from the literature.


##############  DESCRIPTION ################


1) req.txt - requirements-file for python to execute "main.py"
2) main.py - .py-file with all mathematical logic and with benchmarks
from Table 5 (page 14) of the "Supplementary Material.pdf" and real-data benchmark (see Figure 4 of main paper);
uses "ort_poly2.py" and "Bivariate_normal_distribution.py"
3) ort_poly2.py - python code to carry our Polynomial chaos expansion
4) "Bivariate_normal_distribution.py" - self-written code to implement bivariate normal distribution
5) Figures - folder with plots for benchmarks ( see (3) )
6) S1Dataset.txt - dataset from  Munkhammar et al. [2017]
