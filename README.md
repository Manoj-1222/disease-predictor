# Multiple Disease Predictor

A machine learning-powered web application that predicts multiple diseases using various symptoms and medical parameters.

## Features

- **Disease Prediction**: Predict diseases based on symptoms using XGBoost
- **Specialized Predictors**: Individual models for:
  - Diabetes
  - Heart Disease
  - Parkinson's Disease
  - Liver Disease
  - Hepatitis
  - Lung Cancer
  - Chronic Kidney Disease
  - Breast Cancer
- **Medical Imaging**: Pneumonia and Malaria detection
- **Risk Assessment**: Health risk factor evaluation
- **AI Chatbot**: Medical consultation assistance

## Technology Stack

- **Frontend**: Streamlit
- **Machine Learning**: Scikit-learn, XGBoost
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/Manoj-1222/disease-predictor.git
cd disease-predictor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## Models Included

- Pre-trained ML models for 8+ diseases
- XGBoost model for general disease prediction
- Image classification models for medical imaging

## Dataset Sources

- Multiple medical datasets for comprehensive disease prediction
- Symptom-disease mapping databases
- Medical imaging datasets

## License

Open source project for educational and research purposes.

---
*Developed for healthcare assistance and medical research*