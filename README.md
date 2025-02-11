# <img src="app/public/mfg_logo.png" align="left" width=50 height=40> Predictive Analysis API

A lightweight RESTful API for predictive analysis in manufacturing operations. This API predicts machine downtime or product defects using machine learning models. It provides endpoints to upload data, train models, and make predictions to enhance decision-making in manufacturing processes.

![Predictive Analysis](app/public/mfg_dashboard.png)

---

## Features

- **Data Upload:** Accepts manufacturing data in CSV format to prepare the dataset for training.
- **Model Training:** Trains a supervised machine learning model (e.g., Logistic Regression or Decision Tree) and returns metrics like accuracy and F1-score.
- **Prediction:** Accepts feature inputs such as `Temperature` and `Run_Time` to predict outcomes like downtime or product defects.

---

## Installation

### Install Dependencies

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
