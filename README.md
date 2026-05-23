# pw_restaurant-review-sentiment-monitor
A production-style Streamlit NLP application for restaurant review sentiment analysis with live prediction monitoring, confidence tracking, drift detection, batch CSV scoring, and interactive analytics dashboards.

# Restaurant Review Sentiment Monitor

A production-style NLP application built with Streamlit for restaurant review sentiment analysis, live prediction monitoring, confidence tracking, drift detection, and batch CSV scoring.

---

# Features

- Real-time restaurant review sentiment prediction
- Positive and negative sentiment classification
- Confidence score monitoring
- Batch CSV/TSV review scoring
- Interactive monitoring dashboard
- Prediction mix visualization
- Confidence trend tracking
- Input drift detection alerts
- Recent prediction logging
- Deployment-style Streamlit interface

---

# Tech Stack

## Frontend
- Streamlit

## Machine Learning
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression / NLP Pipeline

## Data Processing
- Pandas
- NumPy

## Visualization
- Plotly
- Matplotlib

---

# Project Structure

```bash
pw_restaurant-review-sentiment-monitor/
│
├── streamlit_restaurant_monitoring_app.py
├── restaurant_sentiment_pipeline.joblib
├── Reviews.csv
├── Restaurant_Reviews.tsv
├── README.md
└── BOW & TFIDF.docx
```

---

# Dashboard Capabilities

The application provides deployment-style monitoring metrics such as:

- Model Accuracy
- F1 Score
- Average Prediction Confidence
- Live Positive Prediction Rate
- Low Confidence Detection
- Input Length Drift Monitoring
- Prediction Distribution Analysis

---

# Application Preview

## Single Review Prediction

Users can enter individual restaurant reviews and receive:
- Sentiment prediction
- Confidence score

## Batch Scoring

Upload CSV or TSV files containing a `Review` column for bulk sentiment prediction.

Example CSV format:

```csv
Review
"The food was amazing and fresh."
"The service was very slow."
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/ingledarshan/pw_restaurant-review-sentiment-monitor.git
```

## Navigate to Project Folder

```bash
cd pw_restaurant-review-sentiment-monitor
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Streamlit App

```bash
streamlit run streamlit_restaurant_monitoring_app.py
```

---

# Machine Learning Workflow

1. Text preprocessing
2. TF-IDF vectorization
3. Sentiment classification
4. Confidence estimation
5. Monitoring signal generation
6. Dashboard visualization

---

# Example Predictions

| Review | Prediction |
|---|---|
| "Amazing food and quick service." | Positive |
| "The waiter was rude and the food was cold." | Negative |

---

# Future Improvements

- SHAP explainability integration
- Real-time API deployment with FastAPI
- Database logging
- Docker containerization
- Cloud deployment (AWS/GCP/Azure)
- Advanced drift detection
- Multi-class sentiment analysis

---

# Author

## Darshan Ingle

Machine Learning and Data Science Enthusiast

Areas of Interest:
- Natural Language Processing
- Streamlit Dashboards
- Machine Learning Deployment
- Data Visualization

---

# License

This project is intended for educational and portfolio purposes.
