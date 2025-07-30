🚗 Car Price Prediction
This project focuses on predicting the price of used cars using machine learning techniques. It leverages historical data with multiple vehicle features to train and evaluate predictive models, aiding in understanding which factors most influence car prices.

📊 Dataset
The dataset contains various features including:

Car Name

Year of Purchase

Present Price

Kms Driven

Fuel Type

Seller Type

Transmission

Owner

The target variable is Selling Price.

🛠️ Technologies Used
Python 🐍

Pandas, NumPy

Matplotlib, Seaborn (for data visualization)

Scikit-learn (for ML modeling)

Jupyter Notebook

🔍 Workflow
Data Exploration & Preprocessing

Loaded the dataset using Pandas.

Handled categorical variables using encoding.

Converted the Year feature to the age of the car.

Visualization

Correlation heatmaps.

Pairplots to understand relationships between features.

Feature Engineering

Dropped irrelevant or highly correlated features.

Scaled numeric data when needed.

Model Training

Used multiple regression models (Linear Regression, Lasso, Ridge, Random Forest).

Used GridSearchCV for hyperparameter tuning.

Evaluation

Compared model performances using R² score and MAE.

Selected the best-performing model.

📈 Result
Best Model: Random Forest Regressor

R² Score: ~0.96 (depends on final tuning)

Feature importance was also visualized to understand which parameters influence price prediction most.

💡 Key Learnings
Handling categorical and numerical features differently.

Importance of feature selection in regression tasks.

Hyperparameter tuning using GridSearchCV.

Visualizing feature importance in tree-based models.
