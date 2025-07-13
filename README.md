# mushroom-risk-analyzer
Machine Learning-powered mushroom edibility classifier with SHAP explainability and interactive Gradio UI. Includes model metrics, confidence scoring, and feature-level interpretation.

🍄 Mushroom Edibility Predictor with SHAP & Gradio
Predict whether a mushroom is edible or poisonous based on its physical features — with confidence scores and SHAP explainability.

📌 Project Overview
This project builds a machine learning classifier that:

Classifies mushrooms as edible or poisonous

Shows prediction confidence

Explains why with SHAP force plots

Has an interactive Gradio web app

🔍 Key Features
✅ Random Forest classifier trained on full mushroom dataset

✅ Full SHAP integration for model interpretability

✅ Confidence percentage for each prediction

✅ Supports all 22 categorical features

✅ Easy-to-use Gradio UI

✅ Displays model performance metrics on the dashboard

📊 Sample Outputs
Feature Input	Prediction	Confidence	SHAP Explanation
cap-shape: convex, odor: foul, ...	☠️ Poisonous	99.8%	SHAP force plot
cap-surface: smooth, gill-color: brown, ...	🍄 Edible	97.2%	SHAP force plot

🧠 Technologies Used
Tool	Purpose
Pandas	Data handling
Scikit-learn	ML model training
SHAP	Explainable AI (XAI)
Gradio	Web app interface
Matplotlib	SHAP plot rendering

🚀 How to Run (Locally or in Colab)
🟢 Google Colab
Click to open in Colab
Then upload the mushrooms.csv file and run cells step-by-step.

🖥️ Local Setup
bash
Copy
Edit
git clone https://github.com/your-username/mushroom-edibility-predictor.git
cd mushroom-edibility-predictor
pip install -r requirements.txt
python app.py

🧪 Evaluation Metrics
Metric	Value
Accuracy	1.000
Precision	1.000
Recall	1.000
F1 Score	1.000

📁 Dataset Used
UCI Mushroom Dataset
Includes 8124 samples and 22 categorical features.

🧑‍💻 Author
Tamanna Aggarwal
Feel free to connect on LinkedIn or fork this repo to extend it!
