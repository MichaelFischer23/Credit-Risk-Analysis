#### Credit-Risk-Analysis
###### Overview of the Analysis
The purpose of the analysis was to create a machine learning model that can be used to predict credit risk.
###### Results
* Naive Random Oversampling: Looking at the results you can see that this algorithm was 63% which is not ideal. Then when looking at the confusion matrix it operated at a 68% accuracy. Overall this did not preform at a rate that would suggest it should be used.
![Naive Random Oversampling accuracy](https://user-images.githubusercontent.com/105613428/193447703-53c0c718-eca7-43bc-a63d-29d98036e268.PNG)
* SMOTE Oversampling: The accuracy score of this model was again around 63% and the confusion matrix has it operating at 64%. Not very comforting scores.
![SMOTE Oversampling](https://user-images.githubusercontent.com/105613428/193448024-d09a9178-6e83-4ab4-8616-2d184831f27f.PNG)
* Undersampling: The next algorithm to look at has a accuracy score of 63%. The confusion matrix gives it a score of 45%. 
![undersampling](https://user-images.githubusercontent.com/105613428/193448193-c8958746-ce88-4b15-959e-18cde21e7a59.PNG)
* Combination (Over and Under) Sampling: This algorithm has an accuracy score of 53% and a confusion matrix score of 58%. Not very effective.
![Combination](https://user-images.githubusercontent.com/105613428/193448402-e10d67e3-df63-4ed3-9a0f-9a9cae33885d.PNG)
* Balanced Random Forest Classifier: The accuracy score for this is 79% and the confusion matrix brought back a score of 91%. These are both very promising figures
![Random Forest](https://user-images.githubusercontent.com/105613428/193448704-c20b0807-885c-4cf0-bd28-4da7f87cd86b.PNG)
* Easy Ensemble AdaBoost Classifier: The final model that was create gave an accuracy score of 93% and the confusion matrix gave a score of 94%.
![Easy Ensemble AdaBoost](https://user-images.githubusercontent.com/105613428/193448791-324e0fa3-394d-49e1-9cdf-9cb6810b1140.PNG)

###### Summary
After looking through the results of each model that was created I would recommend using the easy ensemble classifier. It came back with the best scores in all categories by a significant margin. It preformed the best when it came to predicting credit risk.
