# Travel Insurance Prediction

## Project Overview
This project aims to predict whether a customer will purchase travel insurance based on their demographic and trip-related information. The dataset is analyzed using various machine learning models, including Logistic Regression, Decision Trees, Random Forests, and XGBoost.

## Dataset
The dataset is assumed to be `TravelInsurancePrediction.csv`, containing customer-related features such as:
- **Age**
- **Employment Type**
- **GraduateOrNot**
- **AnnualIncome**
- **FamilyMembers**
- **ChronicDiseases**
- **FrequentFlyer**
- **EverTravelledAbroad**
- **TravelInsurance** (Target variable)

## Installation & Requirements
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## Steps in the Notebook
1. **Data Loading & Exploration**
   - Checking for missing values and handling them.
   - Summary statistics & initial visualization.

2. **Feature Engineering & Preprocessing**
   - Encoding categorical variables.
   - Feature scaling (if needed).

3. **Model Training & Evaluation**
   - Training Logistic Regression, Decision Tree, Random Forest, and XGBoost.
   - Hyperparameter tuning using GridSearchCV.
   - Evaluating models based on accuracy, ROC-AUC, and classification reports.

4. **Ensemble Learning**
   - Combining Random Forest & XGBoost using VotingClassifier.

## How to Run
1. Clone the repository.
2. Ensure `TravelInsurancePrediction.csv` is in the project folder.
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook TravelInsurancePrediction.ipynb
   ```

## Results & Findings
- Random Forest and XGBoost showed the best performance.
- Feature importance analysis highlighted key factors influencing insurance purchase.
- An ensemble model improved accuracy further.

## Future Improvements
- Try additional feature engineering techniques.
- Include SHAP or LIME for interpretability.
- Deploy the best model using Flask or FastAPI.
