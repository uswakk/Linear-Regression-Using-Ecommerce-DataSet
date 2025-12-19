

# E-commerce Customer Spend Prediction

### Linear Regression Project

## 📌 Project Overview

In this project, I developed a Multiple Linear Regression model to analyze a dataset from an E-commerce company. The goal was to predict the **Yearly Amount Spent** by customers based on their behavior, specifically focusing on whether the company should prioritize their Mobile App or Website development.

## 🛠️ Skills & Technologies Used

* **Python**: Core programming language.
* **Pandas & NumPy**: Data manipulation and cleaning.
* **Seaborn & Matplotlib**: Exploratory Data Analysis (EDA) and visualizing correlations.
* **Scikit-Learn**: Implementing the Linear Regression model, data splitting, and performance metrics.

## 🧠 Key Learnings & Concepts Mastered

Through this project, I have gained a deep understanding of the following concepts:

* **Exploratory Data Analysis (EDA):** Used `pairplots` to identify the strongest linear correlations (finding that `Length of Membership` is the strongest predictor of spend).
* **The Math of Linear Regression:** Mastered how the model calculates weights (coefficients) and intercepts to create a line of best fit.
* **Cost Functions:** Understood the role of **Mean Squared Error (MSE)** and why squaring errors is essential to penalize outliers and prevent positive/negative errors from canceling out.
* **Model Evaluation:** * **Train/Test Split:** Implemented a 75/25 split to prevent **Overfitting** and ensure the model generalizes to new customers.
* **Metrics Interpretation:** Learned to interpret **MAE (Mean Absolute Error)** in real-world units (dollars) to explain model accuracy to stakeholders.


* **Coefficient Interpretation:** Learned how to translate model parameters into business insights (e.g., "For every 1-year increase in membership, we expect an average increase of $61 in yearly spend").

## 📈 Results

The model successfully identified that the **Mobile App** and **Length of Membership** are the most significant factors driving revenue, providing a clear data-driven recommendation for the company's focus.
