# Credit Risk Analysis

## Purpose
The purpose of this week's challenge was to create multiple machine learning models using the different concepts we learned in the module and then validate them to ensure they are reliable at detecting potential credit risk.

## Results
Through the various models I created there were varying results including different balanced accuracy score and the precision and recall scores. The results are below for each machine learning model:
- Naive Random Oversampling
![naive_random_os](https://user-images.githubusercontent.com/88118759/147439275-833cd4e6-65c0-4d51-95c6-d3b594deb496.PNG)

- SMOTE Oversampling
![smote_os](https://user-images.githubusercontent.com/88118759/147439285-4b1b0e20-e3ff-49e6-86d5-e864f5ddbdb9.PNG)

- Undersampling
![undersampling](https://user-images.githubusercontent.com/88118759/147439297-55d564f2-d646-4dde-9fca-1249fbf91ba4.PNG)

- Combination Sampling (SMOTEENN)
![combination_sampling](https://user-images.githubusercontent.com/88118759/147439305-3f62aec2-8849-4ee7-8232-cdf5be451e16.PNG)

- Balanced Random Forest Classifier
![brfc](https://user-images.githubusercontent.com/88118759/147439312-8824547f-e9e8-47eb-aca2-da48ef4ab10b.PNG)

- Easy Ensemble Classifier
![eec](https://user-images.githubusercontent.com/88118759/147439318-4a966f49-b695-4a39-958a-395e58d32cc1.PNG)

## Summary
In conclusion, my recommendation would be to use either the Balanced Random Forest Classifier or the Easy Ensemble Classifier method. With an accuracy Score of 91% and a "High Risk" recall of 67%, none of the other models were able to predict the number of High Risk applicants with that accuracy.
