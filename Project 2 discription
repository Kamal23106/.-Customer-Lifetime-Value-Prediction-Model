🧾 Project Title:
Customer Lifetime Value (LTV) Prediction Model

🎯 Objective:
The goal of this project is to predict the Lifetime Value (LTV) of customers based on their purchase behavior, such as how often they purchase, how recently, and how much they spend. This helps businesses in:
📢 Targeted marketing
🎯 Customer segmentation
📈 Revenue forecasting

🛠️ Tools & Technologies Used:
Python for data processing and modeling

Libraries:
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Visualization
XGBoost – Machine learning model
Sklearn – Metrics and model tools
Excel – To explore or submit CSV outputs

🧠 Approach & Workflow:
1. 📁 Data Loading & Cleaning:
Dataset: Online customer transactions data
Removed missing CustomerIDs
Converted date columns to datetime format
Created a new column: TotalPrice = Quantity × UnitPrice

2. ⚙️ Feature Engineering:
Grouped data by CustomerID to compute:
Recency: Days since last purchase
Frequency: Number of unique invoices
Monetary: Total amount spent
AOV (Average Order Value): Monetary ÷ Frequency

3. 🎯 Target Variable:
The target for regression is Monetary value, treated as a proxy for Customer LTV.

4. 🤖 Model Training:
Used XGBoost Regressor with:
n_estimators=100, max_depth=4, learning_rate=0.1
Split data into training (80%) and testing (20%)

5. 📊 Evaluation Metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Used these to measure model accuracy.

6. 🔍 Visualization:
Feature importance from the XGBoost model
Histogram of customer spending
Scatter plot: Actual vs Predicted LTV

7. 🧩 Customer Segmentation (Optional):
Used qcut to segment predicted LTV into:
Low, Medium, High value customers

✅ Final Deliverables:
Deliverable	Description
📓 Python Notebook	Full end-to-end implementation
🤖 Trained Model + Visualizations	XGBoost model with performance and insights
📂 CSV File	final_ltv_predictions.csv with predicted LTV and segment labels

📁 Output Sample:
The final CSV contains these columns:
CustomerID
Recency, Frequency, Monetary, AOV
Predicted_LTV
Segment (Low / Medium / High)

📌 Applications of This Project:
🔍 Identify most valuable customers
📣 Run targeted ad campaigns
💰 Plan customer retention strategies
📈 Forecast sales & revenue growth
