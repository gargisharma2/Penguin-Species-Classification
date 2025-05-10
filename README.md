# 🐧 Penguin Species Classification
A machine learning project to classify three species of penguins — Adelie, Chinstrap, and Gentoo — using the Palmer Penguins dataset. This project applies data preprocessing, exploratory data analysis (EDA), and Random Forest classification to identify patterns and build a predictive model.

# 📌 Objective
To build a robust classification model that can accurately identify penguin species based on physical and environmental features, offering a cleaner and more engaging alternative to the classic Iris dataset for ML exploration.

# 🔍 Dataset
- Source: https://github.com/allisonhorst/palmerpenguins
- Features include: bill length, bill depth, flipper length, body mass, island, and sex.

# ⚙️ Tools & Libraries
- Python, Jupyter Notebook

- Pandas, NumPy

- Matplotlib, Seaborn

- Scikit-learn

# 📊 Key Steps
1. Data Cleaning: Removed null values and label-encoded categorical features (island, sex, species).

2. Exploratory Data Analysis (EDA):

 - Visualized distributions and pairwise relationships.

 - Created a missing value heatmap and barplot.

3. Model Building:

 - Used Random Forest Classifier for training and prediction.

 - Achieved high accuracy on the test set.

4. Evaluation:

 - Accuracy score, classification report, confusion matrix.

 - Feature importance visualization to interpret the model.

# ✅ Results
- The model accurately classified penguin species with strong performance metrics.

- Key distinguishing features included flipper length, bill depth, and body mass.

# 📌 Future Improvements
- Try other models like XGBoost, SVM, or Logistic Regression

- Use imputation for missing values instead of row removal

- Deploy the model using Streamlit or Flask
