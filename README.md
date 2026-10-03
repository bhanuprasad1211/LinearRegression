# E-commerce Customer Spending Prediction (Linear Regression)

This is a machine learning project that uses Linear Regression to predict the yearly amount spent by customers on an e-commerce platform. The project is based on the [Linear Regression E-commerce Dataset from Kaggle](link-to-dataset).

## Objective
The goal of this project is to help the company decide whether to focus their efforts on improving their mobile app experience or their website, based on customer spending patterns.

## Dataset
The dataset contains customer information, including:
* **Avg. Session Length:** Average session of in-store style advice sessions.
* **Time on App:** Average time spent on App in minutes.
* **Time on Website:** Average time spent on Website in minutes.
* **Length of Membership:** How many years the customer has been a member.
* **Yearly Amount Spent:** The target variable we are trying to predict.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Project Steps
1. **Exploratory Data Analysis (EDA):** Visualizing relationships between features (e.g., Time on App vs. Yearly Amount Spent).
2. **Data Preprocessing:** Splitting the data into training and testing sets.
3. **Model Training:** Training a multiple linear regression model using Scikit-Learn.
4. **Evaluation:** Checking the model's performance using metrics like MAE, MSE, and RMSE.

## Results
* **Mean Absolute Error (MAE):** [Insert your MAE here]
* **Root Mean Squared Error (RMSE):** [Insert your RMSE here]
* **R-squared Score:** [Insert your R2 score here]

**Key Insight:** [Example: The model coefficients show that 'Length of Membership' has the strongest impact on yearly spending, followed by 'Time on App'.]
