Diabetes Prediction using Logistic Regression
📌 Project Overview
This project demonstrates the use of Logistic Regression to predict the likelihood of diabetes based on patient health data. The dataset contains medical predictor variables such as glucose level, BMI, age, and more. Logistic Regression is chosen for its effectiveness in binary classification problems like predicting diabetes (Yes/No).

📊 Dataset
The dataset used is the Pima Indians Diabetes Dataset (commonly available via Kaggle or UCI Machine Learning Repository).
- Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- Target: Outcome (0 = No Diabetes, 1 = Diabetes)
- 
🚀 Model Training
The model is trained using Logistic Regression from scikit-learn.
Steps include:
- Data preprocessing (handling missing values, scaling features).
- Splitting dataset into training and testing sets.
- Training logistic regression model.
- Evaluating performance using accuracy, precision, recall, and F1-score.


📈 Results
- Accuracy:
- Precision: 
- Recall: 
- F1-score:

          precision    recall  f1-score   support

           0       0.82      0.93      0.87       102
           1       0.82      0.60      0.69        52

    accuracy                           0.82       154
   macro avg       0.82      0.76      0.78       154
weighted avg       0.82      0.82      0.81       154

  
Confusion matrix and ROC curve are included in the notebooks/ folder for visualization.
🛠️ Technologies Used
- Python 3.x
- NumPy, Pandas
- Scikit-learn

Contributions are welcome! Please fork the repository and submit a pull request.
📜 License
This project is licensed under the MIT License.

👉 Sanket, since you’ve trained the model yourself, you can fill in the results section with your actual accuracy/metrics and add any custom scripts you wrote.
Would you like me to also create a sample requirements.txt file for you so your GitHub repo is fully ready to run?
