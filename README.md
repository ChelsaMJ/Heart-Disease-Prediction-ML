# Heart Disease Prediction using Support Vector Machine (SVM)

This project predicts the presence of heart disease using clinical attributes and the Support Vector Machine (SVM) machine learning algorithm. It includes data preprocessing, model training, evaluation, and a user input–based prediction system.

---

## Project Overview

Heart disease is one of the leading causes of mortality worldwide. Early prediction can support preventive healthcare and timely treatment.  
This project applies SVM to classify patients into:

- 0 → No Heart Disease  
- 1 → Heart Disease Present  

The workflow includes:
- Exploratory Data Analysis (EDA)  
- Data cleaning and preprocessing  
- Feature selection  
- Model training using SVM  
- Model evaluation  
- Real-time predictions based on user input  

---

## Dataset Description

The dataset contains 1025 rows and 14 attributes, including patient demographics and clinical measurements.

| Feature | Description |
|--------|-------------|
| age | Age in years |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting ECG result |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression |
| slope | Slope of ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thallium stress test result |
| target | 0 = no disease, 1 = disease |

Dataset Source: Cleveland Heart Disease Dataset

---

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## Model Used

A Support Vector Machine (SVM) classifier is used for prediction.

Model implemented:
SVC(kernel="linear")

Further optimization can be performed using:
SVC(kernel="rbf", C=10, gamma=0.1)

---

## How to Run the Project

1. Clone the repository
```
git clone https://github.com/your-username/heart-disease-SVM.git
```

2. Navigate to the project directory
```
cd heart-disease-SVM
```

3. Install dependencies
```
pip install -r requirements.txt
```

4. Open the notebook
```
jupyter notebook
```

5. Run all cells in the notebook  

---

## Features of the Project

- Complete EDA and visualization  
- Clean and preprocessed dataset  
- SVM model training and testing  
- User input–based prediction function  
- Explanation of risk factors  
- Interpretable results  

---

## Results

The linear SVM model achieved approximately:

- Accuracy: 82%  
- Good performance on both classes  
- Balanced precision, recall, and F1-score  

Accuracy can be improved by:
- Using RBF kernel  
- Hyperparameter tuning  
- Scaling the features  

---

## Conclusion

This project demonstrates that SVM is an effective algorithm for heart disease prediction using structured clinical data.  
Although the linear kernel provides solid baseline results, non-linear kernels such as RBF perform better due to the complex nature of the dataset.  
The project highlights the importance of feature interpretation, dataset quality, and kernel optimization for improving real-world medical predictions.
