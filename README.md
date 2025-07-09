🌲 Random Forest Regression – Salary Prediction

This project demonstrates the use of **Random Forest Regression** to predict salaries based on position level. It uses a non-linear ensemble model to fit and predict more accurately than simple linear models.

---

## 📁 Dataset Overview

- File: `Position_salaries.xlsx.csv`
- Columns:
  - `Position`
  - `Level` (Feature)
  - `Salary` (Target)

---

## 📌 Project Workflow

1. **Import Libraries**
   - Imported `pandas`, `numpy`, `matplotlib`, and `sklearn`.

2. **Load Dataset**
   - Read the data file and explored columns.

3. **Data Preparation**
   - Split into:
     - X → `Level` (independent variable)
     - y → `Salary` (dependent variable)

4. **Train Model**
   - Used `RandomForestRegressor` from `sklearn.ensemble`.
   - Trained the model on the full dataset.

5. **Prediction**
   - Predicted salary for a given input (e.g., level 6.5).

6. **Visualization**
   - Visualized the random forest predictions with higher resolution plots.

7. **User Input**
   - Added an input field to predict salary for user-entered level.

---

## 🛠️ Technologies Used

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `sklearn.ensemble`
