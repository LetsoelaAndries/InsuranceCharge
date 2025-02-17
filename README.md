
# Insurance Charge Prediction

## Project Overview
This project aims to predict insurance charges based on various factors such as age, BMI, smoking status, and region. The goal is to develop a machine learning model that provides accurate cost estimations, helping insurance companies and customers understand key cost drivers.

## Dataset
  - **Age**: Age of the insured person
  - **BMI**: Body Mass Index
  - **Children**: Number of dependent children covered by insurance
  - **Smoker**: Whether the person is a smoker (Yes/No)
  - **Region**: Geographical region of the insured person
  - **Charges**: Insurance cost (Target variable)

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Modeling**: Linear Regression, Decision Tree, Random forest

## Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Split data into training and testing sets

## Model Training & Evaluation
- **Models Used**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor

- **Performance Metrics**:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared (R²)

## Key Insights
- Smoking status significantly impacts insurance charges.
- BMI and age also contribute to higher insurance costs.
- Logistic regression performed best in terms of prediction accuracy.


## Conclusion
This project successfully predicts insurance charges using machine learning techniques. The insights derived can be used by insurance companies to optimize pricing strategies and by individuals to understand cost factors.

## Future Improvements
- Experiment with deep learning models.
- Use more diverse datasets for better generalization.
- Optimize hyperparameters for improved model performance.


