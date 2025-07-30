# 🚗 Car Price Prediction

This project predicts the price of used cars using machine learning techniques. By analyzing various features of a car, the model helps estimate a fair selling price, which can be useful for both buyers and sellers.

---

## 📊 Dataset

The dataset includes the following features:

- **Car Name**
- **Year** (of purchase)
- **Present Price**
- **Kms Driven**
- **Fuel Type**
- **Seller Type**
- **Transmission**
- **Owner**
- **Selling Price** *(Target Variable)*

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for ML models)

---

## 🔍 Workflow

1. **Data Exploration & Cleaning**
   - Loaded the dataset using Pandas
   - Checked for missing values
   - Converted purchase year into car age
   - Encoded categorical variables

2. **Data Visualization**
   - Correlation heatmap
   - Feature distribution plots
   - Pairplots to identify relationships

3. **Feature Engineering**
   - Removed irrelevant features (like `Car_Name`)
   - One-hot encoded `Fuel Type`, `Seller Type`, `Transmission`
   - Feature scaling where necessary

4. **Model Building**
   - Tried multiple models: 
     - Linear Regression
     - Lasso Regression
     - Ridge Regression
     - Random Forest Regressor
   - Used GridSearchCV for hyperparameter tuning

5. **Model Evaluation**
   - Evaluated using:
     - R² Score
     - Mean Absolute Error (MAE)
   - Visualized predictions vs actual prices

6. **Best Performing Model**
   - **Random Forest Regressor**
   - Achieved **~96% R² Score** on test set

---

## 📈 Feature Importance

- Present Price
- Year (age)
- Kms Driven
- Fuel Type (Petrol/Diesel)
- Transmission (Manual/Automatic)

---

## 💡 Key Takeaways

- Feature engineering plays a key role in improving model performance
- Tree-based models like Random Forest often outperform linear models on structured data
- Visualizing feature importance helps in better understanding the model

---

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/car-price-prediction.git
   cd car-price-prediction
