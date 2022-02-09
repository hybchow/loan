# A comparative study in full loan repayment through Multilayer Perceptron and Support Vector Machine

In this work, we analysed the LendingClub.com data, and compared and critically evaluated the use of Multilayer Perceptron (MLP) and Support Vector Machine (SVM) to aid the prediction of full loan repayment using [!Kaggle](https://www.kaggle.com/itssuru/loan-data). PyTorch and Scikit-learn packages were used to build the models.

Both MLP and SVM models exhibited good capability (higher than stratified random guessing) in differentiating borrrowers who would pay back the loan in full or not. The optimal SVM model was slightly better than the MLP model based on the AUC score. The higher sensitivity of SVM (34%) compared to MLP (25%) also suggested the SVM model was more suitable for this task, where a high cost was associated with incorrect classification of borrowers who did not pay back the loan in full. 
