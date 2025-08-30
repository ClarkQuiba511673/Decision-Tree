## 📋 Lab Objectives
By the end of this lab, students will be able to:
- Understand the concept and structure of decision trees 
- Apply the Decision Tree algorithm on a classification dataset
- Evaluate the model using performance metrics and visualizations
- Visualize the decision tree structure
- Perform hyperparameter tuning to optimize model performance

## 🛠 Requirements
- Python 3.x installed
- Libraries: pandas, scikit-learn, matplotlib, seaborn, graphviz, pydot
- Jupyter Notebook or any Python IDE (e.g., VS Code, PyCharm)

## 📦 Installation
Install dependencies (if not already installed):

```bash
pip install pandas scikit-learn matplotlib seaborn graphviz pydot
```
For graphviz, you may also need to install the system package:

- Windows: Download from graphviz.org
- macOS: brew install graphviz
- Ubuntu/Debian: sudo apt-get install graphviz

## 🗂 Dataset Selection
Choose a publicly available dataset appropriate for classification with the following requirements:

- At least two classes (target categories)
- At least five features (can be numerical or encoded categorical)

Suggested datasets:
- Iris dataset (included in scikit-learn)
- Titanic dataset
- Wine quality dataset
- Breast cancer Wisconsin dataset

## 📝 Assignment / Deliverables
1. Apply the Decision Tree algorithm to your chosen dataset
2. Save the results and visualizations
3. Perform hyperparameter tuning with at least 4 different configurations
4. Submit the following:

- Python script or Jupyter notebook
- Visualization of the decision tree (decision_tree.png)
- Confusion matrix heatmap
- Performance metrics (accuracy, classification report)
- Comparison of different hyperparameter configurations

## 📊 Evaluation Metrics Explanation
- Accuracy: Proportion of correct predictions among all predictions
- Confusion Matrix: Shows true vs. predicted labels
- Classification Report: Includes precision, recall, and F1-score for each class

## 🔧 Hyperparameter Explanation
- max_depth: The maximum depth of the tree
- min_samples_split: The minimum number of samples required to split an internal node
- criterion: The function to measure the quality of a split ("gini" or "entropy")

## 📚 Additional Resources
- Scikit-learn Decision Trees documentation
- Graphviz documentation
- Understanding Decision Tree Hyperparameters
Happy modeling! 🌳
