# Churn-Prediction-using-ANN

This project aims at predicting whether a customer will churn or not. 

<img src="https://github.com/user-attachments/assets/49854284-d265-41fd-9b39-42ed154c7303" width="300" height="auto" />

# About Dataset

The dataset consists of 14 attributes and 10000 rows.(RowNumber, CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited) where Exited is the target column.

# ANN Implementation

-> Data preprocessing like standardization and one hot encoding is done.

-> Artificial neural network is used with two hidden layers and one output layer. Adam is used as the optimiser with learning rate=0.01 and sparse cross entropy to calculate the loss function. RELU and softmax are used as the activation function in the hidden and output layers. Validation accuracy of 0.860 was achieved.

# Technologies and libraries used

=> Python

<img src="https://github.com/user-attachments/assets/04136374-157d-4164-ad67-3319486724ed" width="300" height="auto" />

=> Streamlit

<img src="https://github.com/user-attachments/assets/ea0ed8e6-c6e2-46e8-ae58-741ea74ed18e" width="300" height="auto" />

=> TensorFlow

<img src="https://github.com/user-attachments/assets/366f0342-5f30-4c95-b3df-571fe56e0b3e" width="300" height="auto" />

=> Keras

<img src="https://github.com/user-attachments/assets/08f76787-ae59-4869-935d-1a490a9090be" width="300" height="auto" />

=> Sklearn

<img src="https://github.com/user-attachments/assets/2df705d8-a967-48e3-b03b-69311e8fb6d0" width="300" height="auto" />

=> Output on Streamlit

![image](https://github.com/user-attachments/assets/f6d5571c-1764-4f7b-8e0a-6f0985ced0f4)
