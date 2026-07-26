# Spam Detection Using Decision Tree

## Project Overview
This project was developed as part of the **Machine Learning (CS1461)** course. The objective is to build a Decision Tree classifier capable of distinguishing spam emails from legitimate emails through data preprocessing, model optimization, and performance evaluation.

## Objectives
- Build a spam detection model using Decision Tree.
- Compare model performance with and without normalization.
- Reduce overfitting using tree pruning.
- Handle class imbalance using downsampling and upsampling.
- Evaluate the model using standard classification metrics.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Experiments
The project investigates several machine learning scenarios:

- **Case 1:** Without vs. With MinMax Normalization
- **Case 2:** Full Decision Tree vs. Pruned Decision Tree
- **Case 3:** Original Dataset vs. Downsampling vs. Upsampling
- **Final Model:** Pruned Decision Tree trained on the balanced (upsampled) dataset

## Results
- Best tree depth: **10**
- Final Test Accuracy: **92.59%**
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

The final model combined **Decision Tree pruning** with **upsampling**, achieving the best overall performance while reducing overfitting.

## Repository Contents
- `Spam_Detection_DecisionTree.ipynb` – Complete implementation, experiments, visualizations, and evaluation.

## Author
Rawan Bayounis 
B.Sc. Computer Science Student
