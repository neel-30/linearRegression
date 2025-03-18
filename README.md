# linearRegression
# Insurance Charges Prediction using Linear Regression

## Project Overview
This project builds a **Linear Regression model** to predict insurance charges based on key numerical factors such as age, number of steps, salary, and past hospitalizations. The dataset contains various features like **age, sex, number of steps, smoker status, salary, past hospitalizations, expenditures, and charges**. The final model achieves an **R² score of 95%**, indicating high accuracy.

## 📂 Dataset Description
The dataset includes the following columns:
- **Age** (*int*): Age of the insured person.
- **Sex** (*object*): Gender of the insured person.
- **No. of Steps** (*int*): Number of steps taken daily.
- **Smoker** (*object*): Whether the person is a smoker (Yes/No).
- **Salary** (*int*): Annual salary of the person.
- **No. of Past Hospitalizations** (*int*): Number of previous hospitalizations.
- **Expenditure** (*float*): Medical expenditure in the past year.
- **Charges** (*float*): Insurance charges (Target variable).

## 📊 Model & Methodology
1. **Data Preprocessing**
   - Handled missing values (if any).
   - Converted categorical features into numerical form (e.g., encoding gender & smoker status).
   - Performed feature scaling where required.

2. **Feature Selection**
   - Used only **integer-type** features for training: `Age`, `No. of Steps`, `Salary`, `No. of Past Hospitalizations`.

3. **Model Training**
   - Implemented **Linear Regression** using `scikit-learn`.
   - Split the dataset into **80% training and 20% testing**.

4. **Model Performance**
   - **R² Score:** `0.95` (95% accuracy)
   - **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)** evaluated.

## 📈 Results
- The model effectively predicts **insurance charges** based on numerical inputs.
- The high R² score (95%) suggests that the model captures most of the variance in the data.
