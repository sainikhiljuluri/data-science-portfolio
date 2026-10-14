<div align="center">

# Sainikhil Juluri · Data Scientist

**Machine learning, data pipelines, and deployed analytics in Python**

[![Email](https://img.shields.io/badge/Email-sainikhiljuluri15%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sainikhiljuluri15@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sainikhiljuluri-181717?style=flat-square&logo=github)](https://github.com/sainikhiljuluri)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-sainikhiljuluri2015-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/sainikhiljuluri2015)
![Location](https://img.shields.io/badge/Location-San%20Jose%2C%20CA%20·%20Open%20to%20relocation-0B4FA8?style=flat-square)

</div>

---

## About this portfolio

This repository indexes my end-to-end data science projects. Each project covers a real business or research problem, from data cleaning and feature engineering through modeling, evaluation, and a deployed interface. The projects are grouped by the work they demonstrate, so a reviewer can find the evidence for a specific skill quickly.

## Highlights

| Result | Project |
|---|---|
| **0.781 ROC-AUC** (LightGBM) vs 0.729 for logistic regression, on 307,511 loan applications | [Credit Default Risk Predictor](https://github.com/sainikhiljuluri/credit-risk-predictor) |
| **86.3% test accuracy** and about **52% churner recall** with a Keras network tuned by 5-fold grid search | [Customer Churn with Neural Networks](https://github.com/sainikhiljuluri/Churn_modelling_using_ANN) |
| **243,553 subscribers** modeled end to end: ETL, PostgreSQL star schema, 10 classifiers, 8 balancing methods | [Telecom Customer Churn](https://github.com/sainikhiljuluri/telecom-churn-prediction) |
| **101,766 hospital encounters** cleaned and loaded, with a 30-day readmission model (Random Forest, 0.65 ROC-AUC) | [Hospital Readmission Analytics](https://github.com/sainikhiljuluri/hospital-disease-analytics-patient-risk) |
| **~678,000 motor policies** priced with Poisson and Gamma GLMs, benchmarked against XGBoost and LightGBM | [Motor Insurance Pricing](https://github.com/sainikhiljuluri/motor-insurance-pricing) |
| **Real-time fraud decisions** via FastAPI: ALLOW, PEND, or REJECT, with a JSONL audit log | [Fraud Decisioning System](https://github.com/sainikhiljuluri/fraud-detection-system) |

## Projects

### Predictive modeling and explainability

- **[Credit Default Risk Predictor](https://github.com/sainikhiljuluri/credit-risk-predictor)** · LightGBM, SHAP, Streamlit
  Credit-domain feature engineering, class-weighted gradient boosting, RandomizedSearchCV, and SHAP explanations mapped to adverse-action reasons. [Live app](https://credit-risk--predictor.streamlit.app/)
- **[Diabetes Risk Prediction](https://github.com/sainikhiljuluri/patient-risk-prediction)** · XGBoost, SHAP, Streamlit
  Health-indicator classification with per-prediction explanations. [Live app](https://patient-risk-prediction-diabetes.streamlit.app)
- **[Insurance Claims Fraud Detection](https://github.com/sainikhiljuluri/insurance-fraud-detection)** · XGBoost, Isolation Forest, FastAPI, PostgreSQL
  Supervised and unsupervised detection combined in one scoring API. About 0.82 ROC-AUC on a 1,000-claim dataset.
- **[Used Car Price Prediction](https://github.com/sainikhiljuluri/usedcarpriceprediction)** · scikit-learn, XGBoost, Flask, Docker
  Target encoding, log transforms, and a reproducible scikit-learn pipeline served as a containerized Flask app.

### Data pipelines and analytics

- **[Telecom Customer Churn](https://github.com/sainikhiljuluri/telecom-churn-prediction)** · PostgreSQL, Optuna, SHAP, FastAPI, Power BI, Tableau
  SCD Type-2 customer history, a partitioned fact table, post-load validation, and dashboards on the warehouse.
- **[Hospital Readmission Analytics](https://github.com/sainikhiljuluri/hospital-disease-analytics-patient-risk)** · MySQL, scikit-learn, Streamlit, Ollama
  Cleaning decisions documented in code, patient-level train/test splitting to avoid leakage, and a six-page dashboard.

### Machine learning systems

- **[Real-Time Transaction Fraud Decisioning](https://github.com/sainikhiljuluri/fraud-detection-system)** · LightGBM, MLflow, FastAPI, Streamlit
  Offline feature store with lifetime and velocity (1-hour and 24-hour) features, and a shared feature engine so training and serving compute features the same way.
- **[Motor Insurance Pricing](https://github.com/sainikhiljuluri/motor-insurance-pricing)** · statsmodels GLMs, XGBoost, LightGBM, Streamlit
  Frequency-severity modeling that turns expected claims into a pure premium and a commercial premium.

### Deep learning and NLP

- **[Post-Training Alignment of Open-Source LLMs](https://huggingface.co/sainikhiljuluri2015)** · PyTorch, Hugging Face PEFT/TRL, LoRA
  Four fine-tuned security models with LoRA (rank 16) over 50K instruction pairs, released as adapters and merged weights.
- **[Stock Movement Prediction](https://github.com/sainikhiljuluri/Stock-market-prediction-using-numerical-and-texture-analysis)** · Keras LSTM, NLTK VADER
  Next-day price forecasting that adds headline sentiment scores as model inputs.
- **[Advanced Named Entity Recognition](https://ijercse.com/viewabstract.php?id=16396&volume=Volume10&issue=Issue6)** · Published review, IJERCSE, 2023

### Production software

- **[Thrilochana](https://apps.apple.com/us/app/thrilochana/id6759315151)** · FastAPI, PostgreSQL, Flutter, Google Cloud Run
  Agentic RAG document intelligence for retail invoices, live on the Apple App Store. Built with a read-only tool layer, hallucination guardrails, and canary deploys with automatic rollback.

## Routing and optimization

- **[Appliance delivery routing with a VRP solver](https://github.com/sainikhiljuluri/vrp-appliance-delivery-sample)** · ArcGIS API for Python
  Vehicle routing problem for appliance delivery, solved with ArcGIS network analysis tools. Covers route optimization workflow end to end.

## Skills

| Area | Tools and methods used in these projects |
|---|---|
| **Languages** | Python, SQL, TypeScript, Dart |
| **Modeling** | scikit-learn, LightGBM, XGBoost, Isolation Forest, Keras, statsmodels GLMs, cross-validation, class imbalance methods |
| **Explainability** | SHAP, per-prediction explanations, adverse-action reasons |
| **Tuning and evaluation** | GridSearchCV, RandomizedSearchCV, Optuna, ROC-AUC, PR-AUC, recall at fixed false-positive rates |
| **Data engineering** | ETL pipelines, PostgreSQL and MySQL, star-schema warehousing, data validation, deduplication |
| **Visualization** | Power BI, Tableau, Plotly, Matplotlib, Seaborn, Streamlit |
| **Deployment** | FastAPI, Flask, Docker, Docker Compose, Google Cloud Run, AWS Elastic Beanstalk |
| **Workflow** | Git, GitHub, Jupyter, pytest, MLflow |

## Working style

- **Data quality first.** Cleaning decisions are written down, and validation runs after each load.
- **Evaluation that matches the business cost.** I report recall at fixed false-positive rates for fraud, and recall on the minority class for churn, rather than accuracy alone.
- **Reproducible work.** Projects keep the pipeline, the artifacts, and the dependencies in the repo.

## Contact

📧 [sainikhiljuluri15@gmail.com](mailto:sainikhiljuluri15@gmail.com) · 📍 San Jose, CA (open to relocation)

---

<div align="center">
<sub>Built with Python. Projects are linked above, each with its own README and setup steps.</sub>
</div>
