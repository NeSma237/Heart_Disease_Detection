# Heart Disease Detection Project

## 📌 Project Overview
This project predicts heart disease risk using both:
- A **rule-based expert system** built with `Experta`.
- A **machine learning model** (`DecisionTreeClassifier`).

## 📂 Project Structure
- `data/` → Contains raw and cleaned datasets.
- `notebooks/` → Jupyter Notebooks for data analysis.
- `rule_based_system/` → Expert system (Experta-based).
- `ml_model/` → Machine learning model (Decision Tree).
- `ui/` → Streamlit user interface.
- `reports/` → Model comparison results.

## 🛠️ Installation
To install the required dependencies, run:
```bash
pip install -r requirements.txt

##🚀 Running the Project
1️⃣ Run the Expert Syste
python rule_based_system/expert_system.py

2️⃣ Train the Decision Tree Model:
python ml_model/train_model.py

3️⃣ Run the User Interface:
streamlit run ui/app.py

