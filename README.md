# Network inference tutorial

Slides and code for my Network Inference from time-series data tutorial.

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

## Instances:

This tutorial has been run at:
* NetSci 2025


