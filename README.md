# Cases-of-Deaths-in-Indonesia

This repository showcases our group research project focused on analyzing and predicting causes of death in Indonesia. Leveraging historical data on total deaths across multiple years, we utilized a structured approach including Exploratory Data Analysis (EDA), data preprocessing, and machine learning model development to build an accurate predictive model.

Our model, which uses "Total Death" and "Year" as input features, demonstrated a promising accuracy of 73% with an 80-20 train-validation split, making it an efficient tool for distinguishing between "Natural Disasters" and "Non-Natural Disasters and Diseases" as primary causes of death in Indonesia.

## Highlights and Results:
Feature Selection: The model relies on "Total Death" and "Year" as input features, balancing simplicity with predictive strength.
Performance Metrics:
- True Positives (7): Correctly predicted as "Natural Disasters."
- False Negatives (16): Misclassified as "Non-Natural Disasters and Diseases" when they should be "Natural Disasters."
- False Positives (20): Misclassified as "Natural Disasters" when they should be "Non-Natural Disasters and Diseases."
- True Negatives (89): Correctly predicted as "Non-Natural Disasters and Diseases."

While the model achieved solid accuracy, further assessments for potential overfitting or underfitting are recommended to validate and refine its reliability. With these additional evaluations, we can gain deeper insights into the model's performance and uncover areas for optimization.

