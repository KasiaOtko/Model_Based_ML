# About

This is a project for [Model-Based Machine Learning course](https://kurser.dtu.dk/course/42186) at Technical University of Denmark (spring 2021 edition). The goal was to determine color (red/white) and quality of wine (given on a scale from 0 to 10) using only its physico-chemical properties.

To achieve these goals, we constructed multiple Probabilistic Graphical Models (PGMs):
* Multi-class classification model to predict wine quality (based on the quality score, we determined three categories of wines: bad (0 - 4), medium (5 - 6), good (7 - 10));
* Binary classification model to predict wine color;
* Hierarchical model to predict wine color;
* Gaussian Processes as a non-parametric approach to the problem of binary classification;
* Gaussian Processes with Automatic Relevance Determination to determine predictive power of the features on the target variable.

All the results are presented in the .ipynb file. Executive report provides a two-page summary of the project.
