🏠 House Price Prediction using Machine Learning 
This project demonstrates a machine learning approach to predict house prices based on various features using a Jupyter Notebook. It includes data preprocessing, model training, evaluation, and visualization using Python libraries such as pandas, numpy, matplotlib, and scikit-learn.

**📁 Dataset**
The dataset (House Price Prediction Dataset.csv) contains attributes related to house listings such as:
Location
Size (sqft)
Number of Bedrooms
Number of Bathrooms
Age of the Property
Price (Target variable)

**⚙️ Workflow**
Data Loading and initial exploration
Data Cleaning: dropping unused columns like Id, Garage, etc.
Feature Engineering: one-hot encoding for categorical variables (e.g., Location)
Train/Test Split (80/20)

**Model Training:**
Linear Regression
Polynomial Regression (Degree 2)
Feature Scaling using StandardScaler

Evaluation using:
Mean Squared Error (MSE)
R² Score
Visualization: Actual vs Predicted price scatter plot

Model Coefficients overview

**🧪 Model Performance**
Example outputs include:
Linear Regression MSE and R² Score
Polynomial Regression MSE and R² Score
Visualization of actual vs predicted prices

**🧰 Tools & Technologies**
Python 3
Jupyter Notebook / Google Colab
Libraries:
pandas
numpy
matplotlib
scikit-learn

**📌 Future Enhancements**
Try advanced models like Random Forest, Gradient Boosting, or XGBoost
Add interactive web interface for predictions
Implement cross-validation for robust performance

