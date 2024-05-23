### Logistic Regression from Scratch
This project implements logistic regression from scratch in Python to better understand the underlying math. The implementation is based on the famous Titanic dataset. The project includes data preprocessing steps such as feature scaling, generating polynomial features, and one-hot encoding. The model is evaluated using accuracy, precision, and recall.  

### Libraries used:
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (for train-test-split)
- Imbalanced-Learn (for RandomOverSampler)

### Implementation Details:
1. Data Loading and Exploration: The Titanic dataset is loaded and explored using Pandas. Summary statistics, data types, and missing values are investigated.
2. Data Preprocessing: Features are scaled using sklearn's StandardScaler. Polynomial features are generated using NumPy. One-hot encoding is applied to categorical features.
3. Train-Test-Validation Split: The preprocessed data is split into training, validation, and test sets using sklearn's train_test_split function.
4. Oversampling: RandomOverSampler from the imbalanced-learn library is used to address class imbalance in the training data.
5. Logistic Regression Implementation: The sigmoid function, cost function, and gradient descent algorithm are implemented from scratch.
6. Model Training and Evaluation: The logistic regression model is trained using the training and validation sets. Accuracy, precision, and recall are calculated on the test set.

### Final Results:  
After training the logistic regression model and fine-tuning hyperparameters, the following results were achieved on the test set:  
- Accuracy: 74.81%  
- Precision: 68.29%  
- Recall: 58.33%  

### Conclusion:  
This project demonstrates the implementation of logistic regression from scratch and showcases its application on the Titanic dataset. Various data preprocessing techniques and oversampling were used to improve model performance. The final model achieved reasonable accuracy, precision, and recall scores.