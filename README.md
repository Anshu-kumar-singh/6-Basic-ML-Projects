🤖 ML Projects Portfolio
A collection of 6 beginner-to-intermediate machine learning projects covering core concepts — regression, classification, clustering, and time series prediction — built with Python and scikit-learn.

📁 Projects Overview
#ProjectTypeAlgorithm(s)Dataset1Iris Flower ClassificationClassificationKNN, SVM, Decision Tree, Voting EnsembleIris (sklearn)2House Price PredictionRegressionLinear RegressionBoston Housing3Titanic Survival PredictionClassificationLogistic Regression, Random ForestKaggle Titanic4Loan Approval PredictionClassificationLogistic Regression, Decision Tree, Random ForestCustom5Stock Price Trend PredictionTime Series ClassificationLogistic Regression, Random ForestYahoo Finance (AAPL)6Customer SegmentationClusteringKMeans, DBSCAN, HierarchicalMall Customers

🔍 Project Details
1. 🌸 Iris Flower Classification
Folder: 01_iris_classification/
Classifies iris flowers into 3 species (setosa, versicolor, virginica) using multiple classifiers and combines them into a Voting Ensemble for improved accuracy.

Techniques: Feature scaling, train-test split, ensemble voting (hard/soft)
Models: KNN, SVM, Decision Tree
Highlights: Confusion matrix, classification report, model comparison
Result: High accuracy (~97%) with the ensemble model


2. 🏠 House Price Prediction
Folder: 02_house_price_prediction/
Predicts median house prices using the Boston Housing dataset with Linear Regression, including correlation analysis and feature importance.

Techniques: Feature scaling, correlation heatmap, residual analysis
Models: Linear Regression
Highlights: R² score evaluation, actual vs predicted plot
Result: Strong regression performance on 13 housing features


3. 🚢 Titanic Survival Prediction
Folder: 03_titanic_survival/
Classic ML challenge predicting whether a passenger survived the Titanic disaster based on features like age, gender, and class.

Techniques: EDA, missing value handling, feature engineering, label encoding
Models: Logistic Regression, Random Forest
Highlights: Data cleaning walkthrough, feature selection reasoning
Dataset: Kaggle Titanic Competition


4. 💳 Loan Approval Prediction
Folder: 04_loan_approval/
Predicts loan approval status based on applicant features like income, loan amount, education, and gender.

Techniques: Label encoding, imputation, GridSearchCV for hyperparameter tuning
Models: Logistic Regression, Decision Tree, Random Forest
Highlights: Model comparison, confusion matrix, classification report


5. 📈 Stock Price Trend Prediction
Folder: 05_stock_price_prediction/
Predicts whether AAPL stock price will go up or down the next day using historical price data and moving average features.

Techniques: Feature engineering (SMA 5/10/15), time-series aware train-test split (no shuffle)
Models: Logistic Regression, Random Forest
Highlights: yfinance data fetching, directional accuracy metric
Data: Apple Inc. (AAPL) — 2018 to 2024


6. 🛍️ Customer Segmentation
Folder: 06_customer_segmentation/
Segments mall customers into distinct groups based on Annual Income and Spending Score using multiple clustering approaches.

Techniques: Feature scaling, Elbow method, Silhouette scoring, Dendrogram
Models: KMeans (K=5), DBSCAN, Hierarchical Clustering
Highlights: Best silhouette score at K=5 (0.55), 5 clear customer segments identified
Dataset: Mall Customers Dataset


🛠️ Tech Stack

Language: Python 3
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, yfinance, scipy
Environment: Google Colab / Jupyter Notebook


🚀 Getting Started
bash# Clone the repo
git clone https://github.com/Anshu-kumar-singh/ml-projects-portfolio.git
cd ml-projects-portfolio

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn yfinance scipy

# Open any notebook
jupyter notebook 01_iris_classification/IRIS.ipynb

Note: The Titanic project requires a Kaggle API key (kaggle.json) to download the dataset. See Kaggle API docs for setup.


📊 Skills Demonstrated

Supervised Learning (Classification & Regression)
Unsupervised Learning (Clustering)
Feature Engineering & Selection
Data Preprocessing & EDA
Model Evaluation & Comparison
Hyperparameter Tuning (GridSearchCV)
Real-world data fetching (Kaggle, yfinance)


👤 Author
Anshu Kumar Singh

GitHub: @Anshu-kumar-singh
