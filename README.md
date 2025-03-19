# Air-Quality-Classification
The project conducts air quality level predictions using environmental and demographic factors to classify levels into Good Moderate and Hazardous and Poor classifications. The data consists of PM2.5, PM10, NO₂, SO₂, CO concentrations together with temperature measurements, humidity readings, population density data and industrial zone proximity data.

The analysis serves as a complete machine learning process that involves data prep steps alongside feature scaling alongside model construction and hyperparameter optimization and final performance testing. A comparison of Random Forest and Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Gradient Boosting Classifier (GBC) and XGBoost took place during the implementation phase.

The evaluation of models relied on essential performance indicators including accuracy, precision, recall and F1-score. The combination of Random Forest and GBC achieved the best performance metrics which qualify them for practical air quality monitoring scenarios.

The entire implementation process occurred within the Python environment from Jupyter Notebook while adhering to standard practices in machine learning. The project provides hands-on evidence about using AI technology to address environmental issues.

About the code

Dependencies:
- pandas
- numpy
- warnings
- scikit-learn
- XG boost
- matplotlib
- seaborn

Usage:
- Open the notebook in Jupyter or JupyterLab and run the cells sequentially.
- Ensure all necessary libraries are installed before execution.

Steps:
1. Load and preprocess the dataset (e.g., cleaning, feature engineering).
2. Exploratory Data Analysis and Visualization.
3. Train models: Random Forest, SVM, GBC, KNN and XGBoost.
4. Evaluate models using cross-validation and compare their performance.
5. Visualize model performance with metrics such as accuracy, ROC curves.
6. All models comparison.
