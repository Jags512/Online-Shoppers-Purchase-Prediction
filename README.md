Online Shoppers Purchasing Intention Prediction:

This project aims to predict whether a user will generate Revenue (purchase) on an e-commerce website based on their browsing behavior and session attributes. The dataset used is the Online Shoppers Intention Dataset.

📌 Project Overview

E-commerce websites generate large volumes of data about user sessions. Understanding whether a visitor is likely to make a purchase helps in:

Personalized marketing

Improving user experience

Increasing conversion rates

In this project, we applied Machine Learning techniques to classify whether a session will result in a purchase.

📊 Dataset

Name: Online Shoppers Purchasing Intention Dataset

Source: UCI Machine Learning Repository

Shape: 12,330 rows × 18 features

Target Variable: Revenue (Yes/No → encoded as 1/0)

Key features:

Administrative, Informational, Product-related visits

Page values, Bounce rates, Exit rates

Special days, Month, Operating system, Browser, Region, Traffic type

Visitor type, Weekend

⚙️ Tech Stack

Python 🐍

Pandas, NumPy → Data processing

Scikit-learn → Machine learning models & preprocessing

Matplotlib / Seaborn → Data visualization

🚀 Workflow

Load and explore dataset

Handle categorical variables with OrdinalEncoder & LabelEncoder

Train-test split with stratification

Feature scaling using StandardScaler

Apply Logistic Regression for classification

Evaluate with Accuracy, Confusion Matrix

📈 Results

Built a classification model to predict purchase intentions.

Accuracy achieved: ~85% (Logistic Regression baseline)

Model can be extended with Decision Trees, Random Forest, Gradient Boosting for improvement.

📂 Project Structure
├── online_shoppers_intention.csv   # Dataset
├── shopper_intention.ipynb         # Main notebook (EDA + Model)
├── README.md                       # Project documentation

🔮 Future Improvements

Try advanced models (Random Forest, XGBoost)

Perform hyperparameter tuning with GridSearchCV

Apply feature engineering for better insights

Deploy model using Flask / FastAPI / Streamlit.















