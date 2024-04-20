Project Title: Predicting Vehicle Prices using Linear Regression

Description:
This project aims to predict vehicle prices using linear regression techniques. It utilizes a dataset containing various attributes of vehicles such as dimensions, engine specifications, and fuel types. The dataset is preprocessed, including handling missing values, checking for outliers, and converting categorical variables into numerical format. 

Key Steps:

1. **Data Preprocessing:** 
   - Checked data types, null values, and outliers.
   - Utilized data visualization techniques (box plots, histograms, count plots) to understand the distribution of numerical and categorical variables.

2. **Feature Engineering:** 
   - Performed one-hot encoding to convert categorical variables into numerical format.
   - Removed irrelevant columns like 'car_ID' and 'CarName'.

3. **Model Building:** 
   - Split the dataset into training and testing sets.
   - Applied MinMax scaling to normalize numerical features.
   - Utilized Recursive Feature Elimination (RFE) to select the top features for modeling.
   - Trained a linear regression model using the selected features.

4. **Model Evaluation:** 
   - Evaluated the model's performance using metrics such as \( R^2 \) score and mean squared error (MSE).
   - Conducted residual analysis to assess model assumptions.
   - 
**Technologies Used:**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
