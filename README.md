# AI-ML-project
AI-Powered Crop Recommendation System

Project Title

AI-Powered Crop Recommendation System using Machine Learning

Overview of the Project

This project develops a machine learning model to assist farmers in selecting the most suitable crop for their land based on specific environmental and soil parameters. By analyzing nutrient levels (Nitrogen, Phosphorus, Potassium), pH, temperature, humidity, and rainfall, the system predicts the optimal crop, thereby maximizing yield and promoting sustainable agriculture. This demonstrates the core principles of Supervised Classification and data-driven decision-making in the domain of agriculture.

Features

Data Preprocessing: Handles data loading, cleaning, and feature scaling using StandardScaler to normalize the input data.

Model Training: Implements a Random Forest Classifier (an ensemble model) for accurate, multi-class classification of crops.

Model Evaluation: Calculates and displays the Accuracy Score to assess the model's predictive performance on unseen data.

Prediction Interface: Accepts new user-defined soil and climate input data and provides a single, actionable crop recommendation.

Technologies/Tools Used

Programming Language: Python 3.x

Data Manipulation: pandas, numpy

Machine Learning: scikit-learn (RandomForestClassifier, StandardScaler, train_test_split, accuracy_score)

Version Control: Git

Steps to Install & Run the Project

Prerequisites

Ensure you have Python 3.x installed on your system.

Installation

Clone the Repository (Simulated Step):

# git clone [YOUR-REPO-URL]
# cd crop-recommender-project


Install Required Libraries:

pip install pandas numpy scikit-learn


Execution

Run the main Python script from your terminal:

python crop_recommender.py


The script will execute the entire machine learning workflow: data preparation (using synthetic data), model training, evaluation, and a demonstration of two crop predictions using sample inputs.

Instructions for Testing

The script includes an automated Model Evaluation step using a held-out test set (test_size=0.2). The output will clearly show the calculated Model Accuracy on Test Set.

To perform Functional Testing, inspect the final output block which provides two sample predictions:

Input 1 (High NPK, High Rainfall): This input mimics conditions suitable for a water-intensive crop and should recommend RICE.

Input 2 (Low NPK, Moderate Rainfall): This input mimics conditions suitable for a pulse or dry-land crop and should recommend PIGEONPEAS.

Screenshots:
<img width="1372" height="690" alt="Screenshot 2025-11-25 015158" src="https://github.com/user-attachments/assets/b1b0b06e-ccb3-45de-a9b4-3d86309ced6f" />
<img width="1363" height="723" alt="Screenshot 2025-11-25 015211" src="https://github.com/user-attachments/assets/5175f48a-4e73-475c-8bfc-1ec22c2817c6" />
<img width="1368" height="697" alt="Screenshot 2025-11-25 015229" src="https://github.com/user-attachments/assets/e2dda7f2-7b87-4229-991d-2d23525eb229" />
<img width="1365" height="717" alt="Screenshot 2025-11-25 015245" src="https://github.com/user-attachments/assets/805b712f-06e0-4b91-90d5-9b7b64cff84c" />
<img width="1361" height="218" alt="Screenshot 2025-11-25 015258" src="https://github.com/user-attachments/assets/d907c80c-4065-4bd7-b682-90d7f99d3805" />
<img width="1417" height="337" alt="Screenshot 2025-11-25 015309" src="https://github.com/user-attachments/assets/2dd19b24-5394-4b7a-8839-52e183fd1212" />
