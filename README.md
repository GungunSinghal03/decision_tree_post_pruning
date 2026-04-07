🌳 Decision Tree Classifier (with Post-Pruning)
📌 Overview

This project demonstrates the implementation of a Decision Tree Classifier using Python and Scikit-learn.
The model is trained on the Iris dataset and enhanced using Post-Pruning (Cost Complexity Pruning) to reduce overfitting and improve generalization.

🚀 Features
Uses built-in Iris dataset from sklearn
Splits data into training and testing sets
Trains a Decision Tree Classifier
Applies Post-Pruning (ccp_alpha) to optimize the tree
Visualizes the decision tree
Evaluates model using:
Accuracy Score
Classification Report
🛠️ Tech Stack
Python
Pandas
Matplotlib
Seaborn
Scikit-learn
📂 Dataset
Dataset used: Iris Dataset
Loaded from sklearn.datasets
⚙️ Workflow
Import libraries
Load dataset
Prepare features (X) and target (Y)
Split data into train and test sets
Train Decision Tree model
Apply Post-Pruning using cost complexity pruning (ccp_alpha)
Visualize the pruned tree
Make predictions
Evaluate model performance
✂️ Post-Pruning

Post-pruning is applied using Cost Complexity Pruning, where unnecessary branches are removed after the tree is fully grown.

Benefits:

Reduces overfitting
Improves model generalization
Simplifies the tree structure
📊 Model Evaluation
Accuracy score is used to measure performance
Classification report includes:
Precision
Recall
F1-score
▶️ How to Run
git clone <your-repo-link>
cd <folder-name>
jupyter notebook
📌 Notes
This project is for learning purposes
Demonstrates both basic Decision Tree and pruning technique
📎 Future Improvements
Hyperparameter tuning
Cross-validation
Comparison with other models
AUTHOR NAME-Gungun singhal
