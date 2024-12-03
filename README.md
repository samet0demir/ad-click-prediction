# Ad Click Prediction Project

## Objective
The primary objective of this project is to develop a machine learning model that accurately predicts whether a user will click on an advertisement (`is_click`). This involves analyzing user interactions with ads, demographic details, and campaign data to understand factors influencing ad clicks.

---

## Dataset
The dataset contains the following key features:

- **User Information**: Gender, age level, user group, and city development index.
- **Product Details**: Product type and category.
- **Ad Campaign Information**: Campaign IDs and webpage IDs.

---

## Key Steps

1. **Data Exploration and Cleaning**:
   - Analyzed the dataset for missing values and inconsistencies.
   - Handled missing data and performed feature encoding.

2. **Feature Engineering**:
   - Removed irrelevant and highly correlated columns to improve model performance.
   - Scaled features for uniformity.

3. **Model Training and Evaluation**:
   - Tested Logistic Regression for its simplicity and interpretability.
   - Transitioned to Random Forest to address the limitations of Logistic Regression.

4. **Evaluation**:
   - Used metrics like accuracy, precision, recall, and F1-score to evaluate performance.
   - Generated insights about feature importance and ad click behavior.

---

## Results

- **Logistic Regression Accuracy**: 56.57%
- **Random Forest Accuracy**: 93.22%

Detailed classification reports for both models can be found in the project notebook.

---

## Project Structure

- **Notebook**: Contains the Jupyter Notebook `model.ipynb`, showcasing data exploration, preprocessing, and model training.
- **Dataset**: Includes `Ad_click_prediction_train.csv` and `Ad_click_prediction_test.csv`.
- **Predictions**: Final predictions stored in `Test_Set_with_Predictions.csv`.
