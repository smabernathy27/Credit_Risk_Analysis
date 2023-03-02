# Credit_Risk_Analysis
Module 18 Challenge


## Overview
The purpose of this analysis was to use Supervised Learning to determing the credit risk associated with the current loans we had on file. 

## Results
- First we used Naive Random Oversampling method on our data set. This resulted in a Balanced Accuracy Score of 65%. The high-rsik precision score was only at 1%, the recall score was at 71% and a f1 score of 2%.

![image](https://user-images.githubusercontent.com/115592394/222336013-d7766e39-a5bb-4000-b378-a433d6639265.png)

- Next we used the SMOTE Oversampling method. This resulted in a slightly higher balanced accuracy score of 66%. The high-risk precision score was still only at 1%, the recall score was at 63% and the f1 score was at 2%.

![image](https://user-images.githubusercontent.com/115592394/222336356-a6e3e5b4-d6dd-4271-af2a-889f8253533f.png)

- Then we went on to Undersampling method. This resulted in a balanced accuracy score of 60%. The high-risk precision score was again only at 1%, the recall score was at 68% and the f1 score was at 2%.

![image](https://user-images.githubusercontent.com/115592394/222336570-ccda5225-8d3e-439b-ac95-1725320f998a.png)

- The next method we used was a combination or SMOTEENN method. This resulted in a balanced accuracny score of 65%. The high-risk precision score was at 1%, the recall score was at 72% and the f1 score was at 2%.

![image](https://user-images.githubusercontent.com/115592394/222336778-799743c6-5192-43a5-a6a7-f9886c60f864.png)

- Our second to last method used was the Balanced Random Forest Classifier. This resulted in a balanced accuracy score of 79%. The high-risk precision score saw a slight increase to 3%, the recall score was at 70% and the f1 score was at 6%.

![image](https://user-images.githubusercontent.com/115592394/222336991-c11ac309-c3ea-49e5-b3fe-11cf2fced23d.png)

- Lastly, we used the Easy Ensemble AdaBoost Classifier method. This resulted in a balanced accuracy score of 93%. The high-risk precision score saw another increase to 9%, the recall score was at 92% and the f1 score was at 16%.

![image](https://user-images.githubusercontent.com/115592394/222337203-5c6e7667-b6c4-4216-b7ab-1de867911e59.png)

## Summary
After reviewing all 6 of the above methods, it is clear that the Easy Ensemble Classifier method had the best results. The accuracy rate of 93%, 9% precision rate and 92% recall score when prediction high-risk loans was the best of the bunch. The other methods saw a siginificant drop off in results. The only other I would consider using is the Balanced Random Forest Classifier at 79% accuracy, 3% precision and 70% recall.
