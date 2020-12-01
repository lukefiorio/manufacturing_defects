# Manufacturing Defect Detection
### UW Data Science Final Project - Defect Detection

This project uses data from the UCI Machine Learning Repository on manufacturing defects to build a defect detection system.  The data can be found and downloaded here: 
- features: https://archive.ics.uci.edu/ml/machine-learning-databases/secom/secom.data
- target: https://archive.ics.uci.edu/ml/machine-learning-databases/secom/secom_labels.data

Our goal is to predict manufacturing failures based on sensor readings that monitor the manufacturing process.  Specifically, we aim to build a model that achieves high positive recall, with reasonable precision.  Or, in other words, we aim to flag (predict) as many of the defective products as possible, while maintaining a reasonable degree of accuracy.

**This repo contains 4 files:**
| File                          | Description |
| ----------------------------- | ----------- |
| Milestone01_LukasFiorio.pptx  | Data Flow Diagram, which documents the feature reduction methodology |
| Milestone01_LukasFiorio.ipynb | Python Notebook used to explore the data and apply feature reduction |
| Milestone02_LukasFiorio.ipynb | Python Notebook used to build, tune, and evalute ML models (Decision Tree, Random Forest, SVM) |
| Milestone03_LukasFiorio.ipynb | Python Notebook used to build neural networks and compare final accuracy metrics |

**Problem Description:**

The dataset that we use to build and test our model contains 590 sensor readings on approximately 1,600 manufactured products. Our data has a binary target variable which indicates whether the manufactured product was defective.

Given the width of our data (590 features), it is prudent for us to explore feature reduction before building our predictive models.
