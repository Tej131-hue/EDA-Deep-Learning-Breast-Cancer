# Exploratory Data Analysis and Deep Learning for Breast Cancer Classification

## Project Overview
This project performs Exploratory Data Analysis (EDA), statistical analysis, data visualization, and deep learning on the **Wisconsin Diagnostic Breast Cancer Dataset**. A Multi-Layer Perceptron (MLP) neural network is used to classify observations as benign or malignant based on numerical features.

**Course:** Exploratory Data Analysis and Visualization  
**Course Code:** U21ADP05  
**Institution:** KPR Institute of Engineering and Technology  
**Department:** Artificial Intelligence and Data Science  
**Student:** Tejaswini SL  
**Roll Number:** 24CS225  
**Academic Year:** 2026–2027

## Objectives
- Explore a real-world dataset containing more than 15 features.
- Perform data cleaning and statistical analysis.
- Identify patterns, distributions, outliers, and correlations.
- Create meaningful visualizations with interpretations.
- Build and evaluate an MLP neural network.
- Document the complete workflow for reproducibility.

## Dataset Description
- **Dataset:** Wisconsin Diagnostic Breast Cancer
- **Samples:** 569
- **Input features:** 30 numerical features
- **Target:** Benign or malignant
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- **Documentation:** [Scikit-learn Breast Cancer Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Methodology
1. Load and understand the dataset.
2. Check missing values and duplicate records.
3. Calculate descriptive statistics and examine feature distributions.
4. Analyze correlations and relationships between features.
5. Split the dataset into training, validation, and testing sets.
6. Apply median imputation and feature standardization.
7. Train an MLP neural network and compare hidden-layer configurations.
8. Evaluate model performance using classification metrics and visualizations.

## Data Visualizations
The project includes the following visualizations:

1. Diagnosis class distribution
2. Numerical feature distributions
3. Feature correlation heatmap
4. Mean area boxplot by diagnosis
5. Mean radius versus mean texture scatterplot
6. Training loss curve
7. Accuracy versus training data size
8. Confusion matrix
9. Receiver Operating Characteristic (ROC) curve

## Model Evaluation
The model is evaluated using:
- Accuracy
- Classification report
- Confusion matrix
- ROC curve
- Area Under the ROC Curve (ROC-AUC)
- Training loss visualization

See the generated metrics and evaluation charts in the repository for the recorded results.

## Project Structure
```text
EDA-Deep-Learning-Breast-Cancer/
├── README.md
├── data.csv
├── eda_model.py
├── EDA_Breast_Cancer.ipynb
├── Project_Report.pdf
├── Project_Report.docx
├── figures/
│   ├── 01_class_distribution.png
│   ├── 02_feature_distributions.png
│   ├── 03_correlation_heatmap.png
│   ├── 04_boxplot_mean_area.png
│   ├── 05_radius_texture_scatter.png
│   ├── 06_loss_curve.png
│   ├── 07_accuracy_curve.png
│   ├── 08_confusion_matrix.png
│   └── 09_roc_curve.png
└── outputs/
    ├── metrics.json
    ├── hyperparameter_comparison.csv
    └── top_features_descriptive.csv
```

## How to Run the Project

### 1. Install dependencies
```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### 2. Run the Python script
```bash
python eda_model.py
```

### 3. Run the notebook
Open `EDA_Breast_Cancer.ipynb` using Jupyter Notebook or Google Colab and execute the cells.

## Conclusion
This project demonstrates how EDA, statistical analysis, visualization, and neural networks can be combined to analyze a real-world dataset. The visualizations help identify patterns and relationships among numerical features, while the MLP model demonstrates a basic classification workflow.

## Future Scope
- Perform cross-validation and broader hyperparameter tuning.
- Compare MLP performance with other machine learning algorithms.
- Apply model interpretability techniques such as SHAP or permutation importance.
- Evaluate generalization on independent datasets.

## References
1. UCI Machine Learning Repository. *Breast Cancer Wisconsin (Diagnostic) Dataset*. https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
2. Scikit-learn Developers. *load_breast_cancer documentation*. https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
3. Pedregosa, F., et al. (2011). Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research, 12*, 2825–2830. https://jmlr.org/papers/v12/pedregosa11a.html
4. Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. *Computing in Science & Engineering, 9*(3), 90–95. https://doi.org/10.1109/MCSE.2007.55
5. McKinney, W. (2010). Data structures for statistical computing in Python. *Proceedings of the 9th Python in Science Conference*, 56–61. https://doi.org/10.25080/Majora-92bf1922-00a

## Disclaimer
This project is intended for academic and educational purposes only. It is not a medical diagnostic tool and must not be used to make clinical decisions.
