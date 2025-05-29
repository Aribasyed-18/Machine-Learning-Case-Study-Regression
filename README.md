## Machine-Learning-Case-Study-Regression


A machine learning project that predicts the chances of admission for students applying to graduate programs, with an optional decision-support system for scholarship recommendations.

## Project Goals

- Predict admission probability using machine learning models.
- Rank features that impact admission decisions the most.
- Simulate decision-making for awarding scholarships.

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (with tuning)

## Key Results

# Model & R² Score (Test)

Linear Regression   = 0.76
Decision Tree       = 0.69
Random Forest       = 0.83
Top 5 Feature Model = 0.81

# Top Features: CGPA, GRE Score, TOEFL Score, Research, LOR Strength

## Final Test

Predicted chance of admission
Scholarship recommendation:
- Recommend if >85%
- Consider if >70%
- Do not recommend otherwise
