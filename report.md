# Module 12 Report Template

## Overview of the Analysis

The analysis aimed to predict loan risk using machine learning models on financial data from a peer-to-peer lending company. The data focused on various financial attributes to predict loan statuses labeled as 'healthy' (0) or 'high-risk' (1). The initial exploration indicated an imbalanced dataset, with significantly more 'healthy' loans compared to 'high-risk' loans.

The stages involved in the machine learning process included data preprocessing, splitting the data into training and testing sets, and implementing machine learning models such as Logistic Regression. Resampling techniques, specifically RandomOverSampler, were used to address the class imbalance.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The model's report reflects exceptional accuracy in predicting 'healthy' (0) loans, with all metrics close to 1.0. For 'high-risk' (1) loans, the model exhibits strong precision at 0.86, indicating mostly accurate predictions within the 'high-risk' category. 
  * The recall of 0.91 suggests the model's capability to identify most 'high-risk' loans among the actual 'high-risk' instances. 
  * Overall, the model demonstrates robust performance in distinguishing between 'healthy' and 'high-risk' loans, displaying high accuracy and balanced classification.

* Machine Learning Model 2:
  * The logistic regression model, trained with oversampled data, effectively predicts both 'healthy' (0) and 'high-risk' (1) loan labels. 
  * It displays near-perfect precision and high recall for 'healthy' loans, signifying accurate identification. 
  * For 'high-risk' loans, it exhibits solid precision and exceptional recall, demonstrating precise identification within the predicted 'high-risk' category and a strong ability to recognize most actual 'high-risk' instances. 
  * Overall, the model, trained with oversampled data, excels in distinguishing between loan categories, ensuring accurate predictions for both 'healthy' and 'high-risk' loans.

## Summary

The model trained with resampled data demonstrated improved performance in handling the class imbalance, leading to more balanced precision and recall scores for both 'healthy' and 'high-risk' loan predictions. While both models show promising results, the resampled model appears more robust in correctly predicting 'high-risk' loans, minimizing the false negative rate, crucial in this financial context. The choice of the model might depend on the business's priority, whether it's more critical to accurately predict 'healthy' loans or prevent misclassification of 'high-risk' loans. Ultimately, the model trained with resampled data might be more suitable for better generalization and risk mitigation in the lending process.