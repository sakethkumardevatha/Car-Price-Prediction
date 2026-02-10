# Car-Price-Prediction
Aims to predict the selling price of used cars based on various features such as present price, kilometres driven, age of the car, fuel type, seller type, transmission, and ownership history. By applying machine learning regression models, the project helps estimate fair market value and provides insights into the factors that influence car pricing.

# Tech Stack
* Python
* Google Colab / Jupyter Notebook
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn

# Dataset
Includes details like:
* Present Price (current showroom price)
* Selling Price (target variable, in lacs)
* Year (manufacturing year, converted to Age)
* Kms Driven
* Fuel Type, Seller Type, Transmission
* Owner count

# Workflow
1. Data Cleaning – handle missing values and drop irrelevant columns
2. Feature Engineering – convert Year → Age, encode categorical variables
3. Exploratory Data Analysis – correlation heatmaps, distribution plots
4. Model Training – Linear Regression, Random Forest, XGBoost
5. Evaluation – RMSE, MAE, R² metrics
6. Visualization – feature importance and prediction vs. actual plots

# Results
* Present Price and Age are the most influential features
* Ensemble models (Random Forest/XGBoost) achieved strong predictive performance
* Demonstrated how ML can assist in pricing strategy for used cars

# Future Work
* Deploy the model using Streamlit or Flask for interactive predictions
* Integrate with a database/API for real-time car listings
* Extend methodology to other domains (Airbnb, hotel, or house price prediction)

# Contributions
Feel free to fork this repo, open issues, or submit pull requests. Suggestions for improving model accuracy or deployment are welcome!
