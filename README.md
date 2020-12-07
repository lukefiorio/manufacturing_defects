# Manufacturing Defect Detection
### UW Data Science Final Project - Defect Detection

This project uses data from the UCI Machine Learning Repository on manufacturing defects to build a defect detection system.  The data can be found and downloaded here: 
- features: https://archive.ics.uci.edu/ml/machine-learning-databases/secom/secom.data
- target: https://archive.ics.uci.edu/ml/machine-learning-databases/secom/secom_labels.data

Our goal is to predict manufacturing failures based on sensor readings that monitor the manufacturing process.  Specifically, we aim to build a model that achieves high positive recall, with reasonable precision.  Or, in other words, we aim to flag (predict) as many of the defective products as possible, while maintaining a reasonable degree of accuracy.

**This repo contains 5 files:**
| File                          | Description |
| ----------------------------- | ----------- |
| secom_DFD.pptx                | Data Flow Diagram in PPT, which documents the data cleaning and feature selection |
| secom_DFD.pdf                 | PDF of the Data Flow Diagram, for direct viewing (no download required) |
| Milestone01_LukasFiorio.ipynb | Python Notebook used to explore the data and apply feature reduction |
| Milestone02_LukasFiorio.ipynb | Implements Minimal Reproduction of Milestone 1. Then goes further to build, tune, and evaluate various ML models (Decision Tree, Random Forest, SVM) |
| Milestone03_LukasFiorio.ipynb | Implements Minimal Reproduction of Milestones 1, 2.  Then goes further to build neural networks and compare final accuracy metrics |

**Recommended viewing sequence:**

Start with Milestone 3, which is the culmination of this project, and defer back to Milestones 1, 2, or the Data Flow Diagram (DFD) only if interested in additional details on the steps taken.  The DFD may also serve as a helpful summary of the feature selection implemented in Milestone 1.

**Problem Description:**

The dataset that we use to build and test our model contains 590 sensor readings on approximately 1,600 manufactured products. Our data has a binary target variable which indicates whether the manufactured product was defective.

Given the width of our data (590 features), it is prudent for us to explore feature reduction before building our predictive models.
