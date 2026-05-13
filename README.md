🧠 Stroke Prediction Project 
This project aims to build a machine learning model to predict the likelihood of a patient suffering a stroke based on clinical and lifestyle parameters such as age, gender, hypertension, heart disease, smoking status, and glucose level.


 🚀Key Features: 
 Exploratory Data Analysis (EDA): Detailed visualization of features using matplotlib and seaborn.
 Data Cleaning & Preprocessing: Advanced encoding techniques (One-Hot Encoding), and feature scaling using StandardScaler.
 Handling Class Imbalance: Applied SMOTETomek to balance the dataset and avoid model bias.
 Model Evaluation: Detailed performance analysis using Classification Reports and Heatmap Confusion Matrices.
 
 📈 Project Workflow :
 
 1.Data Exploration & Analysis:Understanding data dimensions (df.shape, df.info()), statistical overview (df.describe()), and plotting correlations using Heatmaps.
 
 2. Feature Engineering :
  1-Dropping unneeded columns like id.
  2-Converting categorical features into numerical format via pd.get_dummies().
  3-Normalizing data via StandardScaler.
 
 4. Handling Class Imbalance :Since the dataset has a very low percentage of stroke cases, SMOTETomek was utilized to synthetically generate minority class samples and clean noisy data boundaries.
 
 5. Model Training & Evaluation :Splitting data into 80% training and 20% testing sets using stratified splitting, making predictions, and generating the Confusion Matrix.
