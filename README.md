# Credit_Risk_Analysis

### Overview of the analysis
Machine learning can be used to monitor credit card risk. The purpose of this challenge was to use six different algorithms on a credit card credit dataset from LendingClub, in order to evaluate their performance and suggest a recommended model.

#### Results
The following are the balanced accuracy scores, precision and recall scores for all six machine learning models

- Naive Random Oversampling: The balanced accuracy score is 0.63. Precision is 0.01 for high risk and 1.0 for low risk. The recall is 0.57 for high risk and 0.68 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194459637-76fb5de0-df52-4740-8884-e8f0957aff99.png)

- SMOTE Oversampling: The balanced accuracy score is 0.63. Precision is unchanged from Naive Random Oversampling. The recall is 0.62 for high risk and 0.63 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194459857-cc0ad28e-e589-423e-bde2-961be38c406c.png)

- Undersampling with ClusterCentroids: The balanced accuracy score is 0.51. Precision is the same as the previous models. The recall is 0.59 for high risk and 0.43 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194460037-6098ae6a-fd3e-43c9-8430-2d7e88093dc7.png)

- Combination (Over and Under) Sampling with SMOTEENN: The balanced accuracy score is 0.62. Precision is again unchanged. The recall is 0.70 for high risk and 0.54 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194460347-67cc994b-46d6-43fc-972d-94871ebfaf88.png)

- Ensemble Algorithm with Balanced Random Forest Classifier: The balanced accuracy score is 0.79. Precision is 0.03 for high risk and 1.00 for low risk. Recall is 0.70 for high risk and 0.87 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194460789-520d58a2-bd57-42b0-b8a3-fdf6b04bd882.png)

- Ensemble Algorithm with Easy Ensemble AdaBoost: The balanced accuracy score is 0.93. Precision is 0.09 for high risk and 1.00 for low risk. Recall is 0.92 for high risk and 0.94 for low risk.

![image](https://user-images.githubusercontent.com/107162310/194460958-ccfb60eb-0d76-4ba0-9e27-c903e0179ab5.png)

#### Summary
Precision was similar for all models, so we turn to balanced accuracy score and recall to pick a recommendation. Overall, the ensemble algorithms performed better than the over and undersampling models. And the Easy Ensemble AdaBoost performed best in both balanced accuracy score and recall, and should therefore be the model chosen from this group.
