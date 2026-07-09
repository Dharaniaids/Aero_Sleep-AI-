# Aero_Sleep-AI-
Enhanced-Multimodal-Sleep-Apnea-Severity-Estimator/
│
├── README.md                              ⭐ Main Documentation
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG.md
├── requirements.txt
├── environment.yml
├── .gitignore
├── .env.example
│
├── docs/
│   ├── PROJECT_OVERVIEW.md
│   ├── SYSTEM_ARCHITECTURE.md
│   ├── PROJECT_WORKFLOW.md
│   ├── AI_MODELS.md
│   ├── DATABASE_DESIGN.md
│   ├── API_DOCUMENTATION.md
│   ├── DEPLOYMENT_GUIDE.md
│   ├── USER_MANUAL.md
│   ├── DEVELOPER_GUIDE.md
│   ├── FUTURE_SCOPE.md
│   ├── TROUBLESHOOTING.md
│   └── REFERENCES.md
│
├── dataset/
│   ├── raw/
│   ├── processed/
│   ├── sample_data/
│   └── README.md
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Model_Training.ipynb
│   ├── 05_Model_Comparison.ipynb
│   └── 06_SHAP_Analysis.ipynb
│
├── preprocessing/
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── normalization.py
│   ├── segmentation.py
│   └── signal_processing.py
│
├── models/
│   ├── LSTM/
│   │     ├── model.py
│   │     ├── train.py
│   │     ├── evaluate.py
│   │     └── predict.py
│   │
│   ├── TCN/
│   │     ├── model.py
│   │     ├── train.py
│   │     ├── evaluate.py
│   │     └── predict.py
│   │
│   ├── CNN_LSTM/
│   │     ├── model.py
│   │     ├── train.py
│   │     ├── evaluate.py
│   │     └── predict.py
│   │
│   ├── Siamese/
│   │     ├── model.py
│   │     ├── train.py
│   │     ├── verify_user.py
│   │     └── evaluate.py
│   │
│   ├── SHAP/
│   │     ├── explain.py
│   │     └── visualization.py
│   │
│   └── saved_models/
│
├── backend/
│   ├── app.py
│   ├── main.py
│   ├── routes.py
│   ├── auth.py
│   ├── prediction.py
│   ├── verification.py
│   ├── database.py
│   ├── schemas.py
│   ├── config.py
│   └── utils.py
│
├── frontend/
│   ├── flutter_app/
│   │
│   ├── lib/
│   ├── assets/
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   └── models/
│
├── database/
│   ├── schema.sql
│   ├── tables.sql
│   ├── sample_queries.sql
│   └── migration.sql
│
├── explainability/
│   ├── shap_analysis.py
│   ├── feature_importance.py
│   └── plots.py
│
├── outputs/
│   ├── confusion_matrix/
│   ├── accuracy_graph/
│   ├── roc_curve/
│   ├── shap_plots/
│   ├── prediction_reports/
│   └── screenshots/
│
├── images/
│   ├── architecture.png
│   ├── workflow.png
│   ├── dashboard.png
│   ├── app_screen.png
│   ├── model_comparison.png
│   └── logo.png
│
└── tests/
    ├── test_models.py
    ├── test_api.py
    ├── test_database.py
    └── test_frontend.py
