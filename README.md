# Optimising Higgs Signal Search Using Machine Learning

This project uses machine learning to improve the identification of Higgs boson events from background Z boson events in simulated particle physics data. The goal is to optimise the binning of event data to achieve the most precise binned likelihood fit for the signal rate.

## Overview

In high-energy physics, distinguishing rare signal events (like Higgs bosons) from more common background processes is critical. This project explores how machine learning can be applied to enhance the statistical power of such searches.

## Key Features

Machine learning models: Implemented binary and multiclass classifiers, including XGBoost, to separate Higgs signal events from background events.

Binning strategy: Used predicted probabilities (predict_proba) from ML models to define optimal 1D and 2D histograms for likelihood fitting.

Performance evaluation: Tested different models and performance metrics to identify the setup that provides the most precise signal rate estimate.

Simulations: Worked with simulated particle physics datasets to train and validate models before applying them to the binning problem.

## Technologies

Python

XGBoost

PyTorch

scikit-learn

NumPy, matplotlib

## Project Goals

Explore the effectiveness of ML-based binning compared to traditional methods.

Determine which model architectures provide the best separation of signal and background events.

Evaluate precision improvements in binned likelihood fits using ML-informed bins.
