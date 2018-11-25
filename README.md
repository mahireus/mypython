# mypython
Python data science tools for Qlik
Table of Contents
Introduction
Demonstration Video
Note on the approach
Docker Image
Pre-requisites
Installation
Usage
Introduction
Qlik's advanced analytics integration provides a path to making modern algorithms more accessible to the wider business audience. This project is an attempt to show what's possible.

This repository provides a server side extension (SSE) for Qlik Sense built using Python. The intention is to provide a set of functions for data science that can be used as expressions in Qlik. Sample Qlik Sense apps are also included and explained so that the techniques shown here can be easily replicated.

The current implementation includes:

Supervised Machine Learning : Implemented using scikit-learn, the go-to machine learning library for Python. This SSE implements the full machine learning flow from data preparation, model training and evaluation, to making predictions in Qlik. In addition, models can be interpreted using Skater.
Unupervised Machine Learning : Also implemented using scikit-learn. This provides capabilities for dimensionality reduction and clustering.
Clustering : Implemented using HDBSCAN, a high performance algorithm that is great for exploratory data analysis.
Time series forecasting : Implemented using Facebook Prophet, a modern library for easily generating good quality forecasts.
Seasonality and holiday analysis : Also using Facebook Prophet.
Linear correlations : Implemented using Pandas.
Further information on these features is available through the Usage section below.

For more information on Qlik Server Side Extensions see qlik-oss.

Disclaimer: This project has been started by me in a personal capacity and is not supported by Qlik.
