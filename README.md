# Ford-Car-Price-Prediction

🚗 Ford Car Price Prediction using Machine Learning
📌 Project Overview
This project predicts the selling price of Ford cars using Machine Learning techniques. The dataset contains information about Ford vehicles such as model, year, transmission type, mileage, fuel type, engine size, MPG, and tax.

The goal is to build a regression model capable of accurately estimating vehicle prices based on these features.

🎯 Objectives
Perform data cleaning and preprocessing
Handle categorical and numerical features
Apply feature encoding and scaling
Train a Linear Regression model
Evaluate model performance using R² Score and Adjusted R² Score
Generate price predictions for unseen vehicles
📊 Dataset Features
Feature	Description
model	Ford car model
year	Manufacturing year
transmission	Transmission type
mileage	Distance driven
fuelType	Fuel type
tax	Road tax
mpg	Miles per gallon
engineSize	Engine displacement
price	Target variable
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
🔄 Project Workflow
1. Data Collection
Imported Ford car dataset.
2. Data Cleaning
Checked missing values.
Verified data types.
Removed inconsistencies.
3. Exploratory Data Analysis (EDA)
Distribution analysis
Correlation analysis
Outlier detection
Feature relationship visualization
4. Feature Engineering
One-Hot Encoding for categorical features.
Feature Scaling using StandardScaler.
5. Model Building
Train-Test Split
Linear Regression Model
Model: Linear Regression

R² Score: 0.89 Adjusted R² Score: 0.88 MAE: 1200 RMSE: 1800

Metric	Value
R² Score	0.89
Adjusted R²	0.88
MAE	1200
RMSE	1800
📈 Results
The Linear Regression model was trained and evaluated using unseen test data.

Evaluation Metrics:

R² Score
Adjusted R² Score
The model demonstrates the relationship between vehicle specifications and market price.

🚀 Installation
Clone the repository:

git clone https://github.com/yourusername/ford-car-price-prediction.git
Move into the project folder:

cd ford-car-price-prediction
Install dependencies:

pip install -r requirements.txt
Run Jupyter Notebook:

jupyter notebook
📷 Visualizations
Correlation Heatmap
Price Distribution
Feature Importance Analysis
Prediction Performance Graphs
Future Improvements
Random Forest Regressor
XGBoost Regressor
Hyperparameter Tuning
Model Deployment using Streamlit
Docker Deployment
👩‍💻 Author
Shiva Sengar

Bsc cs Student

Interested in:

Machine Learning
Data Science
Data Engineering
Web Development
Cyber Security
⭐ If you found this project useful, consider giving it a star.
