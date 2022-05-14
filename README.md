# Predicting Default Borrowers

Using the [LendingClub.com dataset](https://www.kaggle.com/itssuru/loan-data), we compared and critically evaluated the use of Multilayer Perceptron (MLP) and Support Vector Machine (SVM) for predicting default borrowers. The PyTorch and Scikit-learn packages in Python were used to develop the models.

Both MLP and SVM models exhibited good capability in detecting default borrrowers. Based on the AUC score, the SVM model was slightly more robust than MLP. The higher sensitivity of SVM (34%) compared to MLP (25%) also suggested the SVM model was more suitable for this task, as a high cost is associated with incorrect classification of default borrowers.
