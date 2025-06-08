📦 Maternal Health Risk Prediction using Machine Learning
A machine learning-based system to predict maternal health risks using real-world clinical data. This project leverages algorithms like Support Vector Machines (SVM) and K-Nearest Neighbors (KNN) to classify risk levels for pregnant women based on physiological parameters such as blood pressure, blood sugar, and heart rate.

🔍 Problem Statement
Maternal health is a critical area of healthcare with global implications. Predicting risk levels early can help save lives by enabling timely medical intervention. This project uses machine learning to classify pregnancy risks into Low, Mid, and High categories, based on features collected from hospitals and health centers.

🧠 Machine Learning Models Used
Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

(Explored: Logistic Regression, Perceptron — excluded due to poor multi-class performance)

🧾 Features in the Dataset
Feature	Description
Age	Age of the pregnant woman
Systolic BP	Upper blood pressure in mmHg
Diastolic BP	Lower blood pressure in mmHg
Blood Sugar (BS)	Glucose concentration in mmol/L
Body Temperature	Body temp in Celsius
Heart Rate	Heart beats per minute
Risk Level	Target variable (Low, Mid, High risk classification)

🛠️ Methods & Techniques
Data Preprocessing: Cleaning, normalization, train-test split

Model Evaluation: Accuracy, Precision, Recall, F1-Score

Bootstrap Resampling: For model confidence estimation

PCA: Dimensionality reduction (tested but not deployed)

Correlation Matrix & Feature Distribution: For feature selection

📈 Results
Model	Accuracy	Best Use Case
SVM	~64%	Balanced precision/recall
KNN	~70%	Fast, high consistency
Logistic Regression	~55%	Less suitable for multi-class
Perceptron	~22%	Poor classification

📊 Visualizations
Histograms for feature distributions

Correlation matrix

Feature-probability plots

Confusion matrices

🚀 How to Run
bash
Copy
Edit
# Install dependencies (if needed)
pip install -r requirements.txt

# Open and run the notebook
jupyter notebook statml_project.ipynb
📚 References
UCI Maternal Health Dataset

Research: Multi-class Classification in Health Informatics

Project inspiration on GitHub

🔮 Future Work
Add a user interface for easy use by doctors and clinics

Build a mobile/web app for real-time input and risk prediction

Explore deep learning for improved accuracy

Include image input (e.g. ultrasound scans) to auto-extract features
