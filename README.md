# Network inference tutorial

Slides and code for my Network Inference from time-series data tutorial.

(c) [Joseph T. Lizier](https://lizier.me/joseph/), 2025-.

## Slides

See `202506-NetSci-NetworkInferenceTutorial.pdf`.

Contents:
* Philosophy: functional, effective and structural connectivity:
* Approaches/measures
* Considerations

## Notebooks

There are two main demonstration notebooks here:
1. `NetworkInference_CAs.ipynb` to run inference on Elementary Cellular Automata data, using non-linear measures (mutual information, transfer entropy, multivariate transfer entropy)
2. `NetworkInference_Linear.ipynb` to run inference on various data sets (synthetic VAR, stock closing prices, fMRI) with linear measures (correlation, least squares regression)

## Requirements:

To run the notebooks, you require Python v3 with packages:
1. The usual suspects: `numpy`, `scipy`, `sys`, `matplotlib`, `os`
2. Specific packages for finance (`yfinance`, `pandas`) and neuroscience (`nilearn`) examples
3. `jpype1` -- it's important that you install jpype1 rather than jpype!

A Java runtime (JRE) installation, so that python's jpype1 can call it, and to run the AutoAnalyser from JIDT to generate Java code.

## References:

* [JIDT](https://github.com/jlizier/jidt) -- toolkit for information-theoretic measures
* [IDTxl](https://github.com/pwollstadt/IDTxl) -- toolkit for effective network inference with information-theoretic measures
* [pyspi](https://github.com/DynamicsAndNeuralSystems/pyspi) -- toolkit for many pairwise statistical measures which could be used for functional connectivity
* [assessing-linear-dependence](https://github.com/olivercliff/assessing-linear-dependence) -- toolkit for handling autocorrelations for linear measures

## Licences:

This repo is distributed under GPLv3.

It redistributes the jar file from my [JIDT](https://github.com/jlizier/jidt) project under GPLv3.

## Instances:

This tutorial has been run at:
* [NetSci 2025](https://netsci2025.github.io/)


