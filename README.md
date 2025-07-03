Breast Cancer Detection using Support Vector Machine (SVM)

This project demonstrates a full machine learning workflow using the Breast Cancer Wisconsin (Diagnostic) dataset to predict whether a tumor is malignant or benign.

Key Features

* Data cleaning and preprocessing
* Feature scaling with StandardScaler
* Binary classification using SVM with Linear and RBF kernels
* Evaluation with Accuracy, Classification Report, and Confusion Matrix
* Hyperparameter tuning using GridSearchCV for C and gamma
* Cross-validation using cross_val_score to assess model generalizability
* Visualization of decision boundaries using selected 2D features

Results

* Linear SVM Accuracy: 100%
* RBF SVM Accuracy (tuned): 100%
* Cross-Validation Accuracy (Linear): 1.0000 ± 0.0000
* Cross-Validation Accuracy (RBF): 0.9965 ± 0.0070

Technologies Used

* Python, NumPy, Pandas
* Scikit-learn
* Matplotlib & Seaborn
* Google Colab for development
