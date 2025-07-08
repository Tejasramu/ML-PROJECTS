# 🏠 House Price Prediction using Machine Learning

This project builds a supervised machine learning model to predict house prices based on features like location, area, number of bedrooms, and more. It helps estimate property values, making it useful for real estate platforms, buyers, and investors.

---

## 📁 Files Included
- `house_price_prediction.ipynb`: Jupyter Notebook with full pipeline from data preprocessing to model training and evaluation.

---

## 🔍 Dataset Overview
The dataset includes:
- Area (in sq. ft.)
- Location
- Number of Bedrooms/Bathrooms
- Balcony, Parking, Floor
- Area Type
- Price (Target Variable)

---

## 🧪 Tech Stack Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**, **XGBoost**

---

## ⚙️ ML Pipeline
1. **Data Cleaning**: Handled null values, duplicates, and inconsistent categories
2. **EDA**: Explored relationships between features and price using visualizations
3. **Feature Engineering**: Created "price per sqft", grouped rare locations, encoded categories
4. **Model Building**:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - XGBoost Regressor
5. **Model Evaluation**:
   - R² Score, MAE, RMSE
   - Cross-validation

---

## 📊 Results
- Best-performing model: Random Forest Regressor
- Achieved R² Score of ~0.85
- Accurate predictions for different property types and locations

---

## 🙋‍♂️ Role
End-to-end project development:
- Data preprocessing
- Model development
- Performance analysis
- Visualizations

---

## 📌 Applications
- Real estate websites (99acres, MagicBricks)
- Investment decision-making tools
- Automated property valuation systems

---

## 📸 Sample Output
![House Price Model Output](house_price_output.png)




