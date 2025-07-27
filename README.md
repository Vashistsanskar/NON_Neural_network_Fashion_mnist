# Fashion MNIST – High-Accuracy Classification Without Neural Networks
### Achieve up to 90% test accuracy on Fashion MNIST using classic machine learning and feature selection—
### no neural networks required!

## ⭐ Overview
 ### *This project demonstrates how powerful traditional machine learning can be for image classification when paired with thoughtful feature selection. Instead of deep learning*
 
## we combine:

Variance thresholding & chi-square test for feature selection

Tree-based ensemble models: Random Forest, XGBoost, AdaBoost

Voting Classifier ensemble

***Final model: XGBoost***

All experiments were run on the Fashion MNIST dataset (28x28 grayscale images, 10 clothing classes).

🚦 Key Results
Model	Accuracy (%):-
-->Random Forest	87
-->AdaBoost	89
-->XGBoost	90
Voting Classifier: Used RandomForest, XGBoost, and AdaBoost as estimators for robust ensemble predictions.

🛠️ Features & Methods
Feature Selection
*Variance Threshold: Removes uninformative low-variance pixels.*

*Chi-Square Test: Selects features statistically associated with class labels.*

Models Used
Random Forest

AdaBoost Classifier

XGBoost Classifier

VotingClassifier (combining the above)

## Pipeline
The full pipeline includes:

*Variance thresholding*

*Chi-square feature selection*

*Final evaluation with XGBoost*

