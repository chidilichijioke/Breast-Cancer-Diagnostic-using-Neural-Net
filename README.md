# Breast-Cancer-Diagnostic-using-Neural-Net
## Executive Summary
This project report outlines the development of breast cancer diagnostic systems using neural networks. Breast cancer is a major health concern worldwide, and early diagnosis plays a crucial role improving patient outcomes.Neural networks, a subset of machine learning techniques, have shown promise in enhancing breast cancer diagnosis accuracy. This project aimed to create a neural network-based diagnostic tool to assist medical professionals in identifying breast cancer.
Introduction
Breast cancer originates in breast tissue. It occurs when breast cells mutate and grow out of control, creating a mass of tissue (tumor). Like other cancers, breast cancer can invade and grow into the tissue surrounding your breast. It can also travel to other parts of your body and form new tumors. When this happens, it’s called metastasis.This project focuses on using neural networks for breast cancer diagnosis using features from a digitized image of a fine needle aspirate (FNA) of a breast mass. The neural network will classify lesions into two categories; malignant and benign. The dataset used for training and testing consist of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].
  
## Methodology
### Data Collection
A publicly available breast cancer dataset was utilized, comprising features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, with corresponding labels indicating malignant or benign status. The dataset was divided into training, validation, and test sets.
### Data Preprocessing
Data preprocessing involved cleaning, standardization, and feature selection technique to improve model generalization. Feature selection included random forest classifier, cross-validation, and recursive feature elimination to create a dataset.
### Neural Network Architecture
A Multilayer perceptron architecture was employed for classification using tensorflow. The Multilayer perceptron consisted of several dense layers, hidden layers, and fully connected layers. Dropout and batch normalization were used to prevent overfitting.
### Model Training
The neural network was trained using the training dataset. The model's performance was monitored on the validation dataset, and hyperparameter tuning was performed to optimize accuracy and reduce overfitting.
### Model Evaluation
The final model was evaluated on the test dataset to assess its diagnostic accuracy metrics, using classification report of the model and Confusion matrix of the model.

## Results
The neural network achieved a diagnostic accuracy of 95% on the test dataset. Indicating the model's ability to correctly classify both malignant and benign cases. The classification report and confusion matrix demonstrated the model's performance in differentiating between the two classes. The model predicted 71 cases as Benign(0) accurately and 2 cases inaccurately as Malignant(1), predicted 23 cases as Malignant(1) accurately and 3 cases inaccurately as Benign(0).

## Discussion
The project successfully developed a neural network-based breast cancer diagnostic tool. The results indicate that the model can classify a fine needle aspirate (FNA) of a breast mass, with high accuracy, potentially assisting medical professionals in making more informed decisions. The use of feature selection and dropout layers helped mitigate overfitting.
## Conclusion
In conclusion, this project demonstrates the potential of neural networks in enhancing breast cancer diagnosis. The developed model exhibits promising accuracy and can serve as a valuable adjunct to traditional diagnostic methods. Further research and clinical validation are necessary before integration into medical practice.
