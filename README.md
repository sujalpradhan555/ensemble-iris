# Ensemble Classification on Iris Dataset  

This project demonstrates ensemble learning using Logistic Regression, Decision Tree, and SVM combined with a Voting Classifier.  

## Installation  
pip install -r requirements.txt


## Dataset  
The project uses the classic **Iris dataset** from `sklearn.datasets`.  
It has 150 samples with 4 features and 3 classes (Setosa, Versicolor, Virginica). 

## Approach  

1. Load the Iris dataset  
2. Split into training and testing sets  
3. Train 3 base classifiers:  
   - Logistic Regression  
   - Decision Tree  
   - Support Vector Classifier (SVC)  
4. Combine them using a **Voting Classifier**  
5. Evaluate using confusion matrix & classification report  
6. Demonstrate pipelines & custom transformers  


## Usage  

Run the notebook:  

jupyter notebook ensemble_iris.ipynb


## Results  

- Voting Classifier achieved high accuracy on the Iris dataset  
- Ensemble learning performed better than individual classifiers 

## Conclusion  

- Ensemble methods improve performance over single classifiers  
- Pipelines make workflows more modular  
- Future improvements: hyperparameter tuning, advanced ensembles (Random Forest, Gradient Boosting)  
