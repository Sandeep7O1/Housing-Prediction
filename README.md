# Housing-Prediction
🏠 **Housing Price Prediction**
  This project focuses on predicting housing prices using a linear regression model. By leveraging data preprocessing techniques and model evaluation metrics, the goal is to provide accurate estimations of house prices based on various features.

📂 **Project Overview**
  The notebook Housing Price Prediction.ipynb walks through the following steps:
**Data Import and Exploration:** Loading the housing dataset and performing initial exploratory data analysis (EDA) to understand the structure and distribution of the data.
**Data Preprocessing:**
**Encoding Categorical Variables:** Converting categorical features into numerical format using one-hot encoding.
**Feature Scaling:** Applying standardization to numerical features to ensure they contribute equally to the model.
**Log Transformation:** Transforming the target variable (price) using log transformation to handle skewness and stabilize variance.
**Model Training:**
  Splitting the dataset into training and testing sets.
  Training a linear regression model using the training data.
**Model Evaluation:**
      Predicting house prices on the test set.
      Evaluating model performance using metrics such as Root Mean Squared Error (RMSE) and R² Score.
      Visualizing the relationship between actual and predicted prices.

**📊 Dataset**
The dataset used contains various features of houses, including:

**area:** Square footage of the house.
**bedrooms:** Number of bedrooms.
**bathrooms:** Number of bathrooms.
**stories:** Number of stories.
**mainroad:** Whether the house is on the main road.
**guestroom:** Availability of a guest room.
**basement:** Presence of a basement.
**hotwaterheating:** Availability of hot water heating.
**airconditioning:** Presence of air conditioning.
**parking:** Number of parking spaces.
**prefarea:** Whether the house is in a preferred area.
**furnishingstatus:** Furnishing status of the house.

🛠️ **Technologies Used**
**Python:** Programming language used for implementation.
**Pandas:** Data manipulation and analysis.
**NumPy:** Numerical computing.
**Matplotlib & Seaborn:** Data visualization.
**Scikit-learn:** Machine learning library for model building and evaluation.

**📈 Results**
After training the linear regression model and evaluating its performance:
**RMSE:** Approximately 1,314,648.20
**R² Score**: 0.658
