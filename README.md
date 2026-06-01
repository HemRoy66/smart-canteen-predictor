# smart-canteen-predictor
🍽️ Artificial Intelligence Based Canteen Food Demand Predictor Using Machine Learning
📌 Project Overview

The AI-Based Canteen Food Demand Predictor is a machine learning project designed to forecast daily food demand in a canteen. The system analyzes historical food consumption data and predicts the quantity of food items required for upcoming days. This helps canteen management reduce food wastage, optimize inventory, and improve operational efficiency.

🎯 Objectives
Predict daily food demand using Machine Learning algorithms.
Reduce food wastage and overproduction.
Improve inventory and resource management.
Support data-driven decision-making in canteen operations.
Enhance sustainability through accurate demand forecasting.
🛠️ Technologies Used
Python
Machine Learning
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
SHAP (Model Explainability)
LIME (Local Model Explainability)
Jupyter Notebook
📂 Project Structure
AI-Canteen-Food-Demand-Predictor/
│
├── Dataset/
│   ├── AI_Canteen_Food_Demand_Dataset.xlsx
│   └── AI_Canteen_Food_Demand_Dataset_With_NonVeg.xlsx
│
├── Source_Code/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── prediction.py
│   └── app.py
│
├── Documents/
│   ├── Project_Report.pdf
│   └── Project_Documentation.docx
│
├── PPT/
│   └── Project_Presentation.pptx
│
├── Results/
│   ├── Prediction_Output.png
│   ├── SHAP_Analysis.png
│   └── Performance_Metrics.png
│
├── README.md
└── requirements.txt
📊 Dataset Description

The dataset contains historical canteen food demand records with features such as:

Date
Day of Week
Food Item
Quantity Prepared
Quantity Sold
Special Event Indicator
Weather Condition
Holiday Indicator
Food Category (Veg / Non-Veg)
🤖 Machine Learning Models Used
Random Forest Regressor
XGBoost Regressor
Logistic Regression (for comparative analysis)
Ensemble Learning Techniques
📈 Evaluation Metrics

The model performance is evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score
🔍 Explainable AI Techniques
SHAP (SHapley Additive exPlanations)

Used to understand the contribution of each feature to the model's predictions.

LIME (Local Interpretable Model-Agnostic Explanations)

Provides explanations for individual predictions made by the model.

🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/AI-Canteen-Food-Demand-Predictor.git
2. Navigate to the Project Folder
cd AI-Canteen-Food-Demand-Predictor
3. Install Required Libraries
pip install -r requirements.txt
4. Run the Application
python app.py
📊 Expected Output
Daily food demand prediction.
Predicted vs Actual demand visualization.
Performance evaluation metrics.
SHAP and LIME explainability reports.
🌟 Key Features

✅ Food Demand Forecasting
✅ Food Waste Reduction
✅ Inventory Optimization
✅ Machine Learning-Based Predictions
✅ Explainable AI (SHAP & LIME)
✅ Sustainable Canteen Management

📚 References
Demand Forecasting for Food Production Using Machine Learning Algorithms: A Case Study of University Refectory (2024)
Machine Learning Techniques for Cafeteria Demand Forecasting: An Institutional Case (2025)
Reducing Food Waste in Campus Dining: A Data-Driven Approach to Demand Prediction and Sustainability (2025)
👨‍💻 Author

Hemanth Kumar Pattem
Master of Computer Applications (MCA)
MITS Deemed to be University

📄 License

This project is developed for academic and educational purposes as part of the MCA curriculum.
