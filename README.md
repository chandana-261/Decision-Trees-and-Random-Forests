# Decision-Trees-and-Random-Forests
# Heart Disease Classification Using Tree-Based Models

## Objective
To learn and implement tree-based models for classification using the Heart Disease dataset. This includes training and evaluating Decision Trees and Random Forests.

## Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib & Seaborn
- Graphviz (for visualizing trees, optional)

## Dataset
The dataset used is `heart.csv`, which contains 13 medical features and a binary target column (`target`):
- `target = 1`: Presence of heart disease
- `target = 0`: Absence of heart disease

## Tasks Performed

### 1. Decision Tree Classifier
- Trained using all features.
- Achieved **98.54% accuracy** on the test set.

### 2. Pruned Decision Tree
- Limited tree depth to avoid overfitting (`max_depth=4`).
- Accuracy reduced to **80.00%**, indicating trade-off between complexity and performance.

### 3. Random Forest Classifier
- Ensemble method with 100 trees.
- Achieved **98.54% accuracy** on the test set.
- Provided feature importance insights.

### 4. Feature Importances
Top 5 contributing features:
1. `cp` (Chest Pain Type)
2. `ca` (Major Vessels)
3. `thalach` (Heart Rate)
4. `oldpeak` (ST Depression)
5. `thal` (Thalassemia)

### 5. Cross-Validation
- 5-fold cross-validation yielded a mean accuracy of **99.71%**.

## Conclusion
Random Forests outperformed both full and pruned Decision Trees in this classification task. Feature importance analysis can guide medical experts toward key diagnostic indicators.

## Usage
Run the provided Python script in Jupyter Notebook or any Python environment. Ensure `heart.csv` is in the same directory.

## Author
LAKSHMI CHANDANA YANAMANDRA
