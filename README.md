

🚢 Titanic Dataset Analysis

📁 Dataset
Source: Kaggle – Titanic: Machine Learning from Disaster

Files Used: titanic.csv
This dataset contains information about passengers aboard the Titanic, including demographics, class, fare, and survival outcome. The objective is to predict passenger survival.

🎯 Project Objective
Analyze passenger data to uncover patterns influencing survival and build predictive models to classify survival outcomes.

⚙ Steps Followed

Data Preparation

Handled missing values (e.g., Age, Cabin).

Removed duplicates and standardized formats.

Explored data using info(), describe(), and basic visualizations.

Exploratory Data Analysis (EDA)

Visualized survival rates by gender, class, and age.

Examined correlations between numerical features (Age, Fare) and survival.

Analyzed categorical features (Sex, Pclass, Embarked) for survival impact.

Data Preprocessing

Encoded categorical variables.

Separated features (X) and target (y).

Split data into training and test sets.

Model Building

Built Logistic Regression and Random Forest classifiers.

Tuned hyperparameters and trained models on training data.

Model Evaluation

Evaluated using accuracy, confusion matrix, ROC-AUC, and classification report.

Visualized model performance with plots.

Feature Importance

Identified top predictors of survival: Sex, Pclass, Age, Fare.

🔧 Tools & Libraries Used

Python 3.x

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Scikit-learn – Modeling & evaluation

Google Colab – Development environment

📊 Key Results & Insights

Women and children had higher survival rates.

First-class passengers survived more often than lower-class passengers.

Age and fare were significant predictors of survival.

Random Forest achieved ~81% accuracy, outperforming Logistic Regression (~79%).

🚀 Future Work

Feature engineering (family size, titles) for better predictions.

Experiment with advanced algorithms (XGBoost, Gradient Boosting).

Create interactive dashboards using Plotly or Streamlit.

📌 How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Run in Colab:


Or locally:

python titanic_analysis.py


✅ Repository Link: https://github.com/Gayathripanchavati/SCT_Ds_02.git

#SkillCraftTechnology #TitanicDataset #DataScience #MachineLearning #EDA #Python #RandomForest #LogisticRegression
