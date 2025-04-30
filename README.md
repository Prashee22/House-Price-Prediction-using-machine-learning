# 🏠 House Price Prediction using Machine Learning

This project demonstrates a machine learning approach to predict house prices based on various features using a Jupyter Notebook. It includes data preprocessing, model training, evaluation, and visualization using Python libraries such as **pandas**, **numpy**, **matplotlib**, and **scikit-learn**.

---

## 📁 Dataset

The dataset (`House Price Prediction Dataset.csv`) includes the following features:

- 📍 Location  
- 📐 Size (in square feet)  
- 🛏️ Number of Bedrooms  
- 🛁 Number of Bathrooms  
- 🏗️ Age of the Property  
- 💰 Price (Target variable)

---

## ⚙️ Workflow

1. **Data Loading** and Initial Exploration  
2. **Data Cleaning**: Dropping unused columns (e.g., `Id`, `Garage`, etc.)  
3. **Feature Engineering**: One-hot encoding for categorical features (`Location`)  
4. **Train/Test Split**: 80% training and 20% testing  

---

## 🤖 Model Training

- **Linear Regression**
- **Polynomial Regression** (Degree 2)
- **Feature Scaling** using `StandardScaler`

---

## 📊 Model Evaluation

The models are evaluated using the following metrics:

- ✅ Mean Squared Error (MSE)
- ✅ R² Score

📉 A scatter plot is used to visualize **Actual vs Predicted Prices**.

🧾 Additionally, model coefficients are examined for insights.

---

## 🧪 Example Performance Results

> (Replace with your actual values if available)

**Linear Regression**
- MSE: _e.g., 1,120,000_
- R² Score: _e.g., 0.87_

**Polynomial Regression**
- MSE: _e.g., 920,000_
- R² Score: _e.g., 0.91_

---

## 🧰 Tools & Technologies

- **Python 3**
- **Jupyter Notebook / Google Colab**
- **Libraries**:
  - pandas  
  - numpy  
  - matplotlib  
  - scikit-learn  

---

## 🚀 Future Enhancements

- 🔍 Experiment with advanced models like **Random Forest**, **Gradient Boosting**, or **XGBoost**
- 🌐 Build an interactive **web interface** for real-time predictions
- ✅ Implement **cross-validation** for more robust evaluation

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Contributions

Feel free to open issues or submit pull requests to contribute!
