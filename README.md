
# Decision Tree Classifier Project

This project demonstrates how to use a Decision Tree Classifier on a dataset using Python and Scikit-learn. It includes data preprocessing, training/testing split, hyperparameter tuning using GridSearchCV, evaluation, visualization, and feature importance analysis.

## Project Structure

All files should be placed in the same directory for the project to run correctly.

```
|--Banknote_Authencation.csv   #dataset
├── decision_tree.ipynb        # Jupyter Notebook with all code
├── README.md                  # Project overview and instructions (this file)
```

## Requirements

Make sure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- scikit-learn
- seaborn (optional)

Install them using:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```

## Features

- Split data into training (80%) and testing (20%) sets
- Train a `DecisionTreeClassifier`
- Tune hyperparameters with `GridSearchCV`
- Evaluate model using accuracy, precision, recall, and F1-score
- Plot the confusion matrix
- Visualize the decision tree using `plot_tree()`
- Extract and plot feature importance

## How to Run

1. Make sure your dataset file is in the same folder as the notebook.
2. Open `decision_tree.ipynb` in Jupyter Notebook or Google Colab.
3. Run each cell step-by-step.
4. The best model will be trained and evaluated automatically.
5. Visual outputs include the decision tree and feature importance plot.
