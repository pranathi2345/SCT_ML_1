# SCT_ML_1
Implement a linear regression model to predict the price of houses based on their square footage and the number of bedrooms and bathrooms
"""
Objective:
- Predict house prices based on square footage, number of bedrooms, and number of bathrooms.
Tools & Technologies Used:
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Environment: Jupyter Notebook  
- Model: Linear Regression (sklearn.linear_model)
Step-by-Step Implementation:
1. Data Collection:
   - Loaded housing dataset (CSV format) containing features:
     - SquareFootage
     - Bedrooms
     - Bathrooms
     - Price (target)
2. Data Preprocessing:
   - Handled missing values
   - Verified and corrected data types
   - Removed outliers where necessary
3. Exploratory Data Analysis (EDA):
   - Used scatter plots, box plots, and correlation matrix
   - Identified relationships between features and target
   - Found that SquareFootage is highly correlated with Price
4. Feature Selection & Splitting:
   - Selected features: SquareFootage, Bedrooms, Bathrooms
   - Target: Price
   - Split data into training and test sets (80/20 split)
5. Model Training:
   - Imported and trained LinearRegression model from sklearn:
     from sklearn.linear_model import LinearRegression
     model = LinearRegression()
     model.fit(X_train, y_train)
6. Model Evaluation:
   - Evaluated using:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
   - Visualized predictions vs actual prices
7. Prediction:
   - Predicted house prices on test data
   - Analyzed feature coefficients to interpret model
8. Conclusion:
   - Square footage has the strongest impact on house price
   - Bedrooms and bathrooms contribute moderately
   - Linear regression provided a good baseline model
   - Future improvement possible with more features or complex models
Skills Demonstrated:
- Data analysis and preprocessing
- Linear regression modeling using sklearn
- Visualization with Matplotlib and Seaborn
- Model evaluation and interpretation
"""
