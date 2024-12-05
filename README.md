# Loan Default Prediction

This project focuses on predicting the likelihood of loan defaults using machine learning techniques. Using a dataset of over 4,000 personal loan customers, the analysis explores borrower characteristics and loan features that impact default risk. The findings aim to assist a national bank in mitigating financial losses and enhancing lending strategies.

## Overview

- Objective: Analyze factors contributing to loan default and develop predictive models for better risk management.
- Machine Learning Models Evaluated:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
- Performance Metrics: Accuracy, ROC AUC

## Key Insights

1. Loan Purpose: Credit card and medical loans have the highest default rates.
2. Loan Amount: Higher loan amounts are linked to increased default risk.
3. Interest Rate: Defaulting customers typically face higher interest rates.
4. Annual Income: Lower-income borrowers default more frequently.
5. Homeownership: Renters and mortgaged customers show higher default rates compared to homeowners.

## File Structure

- `Loan_Default_Prediction.html`: The complete analysis, including exploratory data analysis, model building, and insights.

## Getting Started

### Prerequisites

- Software: A modern web browser to view the `.html` file.
- File: Ensure the `Loan_Default_Prediction.html` file is downloaded and accessible.

### Usage

1. Open the HTML file in your web browser to view the analysis and results.
2. Review the insights, visualizations, and model comparisons presented in the document.

## Results

| Model            | Accuracy | ROC AUC |
|-------------------|----------|---------|
| KNN              | 80.6%    | 0.887   |
| Decision Tree    | 88.7%    | 0.958   |
| Random Forest    | 89.5%    | 0.968   |

## Recommendations

1. Focus risk management efforts on high-risk loan purposes like credit card and medical loans.
2. Adjust lending criteria based on borrower characteristics, such as income and homeownership status.
3. Use the Random Forest model for accurate and reliable loan default predictions.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

[Rohan Tucker](mailto:Rohanctucker@yahoo.com)
