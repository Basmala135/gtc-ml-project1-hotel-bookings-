🏨 Hotel Booking Demand Analysis
📌 Project Overview
This project analyzes the Hotel Booking Demand dataset to explore booking patterns, detect cancellations, and prepare data for machine learning models that predict cancellations.

The main steps include:
Exploratory Data Analysis (EDA)
Data Cleaning & Handling Missing Values
Outlier Treatment
Feature Engineering (new variables like total_guests, total_nights, is_family)
Encoding Categorical Variables
Removing Data Leakage Columns
Splitting Data into Training & Testing Sets

📊 Dataset
Source: Hotel Booking Demand Dataset

⚙️ Installation
Make sure you have Python installed. Install dependencies with:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

🚀 How to Run
Clone this repository:
git clone <repo_url>
cd hotel-bookings
Open the notebook in Jupyter or VS Code:
jupyter notebook hotel_booking_analysis.ipynb
Run cells step by step to reproduce the analysis.

🔍 Key Insights (from EDA)
High proportion of cancellations (~37%).
Majority of bookings are from Portugal (PRT), UK (GBR), and USA.
ADR (Average Daily Rate) has extreme outliers (>1000), capped for modeling.
Missing values mainly in company, agent, and country.
Some features like reservation_status and reservation_status_date leak future info → removed.

📈 Next Steps
Build predictive models (Logistic Regression, Random Forest, XGBoost).
Evaluate performance with accuracy, precision, recall, F1-score.
Deploy as a simple app/dashboard.
